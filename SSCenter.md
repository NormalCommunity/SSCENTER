
### Levantarse
>player.inventory/has/x

>player/leave

{img-eataeuena}
Despiertas en una habitación extraña con un dolor fuerte de cabeza te encuentras algo confuso y no recuerdas como has llegado allí.

Tras incorporarte puedes observar una habitación pequeña sin ventanas con una cama, armario, tv y un escritorio con <b>un documento</b>.

### Leer nota
>rooms.objects/has/note-welcome
>player.action/eq/1

>rooms.objects/remove/note-welcome
>rooms.name/change/Room_SS7
>rooms[4uxvht2a].open/change/true
>player/leave

{img-jxr3nqmk}
Bienvenido al SSCenter sujeto SS7
Tras la firma del contrato se suministro el nuevo medicamento experimental y ha sido trasladado a nuestras instalaciones centrales. 
Como acordamos en la entrevista, el proceso puede llevar de 2 a 3 semanas en algunos casos puede que más. 

Antes de comenzar hemos retirado su ropa, en nuestra instalaciones solo está permitido el uso de la ropa oficial.
En el armario de su habitación encontraras cada día la ropa oficial limpia y lista para su uso. Al salir de su habitación se encontrara con su maestra la cual te guiara por las instalaciones y enseñara las reglas de las instalaciones.

Desde SSCenter queremos darte las gracias por elegirnos.

### Observarse en el espejo
>rooms.objects/has/mirror
>player.action/eq/1
>player.equipment/dist/naked

>player/leave/

Te observas en el espejo:
{[player.equipment eq normal] [Llevas puesto la ropa oficial es de color blanca y negra.] []}

### Observarse en el espejo
>rooms.objects/has/mirror
>player/idle/
>player.equipment/eq/naked

>player/leave/

Te observas en el espejo:
{[player.equipment has naked] [Te encuentras completamente desnudo.] []}
{[player.character has normal-chest] [Tu pecho es normal no musculado.] []}
{[player.character has normal-dick] [Tu pene se encuentra flácido su tamaño es normal.] []}
{[player.character has normal-legs] [Tus piernas son normales y tienen bastante bello.] []}

### Abrir armario
>rooms.objects/has/cupboard
>player/idle

### Cambiarse de ropa
>player.action/eq/$("Abrir armario")


### Quitarse la ropa
>player.action/eq/$("Abrir armario")

### Cerrar el armario
>player.action/eq/$("Abrir armario")

>player/leave

Cierras el armario.
 
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTAxMDA2ODQ2LC0xMjczMzYzMDU2LC0xMz
MwMjA0MzM0LC02Mzc3MDc2ODZdfQ==
-->