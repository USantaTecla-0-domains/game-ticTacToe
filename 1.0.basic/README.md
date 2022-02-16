# game-ticTacToe.1.0.basic
Universo Santa Tecla  
[uSantaTecla@gmail.com](mailto:uSantaTecla@gmail.com)  
  
## useCaseView 

* [requirements](#requirements)  
* [actorsUseCaseDiagram](#actorsUseCaseDiagram)   
* [useCaseContextDiagram](#useCaseContextDiagram)
* [useCaseSpecification](#useCaseSpecification)
    * [startUseCaseSpecification](#startUseCaseSpecification)
    * [playUseCaseSpecification](#playUseCaseSpecification)
    * [resumeUseCaseSpecification](#resumeUseCaseSpecification)   
* [interfacePrototype](#interfacePrototype)   

### requirements 

* _glosary: **[ticTacToe](../README.md)**_
* _functionality: **basic**_
* _interface: **console**_
* _distribution: **standalone**_
* _persistence: **not**_

### actorsUseCaseDiagram

![TicTacToe](../docs/diagrams/out/__WorkspaceFolder__/1.0.basic/docs/actorsUseCaseDiagram/actorsUseCaseDiagram.svg)

### useCaseContextDiagram

![TicTacToe](../docs/diagrams/out/__WorkspaceFolder__/1.0.basic/docs/useCaseContextDiagram/useCaseContextDiagram.svg)

### useCaseSpecification

#### startUseCaseSpecification
 
![Start](../docs/diagrams/out/__WorkspaceFolder__/1.0.basic/docs/startUseCaseSpecification/startUseCaseSpecification.svg)  

#### playUseCaseSpecification

![Play](../docs/diagrams/out/__WorkspaceFolder__/1.0.basic/docs/playUseCaseSpecification/playUseCaseSpecification.svg)  

#### resumeUseCaseSpecification

![Resume](../docs/diagrams/out/__WorkspaceFolder__/1.0.basic/docs/resumeUseCaseSpecification/resumeUseCaseSpecification.svg)  

### interfacePrototype
  
```
--- TIC TAC TOE ---
-------------
|   |   |   |
-------------
|   |   |   |
-------------
|   |   |   |
-------------
Turno para X
Fila destino:  2
Columna destino:  2
-------------
|   |   |   |
-------------
|   | X |   |
-------------
|   |   |   |
-------------
Turno para Y
Fila destino:  3
Columna destino:  1
-------------
|   |   |   |
-------------
|   | X |   |
-------------
| Y |   |   |
-------------
Turno para X
Fila destino:  3
Columna destino:  3
-------------
|   |   |   |
-------------
|   | X |   |
-------------
| Y |   | X |
-------------
Turno para Y
Fila destino:  1
Columna destino:  1
-------------
| Y |   |   |
-------------
|   | X |   |
-------------
| Y |   | X |
-------------
Turno para X
Fila destino:  2
Columna destino:  1
-------------
| Y |   |   |
-------------
| X | X |   |
-------------
| Y |   | X |
-------------
Turno para Y
Fila destino:  2
Columna destino:  3
-------------
| Y |   |   |
-------------
| X | X | Y |
-------------
| Y |   | X |
-------------
Turno para X
Fila origen:  2
Columna origen:  1
Fila destino:  1
Columna destino:  2
-------------
| Y | X |   |
-------------
|   | X | Y |
-------------
| Y |   | X |
-------------
Turno para Y
Fila origen:  2
Columna origen:  3
Fila destino:  2
Columna destino:  1
-------------
| Y | X |   |
-------------
| Y | X |   |
-------------
| Y |   | X |
-------------
Victoria para Y
¿Quieres jugar otra partida?
```
