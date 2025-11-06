# 07 — Calendario y Citas


### Calendario.

Odoo nos permite tener un calendario en el que apuntar todas nuestras actividades y nuestra agenda. Podemos verlo en formato de dias, semanas o meses. Tambien nos da la posibilidad de ver los calendarios de toda la gente de la empresa, lo cual puede venir muy bien para agendar una reunion.

![Calendario](../assets/img/07-calendario_y_citas/paso01_calendarioDisponibilidad.png)

### Integración con Google Calendar (API OAuth GCP).

Este calendario lo podemos conectar junto al calendario de google. Para ello tendremos que ir a tocar algunas cosas de la API.

Primero entraremos en google console y crearemos un nuevo proyecto y lo seleccionaremos. Despues en el buscador buscaremos Google Calendar API y la habilitaremo.

Una vez habilitada le daremos a crear credenciales y marcaremos las siguientes opciones:

- ![Tipo de credencial](../assets/img/07-calendario_y_citas/paso02_crearCredenciales1.png)
- ![Informacion de la aplicacion](../assets/img/07-calendario_y_citas/paso02_crearCredenciales2.png)
- ![Agregar permisos 1](../assets/img/07-calendario_y_citas/paso02_crearCredenciales3.png)
- ![Agregar permisos 2](../assets/img/07-calendario_y_citas/paso02_crearCredenciales4.png)

    La URL de redireccionamiento sera la siguiente:
    https://tuNombre.odoo.com/google_account/authentication

- ![URL de redireccionamiento](../assets/img/07-calendario_y_citas/paso02_crearCredenciales5.png)

    Con esto ya habremos terminado de modificar la API, ahora deberemos meternos en la pestaña de credenciales y buscar el proyecto.

- ![Buscar el proyecto](../assets/img/07-calendario_y_citas/paso02_crearCredenciales6.png)

    Una vez dentro del proyecto encontraremos el ID del cliente y el secreto del cliente. Estos datos deberemos copiarlos, nos iremos a los ajustes del calendario y encontraremos una zona donde podremos pegar esos dos datos(no olvidar darle a guardar).

- ![Informacion del cliente](../assets/img/07-calendario_y_citas/paso02_crearCredenciales7.png)
- ![Agregar el cliente](../assets/img/07-calendario_y_citas/paso02_agregarCliente.png)

### Eventos y Odoo Meet.

En el calendario podremos crear eventos, los cuales se crean tan facil como dar clic encima. Podremos ajustar tanto la fecha de inicio como la de fin, ademas de marcar si queremos que dure todo el dia.

![Creacion de eventos](../assets/img/07-calendario_y_citas/paso03_creacionEventos.png)

Al evento podemos adjuntarle una URL para una videollamada(zoom, meet, etc), pero Odoo tambien nos da una opcion para crear una reunion a traves de su propio servicio.

![Odoo meet](../assets/img/07-calendario_y_citas/paso03_odooMeet.png)

Tambien podremos editar los eventos para darle mas datos y hacerlo mas completo, por ejemplo, podriamos poner etiquetas, mandar correos electronicos a todos los participantes o añadir notas.

![Ajustes de eventos](../assets/img/07-calendario_y_citas/paso03_odooEventosAjustes.png)

### Módulo Citas (Enterprise): enlaces públicos, buffers, preguntas previas.

El modulo de citas es muy interesante si ofrecemos servicios de consultoria, servicios médicos, reservas de equipo, etc, en los que queremos que una persona se apunte a una hora concreta en la que interactuar con el. 

![Modulo de citas](../assets/img/07-calendario_y_citas/paso04_moduloCitas.png)

En los ajustes de las citas podremos ajustar cosas como el asunto, cuanto van a durar, el tiempo de disponibilidad o incluso si quieres reservar un usuario o un recurso.

![Ajustes de citas](../assets/img/07-calendario_y_citas/paso04_ajustesCitas.png)

Si le damos a compartir, nos creara un enlace el cual si lo copiamos y lo pegamos en el navegador, nos saldra unainterfaz donde el cliente podra elegir el dia y la fecha de cuando quiere la cita y luego debera agregar sus datos. 

![Enlaces](../assets/img/07-calendario_y_citas/paso04_enlaceCitas.png)
![Elegir cita](../assets/img/07-calendario_y_citas/paso04_elegirCita.png)
![Confirmar cita](../assets/img/07-calendario_y_citas/paso04_confirmacionCita.png)

Una vez confirmada la cita, en el informe de confirmacion nos saldra un boton que nos permitira añadir la cita al calendario de Google. Al hacerlo, si nos vamos de vuelta al calendario de Odoo, nos aparecera la cita recien creada en el.

![Apuntar cita en el calendario](../assets/img/07-calendario_y_citas/paso04_apuntarCitaCalendar.png)
![Ver la cita en el calendario](../assets/img/07-calendario_y_citas/paso04_verCitaEnCalendarioOdoo.png)