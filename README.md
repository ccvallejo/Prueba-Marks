# Proyecto de Pruebas Automatizadas – MakersPay y SauceDemo

## 🧪 Descripción
Este repositorio contiene los módulos de **pruebas automatizadas y funcionales**. Incluye:

1. **Módulo de Automatización – Smoke Test (SauceDemo)**  
   - **Nota:** No se completó la prueba de login exitoso con credenciales válidas debido a desconocimiento en la automatización.  
   - Se abordaron aspectos teóricos y preparación del entorno para realizar la prueba.

2. **Módulo Funcional – Producto ficticio MakersPay**  
   - Se documentó y diseñó todo el **proceso de testing funcional** para la billetera digital MakersPay.  
   - Incluye escenarios, casos de prueba y reglas de negocio.

3. **Módulo API – ReqRes**  
   - Prueba funcional de la API de creación y consulta de usuarios (`POST /users` y `GET /users/{id}`) con verificación de código de estado y datos enviados.  
   - Se incluyeron **casos de prueba adicionales** para mejorar la cobertura funcional.

---

## 🔹 Tecnologías utilizadas
- **Pruebas API:** Postman

---

## 🗂️ Casos de prueba y documentación

Dentro de las **Issues** del repositorio se encuentra la **HU generada para el punto #3** (API ReqRes) y se agregaron **8 casos de prueba** que contemplan:

- Creación de usuario con datos válidos  
- Consulta del usuario creado  
- Validación de código HTTP 201 y 200  
- Verificación de consistencia de datos  
- Manejo de errores y validación de respuestas inesperadas  
- Escenarios positivos y negativos para robustez  

---

## ⚡ Buenas prácticas aplicadas

- Documentación clara de escenarios y reglas de negocio.  
- Identificación de casos positivos y negativos.  

---

## 📌 Notas importantes

- La prueba de **login exitoso en SauceDemo** no se implementó en ejecución debido a desconocimiento en la automatización de este flujo.  
- El resto de módulos cumplen con todos los requerimientos funcionales y de API.  

---

Dentro de las Issues encontramos la HU generada para el punto #3 y agregamos 8 casos de prueba 

## 📎 Autor
**cristian VALLEJO**  
Analista QA | Ingenierío de Sistemas  
https://github.com/ccvallejo
