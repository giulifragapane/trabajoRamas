# 🌐 Trabajo Práctico - Git y GitHub

## 📚 Tecnicatura Universitaria en Programación

---

## 👥 Integrantes
- Pablo Barrios
- Emiliano García
- Giuliana Fragapane

---

## 📝 Descripción del Proyecto

Este proyecto consiste en el desarrollo de una aplicación web en **HTML puro**, cuyo objetivo principal es practicar:

- ✔ Uso de versiones con **Git**
- ✔ Trabajo colaborativo con **ramas**
- ✔ Resolución de **conflictos**
- ✔ Automatización con **GitHub Actions**

⚠️ El foco NO está en el diseño, sino en el uso correcto de herramientas de control de versiones.

---

## 🧱 Estructura del Proyecto

trabajoRamas/
│
├── .github/
│ └── workflows/
│ └── validar-html.yml → Workflow de validación
│
├── index.html → 🏠 Página de inicio
├── contacto.html → 📩 Página de contacto
├── about.html → ℹ️ Información del grupo
└── README.md

---

## 🌿 Ramas del Proyecto

- main → Rama principal
- feature/giuliana
- feature/pablo
- feature/emiliano

Cada integrante trabajó en su propia rama y luego integró sus cambios mediante merge.

---

## 📸 Evidencias

El repositorio incluye capturas de:

- ✔ Conflicto de merge
- ✔ Resolución del conflicto
- ✔ Ejecución del workflow (éxito y error)
- ✔ Creación de tags

---

## ⚔️ Conflicto de Merge

Se generó un conflicto de forma intencional modificando las **mismas líneas de un archivo HTML** desde distintas ramas.

### 🔴 Proceso:
1. Dos ramas modificaron el mismo archivo (`index.html`)
2. Se intentó hacer merge a `main`
3. Git detectó conflicto

### 🟡 Resolución:
- Se editaron manualmente las diferencias (mantuvimos ambos cambios)
- Se eliminaron los marcadores de conflicto
- Se realizó commit de resolución

📸 Se incluyen capturas del conflicto y su resolución.
- Captura 1 - Intento de merge a main
![Captura 1 - Intento de merge a main](imagenes/conflictomerge.jpeg)
- Captura 2 - Se modificaron las mismas líneas
![Captura 2 - Se modificaron las mismas líneas](imagenes/conflicto.jpeg)
- Captura 3 - Se mantuvieron ambos cambios
![Captura 3 - Se mantuvieron ambos cambios](imagenes/solucion.jpeg)
- Captura 4 - Merge final sin errores
![Captura 4 - Merge final sin errores](imagenes/mergevalido.jpeg)

---

## 🤖 GitHub Actions (Validación Automática)

---

## 🏷️ Versionado con Tags

Se utilizaron tags para marcar versiones del proyecto:
- `v1.0.0` → Primera versión funcional
![`v1.0.0` → Primera versión funcional](imagenes/tagv1.0.0.jpeg)
- `v1.1.0` → Versión final

📌 Permite acceder a distintas versiones del proyecto en GitHub.

---

## 📌 Lo aprendido

Este trabajo permitió comprender el flujo de trabajo real en equipo utilizando Git, incluyendo manejo de ramas, resolución de conflictos y automatización de validaciones.