# WMulticanal

Plugins wp Muestra un boton flotante en el front-end con los diferentes canales sociales y captura los datos del cliente. Tiene panel adminitrativo para configurar los correos de los agente que asisten a los clientes, como se va a mostrar el boton, el formulario de los canales, muestra los reportes por cada uno de los agentes que asisten a los clientes.



**Imagen del panel de control para las comfiguraciones de los correos del admin, los agentes, creacion del formulario del boton flotante de los canales sociales y la credenciales de MailChimp**

![WmPanel](https://user-images.githubusercontent.com/36554510/233482341-09037233-ed4f-4cc5-a6f7-ff5207354fb0.jpg)


**Configuracion de los correos admin**
>los correos admin son donde llegan todos los correos que son enviados por el sistema de agente Wmulticanal
![WmPanelConfigCorreoAdmin](https://user-images.githubusercontent.com/36554510/233482363-8fa358ca-45dc-4550-9277-85e79f42ec44.jpg)

**Registro de los agentes**
>Se puedes registrar varios agentes que el sistema los mandara los clientes uno por uno segundo la disponibilidad en los horarios de cada agente
![WmPanelRegisterAgente](https://user-images.githubusercontent.com/36554510/233482410-08ccc07f-ee02-4dfb-8836-5c1a48caeabd.jpg)



**Editor de los agentes**
>El editor de los agentes se puede editar hasta el rol ya que el sistema tiene un uso del lado del front end como los trabajadores pueden gestionar su perfil y cambiar sus datos y sus reportes de los clientes que ellos han atendido.
![WmPanelEditarAgente](https://user-images.githubusercontent.com/36554510/233482420-693b60ea-62cb-4f61-b4cf-206340e0c863.jpg)



**Suspender agentes**
>Los agentes puedes ser suspendidos de esa manera el sistema no les mandaran los clientes asi en su ahorario esten disponibles.
![WmPanelSuspendido](https://user-images.githubusercontent.com/36554510/233482395-1bf9481d-370c-40cd-8a88-08a751ac7b30.jpg)



**Eliminar agentes**
>Este es el mensaje que se muestra para confirmar si quiere eliminar un agente de sistema.
![WmAgenteEliminar](https://user-images.githubusercontent.com/36554510/233481730-d7237244-980f-4e2e-9c6c-60e5bfa0452b.jpg)



**Activar credenciales de MailChimp**
>El sistema tambien tiene la opcion de trabajar con la plataforma MailChimp para aumentar las posibilidades de mejorar el marketing por correos masivos.
![WmPanelCredencialMailChimp](https://user-images.githubusercontent.com/36554510/233481675-645350d7-7e10-48ab-be75-fa20421a1b51.jpg)



**Confirguracion del boton flontante con su formulario**
>Aqui en la siguientes imagen se muestra las opciones que se tiene para configurarlo, aqui se tiene activado las alertas en las siguientes imagenes se muestran las demas acciones activas y como se muestran.
![WmPanelConfigFormAlerta](https://user-images.githubusercontent.com/36554510/233481561-b84988d1-a7e0-42fb-8ecc-8df5b693c35e.jpg)



**Confirguracion del boton flontante con su formulario Con respuesta selector**
>Los selectores son 10 opciones que tienen los clientes en seleccionar que sean referente a lo que ellos buscan y el agente les pueda responder
![WmPanelConfigFormList](https://user-images.githubusercontent.com/36554510/233481641-54b00478-f545-4b11-8006-c21607c1eeba.jpg)



**Confirguracion del boton flontante con su formulario respuesta escrita**
>En esta parte les muestro la imagen con la opcion respuesta escrita a lo que busca el clientes para ser atendido por los agentes disponibles
![WmPanelConfigFormEscribir](https://user-images.githubusercontent.com/36554510/233481618-1144712e-8f76-4b08-9389-8dddbf937695.jpg)



**Confirguracion del boton flontante con su formulario respuesta ninguna**
![WmPanelConfigFormNinguno](https://user-images.githubusercontent.com/36554510/233481660-23b38ed5-eee6-449e-9d88-198c79c35296.jpg)



**Formulario Externo**
>Tambien tenemos la opcion si no queremos o si necesitamos un formulario directo en las paginas crear un formulario con cualquier editor como Elementor colocar a los campos del formulario los siguietes ID [usuarios_contactos], formulario name ( swconsulta ) ID campos: ( ID para el nombre usar: swname, ID para el Num Telefono usar: swtlf, ID para el Email usar: swemail, tamabien tiene para 5 campos opcionales de la siguiente extrutura los ID escribiendo primero switem1 cambiando el numero una hasta el Num 5 separado con la palabra "separar" seguido con el titulo del campo con los espacios cambiandolos por guiones bajoseste_es_titulo_del_campo por ejemplo switem5separarEste_es_el_titulo_del campo como puede ver este ejemplo fue con el numero 5 pero lo primero si es obligatirio switem despues el numero del 1 al 5 y la para "separar" seguido el nombre o titulo del campo seprado por guiones bajos "_"  al boton del formulario externo se le colocara el siguiente  ID Boton ( swbtnconsulta ). Para el seguimiento de los click como para Google Analytics son los siguintes ID btnwsp, btnsms, btnmsg, btntlg, btnskp y btntlf.
>Esto es un ejemplo de un formulario creado con elementor sencillo y simple con las funciones del sistema al capturar los datos para uso de Marketing.
![WmFormExterno](https://user-images.githubusercontent.com/36554510/233482815-c377746d-73cc-4057-aa71-370e5b1e20de.jpg)



**Aqui se muestra la informacion del agente con sus reportes de los clientes atendidos o que se lograron capturar sus datos**
>En la siguiente imagen se puede observar los datos de ejemplo del agente y la lista de reportes por fechas y el total.
![WmAgenteDatos](https://user-images.githubusercontent.com/36554510/233488542-0c9b58eb-d1ed-4e9d-8d95-ea17156a602a.jpg)




**Reporte por fecha**
>En la siguiente imagen se muestra los datos de los clientes que llenaron los formulario externo y del boton flotante.
![WmReporteFecha](https://user-images.githubusercontent.com/36554510/233488490-04c8eea1-bc9d-4e79-aee5-02320021995e.jpg)



**Reporte total**
>Aqui les muestra el reporte de todos los clientes con su informacion totan de todas las fechas.
![WmReporteTotal](https://user-images.githubusercontent.com/36554510/233488478-ba406d06-a315-4d72-a353-da5876cfe4be.jpg)



**Boton flotante en el front end**
>El texto del boton es editable y el texto mensaje tambien es editable.
![WmBtnFlotante](https://user-images.githubusercontent.com/36554510/233499773-2a100247-e2e3-46a1-8c49-70c0225febcd.jpg)



**Boton flontante con todos los canales**
>Al darle click al boton flontante se muestra todas las opciones que son editables de cuales se quieren mostrar para llamar la atencion de cliente por donde se quiera comunicar con la empresa en este caso del agente.
![WmBtnCanales](https://user-images.githubusercontent.com/36554510/233500128-ccdef7ba-2f1e-4a1b-a647-e4f952d627b9.jpg)



**Formulario del boton flontante**
>Al darle click en alguno de los canales que fueron configurados como skype. whatsapp, telegram, llamada, SMS y messenger que el cliente quiera usar para comunicase con la empresa, se le mostrara el formulario que ya fue editado con los datos que se quieren obtener del cliente al ser llenados se le activara el boton que al darle click sera dirigido por medio del canal que eligio con uno de los agentes que en ese momento este disponible.
>En la imagen se muestra como ejemplo que el cliente elgio el canal por llamada al ser llenado el formualrio y darle click al boton automaticamente se le activara la llamada para con el agente de turno.
![WmBtnForm](https://user-images.githubusercontent.com/36554510/233500559-56774952-60ea-4643-9949-a555acc24a9f.jpg)



**Correo de Bienvenida que se le envia al cliente**
>Un correo de ejemplo se muestra en la siguiente imagel a los clientes que se registran en el formulario externo o por medio del boton flotante
![WmCorreoBienve](https://user-images.githubusercontent.com/36554510/233503740-6b649bc6-cbbe-4ce9-b2f8-304f1f944465.jpg)



**Correo de notificacion que se le envia a los admin y agentes del sistema WMulticanal**
>Correo con toda la informacion obtenida por medio del formulario y ubicacion del cliente todo se guarda en la base de datos y son notificados los administradores del sistema WMulticanal y al agente que por turno se le asigno el cliente,
![WmCorreoNotifi](https://user-images.githubusercontent.com/36554510/233504224-10ab23ac-b02e-42d9-babc-493a302b71c9.jpg)

