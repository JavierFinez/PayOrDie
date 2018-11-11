# Práctica PayOrDie

Práctica del módulo de diseño de apps para desarrolladores.


## Decisiones Tomadas

En primer lugar decidí usar elementos estandar del interfaz de iOS para transmitir la sensación de sencillez y familiaridad para el usuario, además consideré usar el color azul tanto en el fondo como en la letra por la necesidad de transmitir confianza.
Para minimizar el estrés del usuario me ha parecido conveniente primero seleccionar al amigo para evitar la sensación de transacciones erróneas  (en un principio había pensado primero seleccionar si enviar o recibir primero pero tras una pequeña encuesta con varios amigos decidí cambiar de opinión ya que me comentaron que a ellos eso le generaba muchas más dudas)

En segundo lugar mostraría en otra pantalla los datos del usuario seleccionado  en grande, además de mostrar un histórial con las últimas transacciones con el mismo para proporcionar un feedback al usuario que le de idea de garantía de que sus transacciones se han efectuado, junto a esto estaría un control segmentado que permitiría elegir cada vez solo una de las dos únicas dos acciones posibles: enviar o recibir dinero.  Una vez realizado esto, en última se ingresaría la cantidad económica a entregar/recibir (esto minimizará el temor del usuario de lo que pasa con su dinero ante un fallo en la aplicación, agotamiento de batería, etc...). En el caso de la transacción monetaria se ha optado para el caso del pago si el dispositivo lo permite usar la validación mediante Touch ID, donde también se muestra la opción de cancelar la transacción.


## Cuestiones Humanas Clave

Las principales cuestiones consideradas son:

    - La aplicación debe transmitir confianza y seguridad por estar tratando con el dinero del usuario
    - Debe realizarse con sencillez y familiaridad, para facilitar su usabilidad.
    - Eliminar cualquier tipo de estrés que pudiera tener el usuario utilizando la aplicación
    - Mostrar un historial al usuario de todas las cuentas que haya tratado con cualquiera de sus amigos, para que en todo momento conozca el estado de sus transacciones.

 
## Onboarding

En el on-boarding mostraría varias pantallas deslizables tratando de realizar un buen marketing de la aplicación previo a que el usuario realizara el sign-up en la misma para que el potencial usuario sepa lo que le espera y tratar de no defraudarle (tratando en todo momento de transmitir las cuestiones humanas indicadas arriba (sencillez, confiabilidad y seguridad):

-   funcionalidades principales y configuración: cargar amigos de redes sociales, seleccionar amigos, historial, enviar/recibir dinero...
-   seguridad de la aplicación: estándares de seguridad, configuración de medios de pago: Paypal, mastercard...



