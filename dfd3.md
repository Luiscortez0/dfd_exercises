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

```
<!--
dfd para calcular tu edad en base a años ingresados
por teclado
-->
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE1OTk4ODA2NTYsLTIwODg3NDY2MTJdfQ
==
-->