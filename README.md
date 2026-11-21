# Política de seguridad

## Versiones compatibles

Actualmente se aceptan reportes de seguridad para la versión publicada más reciente de GastosLuminaX y para la versión de desarrollo disponible en la rama principal.

Las versiones antiguas pueden no recibir correcciones de seguridad.

## Cómo informar de una vulnerabilidad

No publiques vulnerabilidades en Issues, Discussions, pull requests ni en otros espacios públicos del repositorio.

Envía el reporte de forma privada a:

`contacto.levelrise@gmail.com`

Incluye, si es posible:

- Descripción clara del problema.
- Pasos para reproducirlo.
- Versión de la aplicación y versión de Android afectadas.
- Impacto potencial y datos que podrían quedar expuestos.
- Evidencias o código de prueba estrictamente necesario.
- Una propuesta de mitigación, si la tienes.

Si el reporte contiene información sensible, no adjuntes datos reales de gastos, ingresos, cuentas, tokens, contraseñas ni claves de firma.

## Qué esperar

- Confirmaremos la recepción del reporte cuando sea posible.
- Investigaremos y clasificaremos el impacto de la vulnerabilidad.
- Mantendremos la comunicación privada durante la investigación.
- Publicaremos una corrección o una mitigación cuando sea viable.
- Reconoceremos a quienes reporten vulnerabilidades de forma responsable, salvo que soliciten permanecer anónimos.

No garantizamos un plazo concreto de respuesta ni ofrecemos recompensas económicas actualmente.

## Alcance

Esta política cubre:

- La aplicación Android GastosLuminaX.
- El código fuente y los artefactos de publicación de este repositorio.
- La gestión local de datos financieros almacenados por la aplicación.
- La integración con Google Play Billing y Google Mobile Ads cuando el problema sea causado por la implementación de GastosLuminaX.

Los problemas exclusivamente relacionados con Google Play, AdMob, Google Play Billing, Android o servicios de terceros deben reportarse también al proveedor correspondiente.

## Buenas prácticas de divulgación

Solicitamos que no se acceda, modifique, elimine ni divulgue información de otros usuarios. Evita pruebas destructivas, ingeniería social, spam, denegación de servicio y cualquier actividad que interrumpa el funcionamiento de servicios de terceros.

Trabajaremos de buena fe con quienes respeten esta política y procuraremos coordinar la divulgación pública después de que exista una corrección disponible.

## Protección de secretos

Nunca subas al repositorio:

- Keystores `.jks` o `.keystore`.
- Contraseñas o tokens.
- Credenciales de Play Console, AdMob o Google Cloud.
- Archivos `keystore.properties`.
- Datos personales o financieros reales.
