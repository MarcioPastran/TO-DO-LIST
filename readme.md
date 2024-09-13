#Proyecto de lista de tareas pendientes (TO DO LIST)
Este proyecto es una sencilla aplicación de lista de tareas basada en la web que permite a los usuarios agregar, administrar y eliminar tareas. Está construido con HTML, CSS y JavaScript, y las tareas se almacenan en el , por lo que la lista de tareas persiste incluso después de que la página se actualice o se cierre.localStorage

#Funciones
-Agregar tareas: Los usuarios pueden agregar nuevas tareas usando un campo de entrada y un botón (o presionando la tecla).Enter
-Marcar como completadas: los usuarios pueden marcar las tareas como completadas, lo que marca el nombre de la tarea y cambia el icono.
-Eliminar tareas: Los usuarios pueden eliminar tareas de la lista.
-Almacenamiento persistente: Las tareas se almacenan mediante , por lo que permanecen incluso si la página se actualiza o se cierra.localStorage
-Diseño responsivo: La aplicación es responsiva y funciona bien tanto en dispositivos de escritorio como móviles.
-Fecha dinámica: La fecha actual se muestra en la parte superior de la página.

#Estructura del proyecto

APP DE TAREAS/
│
├── index.html  
├── style.css  
├── script.js  
└── README.md

#Archivos
index.html: Contiene la estructura de la página web, incluidos los campos de entrada, la lista de tareas y los iconos.
style.css: Diseña la aplicación con fuentes, colores y diseños personalizados.
script.js: controla la adición, eliminación, finalización de tareas y la funcionalidad localStorage.

#Tecnologías Utilizadas
HTML5: Estructura de la página web.
CSS3: Estilo de los elementos, incluyendo la capacidad de respuesta y los colores.
JavaScript (ES6): Interactividad de la lista de tareas pendientes, incluida la manipulación del DOM y el manejo de localStorage.
FontAwesome: Se utiliza para iconos como el signo más (agregar), la marca de verificación (completar) y la papelera (eliminar).
Google Fonts: Fuente utilizada en el proyecto, concretamente en la familia tipográfica "Prompt".

#Modo de empleo
Abra la aplicación: Simplemente abra el archivo en su navegador.index.html
Agregar una tarea: Escriba una tarea en el campo de entrada y haga clic en el icono más o presione .Enter
Marcar como completado: haz clic en el icono circular junto a una tarea para marcarla como completada.
Eliminar una tarea: haga clic en el icono de la papelera para eliminar una tarea de la lista.
Persistencia de tareas: Actualiza la página y tus tareas seguirán ahí, gracias a localStorage.
