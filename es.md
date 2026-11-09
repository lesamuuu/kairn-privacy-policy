# Política de privacidad de Kairn

> Borrador pendiente de revisión antes de su publicación, especialmente en materia de datos de salud, menores, bases jurídicas y contratos y transferencias internacionales de los proveedores.

**Última actualización:** 9 de noviembre de 2026

**Responsable del tratamiento:** Samuel Petrucci

**Ubicación:** Santa Cruz de Tenerife, España

**Contacto de privacidad:** samuelpayback@gmail.com

Esta política explica cómo Kairn trata la información cuando utilizas la aplicación y qué opciones tienes para controlarla.

## 1. Lo esencial

Kairn es una aplicación para registrar entrenamientos de fuerza. Puedes utilizar sus funciones principales sin crear una cuenta y sin conexión a Internet.

Tu historial de entrenamiento se guarda en el dispositivo. Kairn no ofrece un servicio propio de sincronización de entrenamientos en la nube y su responsable no puede consultar remotamente el historial guardado en tu teléfono.

Puedes decidir por separado si quieres compartir informes de errores y datos de uso para ayudar a mejorar la aplicación. Ambas opciones están desactivadas de forma predeterminada.

Si envías comentarios desde la aplicación, se transmite el mensaje que hayas escrito junto con información técnica limitada. Este envío es independiente de tus preferencias de analítica y diagnósticos.

Kairn también puede conectarse a servicios de actualización para comprobar y descargar nuevas versiones de su código y recursos.

## 2. Información que se guarda en tu dispositivo

Kairn almacena localmente la información necesaria para ofrecer sus funciones:

- **Entrenamientos:** sesiones, fechas, horas, duración, ejercicios, series, pesos, repeticiones, indicadores de esfuerzo y resultados calculados a partir de tus registros.
- **Organización:** rutinas, orden de ejercicios, equipamiento y etiquetas.
- **Contenido que añadas:** notas, comentarios, imágenes de ejercicios y eventos del calendario interno de Kairn.
- **Preferencias:** idioma, unidades, apariencia, nombre visible opcional y otras opciones de la aplicación.

Esta información permite registrar entrenamientos, consultar el historial, mostrar gráficos y estimaciones, personalizar la aplicación y generar los archivos que solicites. Los registros de actividad física, las imágenes y las notas pueden revelar información personal o relacionada con la salud, dependiendo de su contenido.

Los eventos del calendario de Kairn se introducen en la propia aplicación; esta función no implica acceso al calendario del sistema. La versión actual no integra Apple Health, HealthKit ni Health Connect.

Evita introducir información de otras personas sin una base legítima para hacerlo.

## 3. Informes de errores opcionales

Si activas **«Compartir informes de errores»**, Kairn puede enviar información técnica para detectar y corregir problemas.

Los informes pueden incluir el tipo de error, códigos técnicos, referencias a funciones y posiciones del código, versión de la aplicación, sistema operativo y su versión, fecha y hora e identificadores seudónimos de instalación o sesión.

Kairn filtra los informes para excluir los mensajes originales de error que puedan contener información privada, consultas SQL, variables y rutas locales completas. No adjunta automáticamente tu historial de entrenamiento, nombres de ejercicios, pesos, repeticiones, notas, imágenes ni contenido de archivos.

La implementación actual de PostHog no recoge fallos nativos ni realiza grabaciones de pantalla o de sesiones de uso.

## 4. Datos de uso opcionales

Si activas **«Compartir uso de funciones»**, Kairn puede enviar eventos sobre las funciones que utilizas. Por ejemplo: abrir una sección, utilizar un gráfico, guardar una rutina, registrar una serie o completar una sesión.

Los eventos pueden incluir categorías de acciones y ajustes, fecha y hora, versión de la aplicación, información del sistema operativo e identificadores seudónimos.

No incluyen automáticamente los nombres de tus ejercicios o rutinas, pesos, repeticiones, notas, fotografías, contenido de archivos ni las fechas históricas de tus entrenamientos. Sin embargo, el momento y la frecuencia de los eventos pueden revelar cuándo utilizas determinadas funciones de entrenamiento.

### Proveedor y controles

Kairn utiliza **PostHog Cloud EU** para procesar los informes de errores y eventos de uso autorizados.

Los identificadores no son tu nombre ni una cuenta, pero permiten relacionar eventos de una misma instalación. Por ello, estos datos son seudónimos, no completamente anónimos.

PostHog recibe la dirección IP desde la que se realiza la conexión. Kairn desactiva el enriquecimiento geográfico de los eventos; esto no significa que el proveedor no reciba la IP.

La configuración de Kairn no utiliza esta información para publicidad, grabaciones de sesiones ni seguimiento entre aplicaciones.

Puedes activar o desactivar los diagnósticos y la analítica de forma independiente desde los ajustes. Rechazarlos no impide registrar entrenamientos ni consultar tu historial.

Al cambiar estas preferencias, Kairn descarta los eventos pendientes de la configuración anterior. Desactivar una opción impide nuevos envíos de ese tipo, pero no elimina automáticamente los datos ya transmitidos. Las solicitudes de red iniciadas antes del cambio podrían completarse.

Más información: [política de privacidad de PostHog](https://posthog.com/privacy).

## 5. Comentarios que envías voluntariamente

Si utilizas **«Enviar comentarios»**, se transmiten a PostHog:

- El texto que escribas y la categoría elegida: error o mejora.
- El idioma, la plataforma y la versión y compilación de la aplicación.
- Un identificador generado para ese envío, independiente del identificador de analítica.

El proveedor también recibe la IP de la conexión.

El formulario no adjunta automáticamente tus entrenamientos, imágenes o archivos, ni solicita una dirección de respuesta. El propio mensaje puede contener datos personales si decides escribirlos. No incluyas contraseñas, información médica, datos sensibles o información de terceros que no sea necesaria.

Puedes enviar comentarios aunque tengas desactivados los diagnósticos y la analítica. Pulsar el botón de envío solicita únicamente la transmisión de ese comentario y no activa las demás opciones.

El borrador se mantiene temporalmente en la memoria de la pantalla. No se guarda como mensaje pendiente para enviarlo automáticamente más tarde. Tras un error de envío puedes volver a intentarlo; un fallo de confirmación podría provocar un envío duplicado si repites la operación.

## 6. Actualizaciones de la aplicación

Kairn utiliza **Expo / EAS Update**, de **650 Industries, Inc.**, para comprobar y descargar actualizaciones de código y recursos.

Estas conexiones pueden transmitir información técnica necesaria para entregar una actualización compatible, como plataforma, versión o configuración de la aplicación, identificadores técnicos de actualización y datos de conexión, incluida la IP.

Este proceso es independiente de las opciones de diagnósticos y analítica. No está diseñado para enviar tu historial de entrenamiento, notas o fotografías.

Más información: [política de privacidad de Expo](https://expo.dev/privacy).

## 7. Permisos del dispositivo

Kairn puede solicitar permisos cuando utilizas determinadas funciones:

- **Cámara y fotografías:** para hacer una foto o seleccionar una imagen que quieras asociar a un ejercicio. Las imágenes se procesan y guardan localmente; no se envían automáticamente a PostHog.
- **Notificaciones:** para avisos locales relacionados con el entrenamiento, como temporizadores y recordatorios de sesiones. Estas funciones no utilizan un servicio de notificaciones push para enviar tu historial a un servidor.
- **Archivos y aplicaciones de destino:** cuando importas o exportas información, intervienen los selectores de archivos y las opciones de compartir del sistema.

Puedes gestionar los permisos desde los ajustes de tu dispositivo. Si rechazas uno, la función que lo necesita puede no estar disponible, pero puedes seguir utilizando las demás funciones de Kairn.

## 8. Copias, informes y archivos compartidos

Puedes generar copias completas, archivos de intercambio e informes PDF.

Una copia completa puede contener tu historial, notas, rutinas, imágenes y preferencias. Los archivos de intercambio contienen la información que selecciones. Los informes incluyen los datos correspondientes al informe generado. El nombre visible que hayas configurado también puede aparecer en los nombres de archivos o informes.

Los archivos se generan en el dispositivo. Si eliges compartirlos o guardarlos mediante otra aplicación o proveedor, esa aplicación o proveedor recibe el contenido y lo trata según sus propias condiciones.

Los archivos exportados no incorporan protección mediante contraseña o cifrado propio de Kairn. Guárdalos y compártelos con precaución.

Las copias completas de Kairn no incluyen las preferencias de consentimiento ni los identificadores de su sistema de telemetría.

El sistema operativo también puede realizar copias o transferencias de datos del dispositivo según su configuración. Estas operaciones son distintas de las copias que generas expresamente desde Kairn.

## 9. Finalidades y bases jurídicas

Cuando resulte aplicable el Reglamento General de Protección de Datos —RGPD—, las bases jurídicas se determinan según el tratamiento:

- **Funciones solicitadas:** ejecución del servicio, en la medida en que el tratamiento sea necesario para registrar, consultar, importar o exportar información.
- **Diagnósticos y analítica opcionales:** tu consentimiento, que puedes retirar desde los ajustes.
- **Comentarios voluntarios:** tu consentimiento para el envío y tratamiento del mensaje.
- **Obligaciones legales y solicitudes de derechos:** cumplimiento de las obligaciones legales aplicables.

La instalación o el uso de Kairn no se interpreta como consentimiento para activar los diagnósticos o la analítica opcionales.

**Pendiente de revisión antes de publicar:** confirmar la base jurídica de las conexiones de actualización y seguridad técnica. Si algún tratamiento comprende categorías especiales de datos, como datos relativos a la salud, determinar también la condición aplicable del artículo 9 del RGPD y las medidas necesarias para cumplirla. La ejecución del servicio, por sí sola, no sustituye ese requisito.

## 10. Destinatarios y transferencias internacionales

Los datos transmitidos pueden ser tratados por PostHog y Expo y por los proveedores que estos utilicen para prestar sus servicios, conforme a sus contratos y funciones.

También pueden recibir información las aplicaciones y personas a las que tú decidas enviar archivos, y las autoridades cuando exista una obligación legal válida.

Kairn no vende tus datos personales ni los utiliza para publicidad comportamental.

La integración de PostHog está dirigida a su región europea. La ubicación europea del alojamiento no permite afirmar por sí sola que no exista acceso o tratamiento desde otros países. Expo puede tratar información fuera del Espacio Económico Europeo.

**Pendiente de revisión antes de publicar:** confirmar las entidades contratantes, los países relevantes y las garantías de transferencia aplicables según los contratos de ambos proveedores, e indicar cómo solicitar información o una copia de dichas garantías.

## 11. Conservación y eliminación de datos

Los datos de entrenamiento permanecen en tu dispositivo hasta que los elimines mediante las opciones disponibles o borres los datos de la aplicación.

Quitar una rutina o retirar un ejercicio del catálogo no equivale necesariamente a eliminar sus registros históricos: Kairn conserva el historial en distintas operaciones.

Para eliminar los datos locales completos, utiliza las opciones del sistema para borrar los datos de la aplicación o eliminarla. En iOS, descargar la app conservando sus documentos no equivale a eliminarla con sus datos.

La información enviada voluntariamente, los diagnósticos y los datos de uso se conservan mientras sean necesarios para las finalidades descritas en esta política, teniendo en cuenta la resolución de incidencias, la mejora de la aplicación y las obligaciones legales aplicables. La información técnica de los servicios de actualización se conserva conforme a sus finalidades operativas y obligaciones aplicables.

Puedes solicitar la eliminación de los datos personales que hayamos recibido escribiendo a **samuelpayback@gmail.com**. Desactivar la telemetría detiene los nuevos envíos, pero no elimina automáticamente los anteriores.

Los archivos exportados, los archivos compartidos y las copias guardadas fuera de Kairn deben eliminarse por separado. Una restauración del dispositivo puede recuperar datos de una copia anterior.

Desinstalar Kairn no elimina automáticamente la información ya transmitida a los proveedores ni los archivos guardados fuera de la aplicación.

## 12. Seguridad

Kairn utiliza el almacenamiento privado que proporciona el sistema operativo y conexiones HTTPS para los envíos a los servicios descritos.

Los informes automáticos se filtran para limitar su contenido y excluir los registros de entrenamiento y otros datos privados señalados en esta política.

Estas medidas no equivalen a una garantía de seguridad absoluta ni a cifrado de extremo a extremo. La protección de los datos locales también depende de la seguridad del dispositivo y de sus copias de respaldo.

Utiliza el bloqueo del dispositivo y protege los archivos que exportes, especialmente si contienen notas o imágenes sensibles.

## 13. Tus derechos

Según la legislación aplicable, puedes solicitar acceso, rectificación, supresión, limitación, portabilidad u oposición al tratamiento de tus datos. También puedes retirar el consentimiento sin afectar a la licitud del tratamiento anterior.

Para ejercer estos derechos, escribe a **samuelpayback@gmail.com**.

Como Kairn no tiene cuentas y los eventos no se vinculan a tu nombre o correo, es posible que no podamos localizar determinados datos únicamente con tu dirección de correo electrónico. Te indicaremos qué información adicional, proporcionada y necesaria, puede permitir identificar los registros correspondientes. No tienes que enviarnos tu historial completo para formular una solicitud.

No podemos modificar o recuperar remotamente información que permanezca exclusivamente en tu teléfono.

Cuando resulte aplicable el RGPD, responderemos normalmente en el plazo de un mes, con las ampliaciones y condiciones previstas legalmente.

Puedes presentar una reclamación ante la autoridad de protección de datos competente. En España, la [Agencia Española de Protección de Datos](https://www.aepd.es/).

## 14. Menores

Cuando la legislación exija autorización de los representantes legales para determinados tratamientos de datos de menores, deberá obtenerse antes de realizarlos.

Si crees que un menor ha enviado información personal sin la autorización necesaria, contacta con **samuelpayback@gmail.com** para que podamos valorar las medidas correspondientes.

**Pendiente de revisión antes de publicar:** concretar el público objetivo y los requisitos de edad o autorización aplicables, de forma coherente con las declaraciones de las tiendas y los países de distribución.

## 15. Cambios y contacto

Podemos actualizar esta política cuando cambien las funciones, los proveedores o las obligaciones aplicables.

Publicaremos la versión actualizada con su fecha. Cuando un cambio requiera nueva información o consentimiento, lo comunicaremos y solicitaremos antes de iniciar el tratamiento correspondiente. Publicar una actualización de esta política no sustituye ese consentimiento.

Para consultas sobre privacidad:

**Samuel Petrucci**

Santa Cruz de Tenerife, España

[samuelpayback@gmail.com](mailto:samuelpayback@gmail.com)
