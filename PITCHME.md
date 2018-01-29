## Curso de <span style="color: #e49436">javascript</span>
### Introducción a javascript
#### <span style="color: #e49436">Dictado por:</span>
##### Prof. Erick Agrazal
#### <span style="color: #e49436">¿A qué me dedico?</span>
##### A muchas cosas...

---

¿Qué es Javascript?
-------------------
- Es un lenguage de programación <span style="color: #e49436">Robusto</span>.
- Es un lenguage orientado a objetos y eventos.
- Inventado por: <span style="color: #e49436">Brendan Eich</span>.
- En estos momentos, esta presente en todas partes.

---

A lo nuestro
------------

### ¡Hola mundo!

---

Variables (Definición)
----------------------

- Todas las líneas deben terminar en punto y coma.
- Las variables pueden tener <span style="color: #e49436">casi</span> cualquier nombre.
- Sensibles entre mayúsculas/minúsculas.

```js
var nombreDeLaVariable;
```

---

Variables (Asignación)
----------------------

```js
nombreDeLaVariable = 'Hola mundo';
var nombreDeLaVariable = 'Hola mundo';

var nombreDeLaVariable = 'Bob';
nombreDeLaVariable = 'Steve';
```
---

Variables (Lectura)
-------------------

```js
nombreDeLaVariable;
```
---

Variables (Tipos de datos)
--------------------------

| Variable | Explicación                                                                                                                                 | Ejemplo                                                                                                                |
|----------|---------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------|
| String   | Una cadena de texto. Para indicar que la variable es una cadena, debes,escribirlo entre comillas.                                           | ```js var miVariable = 'Bob'; ```                                                                                      |
| Number   | Un número. Los números no tienen comillas.                                                                                                  | ```js var miVariable = 10; ```                                                                                         |
| Boolean  | Tienen valor verdadero/falso. true/false son palabras especiales en JS, y no necesitan comillas.                                            | ```js var miVariable = true; ```                                                                                       |
| Array    | Una estructura que te permite almacenar varios valores en una sola referencia.                                                              | ```js var miVariable = [1,'Bob','Steve',10];Llama a cada miembro del array así: miVariable[0], miVariable[1], etc. ``` |
| Object   | Básicamente cualquier cosa. Todo en JavaScript es un objeto y puede ser almacenado en una variable. Mantén esto en mente mientras aprendes. | ```js var miVariable = document.querySelector('h1');Todos los ejemplos anteriores también. ```                         |