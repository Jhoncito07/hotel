# Cambio de Base de Datos de H2 a Relacional

### Descripción
Esta tarea tiene como objetivo cambiar la base de datos de H2 (usada para desarrollo) a una base de datos relacional (como PostgreSQL). Indicare los cambios paso a paso que he realizado para el cambio y configuración de la nueva base de datos.

### Cambios realizados

1. **Configurar el archivo [application.properties]:**

- Cambio la configuración de H2 a PostgreSQL en el archivo de configuración de la aplicación Spring Boot:
  
![image](https://github.com/Jhoncito07/hotel/assets/151545686/119dafd0-1f40-41f3-9cb2-f65b5227efce)



2. **Actualizar dependencias:**

- Tener actualizada la dependencia de PostgreSQL en el archivo [pom.xml]:

![image](https://github.com/Jhoncito07/hotel/assets/151545686/273dc3f0-3a12-4ef6-bb63-02a8e3099226)



3. **Ejecución del Springboot:**

- Iniciamos el Springboot para corroborar de que todo marche bien. 

![image](https://github.com/Jhoncito07/hotel/assets/151545686/504c181e-43a2-481b-9447-6fb5ad556fdb)



4. **Funcionamiento en el PostgreSQL (pgadmin)**

- Pre-Visualización de la tabla creada al iniciar el proyecto presente:

![image](https://github.com/Jhoncito07/hotel/assets/151545686/d36b5638-8eac-4b62-80c6-ea9eee81ce01)





