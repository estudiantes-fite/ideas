# Ahora mismo tenemos pensado:

- Automatizar las asignaciones de PITE1
    - Iván tiene algo adelantado sobre esto desde primero, vamos a retomarlo y hacerlo viable

- Montar un FTP
   - Tenemos un FTP funcionando en local cortesía de Iván
   - El FTP está montado como un contenedor de Docker
   - Ahora mismo permite a cualquiera subir y bajar cosas. Pero podemos agregar un sistema de permisos
   - El objetivo es facilitar la distribución y poder integrar mejor la bibliografia con las otras cosas que podemos hacer, como el sistema de anuncios. Es mucho más fácil cuando las cosas están en un sistema de archivos de toda la vida

- Un horario general para la facultad
   - Automatizar hasta donde tenga sentido la generación del horario y el calendario general de eventos (dígase pruebas Bastiones y Aniversarios, etc.)
   - Los objetivos son:
        - evitar que un profesor que da clases en dos años le asignen el mismo turno en dos lugares (Nos ha pasado con Física II y Economía Política)
        - Que de los eventos que son para toda la facultad se enteren todos (esto va integrado al sistema de anuncios)
pase
- Hacer un sistema de anuncios (Estilo hubo una reunión de cualquier conjunto de personas y cada cual de la facultad se entera de lo que debe enterarse)
   - Podemos agregar a los estudiantes automáticamente al grupo del año
   - Podemos enviar mensajes por correo, hacer bots de Whatsapp y Telegram para anunciar cambios de todo tipo 
        - Anunciamos cada vez que hay un cambio en el horario que está en el FTP y damos un enlace de descarga automáticamente
        - De la misma forma podemos suscribirnos a cualquier cambio del FTP y el teleportal para informar a los que haga falta informar de cualquier cosa
        - Podemos clasificar los mensajes por urgencia o importancia (cambiamos el formato de la plantilla de cada mensaje como sea necesario)

- Engrasar el proceso que va desde que el profesor da la nota hasta que secretaría la confirma
   - A ver si no suspendemos más asignaturas de las que suspendemos nosotros (Muchos tenemos arrastres en secretaría que se deben a errores de la nota, este problema llega hasta el punto de que a varios estudiantes se les da de baja automáticamente sin motivo real porque en secretaría aparece que tienen más de dos asignaturas suspensas)
   - El problema es que los errores de las notas en secretaría ahora mismo son prolíficos, y todavía hay notas que no están en Sigenu. Estudiantes de otros años nos dicen que han pasado uno y dos cursos sin que esta u otra nota aparezcan en Sigenu. 
   - El objetivo es identificar los problemas que hacen que eso demore tanto y termine con tantos errores. Sabemos que hay soluciones hechas pero por los resultados que se están obteniendo, nos parece que o las soluciones no funcionan, o no se implementan, o no lubrican todo lo que podrían.
   - Lo que proponemos es implementar x cantidad de pequeñas soluciones que agilicen el proceso, soluciones que tengan como objetivo cada punto que haga falta desde el profesor hasta Sigenu.

- Mejorar el uso de moodle en la facultad 
   - Esto pasa desde hacer más cosas con moodle hasta crear procesos para limar asperesas con los profesores que no les gusta usarlo (si no les gusta es porque no les gusta algo de Moodle o cómo se pretende que lo usen, nadie rechaza la posibilidad de facilitarse la vida porque sí)

- Ver cómo podemos mejorar la disponibilidad de los servicios críticos (ahora mismo estamos pensando en Moodle, el FTP y el teleportal)
  - Este es uno de los puntos más importantes. Una de las razones por las que la gente prácticamente no use el teleportal y no les guste Moodle es que en cualquier momento están caídos cuando hacen falta. Sabemos que hay muchas cosas que no posiblemente no podamos tocar (el correo es otro que nos ha estresado bastante por pasarse no sé cuántos días caído, sobre todo cuando pasamos por las prácticas y PITE, pero tenemos conciencia de que trabajar fuera del alcance de la facultad es complicado para empezar)
  - Este punto pasa por verificar por qué se están callendo tanto e implementar medidas para que eso no pase, como buscar formas de que usen menos recursos o hacerle la alta disponibilidad a todo lo que se pueda para que los servicios no estén por gusto cuando la gente vea que se caen 3 veces seguidas en que los necesitan.
