# Trello API Automation Testing Portfolio 🚀

Este proyecto forma parte de mi portfolio profesional como **Junior QA Tester**. Consiste en una suite de pruebas automatizadas para la API de Trello, cubriendo flujos de trabajo principales, validaciones de integridad de datos y manejo de errores.

## 📌 Escenarios de Prueba

La colección de Postman está organizada en dos grandes módulos estratégicos:

### 1. Regression Suite (Happy Path) ✅
Orientada a verificar que las funcionalidades principales sigan operativas tras cambios en el código.
* **Workspaces:** Creación, consulta y eliminación de espacios de trabajo.
* **Boards:** Flujo completo de gestión de tableros.
* **Lists & Cards:** Pruebas de creación y movimiento de tarjetas entre listas.
* **Validaciones:** Verificación de códigos de estado (200 OK), tiempos de respuesta (<500ms) y esquemas JSON.

### 2. Negative Testing Suite (Error Handling) ❌
Diseñada para evaluar la robustez de la API ante entradas inválidas o acciones no autorizadas.
* **Autenticación:** Intentos de acceso con API Key o Tokens inválidos o expirados.
* **Validación de Campos:** Creación de recursos con nombres vacíos o formatos de datos incorrectos.
* **Recursos Inexistentes:** Consultas a IDs de tableros o listas que no existen (404 Not Found).
* **Límites de Seguridad:** Pruebas de borrado de recursos ya eliminados.

## 🛠️ Tecnologías Utilizadas

* **Postman:** Diseño y ejecución de colecciones de peticiones HTTP.
* **JavaScript:** Scripts de pre-solicitud y tests de aserción (Pm Library).
* **Git/GitHub:** Control de versiones y despliegue del portfolio.
* **Trello API:** Documentación oficial como base para los casos de prueba.

## 🚀 Cómo ejecutar las pruebas

1. **Clonar el repositorio:** `git clone https://github.com/Simondelc/trello-api-automation-testing.git`
2. **Importar en Postman:** Importar el archivo `.json` de la colección y el archivo de ambiente (`environment`).
3. **Configurar Variables:** Asegurarse de tener configuradas las variables `apiKey` y `token` en el ambiente de Postman.
4. **Ejecutar:** Utilizar el *Collection Runner* de Postman para correr todos los tests de forma secuencial.

---
📫 **Contacto:**
Carlos Simón del Carpio - Junior QA Tester 
www.linkedin.com/in/carlos-simón-del-carpio