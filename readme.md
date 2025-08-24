# ⚡️ Costos de Mano de Obra y Materiales de Electricidad para la provincia de Corrientes y alrededores.

Este repositorio contiene una base de datos estructurada en formato JSON para la gestión de precios de servicios y materiales eléctricos. La información está organizada de manera jerárquica para facilitar la consulta y el uso en diferentes proyectos, como aplicaciones de presupuestación, sistemas de gestión de costos o simplemente como una referencia detallada.

---

### 📂 Estructura de los datos

El archivo principal, `costos.json` (o el nombre que le des), está organizado de la siguiente manera:

* **Categorías principales**: Los servicios están agrupados en categorías generales, como `BAJA TENSIÓN`, `CORRIENTES DEBILES` y `COMPUESTOS`.
* **Subcategorías**: Dentro de cada categoría principal, los servicios se dividen en subcategorías más específicas, como `Acometida y tableros` o `Sistemas de seguridad`.
* **Elementos de servicio**: Cada subcategoría contiene una lista de objetos, donde cada uno representa un servicio o material específico con una **descripción** detallada y su **precio** correspondiente.

---

### 💡 Finalidad del repositorio

El objetivo principal es proporcionar una fuente de datos organizada y fácil de manejar para los siguientes propósitos:

* **Presupuestos y cotizaciones**: Permite generar de forma automática o semi-automática presupuestos detallados para proyectos eléctricos.
* **Análisis de costos**: Ayuda a analizar y comparar los precios de diferentes servicios y componentes.
* **Referencia profesional**: Sirve como una guía de precios actualizada para electricistas, ingenieros y constructores.

---

### 🛠️ Cómo usarlo

Puedes clonar este repositorio y utilizar el archivo JSON en tus propias aplicaciones, scripts o bases de datos. La estructura simple y estandarizada facilita la integración con diversas herramientas de software.

**Ejemplo de acceso a un dato en el archivo JSON:**

```json
{
    "description": "Acometida monofásica con sistema doble aislación sin jabalina",
    "price": 160000
}
