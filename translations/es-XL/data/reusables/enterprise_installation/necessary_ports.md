| Port (Puerto) | Servicio | Descripción                                                                                                                                                      |
| ------------- | -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 22            | SSH      | Git a través de acceso SSH. Se admite clonar, extraer y subir operaciones a repositorios privados/públicos.                                                      |
| 25            | SMTP     | SMTP con soporte de encriptación (STARTTLS).                                                                                                                     |
| 80            | HTTP     | Acceso a aplicación web. *Todas las solicitudes se redireccionan al puerto HTTPS cuando se habilita SSL.*                                                        |
| 122           | SSH      | Acceso a shell de instancia. *El puerto predeterminado (22) se dedica a la aplicación de git+el tráfico de red ssh.*                                             |
| 161/UDP       | SNMP     | Se requiere para operar el protocolo de revisión de red.                                                                                                         |
| 443           | HTTPS    | Aplicación web y Git a través de acceso HTTPS.                                                                                                                   |
| 1194/UDP      | VPN      | Túnel de red de replicación segura en la configuración de alta disponibilidad.                                                                                   |
| 8080          | HTTP     | {% data variables.enterprise.management_console %} basada en la web de texto simple. *No se requiere excepto que el SSL esté inhabilitado de forma manual.* |
| 8443          | HTTPS    | {% data variables.enterprise.management_console %} seguro basada en la web. *Requerido para la instalación y la configuración básicas.*                     |
| 9418          | Git      | Puerto simple de protocolo de Git. Únicamente clonar y extraer operaciones a repositorios públicos. *Comunicación de red no encriptada.*                         |