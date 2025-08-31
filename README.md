# Descargador de Libros de Archive.org

Este proyecto es un script de Wolfram Mathematica diseñado para automatizar la descarga de libros desde [archive.org](https://archive.org). El script extrae el número total de páginas de un libro, inicia sesión en una cuenta de archive.org y luego captura cada página, guardándola como un archivo PDF individual.

## Funcionalidades


-   **Automatización de sesión:** Inicia sesión en archive.org de forma automática utilizando las credenciales proporcionadas.
-   **Captura de páginas:** Navega a cada página del libro, espera a que se cargue completamente y toma una captura de pantalla.
-   **Procesamiento de imágenes:** Recorta las capturas de pantalla para separar las páginas individuales y las guarda como archivos PDF.

## Cómo se usa

1.  **Instalar Wolfram Mathematica:** Para ejecutar este script, es necesario tener instalado Wolfram Mathematica en su sistema.
2.  **Configurar el script:**
    *   Abra el archivo `last3.nb` en Wolfram Mathematica.
    *   **URL del libro:** Modifique la variable `url` con el enlace al libro de archive.org que desea descargar.
    *   **Credenciales:** Actualice las variables `email` y `password` con sus propias credenciales de archive.org.
    *   **Directorio de destino:** Cambie la ruta en la función `SetDirectory` para establecer la carpeta donde se guardarán los archivos PDF.
3.  **Ejecutar el script:** Ejecute el notebook en Wolfram Mathematica para iniciar el proceso de descarga.

## Descargo de responsabilidad

Este script está destinado únicamente para fines educativos y de uso personal. El uso de este script para descargar material protegido por derechos de autor puede infringir las leyes de su país y los términos de servicio de archive.org. Por favor, utilice esta herramienta de manera responsable y respete los derechos de autor. Los desarrolladores de este script no se hacen responsables del mal uso que se le pueda dar.
