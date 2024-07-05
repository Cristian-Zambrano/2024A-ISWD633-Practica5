# Ejercicio
Configurar SonarQube utilizando Docker Compose, para esto necesitas dos servicios:
- Servicio: SonarQube
- Desde el host es necesario acceder a SonarQube por lo que necesitas mapear el puerto correspondiente.
- Servicio: PostgreSQL (existen otras opciones: Microsoft SQL Server, Oracle)
- Coloca un healtcheck para cada uno de los servicios.
- Los dos servicios deben pertenecer a uan red de tipo bridge
- Investiga cuáles son los volúmenes necesarios para cada servicio
- Investiga cuáles son las variables de entorno para que los servicios funcionen de manera adecuada.
  
# Una vez creado tu archivo .yaml realiza la respectiva prueba 
# COMPLETAR CON UNA CAPTURA DE PANTALLA LUEGO DE EJECUTAR EL ARCHIVO
![image](https://github.com/Cristian-Zambrano/2024A-ISWD633-Practica5/assets/94475992/c4bac4c0-ad1b-4e9d-b6f5-3582cd26067f)
![image](https://github.com/Cristian-Zambrano/2024A-ISWD633-Practica5/assets/94475992/3748cd9c-c61d-41fc-91a7-da656b22786c)

# ACCEDER A LOCALHOST:puertoDefinido para ingresar a SonarQube
9000
