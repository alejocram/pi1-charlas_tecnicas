## Welcome to GitHub Pages

## NodeJS 

- Instalar NPM
- Instalar NodeJS
- Instalar WebStorm (con correo de EAFIT) o ATOM
- Instalar Postman
- Descargar el [proyecto](https://github.com/alejocram/pi1-charlas_tecnicas/raw/master/41-ExpressExample.zip) y descomprimirlo

Desde consola
Ubicarse dentro del proyecto Ej: /Desarrollo/NodejsProjects/Examples/ExpressExample
`npm start` 
 
Desde el browser
http://localhost:3000
 
http://localhost:3000/users

Desde Postman
POST http://localhost:3000

```
{ "text":"Proyecto Integrador", "title":"Curso" }
```

Recibes un response
```
{ "success": true, "response": { "text": "Proyecto Integrador", "title": "Curso" } }
```

Vuelve a verificar el browser, veras el cambio 

## Android 

- Instalar Java SDK
- Instalar Android Studio
- Descargar el [proyecto](https://github.com/alejocram/pi1-charlas_tecnicas/raw/master/42-ParkingMovil.zip) y descomprimirlo

El proyecto de ejemplo implementa la libreria Volley para el consumo de WebServices y el patrón MVC, además también se implementa el patrón Singleton.

El proyecto consume un servicio REST que retorna un JSON con bloques de la Universidad, luego se almacena en un arrayList y finalmente se pasa el array a un String.

En el siguiente link pueden encontrar un tutorial de Google para el desarrollo de Material Design en la aplicación.
https://codelabs.developers.google.com/codelabs/material-design-style-sp/index.html#0


You can use the [editor on GitHub](https://github.com/alejocram/pi1-charlas_tecnicas/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/alejocram/pi1-charlas_tecnicas/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
