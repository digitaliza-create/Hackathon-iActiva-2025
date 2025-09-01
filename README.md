# Hackathon-iActiva-2025

## 🚀 Bienvenida  
Bienvenido/a al repositorio oficial del **Hackathon iActiva 2025** organizado por **Digitaliza Madrid**.  
Aquí encontrarás la **estructura base de carpetas**, las **instrucciones de trabajo** y los espacios donde cada equipo debe subir sus **entregables**.  

---

## 📅 Información básica  
- **Fecha:** 24 de septiembre de 2025  
- **Horario:** 09:00 – 17:00  
- **Lugar:** Centro de Innovación Digitaliza Madrid (C/ Embajadores 181)  

---

## 🎯 Retos del Hackathon  
- **Reto 1:** Aplicación de Ayudas Públicas con IA Generativa  
- **Reto 2:** Seguridad en un Asistente Conversacional con IA  

👉 Los detalles completos de cada reto están en la **Guía del Participante**.  

---

## ✅ Buenas prácticas
- Documenta cada logro en /docs/logroX/.
- Usa nombres claros en commits y archivos.
- Comenta el código generado con IA (# Generado con ayuda de Copilot).
- Mantén modularidad en el código.
- Añade evidencias de pruebas (logs, capturas, reportes).
---

## ⚖️ Propiedad intelectual y uso del código

- Todos los proyectos se publicarán bajo licencia MIT o GPLv3 (a elección de cada equipo).
- Madrid Digital podrá referenciar, analizar y reutilizar las soluciones con fines no comerciales.
- Los participantes mantienen la autoría y titularidad de sus soluciones y podrán seguir desarrollándolas libremente tras el evento.

## 🏆 Categorías de premios
- Mejor solución técnica – Reto 1
- Mejor solución técnica – Reto 2
- Mejor presentación (Pitch Final)
--

## 📝 Checklist rápido de entregables
- Antes de la hora límite (14:30 h) asegúrate de que tu carpeta contiene:
-  Documentación técnica (máx. 5 páginas).
-  Código fuente limpio y documentado.
-  Evidencias de pruebas (logs, capturas, reportes).
-  Presentación final (máx. 6 diapositivas en PDF/PPT).
-  Pitch de 5 minutos + 3 minutos de preguntas.


## 🗂️ Estructura del repositorio

```text
Hackathon-iActiva-2025/
│
├── reto1_aplicacion/
│   └── equipoX/   # Carpeta de cada equipo
│       ├── docs/
│       ├── src/
│       ├── tests/
│       └── README.md
│
├── reto2_asistente/
│   └── equipoX/
│       ├── docs/
│       ├── src/
│       ├── tests/
│       └── README.md
│
└── README.md   # Este documento


👥 Instrucciones para equipos
Dentro de tu reto asignado (reto1_aplicacion o reto2_asistente), duplica la carpeta equipo1 y renómbrala con el nombre de tu equipo.
Ejemplo: reto1_aplicacion/LosInnovadores/
En tu carpeta encontrarás:
/docs/ → documentación técnica
/src/ → código fuente
/tests/ → pruebas

README.md → información básica del equipo
👉 Rellena tu README.md con:
Nombre del equipo
Miembros y roles
Reto elegido
Avances por cada logro


🔧 Procedimiento con Git
# Crear rama para cada logro
git checkout -b logro1-equipoX

# Guardar cambios
git add .
git commit -m "logro1 – requisitos definidos"

# Subir rama
git push origin logro1-equipoX

# Etiquetar logro
git tag logro1
git push origin --tags
