# Gestion-Universitaria
Manual de buenas prácticas en grupo para las actividades universitarias #UVM
- 📚 Manual de Buenas Prácticas de Gestión Universitaria

- Objetivo
Fomentar el uso de Git y GitHub para la colaboración y el control de versiones, creando un manual que recopile **buenas prácticas para realizar trabajos universitarios en grupo** (organización, gestión de tiempos, formatos, citación, presentación, etc.).

- Contenido del Manual
El manual está dividido en las siguientes secciones clave:
* Organización y Gestión de Tiempos
* Formatos y Estructura del Documento
* Normas de Citación (e.g., APA, ISO)
* Herramientas Colaborativas

-   Estructura del Repositorio
* `/documentos`: Contiene el manual principal.
* `/imagenes`: Contiene las imágenes y diagramas utilizados.
* `/referencias`: Documentos de apoyo y fuentes de información.

-  Cómo Contribuir

Para añadir o modificar secciones del manual, sigue este flujo de trabajo:

1.  **Crea un Issue** para la sección o error que deseas corregir o añadir (si no existe).
2.  **Crea una Rama** de trabajo a partir de `main`. Utiliza la convención `feature/nombre-de-la-seccion` o `fix/descripcion-del-error`.
    ```bash
    git checkout -b feature/seccion-2-formatos
    ```
3.  **Realiza los Cambios** en los archivos del directorio `/documentos`.
4.  **Crea un Commit** y en el mensaje, haz referencia al Issue que cierras (`Cierra #N`).
5.  **Abre un Pull Request (PR)** de tu rama hacia `main`.
6.  Una vez aprobado (o auto-aprobado en este caso), fúndelo (**Merge**).
7.  **Actualiza tu rama local** (`git pull origin main`).
