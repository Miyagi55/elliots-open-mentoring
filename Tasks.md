# 📝 Lista de Tareas - Computación en la Nube  

## 🚀 Task01: Creación de Cuenta y Exploración de Servicios  
### 🔹 Crear una cuenta en AWS  
- La mejor manera de aprender sobre la nube es mediante la práctica. Esta profesión es **98% práctica y 2% teórica**, así que es **indispensable** tener una cuenta en AWS.  
- Puedes registrarte aquí: [AWS - Página Oficial](https://aws.amazon.com/es/)  

### 🔹 Investigación sobre Servicios de Cómputo  
Investigar qué es y para qué sirven los siguientes servicios de cómputo en la nube:  

- **AWS**: EC2 (Elastic Compute Cloud), Lambda (Serverless).  
- **Azure**: Virtual Machines, Azure Functions.  
- **GCP**: Compute Engine, Cloud Functions.  

📌 **Exploración práctica:** Si ya tienes una cuenta en AWS, ubica el servicio **EC2** e interactúa con sus configuraciones (sin necesidad de activar o desplegar nada).  

---

## 🏗️ Task02: Servicios de Cómputo en la Nube - Ejemplos Prácticos  
📌 **Instrucciones:** Comparte tus respuestas en el grupo de Telegram como un mensaje de texto formateado en **Markdown** o como un enlace a un archivo **Markdown en un repositorio público de GitHub** (preferiblemente).  

### ❓ Preguntas:  

1️⃣ **Máquinas Virtuales:**  
   - ¿Qué tipo de aplicaciones podrías ejecutar en una máquina virtual (**AWS EC2, Azure Virtual Machines, Google Compute Engine**)?  
   - Da al menos **3 ejemplos concretos** y explica por qué una máquina virtual sería adecuada en cada caso.  
   - ✍️ [Tu respuesta aquí]  

2️⃣ **Funciones Serverless:**  
   - ¿Qué es una función serverless (**AWS Lambda, Azure Functions, Google Cloud Functions**)?  
   - Explica su funcionamiento y da al menos **2 ejemplos de casos de uso**.  
   - ✍️ [Tu respuesta aquí]  

3️⃣ **Comparación:**  
   - ¿Cuáles son las **diferencias** entre usar una **máquina virtual** y una **función serverless**?  
   - ¿En qué situaciones usarías cada una? Considera factores como **control, escalabilidad, costo y facilidad de uso**.  
   - ✍️ [Tu respuesta aquí]  

4️⃣ **Sitio Web Sencillo:**  
   - Si tuvieras que construir un sitio web sencillo, ¿qué servicio de cómputo usarías (**máquina virtual o función serverless**) y por qué?  
   - Justifica tu elección.  
   - ✍️ [Tu respuesta aquí]  

5️⃣ **Tipos de Instancias (AWS EC2):**  
   - Investiga al menos **3 tipos de instancias de Amazon EC2** (ej. `t2.micro`, `m5.large`, etc.).  
   - Explica para qué se utiliza cada una considerando **procesamiento, memoria RAM y costo**.  
   - ✍️ [Tu respuesta aquí]  

6️⃣ **Activación de Funciones Serverless:**  
   - ¿Cómo se activa una función serverless?  
   - Explica los diferentes **tipos de triggers o eventos** que pueden iniciar su ejecución.  
   - ✍️ [Tu respuesta aquí]  

7️⃣ **Herramientas de Despliegue:**  
   - Investiga al menos **2 herramientas** utilizadas para desplegar aplicaciones en la nube (ej. **AWS Elastic Beanstalk, Azure DevOps, Google Cloud Build**).  
   - Describe brevemente sus funciones.  
   - ✍️ [Tu respuesta aquí]  


## 📚 Recursos Adicionales  

🔹 **Documentación Oficial**:  
- 🟠 [AWS](https://aws.amazon.com/es/)  
- 🔵 [Azure](https://azure.microsoft.com/es-es/)  
- 🟢 [Google Cloud](https://cloud.google.com/)  

🔹 **Git y GitHub** (para compartir tus respuestas en un repositorio público):  
- 📖 [Guía de Git](https://rogerdudler.github.io/git-guide/index.es.html)  
- 📖 [Tutorial de GitHub](https://docs.github.com/es/get-started/quickstart/hello-world)  


🎯 **¡Mucha suerte con la tarea!**  
💬 **Recuerda compartir el enlace a tu repositorio en el grupo de Telegram una vez que hayas terminado. Si necesitas ayuda, no dudes en preguntar.** 🚀 

 ---

## 🔍 Task03: Solución de Problemas Comunes en AWS - S3, IAM y VPC  

📌 **Objetivo:** Investigar y comprender los problemas más comunes en **S3, IAM y VPC**, así como sus soluciones.  

📂 **Formato de entrega:** Documento **Markdown (.md)** en un repositorio de **GitHub** o compartido en el grupo de **Telegram**.  

### 🚨 Problemas Comunes y Soluciones  

#### 🗄️ **S3 (Simple Storage Service)**  
- **Problema Común 1:** Bucket S3 público con datos sensibles  
  - 📌 **Descripción:** Un bucket S3 está configurado como público, permitiendo el acceso a cualquier usuario.  
  - ⚠️ **Impacto:** Exposición de datos, riesgo de multas, pérdida de reputación.  
  - ✅ **Soluciones:**  
    1. Desactivar el acceso público en la consola de AWS o mediante AWS CLI.  
    2. Aplicar políticas de bucket para restringir el acceso.  
    3. Activar cifrado en reposo y en tránsito.  

🔹 **Mejores Prácticas en S3:**  
1. Usar políticas de acceso restringido.  
2. Activar el control de versiones.  
3. Monitorizar costos inesperados.  

#### 🔑 **IAM (Identity and Access Management)**  
- **Problemas Comunes:**  
  - Usuarios y roles con demasiados permisos.  
  - Claves de acceso expuestas.  
  - Falta de autenticación multifactor (MFA).  
  - Uso indebido de roles con privilegios elevados.  

🔹 **Mejores Prácticas en IAM:**  
1. Aplicar el principio de **menor privilegio**.  
2. Habilitar **MFA** para accesos críticos.  
3. Rotar credenciales periódicamente.  

#### 🌐 **VPC (Virtual Private Cloud)**  
- **Problemas Comunes:**  
  - Configuración incorrecta de grupos de seguridad y ACLs.  
  - Falta de aislamiento entre subredes.  
  - Problemas de conectividad a internet.  
  - Errores en la resolución de nombres DNS.  
  - Routing incorrecto de paquetes.  

🔹 **Mejores Prácticas en VPC:**  
1. Definir reglas estrictas en **grupos de seguridad y ACLs**.  
2. Utilizar **subredes privadas y públicas** de forma adecuada.  
3. Configurar correctamente el **enrutamiento**.  

📚 **Recursos Adicionales:**  
- 🔗 [AWS Documentación Oficial](https://aws.amazon.com/es/)  
- 🔗 [AWS Knowledge Center](https://aws.amazon.com/premiumsupport/knowledge-center/)  
- 🔗 [AWS Well-Architected Tool](https://aws.amazon.com/architecture/well-architected/)  

---

## 🏗️ Task04: Introducción a Microservicios y su Relevancia en la Nube y Serverless  

📌 **Objetivo:** Comprender los **microservicios** y su importancia en la nube, especialmente en **entornos serverless**.  

📂 **Formato de entrega:** Documento **Markdown (.md)** en **GitHub** o compartido en **Telegram**.  

### 📡 Parte 1: Modelos Serverless  

🔹 **Event-Driven Architecture (EDA):**  
- **Tarea:** Explica cómo una aplicación serverless responde a eventos y cuáles son sus ventajas.  

🔹 **Cold Starts vs. Warm Starts:**  
- **Tarea:** Explica la diferencia entre ellos y su impacto en el rendimiento.  
- Proporciona estrategias para reducir **cold starts**.  

🔹 **Gestión de Costos en Serverless:**  
- **Tarea:** Investiga cómo se calculan los costos en entornos serverless.  
- Proporciona **dos estrategias** para optimizar gastos.  

### 🏛️ Parte 2: Microservicios  

🔹 **¿Qué son los Microservicios?**  
- **Tarea:** Explica qué son los **microservicios** y cómo se diferencian de una arquitectura **monolítica**.  

🔹 **Relevancia en la Nube:**  
- **Tarea:** Analiza por qué los **microservicios** son útiles en la **nube**, considerando **escalabilidad, independencia de despliegue y flexibilidad**.  

🔹 **Microservicios en Serverless:**  
- **Tarea:** Explica cómo los microservicios se benefician de **serverless** y qué características los complementan.  

---

## 🚀 Task05: Implementación y Desafíos de Microservicios en Serverless  

📌 **Objetivo:** Explorar cómo implementar **microservicios** en **serverless**, identificando desafíos y soluciones.  

📂 **Formato de entrega:** Documento **Markdown (.md)** en **GitHub** o compartido en **Telegram**.  

### 🔍 Contenido  

🔹 **1️⃣ Despliegue de Microservicios en Serverless**  
- **Tarea:** Investigar cómo se despliegan microservicios en **AWS Lambda, Azure Functions y Google Cloud Functions**.  
- Proporcionar un **ejemplo de configuración y despliegue**.  

🔹 **2️⃣ Gestión de Estado en Serverless**  
- **Tarea:** Explorar **técnicas** para manejar el estado en **aplicaciones serverless** con microservicios.  

🔹 **3️⃣ Escalabilidad y Rendimiento**  
- **Tarea:** Explicar una **estrategia** para asegurar la **escalabilidad** de los microservicios.  
- Analizar cómo se gestionan los **cold starts** para minimizar impacto en la experiencia del usuario.  

🔹 **4️⃣ Monitoreo y Observabilidad**  
- **Tarea:** Investigar herramientas de **monitoreo** y prácticas de **observabilidad** en microservicios serverless.  
- ¿Qué soluciones ofrecen **AWS, Azure y GCP**?  

📚 **Recursos Adicionales:**  
- 🔗 [AWS Documentación Oficial](https://aws.amazon.com/es/)  
- 🔗 [Azure Functions](https://azure.microsoft.com/es-es/products/functions/)  
- 🔗 [Google Cloud Functions](https://cloud.google.com/functions/)  

---

🎯 **¡Buena suerte con las tareas!** 🚀  
💬 **Recuerda compartir tu trabajo en GitHub o en el grupo de Telegram. Si necesitas ayuda, pregunta.** 😊