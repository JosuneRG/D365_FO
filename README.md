# D365 F&O -xpp-roadmap

Repositorio de estudio y práctica de **X++ orientado a Microsoft Dynamics 365 Finance & Operations (D365FO)**.

Este proyecto está diseñado para evolucionar desde **conceptos básicos del lenguaje** hasta **escenarios reales de desarrollo en D365FO**, incluyendo acceso a datos, extensibilidad, lógica de negocio y procesos batch.

---

## 🎯 Objetivo

* Aprender **X++ desde cero hasta nivel avanzado**
* Entender el desarrollo real en **Dynamics 365 Finance & Operations**
* Practicar patrones utilizados en proyectos empresariales
* Construir un **portfolio técnico profesional**

---

## 🧱 Estructura del repositorio

```text
d365fo-xpp-roadmap/
│
├─ 00-setup/
├─ 01-basics/
├─ 02-classes/
├─ 03-data-access/
├─ 04-extensions/
├─ 05-events/
├─ 06-business-logic/
├─ 07-transactions/
├─ 08-testing/
├─ 09-advanced/
├─ 10-jobs/
│  ├─ 01_UpdateCustomerCreditJob.xpp
│  ├─ 02_UpdateMultipleCustomersJob.xpp
│  ├─ 03_UpdateRecordsetJob.xpp
│  ├─ 04_DebuggingJob_ReadAndValidate.xpp
│  └─ 05_BatchLikeJob_SysOperation.xpp
│
└─ README.md
```

---

## 📚 Contenido por módulos

### 🔹 01-basics

Fundamentos del lenguaje X++:

* Sintaxis básica
* Variables y condiciones
* Bucles y colecciones (`List`, `Map`)
* Métodos y formateo

---

### 🔹 02-classes

Programación orientada a objetos en X++:

* Clases y métodos
* Constructores
* Parm methods (patrón estándar D365)
* Clases helper y servicios

---

### 🔹 03-data-access

Acceso a datos en D365FO:

* `select firstOnly`
* `while select`
* joins (`exists join`)
* `insert / update / delete`
* `update_recordset`

📌 *Bloque clave para cualquier desarrollador D365FO.*

---

### 🔹 04-extensions

Extensibilidad en D365FO:

* Table extensions
* Class extensions
* Chain of Command (CoC)

📌 *Modelo moderno que sustituye al overlayering.*

---

### 🔹 05-events

Arquitectura basada en eventos:

* Data Event Handlers
* Delegates
* Subscribers

📌 *Permite desacoplar lógica y mejorar escalabilidad.*

---

### 🔹 06-business-logic

Patrones de negocio:

* Validaciones
* Service pattern
* SysOperation (procesos y batch)

---

### 🔹 07-transactions

Gestión de transacciones:

* `ttsBegin / ttsCommit`
* Manejo de errores (`try/catch`)
* Set-based vs row-by-row

---

### 🔹 08-testing

Testing en X++:

* `SysTestCase`
* Pruebas unitarias

📌 *Poco común, pero muy valorado en proyectos.*

---

### 🔹 09-advanced

Conceptos avanzados:

* Rendimiento
* Integraciones
* Buenas prácticas

---

### 🔹 10-jobs 🧪

Jobs de desarrollo y debugging.

Incluye:

* Actualización de datos individuales
* Actualización masiva de registros
* Uso de `update_recordset` (best practice)
* Job de debugging (lectura y validación de datos)
* Ejemplo de proceso tipo batch con **SysOperation**

📌 **Importante:**
Los jobs:

* no forman parte de la lógica productiva
* se usan para pruebas, debugging y utilidades de desarrollo

---

## 🧠 Cómo usar este repositorio

1. Empieza por **01-basics**
2. Avanza progresivamente
3. Entiende cada ejemplo
4. Modifica el código
5. Usa los jobs para probar lógica

---

## ⚠️ Nota importante

Este repositorio está orientado a aprendizaje.

👉 El código X++ solo se ejecuta en un entorno real de **D365FO (Dev VM o entorno conectado)**.

---

## 💼 Enfoque profesional

Este repo simula un entorno real de desarrollo:

* Uso de tablas estándar (`CustTable`, `SalesTable`)
* Separación por capas
* Uso de extensibilidad moderna
* Aplicación de patrones reales

---

## 🛠️ Tecnologías

* X++
* Microsoft Dynamics 365 Finance & Operations
* Visual Studio 2019
* Git / GitHub

---

## 📌 Autor

Josune Rodríguez Gomez
Desarrollador D365FO (en formación)

🔗 LinkedIn: https://www.linkedin.com/in/josune-rodriguez-gomez-854080177/
💻 GitHub: https://github.com/JosuneRG

---

💡 *“En D365FO no solo escribes código, construyes procesos empresariales.”*
