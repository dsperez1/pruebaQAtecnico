# Automatización de Pruebas con Cypress, JavaScript y Page Object Model

Este proyecto contiene pruebas automatizadas para una aplicación web, utilizando **Cypress** como framework de testing, **JavaScript** como lenguaje de programación, y el patrón **Page Object Model (POM)** para mantener una arquitectura modular, reutilizable y fácil de mantener.

---

## 📁 Estructura del Proyecto

/cypress
/e2e
/specs
- 01_login_registro.cy.js
- 02_administracion.cy.js
- 03_evaluaciones.cy.js
/fixtures
- test-data.json
/pages
- LoginPage.js
- RegisterPage.js
- AdminPage.js
- EvaluationsPage.js
/screenshots
/downloads
/support
- commands.js
/README.md


---

## 🚀 Tecnologías Utilizadas

### ✅ Cypress

**¿Por qué usar Cypress?**
- Herramienta moderna para pruebas End-to-End.
- Corre directamente en el navegador, lo que facilita el debugging.
- Proporciona recarga automática, capturas de pantalla, grabaciones de vídeo, y más.

**Beneficios:**
- Esperas automáticas por elementos del DOM.
- API sencilla y expresiva.
- Fácil integración con CI/CD.
- Ideal para pruebas UI de aplicaciones modernas.

### 💻 JavaScript

**¿Por qué JavaScript?**
- Lenguaje de programación nativo del navegador y ampliamente adoptado en desarrollo web.
- Compatible nativamente con Cypress.
- Familiar para la mayoría de los desarrolladores frontend.

**Beneficios:**
- Bajo nivel de entrada.
- Ecosistema maduro y amplio soporte de librerías y herramientas.

### 📦 Page Object Model (POM)

**¿Por qué POM?**
- Patrón de diseño que mejora la separación entre las pruebas y la lógica de interacción con la interfaz de usuario.
- Facilita el mantenimiento cuando cambian los elementos de la UI.

**Beneficios:**
- Mejora la legibilidad del código.
- Evita duplicación.
- Hace que las pruebas sean más escalables y reutilizables.

---

## ▶️ Cómo Ejecutar el Proyecto

1. Clona el repositorio:
   ```bash
   git clone <URL-del-repo>
   cd <nombre-del-proyecto>
```


Instala las dependencias:
```
npm install
```
Abre Cypress en modo interactivo:
```
npx cypress open
```
Ejecuta pruebas en modo headless (CLI):
```
npx cypress run
```

✨ Buenas Prácticas Implementadas
Separación entre datos (/fixtures) y lógica (/pages).

Reutilización de componentes mediante POM.

Agrupación de pruebas por funcionalidad en /specs.

Uso de commands.js para extender comandos personalizados de Cypress.

📌 Licencia
Este proyecto está licenciado bajo los términos de la Licencia MIT.


