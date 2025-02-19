[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vTkcPn0-)
# 2.-Dise-o-Orientado-a-Objetos
Primer acercamiento y prácticas guiadas e individuales de POO

classDiagram
    Compra <|-- Album : Tiene
    Compra <|-- Cliente : Realiza
    class Compra{
        - str nombreCliente
        - str nombreAlbumCompra
        - date fechaCompra
        - boolean estadoCompra
        + registroCompra()
        + devolucionCompra()
        + historialCompras()
    }
    class Album{
        - str titulo
        - int codigo
        - date fechaLanzamiento
    }
    class Cliente{
        - str nombreCliente
        - str nombreAlbumCompra
        - date fechaCompra
        - boolean estadoCompra
        + registroCompra()
        + devolucionCompra()
        + historialCompras()
    }

    