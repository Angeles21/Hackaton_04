1. ¿Qué es ESLINT y cuál es su uso?

Lint (definido como pelusa o hilachas en español) son herramientas de programación 
diseñadas para ubicar problemas dentro del código de un proyecto, aspectos de este que puedan entorpecer el trabajo, ponerlo en riesgo o en general que lo vuelva más complicado
de entender de lo que realmente tiene que ser.  Ayudan a localizar problemas y errores 
no necesariamente de tipo sintácticas (por ejemplo, errores de cálculo entre variables 
que quieren emplearse). Funcionan bajo un análisis estático, lo que significa que no 
necesitan ejecutar el programa para revisarlo. 

ESLINT es un derivado de las herramientas lint, efocado para Javascript para ayudar al desarrollador a mantener el orden y evitar errores humanos, ya que el lenguaje utilizado en Javascript abarca muchos tipos de conceptos y estilos de escritura. ESLINT permite determinar que comandos son posibles, y cuales requieren corrección. 

Hay tres partes que conforman ESLINT: Parser, Reglas y Resultado. 

Parser convierte el código elaborado por el programado a una representación abstracta (referido como Árbol de Sintaxis Abstracto) que pueda ser comprendida por el ordenador. 

Las Reglas, como su nombre lo indica, permiten encontrar la mayor cantidad de errores analizando cada nodo del Árbol mencionado anteriormente, y así puede alertar al programador de la falla. Tambien puede ofrecer una solución si el error en particular se de ocurrencia común. Las Reglas se aplican por medio de un Transformador, el cual permite visualizar que nodo está siendo analizado actualmente.

Por útlimo, el Resultado. Se puede definir como el reporte final de todos los errores y observaciones que ESLINT tiene al final de su análisis. Este puede leerse en más de un editor de texto para tener más versatilidad con diferentes programadores. 


Entre los beneficios de usar ESLINT podemos nombrar: 

- Mostrar errores o equivocaciones (ya sean por falla humana o por malas prácticas de programación).
- Muestra errores de sintáxis.
- Mantiene un estilo consistente y fácil de comprender (especialmente útil en trabajos que requieren apoyo de diferentes miembros).
- Ofrece sugerencias de mejora. 