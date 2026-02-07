# Song Favorites
## Parte 1 del laboratorio
### Link del video de explicación: https://drive.google.com/file/d/1avG2VL4XR1uh-i1AfAkuP-lY40tRMj4i/view?usp=sharing
Esta parte se enfocó en poner en practica el funcionamiento de UDF y MVVM, manejando los cambios de estado.
Se añadio un boton de favoritos a las canciones en forma de corazón, el cual refleja el estado actual de una cancion dependiendo si esta marcada como favorita o no, cumpliendo el DoD.

| Criterio | Descripción |
|---------|-------------|
| Modelo actualizado | Song tiene el campo `isFavorite: Boolean = false` |
| Ícono de corazón visible | Cada `SongCard` muestra el ícono de corazón (relleno/vacío) |
| Elevación de eventos | `SongCard` recibe `onFavoriteClick: (String) -> Unit` |
| ViewModel maneja la acción | Método `toggleFavorite(id: String)` en el ViewModel |
| Estado se actualiza | Hacer clic en el corazón actualiza el estado de favorito de la canción |
| La UI refleja el cambio | El ícono del corazón cambia entre relleno y vacío |
| Sin estado en el componente hijo | `SongCard` es sin estado (recibe datos y emite eventos) |
