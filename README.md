# Resumen-Hacker-tico---capitulo-7-8-9-10

# Capitulo 7
En este capitulo podemos observar de manera detallada la seguridad en la computación en nube, examinando tanto sus beneficios operativos como los riesgos críticos asociados a su implementación. Aquí se realizara la explicación de algunos de ellos. 

# Modelos de Servicio y Despliegue 
Suele dividirse en tres aspectos principales 
# Infraestructura como Servicio (IaaS):
El usuario paga por lo que consume, funcionando de manera parecida a un servidor virtual
# Plataforma como Servicio (PaaS): 
# Software como Servicio (SaaS):
Ofrece una solución completa que el usuario alquila y a la que accede generalmente mediante un navegador web

En el capitulo también se habla sobre las amenzas y Vectores de Ataque Detallados.
Como sabemos, la seguridad en la nube enfrenta riesgos específicos debido a la complejidad de herramientas y la facilidad con la que se pueden crear y olvidar recursos, lo que lleva a configuraciones incorrectas.

Uno de los ataques mas comunes es el uso de correos de phishing y spear phishing, aquí el atacante redirige al usuario a un sitio falso (como una página de inicio de sesión de Twitter o Microsoft 365) para robar nombres de usuario, contraseñas y tokens de sesión.
También tenemos el secuestro de cuentas  en la nube , este suele ser mas dificil de detectar y corregir 
Otro ataque que pueden usar es ataque al servidor metadatos entregan credenciales temporales a las aplicaciones. Los atacantes intentan consultar estos servicios para obtener acceso no autorizado a recursos como los depósitos S3 de AWS
También se conoce el Agotamiento de Recursos (DoS/DDoS), aunque la arquitectura de la nube es resistente, los atacantes utilizan botnets masivas para lanzar ataques volumétricos que miden bits, paquetes o solicitudes por segundo (bps, pps, rps) para intentar saturar el servicio

# Capitulo 8 

En este capitulo pudimos observar de manera detalla las metodologías utilizadas por los atacantes para garantizar el acceso persistente en sistemas comprometidos tras una intrusión inicial. 
Se tocan algunos conceptos claves y herramientas utilizadas:
# Creación de usuarios: 
Si se obtiene acceso de administrador o root, se pueden crear nuevas cuentas con contraseñas complejas.
# Tareas y trabajos programados: 
En Windows, los atacantes usan el Programador de tareas para ejecutar software de forma automatizada. Esto es especialmente útil para omitir el Control de cuentas de usuario 
# Daemons y procesos personalizados: 
Se crean servicios (daemons) que se inician automáticamente al arrancar el sistema.

# Shell:
Actua como la interfaz entre el atacante y el sistema operativo de la víctima

Se toca el tema de las herramientas especializadas, algunas de ellas son:
-Netcat 
-Meterpreter

# Capitulo 9
En el capitulo 9 pudimos observar que nos muestra los elementos escenciales para lograr construir un informe de pruebas de penetración , nos indica que un buen documento debe llevar secciones como:

-resumen ejecutivo
-hallazgos y metodologías de mitigación

También nos recalca la importancia de tener una distribución segura , esto para lograr evitar falsos positivos.
vamos a tocar el tema de como tener la estructura y contenido detallado de un informe:
Como se menciono , es importante contar con un buen informe para poder evitar hallazgos falsos , para ello debe tener:
- Resumen Ejecutivo
- Detalles del Alcance y Metodología
- Hallazgos y Análisis de Causa Raíz

También mencionaremos algunas estategias que mencionaba el capitulo para poder tenerlo presente.

# Estrategias de Remediación (Controles de Seguridad)
El informe debe recomendar controles específicos para mitigar los riesgos encontrados, clasificados en cuatro categorías:
-Controles Técnicos (Uso de tecnología)
-Fortalecimiento del sistema: Cerrar puertos innecesarios y eliminar software no utilizado
-Sanitización de entradas: Prevenir ataques como SQL Injection mediante consultas parametrizadas
- Autenticación de Varios Factores (MFA): Combinar "algo que sabe" (PIN) con "algo que tiene" (tarjeta o código) o "algo que es" (biometría)
- Microsegmentación: Aplicar políticas de seguridad a nivel de máquina virtual o contenedor, siguiendo un modelo de confianza cero (Zero Trust)

# Capitulo 10 

