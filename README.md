#  NexoUp

Aplicacion web diseñada para facilitar la gestion de negocios minoristas, pequeños comercios y kioscos, permitiendo controlar ventas, stock,pagos, proveedores y finanzas  de forma simple y eficiente.

##  Documentación y Wiki
la información detallada, guías y documentos del proyecto se encuentran  en la Wiki.

 **[Haz clic aquí para ir a la Wiki del proyecto](https://github.com/celer2001/NexoUp/wiki)**

## Descripción y Objetivos
NexoUp busca ayudar a emprendedores y comerciantes, con distintos niveles de experiencia, enfocandonos en novatos a intermedios, permitiendoles administrar su negocio sin necesidad de preparacion previa.

### Objetivos principales
- Registrar ventas y generar comprobantes.
- Gestionar y controlar el stock de productos (incluyendo búsqueda por nombre o código de barras).
- Registrar y gestionar clientes, cuentas corrientes de clientes y proveedores.
- Generar presupuestos y registrar/consultar ingresos, egresos, medios de pago y reportes financieros.
## Alcance y Limitaciones
- **Incluye:** gestion de ventas, comprobantes, productos,stock,clientes, cuentas corrientes,proveedores, medios de pago movientos financieros.
- **No incluye:** pagos online ni integración bancaria.
## Tecnologías y Recursos
- **Tipo de aplicación:** aplicación web alojada en servidor con base de datos.
- **Entorno y herramientas:** navegadores web modernos, posible lector de códigos de barras, pruebas E2E con Playwright y auditoría de accesibilidad con Lighthouse.
  ## Instalación y Ejecución
**Requisitos Previos**
- Node.js.
- Java JDK 21.
- PostgreSQL.
- Un entorno de desarrollo como IntelliJ IDEA o Visual Studio Code.
**Paso 1. Configurar la base de datos**
- Iniciar PostgreSQL y crear la base de datos NexoUp si todavia no existe (CREATE DATABASE "Nexoup";).
- la conexion utilizada por el backend es local:
  -Host: localhost
  -Puerto: 5432
  -Base de datos: Nexoup
**Paso 2. Instalar las dependencias del frontend**
  - Abrir PowerShell en la carpeta dek proyecto y ejecutar:
 - cd Frontend
 npm.cmd install
**Paso 3. Configurar el backend**
- En el archivo application.properties del backend esta configurada de esta manera:
-spring.datasource.url=jdbc:postgresql://localhost:5432/NexoUp
-spring.datasource.username=postgres
- spring.datasource.password=TU_CONTRASEÑA
- Reemplazar TU_CONTRASEÑA por la contraseña configurada en PostgreSQL.
**Ejecución del backend**
  -Desde IntelliJ IDEA, ejecutar la clase principal com.nexoup.backend.BackendApplication. El servidor se inicia en el puerto 8080.
  **Ejecución del frontend**
-Desde la carpeta Frontend, ejecutar:
- npm.cmd run dev
Finalmente, ingresar desde el navegador a:
- http://localhost:5173
- Para utilizar el sistema correctamente, PostgreSQL y el backend deben estar en funcionamiento antes de iniciar el frontend.
## Estado del Proyecto
- **Sprints registrados en Issues:** Sprint 1, Sprint 2, Sprint 3 y Sprint 4.
- **Estado actual de Issues:** 13 abiertos / 0 cerrados (revisar y actualizar según el avance real).
## Equipo
