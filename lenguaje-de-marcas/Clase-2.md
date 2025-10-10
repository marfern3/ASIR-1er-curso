# 🌟 PARA LA CLASE DE HOY

---

## 🧾 Requisitos previos

Ten siempre a mano el **PDF de la Unidad 1** (en recursos extra de la asignatura):  
🔗 [Unidad 1 - ThePowerMBA](https://app.thepowermba.com/programs/67af3eec3726e80bda94ecc3/pills/68cabe05a5470d15a1dfb791)

---

### 💻 Programas y configuraciones necesarias

- Instala **Visual Studio Code** → [https://code.visualstudio.com/](https://code.visualstudio.com/)
- Instala las **extensiones** que pasó Olga (enlaces en la página 10 del PDF anterior).
- Crea una **cuenta en GitHub** → [https://github.com/](https://github.com/)  
  y sincronízala con tu VSCode.
- Instala **Git** → [https://git-scm.com/](https://git-scm.com/)
- Instala también la extensión **Git Graph** → [https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)

---

## 1️⃣ **PRIMERA PARTE - Abrir Git en Visual Studio Code**

1. En la interfaz de **VSCode**, abre la barra superior:
   - `Terminal > New Terminal`
2. Se abrirá una terminal en la parte inferior.
3. En la barra superior del recuadro, pulsa el **icono junto al “+”**.
4. Si instalaste Git correctamente ([https://git-scm.com/](https://git-scm.com/)), verás la opción **Git Bash** → selecciónala.  
   ✅ ¡Ya lo tienes! Verás todas las consolas abiertas en la columna derecha y puedes cerrar las que no uses.

---

### 🧑‍💻 Configurar usuario y e-mail en Git

```bash
git config --global user.name "Nombre Apellido"
git config --global user.email email@dominio.com
```

## 2️⃣ **SEGUNDA PARTE - Subir nuestro código y modificaciones a GitHub**

> 💡 **¿Por qué es útil?**  
> No solo para compartir código en equipos, sino también como **copia de seguridad** de tus proyectos en la nube (GitHub).

---

### 🪶 Pasos

1. Crea una carpeta en la ubicación que quieras.  
   Ábrela desde **VSCode** y crea dentro un archivo `index.html`.  
   (Podrás verlo en la pestaña del explorador, a la izquierda).

2. Crea un **repositorio** (dos opciones):

   - Desde la terminal Git:
     ```bash
     git init
     ```

   - Desde VSCode:  
     Ve a la pestaña de **Control de código fuente (Source Control)** → pulsa **Iniciar Repositorio**.

3. Edita tu archivo HTML (por ejemplo, añade comentarios o texto nuevo).  
4. En la pestaña **Source Control**, en el campo de “Mensaje”, escribe una descripción del cambio.  
   Luego pulsa **Commit** → **Publish Branch**.  
5. Si tu VSCode está vinculado correctamente a tu cuenta de GitHub,  
   el proyecto se subirá automáticamente.  
   Revisa tu perfil → **Repositories** → ahí debería aparecer tu proyecto 💯.

---

### 🧭 En GitHub

- En la pestaña **Code** verás el contenido del archivo.  
- En la pestaña **Blame** verás el **historial de modificaciones**.

---

### ‼️ Diferencias entre una carpeta y un repositorio

| Concepto | Carpeta | Repositorio |
|:----------|:---------|:-------------|
| **Definición** | Estructura básica del sistema operativo para organizar archivos. | Carpeta especial usada para control de versiones. |
| **Historial de cambios** | ❌ No tiene historial ni control de versiones. | ✅ Guarda cada cambio realizado. |
| **Colaboración** | No permite trabajar en equipo fácilmente. | Permite colaborar, revertir cambios y crear ramas. |
| **Ubicación** | Solo local. | Local y/o remoto (GitHub, GitLab...). |

---

## 3️⃣ **TERCERA PARTE - Clonar (descargar) un repositorio desde GitHub**

> 🧠 Imagina que perdiste tu carpeta local... ¡no pasa nada!  
> Puedes recuperarla desde GitHub fácilmente.

---

### 🪶 Pasos para clonar tu repositorio

1. Entra a [GitHub](https://github.com/) → icono de perfil → **Repositories**.  
2. Selecciona tu proyecto.  
3. Pulsa el botón verde **“<> Code”** y copia la URL que aparece.  
4. En VSCode, abre la carpeta donde quieras clonar el proyecto.  
5. Abre tu terminal Git Bash y ejecuta:

```bash
git clone https://github.com/tuusuario/turepositorio.git
```

## 4️⃣ **ANEXO - Comandos y etiquetas HTML**

---

### 💻 **Comandos básicos de Git Bash (Linux style)**

| Comando | Descripción |
|:---------|:-------------|
| `ls` | Muestra el contenido del directorio actual. |
| `ls -la` | Muestra archivos ocultos. |
| `clear` | Limpia la terminal. |
| `git init` | Inicia un nuevo repositorio Git. |
| `git log` | Muestra el historial de commits. |
| `git clone <url>` | Descarga (clona) un repositorio remoto. |
| `pwd` | Muestra la ruta del directorio actual. |

---

### 🔧 **Configurar usuario y correo globalmente**

```bash
git config --global user.name "Nombre Apellido"
git config --global user.email email@dominio.com
```

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<h1>Encabezado mega importante</h1>
<h2>Encabezado importante</h2>
<h3>Encabezado no tan importante</h3>
<h4>Encabezado poco importante</h4>
<h5>Encabezado poquito importante</h5>
<h6>Encabezado menos importante</h6>
