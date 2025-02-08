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