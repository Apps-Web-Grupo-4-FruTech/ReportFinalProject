# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

**To-Be Scenario Mapping segmento objetivo 1**

<img src="assets/To-Be_Segmento-1.jpg" alt="To-be Scenario Mapping Segmento 1">

**To-Be Scenario Mapping segmento objetivo 2**

<img src="assets/To-Be_Segmento-2.jpg" alt="To-be Scenario Mapping Segmento 1">

## 3.2. User Stories

**Epicas para CultiConection**

<table>
  <thead>
    <tr>
      <th> EPIC (ID)</th>
      <th> Titulo</th>
      <th> Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th> 01</th>
      <th> Gestion de usuarios </th>
      <th> Como usuario de CultiConection, quiero crear un perfil, modificarlo, abrir y cerrar sension en cualquier dispositivo y recuperar la contraseña de mi cuenta para crear mi identidad dentro de la aplicacion y acceder a sus funcionalidades. </th>
    </tr>
    <tr>
      <th> 02</th>
      <th> Publicacion de Cultivos </th>
      <th> Como usuario de CultiConection, quier crear, eliminar y editar cultivos para tener un control de ellos en tiempo real y actualizado usando las funcionalidades de CultiConection.  </th>
    </tr>
    <tr>
      <th> 03</th>
      <th> Evaluaciones de cultivos </th>
      <th> Como usuario a CultiConection, quiero pedir y recibir evaluaciones de los cultivos que sienta que puedan mejorar para evitar perdidas o una posible muerte de los cultivos por un mal cuidado del que no sepa. </th>
    </tr>
    <tr>
      <th> 04</th>
      <th> Mantenimiento de cultivos </th>
      <th> Como usuario de CultiConection, quiero señalar y recibir señales de datos que necesiten mantenimiento en mi cultivo para asi enfocarme en mejorar y revisar evitando perdidas. </th>
    </tr>
    <tr>
      <th> 05</th>
      <th> Notificaciones de estado del cultivo</th>
      <th> Como usuario de CultiConection, quiero recibir notificaciones personalizadas y adaptadas a mis cultivos para no olvidar los cuidados o si muchos de sus datos estan desactualizados antes de perdir una evaluacion. </th>
    </tr>
    <tr>
      <th> 06</th>
      <th> Seguridad de informacion </th>
      <th> Como administrador de CultiConection, quiero gestionar y cuidar el perfil de mis usuario, para asegurar su estadia dentro de la aplicacion y no sientan un riesgo de ssu datos al navegar dentro de ella. </th>
    </tr>
    <tr>
      <th> 07</th>
      <th> Historial de cultivo </th>
      <th> Como usuario de CultiConection, quiero tener un historial actualizado de los cambios y modificaciones que pueda hacerle a mi cultivo, para saber en que paso pudo cambiar el rendimiento de mi cultivo. </th>
    </tr>
    <tr>
      <th> 08</th>
      <th> Verificacion de identidad </th>
      <th> Como administrador de CultiConection, quiero un sistema de verificacion de identidades de mis usuarios, para asegurarme de que no existan cuentas duplicadas o falsificadores de identidad. </th>
    </tr>
    <tr>
      <th> 09</th>
      <th> Accesibilidad  </th>
      <th> Como usuario de CultiConection, quiero funcionalidades que ayuden a que la aplicacion sea mas accesible en aspectos como color, configuracion y optimizacion para no tener problemas durante su uso. </th>
    </tr>
    <tr>
      <th> 10</th>
      <th> User Experience en la Landing Page </th>
      <th> Como usuario de CultiConection, quiero navegar por una Landing Page con una experiencia de usuario fluida y agil, para verificar y experimentar sus funcionalidades y el acceso a la informacion util del producto. </th>
    </tr>
  </tbody>
</table>

**Historias de Usuario para CultiConection**


<table>
  <thead>
    <tr>
      <th> Storie ID</th>
      <th> Titulo</th>
      <th> Descripción</th>
      <th> Acceptance Criteria</th> 
      <th> Epic ID</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th> 01</th>
      <th> Registro de cuenta </th>
      <th> Como usuario, quiero registrarme en la aplicacion, para acceder a sus funciones</th>
      <th> Scenario 1: Registro correcto <br>
      Given el usuario ha ingresado los datos <br>
      When el usuario presiona el boton "Create Account" <br>
      Then la cuenta es creada exitosamente y se accede a la aplicacion <br>
      <br>
      Scenario 2: Registro incorrecto<br>
      Given el usuario no ha ingresado ningun dato <br>
      When el usuario presiona el boton "Create Account" <br>
      Then el sistema muestra un mensaje de campos incompletos <br> 
      </th>
      <th>01</th>
    </tr>
    <tr>
      <th> 02</th>
      <th> Inicio de Sesión </th>
      <th> Como usuario, quiero iniciar sesion, para acceder a mi cuenta</th>
      <th> Scenario 1: Login Exitoso <br>
      Given el usuario ingrese sus datos de cuenta correctamente<br>
      When el usuario presione el boton "Iniciar Sesión" <br>
      Then el sistema abrira la sesion del usuario con sus datos <br>
      <br>
      Scenario 2: Login Fallido <br>
      Given el usuario ingrese datos incorrectos <br>
      When el usuario presione el boton "Inciar Sesion"<br>
      Then el sistema negara el acceso e indicara un mensaje de datos erroneos<br><br>
      Scenario 3: Cerrar sesion<br>
      Given el usuario ingrese a su perfil<br>
      When el usuario presione el boton "Cerrar Sesion"<br>
      Then el sistema cerrar la sesion del usuario
      <th>01</th>
      </th>
    </tr>
    <tr>
      <th> 03</th>
      <th> Recuperar Contraseña </th>
      <th> Como usuario, quiero recuperar la contraseña de mi cuenta, para recuperar el acceso a ella en caso se me olvide </th>
      <th>Scenario 1: Pedir contraseña <br>
      Given el usuario no recuerde la contraseña de su cuenta<br>
      When el usuario presione el boton de "Recuperar contraseña"<br>
      Then el sustema iniciaria el proceso para recuperar o reemplazar su anterior contraseña<br>
      </th>
      <th>01</th>
    </tr>
    <tr>
      <th> 04</th>
      <th> Editar perfil </th>
      <th> Como usuario, quiero modificar mi perfil, para mantenerlo actualizado todo el tiempo </th>
      <th>Scenario 1: Acceso a la ediion<br>
      Given el usuario esta en al seccion "Mi Perfil"<br>
      When el usuario presione el boton "Editar Perfil"<br>
      Then el sistema iniciara el formulario de datos editables del perfil de usuario<br><br>
      Scenario 2: Edicion de Perfil<br>
      Given el usuario esta en el formulario de editar perfil<br>
      When el usuario modifique los datos que desee<br>
      Then el sistema lo actualizara y su perfil mostrara los nuevos datos<br>
      </th>
      <th>01</th>
    </tr>
    <tr>
      <th> 05</th>
      <th> Registrar cultivos</th>
      <th> Como agricultor, quiero registrar diferentes cultivos, para mantener un registro a mi alcance </th>
      <th>Scenario 1: Registrar cultivo<br>
      Given el agricultor quiere registrar un ultivo en la aplicacion <br>
      When el agricultor seleccione el boton "Agregar Cultivo"<br>
      Then el sistema abrira un formulario para llenar con los datos de su cultivo<br>
      </th>
      <th>02</th>
    </tr>
    <tr>
      <th> 06</th>
      <th> Eliminar cultivos</th>
      <th> Como agricultor, quiero eliminar los cultivos que desee, para mantener un registro actualizado </th>
      <th>Scenario 1: Eliminar cultivo<br>
      Given el agricultor desee eliminar un ultivo previamente registrado <br>
      When el agricultor este en el cultivo que desee eliminar<br>
      When el agricultor presione el boton "Elimar Cultivo"<br>
      Then el sistema eliminara el registro del cultivo con toda su informacion<br>
      </th>
      <th>02</th>
    <tr>
      <th> 07</th>
      <th> Editar cultivos</th>
      <th> Como agricultor, quiero editar los cultivos que tenga registrados, para asegurarme que siempre esten actualizados </th>
      <th>Scenario 1: Formulario de edicion<br>
      Given el agricultor se encuentre en el registro del cultivo deseado <br>
      When el agricultor presione el boton "Editar Cultivo"<br>
      Then el sistema abrira un registro para editar datos del cultivo<br>
      <br>
      Scenario 2: Edicion de cultivo
      Given el agricultor se encuentre en el formulario de edicion <br>
      When el agricultor cambie los datos que desee<br>
      When el agricultor presione el boton "Actualizar Cultivo"
      Then el sistema actualizara los datos<br>
      </th>
      <th>02</th>
    </tr>
    <tr>
      <th> 08</th>
      <th> Peticion de evaluacion </th>
      <th> Como agricultor, quiero pedir una revision, para comprobar si el estado de mis cultivos es el adecuado </th>
      <th>Scenario 1: Llamado de evaluacion<br>
      Given el agricultor este en el cultivo que desee pedir una revision<br>
      When el agricultor presione el boton "Pedir Revision"<br>
      Then el sistema iniciara una proceso de evaluacion con un asesor
      </th>
      <th>03</th>
    <tr>
      <th> 09</th>
      <th> Recepción de evaluación </th>
      <th> Como agricultor, quiero recibir una evaluacion de mi cultivo, para identificar problemas de mi cultivo</th>
      <th>Scenario 1: Llegada de evaluación<br>
      Given el usuario pidio una evaluacion de forma previa<br>
      When el sistema envie una evaluaion acorde al cultivo que el agricultor haya seleccionado<br>
      Then el usuario podra ver la evaluacion <br>
      </th>
      <th>03</th>
    </tr>
    <tr>
      <th>10</th>
      <th> Pago por evaluaciones </th>
      <th> Como usuario, quiero pagar por una evaluacion de mi cultivo para asegurar un trabajo de calidad </th>
      <th>Scenario 1: Pago realizado<br>
      Given el usuario pidio una evaluacion previamente<br>
      When el sistema informe que la evaluacion ya esta lista<br>
      Then el sistema mostrara metodos de pago para recibir la evaluacion<br>
      </th>
      <th>03</th>
    </tr>
    <tr>
      <th> 11</th>
      <th> Señalaciones </th>
      <th> Como agricultor, quiero ver la señalaciones en mis cultivos, para saber si algo puede estar mal</th>
      <th>Scenario 1: Visualizacion de señales<br>
      Given el usuario ya recibio una evaluacion de su cultivo<br>
      When el usuario acceda a su cultivo<br>
      Then el sistema mostrara señalaciones en partes de su registro que puedan necesitar cambios
      </th>
      <th>04</th>
    </tr>
    <tr>
      <th> 12</th>
      <th> Datos adicionales </th>
      <th> Como agricultor, quiero señalar si mi cultivo tiene caracteristias adicionales, para recibir mejor informacion </th>
      <th>Scenario 1: Señalar datos <br>
      Given el agricultor esta registrando su cultivo<br>
      When el agriculto presione el boton "Cuidados Adicionales"<br>
      Then el sistema abrira una formulario que permita señalar nuevos datos<br>
      <br>
      Scenario 2: Eleccion de datos<br>
      Given el agriculto señalo la opcion "Cuidados adicionales"<br>
      When el sistema muestre formularios adiionales<br>
      Then el agriultor podra señalar que cuidados necesitara<br>
      </th>
      <th>04</th>
    </tr>
    <tr>
      <th> 13</th>
      <th> Notificacion de riego </th>
      <th> Como agricultor, quiero recibir recordatorios en forma de mensajes, para saber cuando regar mis cultivos </th>
      <th>Scenario 1: Activar recordatorios<br>
      Given el agricultor registro en los datos los dias de cultivo<br>
      When el sistema detecte el dia de riego<br>
      Then el sistema mandara recordatorios mediante señalando el dia de riego<br>
      <br>
      Scenario 2: Desactivar recordatorios<br>
      Given el agricultor registro en los datos los dias de cultivo<br>
      When el usuario no quiera recibir recordatorios<br>
      And el usuario marque la opcion "No recibir recordatorio"<br>
      Then el sistema no enviara recordatorios<br>
      </th>
      <th>05</th>
    </tr>
    <tr>
      <th> 14</th>
      <th> Recordatorio de datos del cultivo</th>
      <th> Como agricultor, quiero recibir recordatorios de los datos de mi cultivo, en caso necesite actualizarlos </th>
      <th>Scenario 1: Recordatorio de datos<br>
      Given el usuario ya registro su cultivo<br>
      When el sistema detecte que ha pasado demasiado tiempo<br>
      Then el sistema enviara un recordatorio sobre los datos del cultivo en caso necesiten un cambio<br>
      </th>
      <th>05</th>
    </tr>
    <tr>
      <th> 15</th>
      <th> Gestionar usuarios </th>
      <th> Como administrador, quiero verifiar y gestionar a los usuarios registrados, para una correcta administracion de la aplicacion </th>
      <th>Scenario 1: Acceso a gestion<br>
      Given el adminitrador ingrese al sistema <br>
      And el administrador inicie la sesion<br>
      When el administrador entre al modulo de gestion de usuarios<br>
      Then el sistema mostrara una lista de todos los usuarios registrados<br>
      </th>
      <th>06</th>
    </tr>
    <tr>
      <th> 16</th>
      <th> Bloqueo de cuenta </th>
      <th> Como administrador, quiero asegurar el acceso al perfil de los usuarios, para mantener su informacion segura </th>
      <th>Scenario 1: Acceso bloqueado<br>
      Given el sistema detecta un ingreso fallido a una cuenta<br>
      When el sistema detecte mas de 10 intentos fallidos de aeder a una cuenta<br>
      Then el sistema bloqueara el acceso a la cuenta por un tiempo definido<br>
      </th>
      <th>06</th>
    </tr>
    <tr>
      <th> 17</th>
      <th> Creacion de historial </th>
      <th> Como agricultor, quiero acceder a un historial de los cambios del cultivo para mantener un registro detallado </th>
      <th>Scenario 1: Historial creado<br>
      Given el agricultor realizo una edicion de su cultivo en la aplicacion<br>
      When el agricultor este por guardar el cambio <br>
      Then el sistema creara un historial y lo enviara al agricultor
      </th>
      <th>07</th>
    </tr>
    <tr>
      <th> 18</th>
      <th> Atajos sencillos </th>
      <th> Como usuario, quiero tener acceso a atajos de organización para
      una mejor navegación dentro de la aplicacion </th>
      <th>Scenario 1: Regreso al inicio<br>
      Given el usuario quiere regresar a la sección de “Inicio”<br>
      When el usuario presione el logo del producto<br>
      Then se regresará a la sección de “Inicio” nuevamente cargada<br>
      </th>
      <th>09</th>
    </tr>
    <tr>
      <th> 19</th>
      <th> Disponibilidad de sistema </th>
      <th> Como usuario, quiero un sistema que esté disponible en cualquier
      hora para acceder cuando quiero sin problema de disponibilidad o
      mantenimiento</th>
      <th>Scenario 1: Uso del sistema<br>
      Given el usuario necesite usar el sistema<br>
      When el usuario ingrese a la página del producto<br>
      Then entrara con normalidad sin problemas de coneccion o
      soporte<br>
      </th>
      <th>09</th>
    </tr>
    <tr>
      <th> 20</th>
      <th> Visualizar página de inicio </th>
      <th> Como usuario, quiero visualizar una página de inicio clara para
      comprender rápidamente de qué trata CultiConection. </th>
      <th>Scenario 1: Acceso a la página principal<br>
      Given  el usuario accede al landing page de CultiConection<br>
      When el sistema cargue la página <br>
      Then el sistema mostrara el nombre del producto, una descripción
      breve y una pagina correctamente diseñada.<br>
      </th>
      <th>10</th>
    </tr>
    <tr>
      <th> 21</th>
      <th> Navegación desde el footer </th>
      <th> Como usuario, quiero acceder a enlaces de navegación en el footer
      para moverme entre secciones fácilmente </th>
      <th>Scenario 1: Acceso a secciones desde el footer<br>
      Given el usuario está visualizando el footer<br>
      When haga clic en un enlace de sección (Inicio, Características, etc)<br>
      Then será desplazado automáticamente a la sección correspondiente del landing.
      </th>
      <th>10</th>
    </tr>
  </tbody>
</table>

## 3.3. Impact Mapping.

<img src="assets/Impact_Mapping.png" alt="Impact Mapping">

## 3.4. Product Backlog.

<table>
  <thead>
    <tr>
      <th> #Orden</th>
      <th> User Story ID</th>
      <th> Título</th>
      <th> Descripción</th>
      <th> Story Points (1/2/3/5/8)</th>
      <th> Epic ID</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th> EP01</th>
      <th> Gestion de usuarios </th>
      <th></th>
      <th>Como usuario de CultiConection, quiero crear un perfil, modificarlo, abrir y cerrar sension en cualquier dispositivo y recuperar la contraseña de mi cuenta para crear mi identidad dentro de la aplicacion y acceder a sus funcionalidades.</th>
      <th></th>
      <th>01</th>
    </tr>
    <tr>
      <th> 1</th>
      <th> US01 </th>
      <th>Registro de cuenta</th>
      <th>Como usuario, quiero registrarme en la aplicacion, para acceder a sus funciones</th>
      <th>2</th>
      <th>01</th>
    </tr>
    <tr>
      <th> 2</th>
      <th> US02 </th>
      <th>Inicio de Sesión</th>
      <th>Como usuario, quiero iniciar sesion, para acceder a mi cuenta</th>
      <th>1</th>
      <th>01</th>
    </tr>
    <tr>
      <th> 3</th>
      <th> US03 </th>
      <th>Recuperar Contraseña</th>
      <th>Como usuario, quiero recuperar la contraseña de mi cuenta, para recuperar el acceso a ella en caso se me olvide</th>
      <th>3</th>
      <th>01</th>
    </tr>
    <tr>
      <th> 4</th>
      <th> US04 </th>
      <th>Editar perfil</th>
      <th>Como usuario, quiero modificar mi perfil, para mantenerlo actualizado todo el tiempo</th>
      <th>1</th>
      <th>01</th>
    </tr>
    <tr>
      <th> EP02</th>
      <th> Publicacion de Cultivos </th>
      <th></th>
      <th> Como usuario de CultiConection, quier crear, eliminar y editar cultivos para tener un control de ellos en tiempo real y actualizado usando las funcionalidades de CultiConection.  </th>
      <th></th>
      <th>02</th>
    </tr>
    <tr>
      <th> 5</th>
      <th> US05 </th>
      <th>Registrar cultivos</th>
      <th>Como agricultor, quiero registrar diferentes cultivos, para mantener un registro a mi alcance</th>
      <th>3</th>
      <th>02</th>
    </tr>
    <tr>
      <th> 6</th>
      <th> US06 </th>
      <th>Eliminar cultivos</th>
      <th>Como agricultor, quiero eliminar los cultivos que desee, para mantener un registro actualizado</th>
      <th>2</th>
      <th>02</th>
    </tr>
    <tr>
      <th> 7</th>
      <th> US07 </th>
      <th>Editar cultivos</th>
      <th>Como agricultor, quiero editar los cultivos que tenga registrados, para asegurarme que siempre esten actualizados</th>
      <th>1</th>
      <th>02</th>
    </tr>
    <tr>
      <th> EP03</th>
      <th> Evaluaciones de cultivos </th>
      <th></th>
      <th> Como usuario a CultiConection, quiero pedir y recibir evaluaciones de los cultivos que sienta que puedan mejorar para evitar perdidas o una posible muerte de los cultivos por un mal cuidado del que no sepa. </th>
      <th></th>
      <th>03</th>
    </tr>
    <tr>
      <th> 8</th>
      <th> US08 </th>
      <th>Peticion de evaluacion</th>
      <th>Como agricultor, quiero pedir una revision, para comprobar si el estado de mis cultivos es el adecuado</th>
      <th>3</th>
      <th>03</th>
    </tr>
    <tr>
      <th> 9</th>
      <th> US09 </th>
      <th>Recepción de evaluación</th>
      <th>Como agricultor, quiero reibir una evaluacion de mi cultivo, para identificar problemas de mi cultivo</th>
      <th>5</th>
      <th>03</th>
    </tr>
    <tr>
      <th> 10</th>
      <th> US10 </th>
      <th>Pago por evaluaciones</th>
      <th>Como usuario, quiero pagar por una evaluacion de mi cultivo para asegurar un trabajo de calidad</th>
      <th>5</th>
      <th>03</th>
    </tr>
    <tr>
      <th> EP04</th>
      <th> Mantenimiento de cultivos </th>
      <th></th>
      <th> Como usuario de CultiConection, quiero señalar y recibir señales de datos que necesiten mantenimiento en mi cultivo para asi enfocarme en mejorar y revisar evitando perdidas. </th>
      <th></th>
      <th>04</th>
    </tr>
    <tr>
      <th> 11</th>
      <th> US11 </th>
      <th>Señalaciones</th>
      <th>Como agricultor, quiero ver la señalaciones en mis cultivos, para saber si algo puede estar mal</th>
      <th>2</th>
      <th>04</th>
    </tr>
      <th> 12</th>
      <th> US12 </th>
      <th>Datos adicionales</th>
      <th>Como agricultor, quiero señalar si mi cultivo tiene características adicionales, para recibir mejor informacion</th>
      <th>2</th>
      <th>04</th>
    </tr>
    <tr>
      <th> EP05</th>
      <th> Notificaciones de estado del cultivo</th>
      <th></th>
      <th> Como usuario de CultiConection, quiero recibir notificaciones personalizadas y adaptadas a mis cultivos para no olvidar los cuidados o si muchos de sus datos estan desactualizados antes de perdir una evaluacion. </th>
      <th></th>
      <th>05</th>
    </tr>
    </tr>
      <th> 13</th>
      <th> US13 </th>
      <th>Notificacion de riego</th>
      <th>Como agriultor, quiero reibir recordatorios en forma de mensajes, para saber cuando regar mis cultivos</th>
      <th>1</th>
      <th>05</th>
    </tr>
    </tr>
      <th> 14</th>
      <th> US14 </th>
      <th>Recordatorio de datos del cultivo</th>
      <th>Como agricultor, quiero recibir recordatios de los datos de mi cultivo, en caso necesite actualizarlos</th>
      <th>2</th>
      <th>05</th>
    </tr>
    <tr>
      <th> EP06</th>
      <th> Seguridad de informacion </th>
      <th></th>
      <th> Como administrador de CultiConection, quiero gestionar y cuidar el perfil de mis usuario, para asegurar su estadia dentro de la aplicacion y no sientan un riesgo de ssu datos al navegar dentro de ella. </th>
      <th></th>
      <th>06</th>
    </tr>
    </tr>
      <th> 15</th>
      <th> US15 </th>
      <th>Gestionar usuarios</th>
      <th>Como administrador, quiero verificar y gestionar a los usuarios registrados, para una correcta administracion de la aplicacion</th>
      <th>5</th>
      <th>06</th>
    </tr>
    </tr>
      <th> 16</th>
      <th> US16 </th>
      <th>Bloqueo de cuenta</th>
      <th>Como administrador, quiero asegurar el acceso al perfil de los usuarios, para mantener su informacion segura</th>
      <th>3</th>
      <th>06</th>
    </tr>
    <tr>
      <th> EP07</th>
      <th> Historial de cultivo </th>
      <th></th>
      <th> Como usuario de CultiConection, quiero tener un historial actualizado de los cambios y modificaciones que pueda hacerle a mi cultivo, para saber en que paso pudo cambiar el rendimiento de mi cultivo. </th>
      <th></th>
      <th>07</th>
    </tr>
    </tr>
      <th> 17</th>
      <th> US17 </th>
      <th>Creacion de historial</th>
      <th>Como agricultor, quiero acceder a un historial de los cambios del cultivo para mantener un registro detallado</th>
      <th>3</th>
      <th>07</th>
    </tr>
    <tr>
      <th> EP09</th>
      <th> Accesibilidad  </th>
      <th></th>
      <th> Como usuario de CultiConection, quiero funcionalidades que ayuden a que la aplicacion sea mas accesible en aspectos como color, configuracion y optimizacion para no tener problemas durante su uso. </th>
      <th></th>
      <th>09</th>
    </tr>
    </tr>
      <th> 18</th>
      <th> US18 </th>
      <th>Atajos sencillos</th>
      <th>Como usuario, quiero tener acceso a atajos de organización para
      una mejor navegación dentro de la aplicacion</th>
      <th>2</th>
      <th>09</th>
    </tr>
    </tr>
      <th> 19</th>
      <th> US19 </th>
      <th>Disponibilidad de sistema</th>
      <th>Como usuario, quiero un sistema que esté disponible en cualquier
      hora para acceder cuando quiero sin problema de disponibilidad o
      mantenimiento</th>
      <th>1</th>
      <th>09</th>
    </tr>
    <tr>
      <th> EP10</th>
      <th> User Experience en la Landing Page </th>
      <th></th>
      <th> Como usuario de CultiConection, quiero navegar por una Landing Page con una experiencia de usuario fluida y agil, para verificar y experimentar sus funcionalidades y el acceso a la informacion util del producto. </th>
      <th></th>
      <th>10</th>
    </tr>
    </tr>
      <th> 20</th>
      <th> US20 </th>
      <th>Visualizar página de inicio</th>
      <th>Como usuario, quiero visualizar una página de inicio clara para
      comprender rápidamente de qué trata CultiConection</th>
      <th>3</th>
      <th>10</th>
    </tr>
    </tr>
      <th> 21</th>
      <th> US21 </th>
      <th>Navegación desde el footer</th>
      <th>Como usuario, quiero acceder a enlaces de navegación en el footer
      para moverme entre secciones fácilmente</th>
      <th>2</th>
      <th>10</th>
    </tr>
  </tbody>
</table>
