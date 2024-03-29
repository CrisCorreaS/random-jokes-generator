# 🥳 Random Jokes Generator
![Badge en Desarollo](https://img.shields.io/badge/STATUS-FINALIZADO-violet)
<img align="right" alt="License MIT" src="https://img.shields.io/badge/LICENSE-MIT-green" /> <br/><br/>
<img alt="html5" src="https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
<img alt="css3" src="https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" />
<img alt="javascript" src="https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
<br/><br/>
[![Vista previa del generador de bromas](https://github.com/CrisCorreaS/random-jokes-generator/blob/main/img/visualizaci%C3%B3n/generador-vista.png)](https://criscorreas.github.io/random-jokes-generator/)

Este generador de bromas online ha sido creado por **[Cristina Correa](https://www.linkedin.com/in/cristina-correa-segade/)**

## 👀 Vista Previa

### ➡️ **Demo desplegada en GitHub Pages:** **[Haz click aquí](https://criscorreas.github.io/random-jokes-generator/)**

#### Vista del generador de bromas
![Vista previa del generador de bromas](https://github.com/CrisCorreaS/random-jokes-generator/blob/main/img/visualizaci%C3%B3n/generador-vista.png)

### Funcionalidades:
 1️⃣ **Creación de bromas nuevas dinámicamente**:
  - Permite a los usuarios generar bromas dinámicamente con un solo click.   

![Vista previa de las funcionalidades del generador](https://github.com/CrisCorreaS/random-jokes-generator/blob/main/video/feature1.gif)

## 🌱 Características

- **Interfaz**: Diseño sencillo y adaptable, con una estética monocromática que garantiza una experiencia visual uniforme en cualquier dispositivo.
- **Funciones básicas**: Realiza peticiones a una API de bromas de programación para luego presentarlas de manera dinámica en HTML, ofreciendo así una experiencia entretenida y ligera para el usuario.
- **Conexión a una API Open Source**: Conexión con el objeto XMLHttpRequest a una [API Open Source](https://official-joke-api.appspot.com/) que devuelve datos en formato json.
- **Contador de bromas**: Cuenta el número de bromas que has visto
 
## 🛠️ Tecnologías Utilizadas

- HTML
- CSS
- JavaScript
- [API Open Source](https://official-joke-api.appspot.com/jokes/random)

## 🤖 API
- Al acceder a la [URL de la API](https://official-joke-api.appspot.com/jokes/random), se solicita un chiste aleatorio. La respuesta es un objeto JSON que contiene varios campos principales. Un ejemplo de la llamada a la API sería haciendo "https://official-joke-api.appspot.com/jokes/random" lo cual nos devuelve:
 ```
{
    "type":"programming",
    "setup":"What's the object-oriented way to become wealthy?",
    "punchline":"Inheritance",
    "id":16
}
 ```
- Una posible alternativa para generar bromas aleatorias de programación es la [JokeAPI](https://v2.jokeapi.dev/). Esta devuelve un objeto JSON con varios campos entre los que se encuentra la propia broma. Un ejemplo de la llamada a la API sería haciendo "https://v2.jokeapi.dev/joke/Programming?lang=es" lo cual nos devuelve:
```
{
    "error": false,
    "category": "Programming",
    "type": "single",
    "joke": "Sólo hay 10 tipos de personas en este mundo, las que entienden binario y las que no.",
    "flags": {
        "nsfw": false,
        "religious": false,
        "political": false,
        "racist": false,
        "sexist": false,
        "explicit": false
    },
    "safe": true,
    "id": 5,
    "lang": "es"
}
```


## 🔎💡 Información
> [!IMPORTANT]
> - Este es un proyecto para principiantes. No se requieren conocimientos avanzados de HTML, CSS o JavaScript, pero sí saber cómo hacer conexiones a apis con el objeto XMLHttpRequest.
> - Está desarrollado utilizando JavaScript Vanilla, así que no se utiliza ningún framework. Sin embargo, si estás buscando un poco más de desafío, ¡siéntete libre de explorar la posibilidad de integrar un framework!
> - **Nivel de dificultad del proyecto:** 🔴⭕⭕⭕⭕⭕⭕⭕⭕⭕ (1 sobre 10)

> [!TIP]
> A la hora de desarrollar el proyecto, te pueden venir bien los siguientes recursos:
> - [API de Generación de Bromas de Programadores](https://official-joke-api.appspot.com/jokes/random)
> - CSS
>    - [Manz.Dev Lenguaje CSS](https://lenguajecss.com/css/)
> - JavaScript:
>    - [Manz.Dev Lenguaje Javascript](https://lenguajejs.com/javascript/)
>    - [JavaScript MDN Documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
>    - [XHR: XMLHttpRequest - Manz](https://lenguajejs.com/javascript/peticiones-http/xhr/)
> - Font Awesome
>    - [Font Awesome Get Started](https://fontawesome.com/docs/web/setup/get-started)
>    - [Font Awesome Documentation](https://fontawesome.com/v5/docs/web/reference-icons/)

## 📓 Cómo Usar

1. Descarga o clona este repositorio en tu máquina local.
2. Abre el archivo `index.html` en tu navegador web.

¡Y eso es todo! Ahora cualquier persona puede usar un generador de bromas desde un dispositivo.

## ✨ Contribuciones

¡Las contribuciones son bienvenidas! Si deseas mejorar el generador de bromas existente, como agregar más contenido o mejorar el diseño, no dudes en enviar tus pull requests. También puedes sugerir nuevas funcionalidades o brindar retroalimentación para hacer que este proyecto sea aún mejor.

## 🎯 Propósito del Proyecto

Este proyecto forma parte de una tarea de la asignatura de "Desarrollo Web en Entorno Cliente" y tiene como objetivo principal el aprendizaje de tecnologías para mejorar en el plano del desarrollo.
