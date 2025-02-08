### 🐳 Ejercicio nivel intermedio con Docker:  
**Optimizar una imagen Docker Multi-Stage**  
En esta tarea, optimizarás una imagen Docker existente utilizando **multi-stage builds**.  
El objetivo es reducir el tamaño de la imagen final y mejorar la seguridad. 🔒  

#### 🚀 Pasos:

1. **Selecciona una imagen base**:  
   - Elige una imagen base popular (ej. Node.js, Python, Java) que tenga un tamaño considerable.  

2. **Crea un Dockerfile**:  
   - Crea un `Dockerfile` que construya una aplicación simple (ej. un "Hola Mundo") utilizando la imagen base seleccionada.  

3. **Optimiza con Multi-Stage Builds**:  
   - Modifica el `Dockerfile` para utilizar multi-stage builds.  
   - Copia solo los archivos necesarios para la ejecución de la aplicación a una imagen más ligera (ej. `alpine`).  

4. **Compara los tamaños**:  
   - Compara el tamaño de la imagen original con el tamaño de la imagen optimizada.  

5. **Documenta el proceso**:  
   - Crea un archivo `README.md` en un repositorio de GitHub explicando el proceso de optimización.  
   - Incluye el `Dockerfile` original y el optimizado, y los resultados de la comparación de tamaños.  

---

### ☸️ Ejercicio nivel intermedio con Kubernetes:  
**Tarea: Desplegando una Aplicación con Despliegues y Servicios**  
En esta tarea, desplegarás una aplicación sencilla en un clúster **Kubernetes** utilizando **Deployments y Services**.  
Aprenderás a gestionar el ciclo de vida de la aplicación y a exponerla a través de un servicio. 🌍  

#### 📌 Pasos:

1. **Prepara la aplicación**:  
   - Elige una aplicación sencilla que puedas contenerizar (ej. un "Hola Mundo" en un contenedor web).  

2. **Crea un Deployment**:  
   - Crea un `Deployment` en Kubernetes para desplegar la aplicación.  

3. **Configura el número de réplicas y la estrategia de despliegue**:  
   - Define estrategias como `RollingUpdate`.  

4. **Crea un Service**:  
   - Crea un `Service` para exponer la aplicación.  
   - Elige el tipo de servicio adecuado (`ClusterIP`, `NodePort`).  

5. **Accede a la aplicación**:  
   - Verifica que la aplicación esté funcionando correctamente accediendo a ella a través del `Service`.  

6. **Escala la aplicación**:  
   - Ajusta el `Deployment` para aumentar o disminuir el número de réplicas.  

7. **Actualiza la aplicación**:  
   - Simula una actualización desplegando una nueva versión de la imagen del contenedor.  

8. **Documenta el proceso**:  
   - Crea un archivo `README.md` en un repositorio de GitHub explicando el proceso de despliegue.  
   - Incluye los archivos YAML del `Deployment` y `Service`, y los comandos utilizados.  

---

### 📢 Instrucciones:
✅ Comparte tus respuestas en el grupo de Telegram como un mensaje de texto formateado con Markdown o como un enlace a un archivo Markdown en un repositorio público de GitHub (preferiblemente).  
⏳ **Deadline:** Martes **21/01/25** 📆

