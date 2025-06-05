# cómo crear una aplicación de tareas en JavaScript
En este documento aprenderás a construir una aplicación sencilla de tareas utilizando JavaScript, HTML y CSS. Esta aplicación te permitirá agregar, completar y eliminar tareas.

###  Instrucciones Generales
1. Crea un archivo index.html.
2. Incluye un formulario para agregar nuevas tareas.
3. Muestra la lista de tareas debajo del formulario.
4. Guarda las tareas usando localStorage.4


### Código JavaScript Básico
Para agregar una nueva tarea, puedes usar el siguiente fragmento de código:
```javascript
const form = document.querySelector('form');
const input = document.querySelector('input');
const list = document.querySelector('ul');

form.addEventListener('submit', function(event) {
  event.preventDefault();
  const text = input.value.trim();
  if (text) {
    const li = document.createElement('li');
    li.textContent = text;
    list.appendChild(li);
    input.value = '';
  }
});
```

## Imagen de Ejemplo
![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQwmhEi0obPGjoa2Mt0_gOUNav2jQa7_Cab3SX0BcP1zkqapmZsqCvFZvNNk545qrfhRMU&usqp=CAU "ESTO ES UNA PRUEBA")

## Enlaces Recomendados
- [Link text Here](https://link-url-here.org)