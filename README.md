# POIs API 🌍

## Descripción
Esta es una **API REST** creada con **Spring Boot** para gestionar Puntos de Interés (**POIs**). La aplicación se conecta a una base de datos **MongoDB** para almacenar información de los POIs y proporciona endpoints para la creación, consulta y eliminación de estos.

## Características
- Crear, consultar y eliminar POIs.
- Conexión a **MongoDB** mediante una URL de conexión configurada a través de **variables de entorno**.
- Desplegado usando **Docker** y **OpenShift**.

## Tecnologías Usadas
- **Java** con **Spring Boot**.
- **MongoDB Atlas** (base de datos en la nube).
- **Docker** para contenerización.
- **OpenShift** para el despliegue.

## Instrucciones de Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/FerCz2489/pois-api.git
   cd pois-api
2. Construye el maven
   ```bash
   mvn clean package
3. Dockeriza la imagen
   ```bash
   Docker build
4. Despliega en OpenShift
   ```bash
   Ocupa el manifiesto yaml que viene en los archivos para desplegarlo con comandos oc
5. Verificación de mi CI/CD desde mi repositorio diploe2-lfcz/pois-api

