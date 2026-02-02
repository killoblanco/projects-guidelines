# 📑 Guias de Proyectos
Crear una aplicación de software es un proceso estructurado que transforma una idea abstracta en un producto funcional. Este ciclo se conoce comúnmente como SDLC (Software Development Life Cycle).

Aquí te detallo las etapas clave, desde la investigación hasta la implementación técnica:

## 1. Definición e Investigación
Antes de escribir una sola línea de código, debes entender **qué** vas a construir y **para quién**.

- **Identificación del Problema:** ¿Qué necesidad resuelve la app?
- **Investigación de Mercado:** Analizar a la competencia y definir el público objetivo (User Personas).
- **Estudio de Viabilidad:** Evaluar si el proyecto es posible técnica y financieramente.
- **Definición de Alcance:** Establecer qué funciones tendrá la versión inicial (MVP - Producto Mínimo Viable).

## 2. Requerimientos del Software
Los requerimientos actúan como el contrato de lo que el sistema debe hacer. Se dividen en dos tipos:

### Requerimientos Funcionales
Son las acciones específicas que el software debe ejecutar.

- *Ejemplo:* "El sistema debe permitir al usuario recuperar su contraseña vía email."
- *Ejemplo:* "La app debe procesar pagos con tarjeta de crédito."

### Requerimientos No Funcionales
Se refieren a las cualidades y restricciones del sistema (el "cómo" se comporta).

- **Rendimiento:** El tiempo de carga debe ser menor a 2 segundos.
- **Seguridad:** Los datos deben estar cifrados bajo el estándar AES-256.
- **Escalabilidad:** Debe soportar hasta 10,000 usuarios simultáneos.

## 3. Diseño y Diagramación
Aquí es donde la lógica se visualiza. Los diagramas (generalmente usando el estándar UML) son esenciales para que los desarrolladores entiendan la arquitectura.

### Diagramas Principales
Tipo de Diagrama |	Propósito
-----------------|------------
**Casos de Uso** |	Describe cómo el usuario interactúa con el sistema.
**Diagrama de Clases** |	Muestra la estructura de los datos y cómo se relacionan los objetos.
**Diagrama de Secuencia** |	Ilustra el orden de los mensajes o procesos entre objetos a lo largo del tiempo.
**Diagrama de Flujo** |	Define la lógica algorítmica de un proceso específico.

## 4. Implementación Técnica (Desarrollo)
En esta fase se traduce el diseño a código real. Se suele dividir en dos capas:

- **Frontend:** La interfaz que el usuario ve y toca (HTML, CSS, JavaScript, React, Flutter).
- **Backend:** La lógica del servidor, bases de datos y APIs (Python, Node.js, Java, PostgreSQL).
- **Control de Versiones:** Uso de herramientas como Git (GitHub/GitLab) para gestionar los cambios en el código.

## 5. Pruebas y Despliegue

- **QA (Quality Assurance):** Se realizan pruebas unitarias, de integración y de usuario para encontrar errores (bugs).
- **Despliegue (Deployment):** La aplicación se sube a servidores (AWS, Google Cloud, Azure) o tiendas de aplicaciones (App Store, Play Store).
- **Mantenimiento:** Actualizaciones constantes para mejorar el rendimiento y corregir fallos reportados por los usuarios.
