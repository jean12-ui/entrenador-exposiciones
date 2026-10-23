# 🎙️ Simulador para Exposiciones (PRO Coach)

Un entorno web interactivo diseñado para ayudar a estudiantes a practicar y perfeccionar sus habilidades de oratoria y presentaciones académicas en tiempo real.

---

## 🚀 Características Principales

- **Reconocimiento de Voz en Tiempo Real:** Transcripción instantánea mediante el uso del `Web Speech API` de HTML5 (configurado para español de Perú `es-PE`).
- **PRO Coach & Evaluación Automatizada:** Generación de un reporte final con calificación global sobre 100, análisis de ritmo (PPM - Palabras Por Minuto) y diagnóstico cualitativo.
- **Análisis de Guion (Modo Lectura vs. Improvisación):** Permite ingresar el texto o diapositiva para calcular el porcentaje de coincidencia entre el discurso hablado y el escrito.
- **Detección Doble de Lenguaje:**
  - **Diccionario de Muletillas:** Identificación de pausas sonoras y palabras repetitivas (`este`, `o sea`, `eh`).
  - **Filtro de Registro Informal:** Detección de modismos y jerga no adecuada para presentaciones formales.
- **Personalización e Historial Local:**
  - Panel para agregar o eliminar muletillas personalizadas dinámicamente.
  - Registro de prácticas recientes almacenado en `localStorage`.
- **Acceso Freemium por PIN:** Modal de validación con PINs de demostración (`PALTA2026`, `DEMO-2026`, `EXPO100`).

---

## 🛠️ Tecnologías Utilizadas

- **Frontend:** HTML5, JavaScript vanilla (ES6+).
- **Estilos:** Tailwind CSS (vía CDN).
- **APIs del Navegador:** Web Speech API, Web Storage API (`localStorage`).
- **Entorno de Desarrollo:** Visual Studio Code, Live Server, Git & GitHub.

---

## 💻 Instalación y Uso Local

1. Clonar el repositorio:
   ```bash
   git clone [https://github.com/TU-USUARIO/entrenador-exposiciones.git](https://github.com/TU-USUARIO/entrenador-exposiciones.git)