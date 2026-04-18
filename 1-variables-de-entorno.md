# Variables de Entorno
### ¿Qué son las variables de entorno?
Las variables de entorno son variables disponibles para tu programa/aplicación de forma dinámica durante el tiempo de ejecución. 
# COMPLETAR

### Para crear un contenedor con variables de entorno

```
docker run -d --name <nombre contenedor> -e <nombre variable1>=<valor1> -e <nombre variable2>=<valor2>
```

### Crear un contenedor a partir de la imagen de nginx:alpine con las siguientes variables de entorno: username y role. Para la variable de entorno rol asignar el valor admin.

# COMPLETAR

<img width="1650" height="672" alt="image" src="https://github.com/user-attachments/assets/f7b89f42-8a22-4070-8cf9-54ae53137e58" />


### Crear un contenedor con la imagen de mysql, mapear todos los puertos
# COMPLETAR
<img width="1711" height="1035" alt="image" src="https://github.com/user-attachments/assets/bef2d836-2351-4fb2-b8f0-bc9ce4f1b2d6" />

### ¿El contenedor se está ejecutando?
No
# COMPLETAR
<img width="2839" height="384" alt="image" src="https://github.com/user-attachments/assets/b2880d46-bada-4f49-865f-c4273390221f" />

### Identificar el problema
# COMPLETAR
<img width="2386" height="392" alt="image" src="https://github.com/user-attachments/assets/0db345fa-26b9-4bd1-8a70-665a28b125ed" />

### Para crear un contenedor con variables de entorno especificadas
- Portabilidad: Las aplicaciones se vuelven más portátiles y pueden ser desplegadas en diferentes entornos (desarrollo, pruebas, producción) simplemente cambiando el archivo de variables de entorno.
- Centralización: Todas las configuraciones importantes se centralizan en un solo lugar, lo que facilita la gestión y auditoría de las configuraciones.
- Consistencia: Asegura que todos los miembros del equipo de desarrollo o los entornos de despliegue utilicen las mismas configuraciones.
- Evitar Exposición en el Código: Mantener variables sensibles como contraseñas, claves API, y tokens fuera del código fuente reduce el riesgo de exposición accidental a través del control de versiones.
- Control de Acceso: Los archivos de variables de entorno pueden ser gestionados con permisos específicos, limitando quién puede ver o modificar la configuración sensible.
<img width="2879" height="581" alt="image" src="https://github.com/user-attachments/assets/de9ead61-8699-4777-af92-b8c582d62af4" />

### ¿Qué bases de datos existen en el contenedor creado?
# COMPLETAR
<img width="753" height="429" alt="image" src="https://github.com/user-attachments/assets/bff6fe85-0438-42f3-8a99-812f26215f87" />

