# Grúñon

#### _La red social para quejarse de otros!_

Queres corregir y quejarte de opiniones ajenas? Esta es tu red social!

Aca te vamos a pasar continuamente opiniones ajenas, tu trabajo va a ser 
corregirlas. Convertite en un _cibercobani_ con un par de clicks!

***

**Iteracion 1**
Los usuarios pueden crearse una cuenta. Para ello, es necesario solamente un mail
y una password.

_Resultados_

- Registro satisfactorio: el usuario debe ver la pantalla de exito de registro
- Registro fallido: el mail ya esta en uso
- Registro fallido: el mail esta vacio / no cumple con el formato correcto
- Registro fallido: el usuario no pudo ser almacenado por problemas internos de almacenamiento

***

**Iteracion 2**

_Accion_

Los usuarios pueden loggearse en la plataforma.

_Resultados_

- Log in satisfactorio: el usuario debe ver la pantalla de bienvenida
- Log in fallido: credenciales invalidas
- Log in fallido: el sistema esta caido

***

**Iteracion 3**

_Accion_

Los usuarios pueden publicar quejas, una por vez.

_Resultados_

- Posteo satisfactorio: el usuario ve que su queja fue registrada.
- Posteo fallido: no hay texto en la queja
- Posteo fallido: no pudimos almacenar su queja

***

**Iteracion 4**

_Accion_

Los usuarios leen en un feed las opiniones ajenas, sin importar quien ni cuando la escribio, 
recibiendolas aleatoriamente.

_Resultados_

- Feed entregado satisfactoriamente: El usuario recibe una queja aleatoriamente
- Feed no entreado: El usuario ve que no es posible actualmente ver las quejas

***

**Iteracion 4b**

_Accion_

Los usuarios pueden opinar con audios. Los audios pueden ser corregidos pero 
unicamente mediante otro audio.

_Resultados_
Idem iteracion 4
***

**Iteracion 5**

_Accion_


Los usuarios pueden corregir las opiniones ajenas. Al ser corregidas, los usuarios
son notificados de la correccion. _Las correciones no pueden ser correjidas_.

_Resultados_

- Correccion procesada: El usuario que corrije pasa a la proxima queja, el usuario que recibe la correccion
es notificado
- Correccion no procesada: El usuario que corrije queda en la queja actual, se le informa que no se pudo 
guardar su queja

***

**Iteracion 5b**

_Accion_

Los usuarios al crearse la cuenta son loggeados automaticamente.

_Resultados_

Idem iteracion 2

\+

Idem iteracion 1 

***

**Iteracion 6**

_Accion_

Los usuarios pueden taggear sus opiniones y suscribirse a tags en el feed, a modo
de poder leer opiniones de solo ciertos temas.

_Resultados_

Al crear una queja, se añade la opcion de taggearla.
Un usuario que se suscribe a un/unos tag/s debe ver quejas solo de ese/esos tag/s

***

**Iteracion 7**
Las correcciones sobre las opiniones tambien son ofrecidas en el feed, manteniendo
el tag de la opinion corregida. Existe el derecho a replica, donde una correcion
puede ser corregida.

***

**Iteracion 6**
Estamos teniendo muchos usuarios, y la popularidad trae consigo a _los malignos_.
Estos tipos son molestos por naturaleza, y estan creando bots que llenan de basura
nuestra red. Para acabar con esto, se validaran los mails mediante un mail
de confirmacion. Los usuarios existentes tambien recibiran el mail de confirmacion,
y hasta que no confirmen su mail no podran operar en la red. Al ingresar, se les 
advierte de su situacion.

***

**Iteracion 7**

La mayoria de las opiniones provenian de bots. Cayeron las metricas de uso en una
magnitud significativa. Para entuciasmar a los usuarios, creamos 2 mecanismos

- **El aplauso**: Las correcciones pueden ser aplaudidas, entregando al corrector
    un aplauso. Semanalmente hay un ranking de los mas aplaudidos. El ranking 
    muestra al corrector y su correccion aplaudida. Inicia los lunes.
- **La censura**: Los usuarios que no corrijen usuarios por mas de una semana, 
    no podran opinar sin antes corregir a otro.
    
***

**Iteracion 8**
Las opiniones con audios no rinden. Eliminarlas.
