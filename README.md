# 💻 Laboratorio 1: Mi Currículum Web

## Objetivo

El presente laboratorio tiene como obejtivo introducir al estudiante al desarrollo web, a través de la creacion una página web con el currículum vitae del estudiante utilizando **HTML** para estructurar el contenido y **CSS** para aplicar estilos utilizando la propiedad `class`.

---

## 📁 Estructura del proyecto

El proyecto debe contener al menos los siguientes archivos:

/laboratorio-1/ <br>
  ├── index.html <br>
  ├── estilos.css <br>
  └── README.md <br>


---

## Instrucciones

### 1. Estructura básica (index.html)

Crear una página HTML que contenga:

- Un **título principal** con tu nombre completo (`<h1>`)
- Una **foto** tuya (opcional) usando la etiqueta `<img>`
- Una **descripción breve o perfil profesional** (`<p>`)
- Una **lista de habilidades** usando `<ul>` y `<li>`
- Sección de **educación** y **experiencia laboral**
- Enlaces a tus **redes sociales o correo electrónico** usando `<a href="...">`

### 2. Estilos con CSS (estilos.css)

Crear un archivo `estilos.css` y usa **clases (`class`)** para aplicar estilos como:

- Color de fondo
- Color del texto
- Tamaño y tipo de letra
- Bordes o separación entre secciones
- Alineación del texto
- Estilos para la imagen

### 3. Conecta el CSS con tu HTML

En tu archivo `index.html`, dentro de la etiqueta `<head>`, enlaza el archivo de estilos:

```html
<link rel="stylesheet" href="estilos.css">
```

## Entrega del laboratorio
Clonar el repositorio (desde GitHub Classroom)

```bash
git clone <URL-del-repositorio>
cd <nombre-del-repositorio>
```

### 4. Configurar token de acceso (solo si es la primera vez)
- Dirigirse a a: https://github.com/settings/tokens
- Genera un token clásico con permisos para repositorios.
- Guarda el token en un sitio seguro, ya que se lo necesitará para autenticarse al hacer push.

### 5. ✅ Hacer commit y push de tus cambios
```bash
git add .
git commit -m "Laboratorio 1 terminado"
git push origin main
```

¡Mucho éxito con tu primer sitio web personal! 🚀
