# 08 — Proyectos (Kanban)

1. [Proyectos, etapas, tareas, subtareas](#proyectos-etapas-tareas-subtareas)
2. [Tareas recurrentes, dependencias, hitos](#tareas-recurrentes-dependencias-hitos)
3. [Vistas: tarjetas, lista, calendario propio](#vistas-tarjetas-lista-calendario-propio)
4. [Calificación del cliente](#calificación-del-cliente)

### Proyectos, etapas, tareas, subtareas.

El modulo de proyectos es uno de los módulos que debemos instalar cuando empezamos la prueba gratuita. A la hora de crear un proyecto nos preguntara si va a ser facturable o no, lo cual puede ser útil ya que podríamos asignarle un cliente que tengamos guardado.

![Creacion de un proyecto](../assets/img/08-proyectos/paso01_crearProyecto.png)

Ya en del proyecto, lo primero que tendremos que hacer es crear una etapa, al lado de la etapa que acabamos de crear podremos darle a "Añadir etapa" para crear una nueva etapa del proyecto, como podría ser la etapa "En progreso" o "Finalizado".

![Creacion de etapas](../assets/img/08-proyectos/paso01_crearEtapas.png)

Dentro de una etapa, dándole al "+" podremos crear tareas, las cuales podrán ser asignadas a alguno de los usuarios de la base de datos. Podemos entrar en la tarea para configurar datos de ella como su descripción, el cliente, la prioridad o la fecha limite. Estas tareas podemos ir moviéndolas entre etapas simplemente arrastrándolas o desde la propia configuración de la tarea.

![Creacion de tareas](../assets/img/08-proyectos/paso01_crearTareas.png)
![Edicion de tareas](../assets/img/08-proyectos/paso01_editarTareas.png)
![Mover tareas](../assets/img/08-proyectos/paso01_moverTareas.png)

Además también, dentro de las tareas podremos crear subtareas lo cual nos va a ayudar a jerarquizar las prioridades. Incluso puedes entrar en la configuración de la subtarea para poner aun mas subtareas.

![Creacion de subtareas](../assets/img/08-proyectos/paso01_crearSubtareas.png)

### Tareas recurrentes, dependencias, hitos.

Nos tenemos que ir a los ajustes del proyecto, para ello pondremos el ratón sobre el proyecto y pinchamos en los tres puntos que aparecerán, acto seguido le daremos a ajustes y ahí activaremos las tareas recurrentes, las dependencias y los hitos.

![Activar opciones del proyecto](../assets/img/08-proyectos/paso02_activarHitos.png)

Ahora podremos irnos a alguna tarea de ese proyecto y nos aparecerá una opción con forma de rueda de carga. Si pulsamos en ella podremos decirle cada cuanto se va a estar repitiendo esta tarea y durante cuanto tiempo.

![Tareas recurrentes](../assets/img/08-proyectos/paso02_activarTareasRecurrentes2.png)

Otra de las opciones de ajustes es la dependencia de tareas. Al activarla, al lado de la opción de subtareas dentro de una tarea, aparecerá un nuevo botón llamado "Bloqueado por". Esto sirve para condicionar una tarea de forma que no pueda hacerla antes de hacer otra que le digamos.

![Dependencias](../assets/img/08-proyectos/paso02_Dependencias.png)

Por ultimo están los hitos. Los hitos sirven como puntos clave de seguimiento dentro de un proyecto. Son especialmente útiles para estructurar, controlar y comunicar el progreso de tareas importantes.

![Hitos](../assets/img/08-proyectos/paso02_hitos.png)

### Vistas: tarjetas, lista, calendario propio.

Los proyectos nos aparecerán como tarjetas, lo cual puede sonar familiar si se esta familiarizado con Trello. Sin embargo también podemos cambiarlo para que nos aparezca como si fuese una lista, en la cual podríamos ver no solo nuestras tareas sino también la del resto de usuarios de la base de datos.

![Lista de las tareas](../assets/img/08-proyectos/paso03_listaTareas.png)

Una de las formas de vista que nos permite usar Odoo es la de calendario, que nos permite ver las tareas recurrentes y las tareas pendientes por hacer. Un punto importante es que este calendario es único para el proyecto en el que lo vemos, ya que en Odoo no existe un calendario maestro en el que podamos ver todos los módulos que tengamos.

![Calendario de las tareas](../assets/img/08-proyectos/paso03_calendarioTareas.png)

### Calificación del cliente.

La opción de calificación del cliente es una opción muy útil en la que podamos recibir el feedback de los clientes, lo cual es una información muy importante para saber como lo vamos haciendo.

![Calificacion de clientes](../assets/img/08-proyectos/paso04_calificacionClientes.png)
