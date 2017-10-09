
Nombre: Tomas Julian Lemus Rubiano

Codigo: A0054616

URL: https://github.com/tjlr50/so-exam1

Examen Parcial 1

1.

RETO sum_all_numbers

CMD CHALLENGE

![][1]

[1]:images/c1.PNG

CENTOS

![][2]

[2]:images/c1_centos.PNG


--


RETO replace_spaces_in_filenames

CMD CHALLENGE

![][3]

[3]:images/c2.PNG

CENTOS

![][4]

[4]:images/c2_centos.PNG

--


RETO reverse_readme

CMD CHALLENGE

![][5]

[5]:images/c3.PNG

CENTOS

![][6]

[6]:images/c3_centos.PNG

--

RETO remove_duplicated_lines


CMD CHALLENGE

![][7]

[7]:images/c4_1.PNG

![][11]

[11]:images/c4_2.PNG

CENTOS

![][8]

[8]:images/c4_centos.PNG

--

RETO disp_table

CMD CHALLENGE

![][9]

[9]:images/c5.PNG

CENTOS

![][10]

[10]:images/c5_centos.PNG

----

---

Realice un script que cumpla las condiciones que se describen a continuación. Presente capturas de pantalla relevantes como evidencias del funcionamiento.

Primera prueba para descargar libros del gutenberg SIN forma aleatoria: Aprobado

![][12]

[][12]:images/1.PNG


Primera prueba para descargar libros del gutenberg de forma aleatoria: Aprobado

Primero, creo un archivo prueba para generar aleatorios



[][13]:images/2.PNG

Segundo, incerto el valor aleatorio a la descarga del libro

[][19]:images/3.PNG




[][14]:images/4.PNG
 
 Por último, uso una dirección designada en la cual se va a reemplazar el libro en caso de que ya exista, por medio del siguiente Script:
 
 
[][15]:images/script.PNG


Realizar esta acción cada 5 minutos usando crontab: Aprobado

Edición contrab


[][16]:images/configuracion.PNG

Configuración crontab


[][17]:images/crontab.PNG

--

EVIDENCIAS

--

PRIMERA MUESTRA

[][18]:images/primerCorreo.PNG

[][19]:images/Prueba1.PNG


SEGUNDA MUESTRA

[][20]:images/segundoCorreo.PNG

[][21]:images/Prueba2.PNG


------------------------------------------------------


Describa el funcionamiento del código fuente rickroll.c del repositorio de github https://github.com/jvns/kernel-module-fun. 

Rickroll es una broma de internet que consiste en un enlace trampa disfrazado como algo de interés para que el usuario haga click sobre él, pero lo redirige hacia el vídeo musical de Rick Astley “Never Gonna Give You Up” (1987).1 Cuando una persona entra en el enlace que le lleva a este video musical, se dice que ha sido “rickrolleado”.

En este caso para los archivos con extensión .mp3. Esto se logra al obtener y modificar los llamados al sistema ejecuta la “víctima”, a partir de la modificación del cr0. Se cambia el NR_open, por lo que se desee mostrar (rickroll_open).




















