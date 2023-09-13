``` mermaid 
flowchart TB
A((Inicio))
B[/Año de nacimiento:/]
C[\an\]
D{an>0}
E[/Año actual:/]
F[\aa\]
G{aa>0}
H[edad=aa-an]
I[/tienes:,edad/]
J((Fin))

A --> B
B --> C
C --> D
D --> |no| B
D --> |si| E
E --> F
F --> G
G --> |no| E
G --> |si| H
H --> I
I --> J

```
<!--
dfd para calcular tu edad en base a años ingresados
por teclado
-->
<!--stackedit_data:
eyJoaXN0b3J5IjpbNDYwOTI4OTgsLTIwODg3NDY2MTJdfQ==
-->