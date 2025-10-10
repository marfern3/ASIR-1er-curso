# 📝 RESUMEN DE LA CLASE DE HOY (07/10/25)

---

## 🧠 Conceptos nuevos

### UEFI (Unified Extensible Firmware Interface)
Interfaz moderna que **sustituye a BIOS**. Ofrece arranque más flexible y seguro (Secure Boot), soporte para discos grandes y UI más amigable.

### GPT (GUID Partition Table)
Esquema de particionado que **soporta >2 TB** y muchas más particiones que MBR. Recomendado con UEFI.

### Bootloader (cargador de arranque)
Programa que **carga el sistema operativo en memoria** y transfiere el control para iniciar el SO.  
Ejemplos: GRUB (Linux), Windows Boot Manager (Windows).

### Boot Record
Zona del disco con la **info necesaria para arrancar**:
- **MBR (Master Boot Record):** al inicio del disco (sector 0). Incluye *código de arranque* y *tabla de particiones MBR*.
- **VBR (Volume Boot Record):** sector de arranque de **cada partición**.

### Tipos de arranque
- **Legacy Boot (BIOS + MBR):** método clásico, limita discos a 2 TB y 4 particiones primarias.
- **UEFI Boot (UEFI + GPT):** método moderno; requiere **partición EFI (ESP)** para los archivos de arranque.

> 💡 Regla práctica: **UEFI ↔ GPT** (pareja ideal). **BIOS/Legacy ↔ MBR**.

---

## 🔁 Tabla rápida: Legacy vs UEFI

| Característica            | Legacy (BIOS + MBR)       | UEFI (UEFI + GPT)                  |
|---------------------------|---------------------------|------------------------------------|
| Límite tamaño de disco    | ~2 TB                     | > 2 TB                              |
| Nº de particiones         | 4 primarias (o 3+extend.) | Muchas más (dependiendo del SO)     |
| Partición de arranque     | MBR/VBR                   | **ESP** (EFI System Partition)      |
| Secure Boot               | No                        | **Sí**                              |
| Velocidad de arranque     | Menor                     | **Mayor**                           |
| Compatibilidad            | Muy alta con equipos viejos| Requiere firmware UEFI              |

---

## 🛠️ Actividades a realizar

1) **Instalar Ubuntu Server** (en VM o hardware de pruebas).  
2) Si ya lo hiciste, **instalar Windows 11** o **Windows Server**:
   - Windows 11: https://www.microsoft.com/es-es/software-download/windows11  
   - Windows Server 2025 (evaluación): https://www.microsoft.com/es-mx/evalcenter/download-windows-server-2025

> 🔐 Consejos de instalación:
> - Para **UEFI**: crea/asegura la **partición EFI (ESP)** (FAT32 ~100–300 MB).  
> - Para **Legacy**: tabla **MBR** y marca partición activa.  
> - En VMs (VirtualBox/VMware): configura el **modo de firmware** (UEFI o BIOS) antes de instalar.

---

# ✉️ Ejercicio Extra — Comunicación entre máquinas virtuales (Ping entre VMs)

---

## 🎯 Objetivo

Comprobar la **conectividad en red entre dos máquinas virtuales (VMs)** usando el comando `ping`  
y **enviar las capturas de pantalla** por correo a `jesus.nino@thepower.education`.

---