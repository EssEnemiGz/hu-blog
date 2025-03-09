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
    permalink: /posts/categoria/nombre-del-articulo
    date: DD-MM-YYYY
    ---
    ```

5.  **Compilar Jekyll:**
   Si no puede compilar su articulo, aviselo en la primera línea del Pull Requests (paso 8).
   **Linux:**
   1. Asegúrate de tener Ruby y Bundler instalados. Puedes instalarlos usando:
    - **Ubuntu:**
        ```bash
        sudo apt-get install ruby-full build-essential
        sudo gem install bundler
        ```
    - **Fedora:**
        ```bash
        sudo dnf install ruby-devel
        sudo gem install bundler
        ```
    - **Arch Linux:**
        ```bash
        sudo pacman -S ruby
        sudo gem install bundler
        ```
    - **OpenSUSE:**
        ```bash
        sudo zypper install ruby-devel
        sudo gem install bundler
        ```

   2. Navega a la carpeta del proyecto y ejecuta:
      ```bash
      bundle install
      bundle exec jekyll build
      ```

   **Windows:**
   3. Instala Ruby usando el instalador de RubyInstaller. Asegúrate de seleccionar la opción para agregar Ruby al PATH.
   4. Abre una terminal (cmd o PowerShell) y ejecuta:
      ```bash
      gem install bundler
      ```
   5. Navega a la carpeta del proyecto y ejecuta:
      ```bash
      bundle install
      bundle exec jekyll build
      ```

   **MacOS:**
   6. Instala Homebrew si no lo tienes. Luego, instala Ruby y Bundler:
      ```bash
      brew install ruby
      gem install bundler
      ```
   7. Navega a la carpeta del proyecto y ejecuta:
      ```bash
      bundle install
      bundle exec jekyll build
      ```

6.  **Realiza tu commit:**

7.  **Sube tus Cambios a GitHub:**
    * Sube tu rama a tu repositorio en GitHub:

    ```bash
    git push origin mi-articulo
    ```

8.  **Crea un "Pull Request":**
    * Ve a tu repositorio en GitHub.
    * Verás un mensaje que te pregunta si quieres crear un "pull request".
    * Haz clic en "Compare & pull request".
    * Escribe una descripción de tu contribución y haz clic en "Create pull request".

9.  **Espera la Revisión:**

> **INFO** Nota
Por favor, hacer un pull request por artículo, para que los administradores puedan tener un mejor control sobre lo que se publica.