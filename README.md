# # Tarea (a+b) · Cloud: niveles y funciones (DAW 1º)

## 🅰️ Tarea A — Niveles de cloud (IaaS/PaaS/SaaS)
Crea una tabla con 10 servicios reales. Incluye enlace oficial y justifica responsabilidades.

| Servicio | Proveedor | Nivel (IaaS/PaaS/SaaS) | Enlace oficial | ¿Qué gestiona el proveedor? | ¿Qué gestiona el equipo/usuario? |
|---------|----------|-------------------------|----------------|-----------------------------|----------------------------------|
| EC2 | Amazon Web Services | IaaS | https://aws.amazon.com/ec2/ | Infraestructura física, virtualización, red | Sistema operativo, aplicaciones, seguridad |
| Compute Engine | Google Cloud | IaaS | https://cloud.google.com/compute | Servidores, red, almacenamiento base | SO, configuración, apps |
| Azure Virtual Machines | Microsoft Azure | IaaS | https://learn.microsoft.com/azure/virtual-machines/ | Infraestructura y virtualización | SO, middleware, aplicaciones |
| Heroku | Salesforce | PaaS | https://www.heroku.com/ | Plataforma, runtime, escalado | Código de la aplicación |
| Google App Engine | Google Cloud | PaaS | https://cloud.google.com/appengine | Entorno de ejecución, escalado | Código y configuración de la app |
| Azure App Service | Microsoft Azure | PaaS | https://learn.microsoft.com/azure/app-service/ | Hosting y plataforma de ejecución | Código y lógica de negocio |
| Azure SQL Database | Microsoft Azure | PaaS | https://learn.microsoft.com/azure/azure-sql/ | Motor de base de datos, backups | Esquema, consultas y datos |
| Salesforce CRM | Salesforce | SaaS | https://www.salesforce.com/ | Aplicación completa, actualizaciones | Uso y configuración de datos |
| Google Workspace | Google | SaaS | https://workspace.google.com/ | Apps, infraestructura y mantenimiento | Gestión de usuarios y documentos |
| Dropbox Business | Dropbox | SaaS | https://www.dropbox.com/business | Aplicación y almacenamiento cloud | Subida y gestión de archivos |

---

## 🅱️ Tarea B — Funciones principales de cloud (arquitectura)
Incluye un diagrama (ASCII/Mermaid/imagen) y una explicación breve.

### Diagrama


graph TD
    U[Usuario / Navegador]
    CDN[CDN / Edge]
    FE[Frontend Web]
    API[API Backend]
    DB[(Base de Datos)]
    ST[Storage de ficheros]

    U --> CDN
    CDN --> FE
    FE --> API
    API --> DB
    API --> ST



### Explicación (8–12 líneas)
(Describe el flujo front → API → BBDD/storage y dónde entra la cloud)

El usuario accede a la aplicación web desde el navegador.
La petición llega a la CDN, que entrega el contenido estático de forma rápida.
El frontend se ejecuta en la cloud y muestra la interfaz.
Cuando el usuario realiza una acción, el frontend llama a la API backend.
La API se ejecuta en la cloud y procesa la lógica de negocio.
Para datos estructurados consulta la base de datos cloud.
Para archivos utiliza el servicio de almacenamiento cloud.
La base de datos devuelve los datos a la API.
La API responde al frontend.
El frontend muestra el resultado al usuario final.

### Mapeo de funciones cloud a componentes (mínimo 3)
- Procesamiento → Frontend web y API backend alojados en la cloud
- Ejecución → API backend que ejecuta la lógica de negocio
- Almacenamiento → Base de datos cloud y storage de ficheros
- Intercambio → API REST y CDN para comunicación y entrega de contenidos

## 📚 Fuentes (enlaces oficiales)
[(Enlaces oficiales usados en la tabla A y en la B)]

https://aws.amazon.com/ec2/

https://cloud.google.com/compute

https://learn.microsoft.com/azure/virtual-machines/

https://www.heroku.com/

https://cloud.google.com/appengine

https://learn.microsoft.com/azure/app-service/

https://learn.microsoft.com/azure/azure-sql/

https://www.salesforce.com/

https://workspace.google.com/

https://www.dropbox.com/business)
