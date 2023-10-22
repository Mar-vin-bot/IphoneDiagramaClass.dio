# IphoneDiagramaClass.dio

```mermaid
classDiagram
    class Iphone {
    }

    class Player {
        + tocarMusica()
        + pausarMusica()
        + selecionarMusica()
    }

    class Telefone {
        + ligar()
        + atender()
        + encerrarChamada()
    }

    class Internet {
        + exibirPagina()
        + addNewGuia()
        + attGuia()
    }

    Iphone --> Player: 
    Iphone --> Telefone: 
    Iphone --> Internet: 
```
