# Hackathon-iActiva-2025

🚀 Bienvenida
Bienvenido/a al repositorio oficial del Hackathon iActiva 2025 organizado por Digitaliza Madrid.
Aquí encontrarás la estructura base de carpetas, las instrucciones de trabajo y los espacios donde cada equipo debe subir sus entregables.
📅 Información básica
Fecha: 1 de julio de 2025
Horario: 09:00 – 17:00
Lugar: Centro de Innovación Digitaliza Madrid (C/ Embajadores 181)
🎯 Retos del Hackathon
Reto 1: Aplicación de Ayudas Públicas con IA Generativa
Reto 2: Seguridad en un Asistente Conversacional con IA
👉 Los detalles completos de cada reto están en la Guía del Participante.
🗂️ Estructura del repositorio
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
Rellena tu README.md con:
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
✅ Buenas prácticas
Documenta cada logro en /docs/logroX/.
Usa nombres claros en commits y archivos.
Comenta el código generado con IA (# Generado con ayuda de Copilot).
Mantén modularidad en el código.
Añade evidencias de pruebas (logs, capturas, reportes).
⚠️ Nota: Todos los entregables deben estar en la carpeta del equipo y subidos al repositorio antes de la hora límite indicada en la agenda.
