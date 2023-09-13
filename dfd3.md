``` mermaid 
flowchart TB
A((Inicio))
B[/Año de nacimiento:/]
C[\an\]
D{an>0}
E[/Año actual:/]
F[\aa\]
G{aa>0}

A --> B
B --> C
C --> D
D --> |no| B
D --> |si| E
E --> F
F --> G
G --> |no| E

```
<!--
dfd para calcular tu edad en base a años ingresados
por teclado
-->
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0ODc5NTU3MjgsLTIwODg3NDY2MTJdfQ
==
-->