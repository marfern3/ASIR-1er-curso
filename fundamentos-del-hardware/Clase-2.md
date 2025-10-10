# 📝 RESUMEN DE LA CLASE DE HOY

---

## 🧩 Relación entre hardware y software

- El **hardware** es la parte física del ordenador (CPU, memoria, discos, periféricos).  
- El **software** es el conjunto de programas que permiten que el hardware funcione correctamente.  
- **Tipos principales de software:**
  - **Sistemas operativos:** gestionan el hardware y permiten la ejecución de programas (Windows, Linux, macOS).
  - **Software de programación:** herramientas que permiten desarrollar otros programas (editores, compiladores, IDEs).
  - **Aplicaciones:** programas que usamos para realizar tareas específicas (navegadores, procesadores de texto, juegos, etc.).

---

## 👨‍💻 Figuras importantes en la computación

- **Alan Turing:** pionero de la informática teórica y la inteligencia artificial.  
  Diseñó el concepto de **máquina de Turing**, base de la computación moderna.

- **John Von Neumann:** propuso la **arquitectura Von Neumann**, modelo en el que se basan la mayoría de los ordenadores actuales.  
  Define una estructura con memoria, unidad de control, unidad aritmético-lógica (ALU) y dispositivos de entrada/salida.

---

## 🧠 Arquitectura básica de un ordenador

Los **cuatro pilares fundamentales**:

1. **CPU (Unidad Central de Procesamiento)** → ejecuta las instrucciones y coordina el sistema.  
2. **RAM (Memoria principal)** → almacena temporalmente los datos y programas en uso.  
3. **I/O (Entrada/Salida)** → permite la comunicación con el exterior (teclado, ratón, pantalla, etc.).  
4. **Buses** → canales que interconectan los componentes y permiten el intercambio de información.

```mermaid
flowchart LR
  A[Dispositivos de Entrada/Salida] --> B[CPU]
  B --> C[Memoria RAM]
  B <--> D[Buses]
  D --> E[Almacenamiento]
```
## 🗂️ Jerarquía de memoria

Del nivel más rápido (pero pequeño y caro) al más lento (grande y económico):

| Nivel | Tipo de memoria                         | Velocidad | Capacidad | Volatilidad |
|:------|:----------------------------------------|:-----------|:-----------|:-------------|
| 1️⃣ | Registros (CPU)                        | Muy alta  | Muy baja   | Volátil      |
| 2️⃣ | Caché (L1, L2, L3)                     | Alta      | Baja       | Volátil      |
| 3️⃣ | Memoria principal (RAM)                | Media     | Media      | Volátil      |
| 4️⃣ | Almacenamiento (SSD/HDD)               | Baja      | Alta       | No volátil   |
| 5️⃣ | Almacenamiento externo (USB, nube)     | Muy baja  | Muy alta   | No volátil   |

---

## 🧰 Softwares para ver nuestro hardware

Herramientas gratuitas para conocer los componentes del ordenador:

- **CPU-Z:** muestra información detallada de CPU, RAM y placa base.  
  🔗 [Descargar CPU-Z (portable)](https://cpu-z-portable.uptodown.com/windows/descargar)

- **HWiNFO:** herramienta avanzada para monitorizar sensores, temperaturas y componentes.  
  🔗 [Página oficial de HWiNFO](https://www.hwinfo.com/)

- **Speccy:** resumen general del hardware (ideal para usuarios menos técnicos).  
  🔗 [Descargar Speccy (Microsoft Store)](https://apps.microsoft.com/detail/xpfft31d40mgfq?hl=es-ES&gl=US)
