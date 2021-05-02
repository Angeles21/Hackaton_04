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

---

2. ¿ Qué es PRETTIER y cuál es su uso?

PRETTIER es una herramienta que garantiza un mismo estilo consistente dentro del código de un proyecto, analizando sus componentes y ajustando de manera automática cada fez que es 
ejecutado. Es compatible con HTML, CSS, JavaScript, GraphQL, Markdown, YAML entre otros, y además también funciona correctamente con otros lenguajes como Ruby, PHP y Apex, aunque abarca muchos más. 

Su beneficio más notorio, es que al momento de trabajar en equipos grandes (los cuales implican múltiples posibilidades de como presentar una parte del código final) se mantiene una guía de estilo consistente que es aplicada de manera automática. No solo ahorra tiempo, sino que evita que los colaboradores del proyecto se sientan estresados con respecto a quien debe de re-escribir su parte para que iguale a las otras en cuanto a estilo se refiere. 

---

3. ¿Qué es .EDITORCONFIG y cuál es su uso?

Es una extensión que permite determinar un estilo consistente y compatible sin importar el editor que los miembros de un equipo utilicen. Permiten la lectura apropiada del código, así como su corrección sin necesidad de perder el tiempo en discusiones. 

- Alerta al programador cuando hay una "advertencia" en el código con respcto a como ha sido escrito o aplicado. 
- Facilita la comunicación entre los miembros de un equipo.
- Propiedades que pueden ser pre-determinadas (Estilo y tamaño de la sangría, recortes, espaciados, finales de línea, entre otros).


