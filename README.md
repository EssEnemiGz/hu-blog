# Cómo Colaborar en el Blog de HackingUtils.c

## Requisitos Previos

* Conocimientos básicos de Markdown.
* Conocimientos básicos de Git y GitHub.

> **TIP** Pasos para Colaborar

1.  **Haz un fork del Repositorio:**

2.  **Clona tu fork Localmente:**

3.  **Crea una Rama para tu Contribución:**
   Estando en la ruta indicada, ejecute el siguiente comando para crear una rama
    ```bash
    git checkout -b mi-articulo
    ```

4.  **Escribe tu Artículo en Markdown:**
    * Crea un nuevo archivo Markdown (`.md`) en la carpeta `articles`.
    * Utiliza Markdown para escribir tu artículo.
    * Asegúrate de incluir el siguiente front matter al principio de tu archivo:

    ```markdown
    ---
    layout: post
    title: "Título de tu artículo"
    permalink: /hu-blog
    date: DD-MM-YYYY
    ---
    ```

5.  **Realiza tu commit:**

6.  **Sube tus Cambios a GitHub:**
    * Sube tu rama a tu repositorio en GitHub:

    ```bash
    git push origin mi-articulo
    ```

7.  **Crea un "Pull Request":**
    * Ve a tu repositorio en GitHub.
    * Verás un mensaje que te pregunta si quieres crear un "pull request".
    * Haz clic en "Compare & pull request".
    * Escribe una descripción de tu contribución y haz clic en "Create pull request".

8.  **Espera la Revisión:**

> **INFO** Nota
Por favor, hacer un pull request por artículo, para que los administradores puedan tener un mejor control sobre lo que se publica.