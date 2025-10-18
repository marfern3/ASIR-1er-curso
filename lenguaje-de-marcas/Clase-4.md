# 📝 RESUMEN DE LA CLASE DE HOY

- Recordatorios de la clase anterior  
- Definiciones  
- Tablas  
- Formularios  
- Extras  

---

## 1️⃣ Recordatorio de la clase anterior

Simplemente como recopilación de lo que vimos de **HTML** en la clase anterior:

- Algunas etiquetas básicas (enlaces, párrafos, separadores y saltos de línea)  
- Formatos de texto desde HTML  
- Atributos (`id`, `name`, `href`)  
- Navegar entre "pestañas"  
- Enlazar distintas partes de una página  
- Enviar correos  
- Insertar imágenes  

📎 **Ejercicio corregido en clase:**  
[https://github.com/olga3emes/proyectos](https://github.com/olga3emes/proyectos)

---

## 2️⃣ HTML

### 🟡 Definiciones

Usamos la etiqueta `<dl>` para crear **listas de definiciones** (*Definition Lists*).

**Estructura:**
```html
<dl>  <!-- Contenedor de la lista de definiciones -->
  <dt>Termino</dt>  <!-- Definition Term -->
  <dd>Descripción o definición del término</dd>  <!-- Definition Description -->
</dl>


()

🟡 Tablas

Estructura básica:

<h1>TABLAS</h1>

<table border="1">
  <tr>
    <th>ASIR</th>
    <th>DAW</th>
    <th>SMR</th>
    <th>HTML</th>
  </tr>
  <tr>
    <td>Administración de Sistemas Informáticos en Red</td>
    <td>Desarrollo de Aplicaciones Web</td>
    <td>Soporte de Microinformática y Redes</td>
    <td>HyperText Markup Language</td>
  </tr>
  <tfoot>
    <td>Dato 01</td>
    <td>Dato 02</td>
    <td>Dato 03</td>
    <td>Dato 03</td>
  </tfoot>
</table>


📸 Resultado:

🟡 Ejercicio con <thead>, <tbody> y <tfoot>

Ejemplo de uso de secciones de tabla:

<table border="1">
  <thead>
    <tr>
      <th>Paquete 1</th>
      <th>Paquete 2</th>
      <th>Paquete 3</th>
      <th>Paquete 4</th>
      <th>Paquete 5</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Matemática</td>
      <td>Ciencias</td>
      <td>Matemática</td>
      <td>Sociales</td>
      <td>Arte</td>
    </tr>
    <tr>
      <td>Inglés</td>
      <td>Comunicación</td>
      <td>Biología</td>
      <td>Historia</td>
      <td>Física</td>
    </tr>
    <tr>
      <td>Computación</td>
      <td>Historia</td>
      <td>Economía</td>
      <td>Química</td>
      <td>Redacción</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td>10 $</td>
      <td>20 $</td>
      <td>30 $</td>
      <td>40 $</td>
      <td>50 $</td>
    </tr>
  </tfoot>
</table>


📸 Resultado:

🟡 Colores (mini práctica visual)

📸 Ejemplo de cuadrícula de colores:

🟡 Formularios

Código HTML del formulario:

<form>
  <label for="name">Nombre:</label>
  <input type="text" id="name" name="nombre"><br><br>

  <label for="email">Correo Electrónico:</label>
  <input type="email" id="email" name="email"><br><br>

  <label for="edad">Edad:</label>
  <input type="number" id="edad" name="edad" min="0" max="120"><br><br>

  <label for="genero">Género:</label>
  <select id="genero" name="genero">
    <option value="masculino">Masculino</option>
    <option value="femenino">Femenino</option>
    <option value="otro">Otro</option>
  </select><br><br>

  <label>Intereses:</label><br>
  <input type="checkbox" id="deporte" name="intereses" value="deporte">
  <label for="deporte">Deporte</label><br>
  <input type="checkbox" id="musica" name="intereses" value="musica">
  <label for="musica">Música</label><br>
  <input type="checkbox" id="tecnologia" name="intereses" value="tecnologia">
  <label for="tecnologia">Tecnología</label><br><br>

  <label>Suscripción</label><br>
  <input type="radio" id="si" name="suscripcion" value="si">
  <label for="si">Sí</label><br>
  <input type="radio" id="no" name="suscripcion" value="no">
  <label for="no">No</label><br><br>

  <label for="comentarios">Comentarios:</label><br>
  <textarea id="comentarios" name="comentarios" rows="4" cols="50"></textarea><br><br>

  <label for="archivo">Subir archivo:</label>
  <input type="file" id="archivo" name="archivo"><br><br>

  <input type="reset" value="Restablecer">
  <input type="submit" value="Enviar">
</form>


📸 Resultado visual:

3️⃣ Extras

🏆 Sugerencia de ejercicios:
Practica todo lo posible creando formularios y tablas.
📩 Puedes enviárselas a Olga.

🌐 Sitios útiles:

userinyerface.com
 → Ejemplo de mala experiencia de usuario

validator.w3.org
 → Revisar y validar tu código HTML

📚 Diapositivas de clase:
Archivo adjunto → Diapositivas_Unidad_1.pdf (3.36 MB)


---

👉 Este Markdown está listo para pegar directamente en **Notion, VS Code, GitHub o cualquier editor de apuntes**, manteniendo toda la estructura y los ejemplos.  
¿Quieres que te lo exporte también como `.md` descargable?