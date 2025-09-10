# GoDorksPY - Herramienta OSINT con Google Dorks

![GoDorksPY Screenshot](https://via.placeholder.com/600x400?text=GoDorksPY+Screenshot) <!-- Placeholder for a future screenshot -->

## Descripción

GoDorksPY es una aplicación de escritorio desarrollada con Python y Flet, diseñada para simplificar las búsquedas OSINT (Open Source Intelligence) utilizando Google Dorks. Proporciona una interfaz gráfica de usuario intuitiva que permite a los usuarios generar automáticamente una variedad de consultas de Google Dorks basadas en una única entrada, facilitando la exploración de información pública en la web.

## Características

-   **Interfaz Gráfica Intuitiva**: Desarrollada con Flet para una experiencia de usuario moderna y responsiva.
-   **Búsqueda Simplificada**: Un único campo de entrada para tus consultas OSINT.
-   **Generación Automática de Dorks**: Transforma tu consulta en una lista de Google Dorks comunes y efectivos (ej. búsqueda de PDFs, documentos de Word, perfiles de LinkedIn, directorios públicos, etc.).
-   **Previsualización en la Aplicación**: Visualiza los detalles de cada dork generado (nombre, consulta dork, URL de Google) dentro de la aplicación antes de abrirlo en el navegador.
-   **Apertura en Navegador Externo**: Abre la búsqueda de Google Dork seleccionada en tu navegador web predeterminado con un solo clic.
-   **Tema Oscuro**: Interfaz con fondo negro y texto blanco, inspirada en la estética de los buscadores tradicionales y herramientas de seguridad.

## Instalación

Para ejecutar GoDorksPY, necesitarás tener Python instalado en tu sistema. Luego, puedes instalar Flet y las dependencias del proyecto:

1.  **Clona el repositorio** (si aún no lo has hecho):
    ```bash
    git clone https://github.com/tu_usuario/GoDorksPY.git # Reemplaza con la URL de tu repositorio
    cd GoDorksPY
    ```
2.  **Instala Flet** y las dependencias:
    ```bash
    pip install -r requirements.txt
    ```

## Uso

Una vez instalado, puedes iniciar la aplicación ejecutando el script principal:

```bash
python main.py
```

### Cómo funciona:

1.  **Introduce tu término de búsqueda**: En el campo de entrada principal, escribe el nombre, la empresa, el tema o cualquier término que desees investigar.
2.  **Genera las búsquedas Dork**: Haz clic en el botón "Generate Dork Searches".
3.  **Explora los resultados**: Aparecerá una lista de Google Dorks generados automáticamente. Cada elemento representa una búsqueda OSINT específica.
4.  **Previsualiza y Abre**: Haz clic en cualquier dork de la lista para ver sus detalles en una pantalla de previsualización dentro de la aplicación. Desde esta pantalla, puedes hacer clic en "Open in Browser" para ejecutar la búsqueda en Google.

## Contribución

¡Las contribuciones son bienvenidas! Si tienes ideas para mejorar la herramienta, por favor, abre un 'issue' o envía un 'pull request'.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.
