# IphoneDiagramaClass.dio
```plantuml
@startuml
+-----------------+
|    Iphone     |
+-----------------+
| + tocarMusica() |
| + pausarMusica() |
| + selecionarMusica() |
+-----------------+

+-----------------+
|    Player     |
+-----------------+
| + tocarMusica() |
| + pausarMusica() |
| + selecionarMusica() |
+-----------------+

+-----------------+
|    Telefone    |
+-----------------+
| + ligar()       |
| + atender()     |
| + encerrarChamada() |
+-----------------+

+-----------------+
|    Internet    |
+-----------------+
| + exibirPagina() |
| + addNewGuia()   |
| + attGuia()      |
+-----------------+
@enduml
