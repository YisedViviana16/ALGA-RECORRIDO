# ALGA-RECORRIDO
# ALGA: Del Feedback a la Acción (Versión Web Transferible)

Este repositorio contiene la versión interactiva y desacoplada del dispositivo pedagógico **ALGA**, diseñado para mediar la retroalimentación formativa, el *feedback literacy* y la autorregulación estudiantil en cualquier área curricular.

## 🚀 Despliegue Inmediato en GitHub Pages

1. **Crear Repositorio en GitHub:**
   * Entra a [github.com/new](https://github.com/new).
   * Nombre sugerido: `alga-recorrido` (público).
2. **Subir los Archivos:**
   * Sube los archivos `index.html` y `README.md` a la rama principal (`main`).
3. **Activar GitHub Pages:**
   * Dirígete a la pestaña **Settings** (Configuración) de tu repositorio.
   * En el menú lateral izquierdo, haz clic en **Pages**.
   * En la sección **Build and deployment > Branch**, selecciona `main` y la carpeta `/ (root)`.
   * Presiona **Save**.
4. **Acceder:**
   * En 1 o 2 minutos, GitHub te entregará la URL pública:  
     `https://<tu-usuario>.github.io/alga-recorrido/`

---


## 🧩 Transferibilidad a Cualquier Asignatura

La estructura técnica fue separada del contenido curricular:

* **Zona Editable (`CONFIG`):** En el archivo `index.html`, todas las preguntas, categorías de análisis y bancos de vocabulario están centralizados en las primeras líneas de JavaScript (`const CONFIG = { ... }`).
* Para implementar ALGA en **Matemáticas, Lenguaje, Ciencias o Ciencias Sociales**, el docente únicamente modifica las cadenas de texto de esa sección; nunca toca el motor de navegación, persistencia ni gamificación.

---

## 🏆 Ruta Metodológica del Usuario

1. **Bienvenida e Identificación:** Registro del estudiante y presentación del propósito formativo.
2. **Reto 1 (Explorador/a del Eco):** Decodificación del feedback recibido apoyado en un banco léxico reflexivo.
3. **Reto 2 (Analista del Saber):** Cuestionarios interactivos con retroalimentación inmediata sobre criterios de calidad.
4. **Reto 3 (Constructor/a ALGA):** Principios de coevaluación ética y constructiva entre pares.
5. **Reto 4 (Espejo del Pensamiento):** Consolidación de un plan de acción concreto hacia el producto final.
6. **Cierre:** Certificado de logro descargable como **Maestro/a ALGA**.

---

## 🛠️ Especificaciones Técnicas

* **Arquitectura:** HTML5, CSS3 moderno (diseño responsivo) y JavaScript vanilla.
* **Persistencia:** `localStorage` (guarda el avance del estudiante de manera local sin necesidad de base de datos ni backend).
* **Dependencias CDN:** Google Fonts y Canvas Confetti.

