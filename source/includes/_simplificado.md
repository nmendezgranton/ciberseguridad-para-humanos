# Ciberseguridad para humanos


Esta guía está pensada **para gente que no tiene conocimientos técnicos** y necesita conocer cómo protegerse de riesgos básicos a los que todos estamos expuestos.

* No utilizaremos lenguaje técnico.
* No abarca temas en profundidad.



<aside class="warning">
<strong>Si crees que te han hackeado esta guía no te ayudará:</strong><br />
Esta guía es preventiva. Para este caso deberás contratar a un especialista que analice qué tan comprometido es tu caso, y evaluar cuánto y como es posible recuperarlo.
</aside>

# Claves/contraseñas

* **Todo tiene que tener una clave** - Tu ordenador al iniciar, tu cuenta de correo, tu smartphone, tu Wi-Fi. Esto es porque cada uno puede utilizarse para desbloquear los otros.

* **Las claves deben ser largas y complejas** - Si tu clave es `martina`, un programa automático puede averiguarla en 7 minutos, agrégale una mayúscula, un punto y algunos números `Martina.18` y tardará milenios.

* **No uses la misma clave en todos lados** - Si lo haces y un atacante hackea cualquiera de los servicios que no tuviera medidas de seguridad suficientes, todas tus cuentas estarán expuestas.

* **No las escribas en notas / archivos / post-it** - Es una pésima idea usar las notas de tu smartphone, documentos o planillas para guardarlas. Usa la función "guardar contraseña" que ya tienes en tu navegador de internet. [Más info](./claves/).

* **No las mandes por mail** - El mail no es tan seguro como crees, además si un día hackean tu correo tienen tus claves.


# Correo electrónico

* **Es increiblemente fácil de falsificar** - Nunca confíes en un correo electrónico solamente por su remitente. Te sorprendería lo fácil que es enviar un correo en nombre de otra persona o entidad (como un banco).

* **Abre adjuntos sólo si los estás esperando** - Es común que una PC infectada envíe correo a todos los contactos que encuentre, así que es altamente probable recibir un virus de alguien conocido.

* **Nunca envíes información confidencial** - Aunque tu conexión con el proveedor sea segura, la transmisión entre servidores no lo es. Así que si lo que envías es realmente confidencial no lo hagas por correo.

* **Cambia tu clave con frecuencia** - Hoy en día utilizamos el mail para desbloquear/resetear todas las demás claves, si alguien accede a tu correo es un tema posiblemente grave.


# Antivirus y antimalware

**Usuarios de Mac o Linux** - Puedes ignorar toda esta sección.

**Usuarios de Windows** - Es absolutamente necesario que tengas un antivirus y un antimalware. Si utilizas Windows 10, es probable que tengas activo Windows Defender, un antivirus de Microsoft que ha probado ser efectivo.

### Antivirus

Todos los antivirus se mantienen actualizados y protegen tu equipo en tiempo real (no necesitas hacer nada más). Si no tienes uno, te recomendamos alguno de los siguientes (que tienen opciones gratuitas):

* [Avast!](https://www.avast.com/)
* [AVG](https://www.avg.com/)

### Antimalware

Un antimalware te protege de otras amenazas además de los virus. Entre otras cosas permite eliminar:

* Complementos que abren ventanas emergentes (popups) en tu navegador.
* Programas no deseados que se instalan sin tu consentimiento.
* Utilidades de robo de información (spyware) y ransomware.

Actualmente recomendamos Malwarebytes Antimalware: [link](https://es.malwarebytes.com/).

### Ignora avisos inútiles

Ten en cuenta que los antivirus gratuitos hacen dinero vendiendo funciones adicionales. Algunos de ellos **han optado por alarmar a los usuarios por cada riesgo mínimo sin sentido** para lograr que compren el producto pago.<br />Lamentablemente es responsabilidad del usuario (o sea tuya), evaluar si lo que te advierte el antivirus es un riesgo real y potencialmente peligroso (como un virus), o alguna pavada como que alguien puede ver tu dirección IP (de internet).


# Programas actualizados

A más viejo el programa (incluido el sistema operativo) más vulnerable. En lo posible:

* **Utiliza un sistema operativo reciente** - Utiliza el sistema operativo más reciente que tu PC admita.

* **Activa las actualizaciones automáticas** - Tanto del sistema operativo como de los programas.

# Copias de seguridad

> Si tu equipo fue atacado por una horda de chimpancés cibernéticos que han destruido toda tu información y te piden rescate, puedes recuperarla si has hecho una **copia de seguridad**.

Si todo lo anterior falló y has perdido o te han robado la información, podrás recuperarla de manera rápida restaurándola  desde un backup que has hecho (esperemos) recientemente.

### Opciones para Backup

1. **Copia manual en un pen drive / disco externo** - Puedes enchufar cada tanto el pen drive a tu ordenador y copiar manualmente las carpetas que quieras resguardar, ten en cuenta hacerlo tan seguido como te parezca adecuado.

2. **Utilidad de respaldos de tu sistema operativo** - Algunos sistemas operativos incluyen funciones para hacer respaldos automáticos de la información. Aquí tienes instrucciones para [Windows 10](https://support.microsoft.com/es-ar/help/4027408/windows-10-backup-and-restore) y [Mac OS](https://support.apple.com/es-es/HT201250).

3. **Backup en la nube** - Puedes usar [Google Drive](https://drive.google.com/), [Dropbox](https://www.dropbox.com/) u otros servicios de sincronización de archivos para mantener una copia de tus archivos en internet. Además con la ventaja de poder acceder a ellos en cualquier lugar y dispositivo.

# Limpiar tu equipo

Es normal que, con el tiempo, tu equipo se vaya poniendo lento gradualmente hasta que un día tengas que reinstalarlo. Ahora, si esto ocurre de un día para otro o realmente está demasiaaaaaaadddo leeeeeentooo, puede ser un indicador de que tenga algún tipo de infección de virus o malware.

**Otros signos de posible infección**:

* Al estar navegando en internet se abren páginas solas.
* Se ha cambiado la página de búsqueda o la página inicial.
* Aparece publicidad de la nada.

### Usuarios de Windows

1. Actualiza tu antivirus y escanea tu equipo.
2. Instala un antimalware y escanea tu equipo.

# Empresas

Las empresas se encuentran con todo un panorama distinto de seguridad y se debe a que en general se comparten recursos (como archivos) entre distintos equipos, utilizados por distintos usuarios, con distintos roles, niveles de conocimiento y hábitos.

Es un tema extenso y realmente si la información es una preocupación, conviene contratar un profesional para analizar el caso particular. Dicho esto, algunas recomendaciones generales:

1. **Cada quien con su clave** - No se deben compartir usuarios y claves entre empleados. Esto permite trazabilidad (si hay algún problema), mayor control y aislar posibles problemas.

2. **Política de mínimos privilegios** - No dar acceso a los usuarios a recursos (archivos, carpetas) a los que no necesiten acceso para llevar a cabo sus funciones. Esto permite reducir el impacto en caso que su usuario se vea comprometido.

3. **Controlar el uso de internet** - Bloquear categorías de sitios de internet que puedan ser riesgosas para la integridad de los equipos y la información: pornografía, descarga de películas, sitios para ver películas online pirateadas.

4. **Backups rotativos** - Mantener copias históricas (no sólo la última) de la información importante; esto permite recuperarla incluso si se detecta un problema mucho tiempo después.

5. **No compartir Wi-Fi con clientes** - Esto hace que puedan ver los equipos de la red y potencialmente acceder a la información en ellos. La mayoría de los routers modernos permiten crear una red adicional para invitados (aislada y segura).

# Modo paranoia: On

**¿Tapo la cámara?** - Si tu equipo está infectado por un malware (en muchos casos ni te enteras) podría acceder a ver/grabar desde tu webcam. Así que la **respuesta corta es Si**.

**¿Es seguro guardar fotos privadas en mi equipo?** - De nuevo esto dependerá si tu equipo está infectado por algún tipo de malware (o lo estará en el futuro). Es bastante común que si nos roban este tipo de fotos, pidan un "rescate" para no divulgarlas. Así que **No recomendable**

**¿Es seguro el Home banking?** - Los bancos invierten muchos recursos en mantener sus sistemas tan seguros como sea posible. Dicho esto, la otra parte de la seguridad la determina el equipo que utilizas para conectarte, si puedes confiar que es seguro y no está infectado por un virus o spyware. <br />Así que se resume en: **¿que tanto confías en tú equipo?**.

**Navegación privada** - Hay distintos niveles al hablar de navegación privada. Para conocer qué puedes volver privado y cómo visita [este link](./navegacion-privada/).
