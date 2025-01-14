# Reproductor de Música con Listado de Canciones

Este proyecto es un simple reproductor de música basado en HTML, CSS y JavaScript que permite:
- Seleccionar varias canciones desde una carpeta.
- Mostrar una lista de las canciones seleccionadas.
- Reproducir canciones individuales haciendo clic en sus nombres.
- Navegar entre canciones usando los botones "Siguiente" y "Anterior".

## Características
1. **Selección de Archivos**:
   - El usuario puede seleccionar varios archivos de audio utilizando un input tipo `file` con la opción `multiple` habilitada.

2. **Listado de Canciones**:
   - Se genera una lista de los archivos seleccionados, mostrando sus nombres.
   - Cada elemento de la lista es clickeable y permite reproducir la pista correspondiente.

3. **Navegación Entre Canciones**:
   - Los botones "Siguiente" y "Anterior" permiten cambiar entre las canciones seleccionadas.

4. **Reproducción Activa**:
   - La canción que está en reproducción se resalta en la lista.

## Tecnologías Utilizadas
- **HTML**: Estructura de la página.
- **CSS**: Estilizado básico para mejorar la experiencia visual.
- **JavaScript**: Manejo de eventos, reproducción de audio y actualización de la interfaz.

## Instrucciones de Uso
1. Clona este repositorio o copia el código en un archivo `index.html`.
2. Abre el archivo en tu navegador.
3. Usa el botón para seleccionar archivos de audio desde tu dispositivo.
4. Los archivos seleccionados aparecerán listados.
5. Haz clic en una canción para reproducirla, o usa los botones "Siguiente" y "Anterior" para navegar entre las canciones.

## Código Principal
A continuación, una breve descripción de las secciones principales del código:

### HTML
- Input tipo `file` para seleccionar canciones.
- Elemento `<audio>` para la reproducción.
- Lista desordenada `<ul>` para mostrar las canciones seleccionadas.

### CSS
- Estilo para centrar y organizar los elementos visualmente.
- Resaltado de la canción activa con la clase `active`.

### JavaScript
- **Manejo de eventos:**
  - Detectar selección de archivos.
  - Reproducir la canción seleccionada.
  - Cambiar entre canciones usando los botones.
- **Creación dinámica de la lista:**
  - Los archivos seleccionados se listan automáticamente.
  - Se agrega un evento `click` a cada elemento de la lista.

## Ejemplo de Uso
Si seleccionas las siguientes canciones:
- `cancion1.mp3`
- `cancion2.mp3`
- `cancion3.mp3`

El reproductor mostrará una lista:
```
1. cancion1.mp3
2. cancion2.mp3
3. cancion3.mp3
```
Puedes hacer clic en cualquiera para reproducirla o usar los botones de navegación.

## Captura de Pantalla
_Añade una captura de pantalla aquí si es necesario._

## Requisitos del Sistema
- Navegador moderno compatible con HTML5 y JavaScript.

## Contribuciones
Si deseas mejorar este proyecto, siéntete libre de enviar un pull request o reportar problemas en el repositorio.

## Licencia
Este proyecto está bajo la Licencia MIT. Puedes usarlo libremente con fines personales o comerciales.

