# Highlights Screen with Bottom Navigation
## Parte 2 del laboratorio
### Link del video de explicación: https://drive.google.com/file/d/1LqjmbsX68MTMSbj0twFG2e2oMbSKiNUQ/view?usp=drive_link
En esta parte se añadio una pestaña más a la aplicacion para las canciones favoritas, permitiendo la navegación entre pestañas sin problemas, la pestaña de canciones favoritas
unicamente muestra canciones marcadas como favoritas, y permite interactuar con ellas con total normalidad, a su vez que permite quitarles el estado de favoritas.

## Definition of done
| Criterio | Descripción |
|---------|-------------|
| Ruta existente | `HighlightsDestination` definido en `Destinations.kt` |
| Pantalla creada | `HighlightsScreen.kt` muestra las canciones favoritas filtradas |
| Barra inferior visible | `NavigationBar` con 2 `NavigationBarItem` |
| Cambio de pestañas funcional | Al tocar las pestañas se navega entre pantallas |
| Íconos correctos | Ícono de Home para Home, ícono de estrella para Highlights |
| Estado compartido | Marcar favorito en Home se refleja inmediatamente en Highlights |
| Pestaña actual resaltada | La pestaña activa se distingue visualmente |
