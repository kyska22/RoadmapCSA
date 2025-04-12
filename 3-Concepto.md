# **El Poder de la "C" en CADD-SAML-DISCO: Dominando los Conceptos Clave en la Nube**  

**Como Arquitecto de Soluciones en la Nube**, el primer paso para diseñar cualquier sistema es **comprender profundamente los conceptos fundamentales** de las tecnologías que estás utilizando.  

**La "C" (Concepto)** en la **Etapa 1 (CADD)** es crucial: **antes de diseñar, desplegar u optimizar, debes entender a fondo los recursos** que vas a utilizar.  

---

## **🔍 ¿Por Qué el "Concepto" Va Primero?**  
No construirías una casa sin saber para qué sirven los ladrillos, el cemento o las vigas de acero. De la misma manera, en la arquitectura en la nube:  
- **Debes entender cada servicio antes de usarlo.**  
- **Implementar recursos sin conocimiento lleva a ineficiencias, riesgos de seguridad y costos innecesarios.**  

---

## **❓ Preguntas Clave que Todo Arquitecto Debe Hacerse**  
Antes de usar **cualquier** servicio en la nube (una VM, una base de datos, una función serverless, etc.), pregúntate:  

### **1️⃣ ¿Qué es este recurso?**  
- **Ejemplo:** *"¿Qué es AWS Lambda?"*  
  - Respuesta: Un servicio de computación serverless que ejecuta código en respuesta a eventos.  

### **2️⃣ ¿Cuál es su propósito?**  
- **Ejemplo:** *"¿Por qué usar Amazon S3 en lugar de EBS?"*  
  - Respuesta: S3 es para almacenamiento de objetos (datos no estructurados), mientras que EBS es almacenamiento en bloques (para instancias EC2).  

### **3️⃣ ¿Cómo funciona?**  
- **Ejemplo:** *"¿Cómo distribuye el tráfico un Azure Load Balancer?"*  
  - Respuesta: Usa reglas para dirigir solicitudes entre instancias de VM saludables.  

### **4️⃣ ¿Cuáles son sus características principales?**  
- **Ejemplo:** *"¿En qué se diferencia Google Cloud Pub/Sub de AWS SQS?"*  
  - Respuesta: Pub/Sub es un sistema de mensajería en tiempo real, mientras que SQS es un servicio basado en colas.  

### **5️⃣ ¿Cuáles son sus ventajas y desventajas?**  
- **Ejemplo:** *"¿Debo usar Kubernetes (EKS) o Serverless (Lambda)?"*  
  - ✅ **Ventajas de EKS:** Control total, ideal para cargas de trabajo largas.  
  - ❌ **Desventajas de EKS:** Complejidad de gestión, mayor costo.  
  - ✅ **Ventajas de Lambda:** Sin gestión de servidores, escalado automático.  
  - ❌ **Desventajas de Lambda:** "Cold starts", tiempo de ejecución limitado.  

---

## **🚀 Cómo Este Enfoque Te Convierte en un Mejor Arquitecto**  
1. **Evita errores costosos** (ej: elegir la base de datos incorrecta para una app con muchas transacciones).  
2. **Ayuda a optimizar costos** (seleccionando servicios eficientes).  
3. **Mejora la seguridad** (sabiendo cómo maneja el servicio el cifrado y el control de acceso).  
4. **Permite resolver problemas más rápido** (si entiendes cómo funciona, puedes depurar mejor).  

---

## **📌 Ejercicio Práctico**  
Elige **un servicio en la nube** (ej: AWS RDS, Azure Functions, GCP BigQuery) y **responde las 5 preguntas clave** sobre él.  

💡 **Ejemplo:**  
- **Servicio:** AWS DynamoDB  
- **¿Qué es?** Base de datos NoSQL para aplicaciones de baja latencia.  
- **¿Propósito?** Base de datos altamente escalable y serverless.  
- **¿Cómo funciona?** Usa particiones para escalar, precio por solicitud.  
- **¿Características clave?** Latencia en milisegundos, escalado automático.  
- **¿Pros y contras?**  
  - ✅ Rápido, escalable, serverless.  
  - ❌ No soporta JOINs SQL, costoso para cargas con muchas escrituras.  

---

## **🎯 Conclusión**  
**"No puedes diseñar lo que no entiendes."**  
- **Dominar los conceptos** es la base de una buena arquitectura en la nube.  
- **Nunca dejes de aprender** (¡la nube evoluciona rápido!).  

**En la próxima sesión, profundizaremos en la "A" (Arquitectura) de CADD-SAML-DISCO.** 🚀  

¡Gracias! 🙌
