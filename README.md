[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/4R8RwCyR)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=23860630)
# Certamen: Git y GitHub Básico

## Instrucciones Generales

Este certamen evalúa el manejo básico de Git y GitHub. Debes completar **todas las tareas** en orden, realizando los commits indicados. El historial de commits es parte de la evaluación.

**Tiempo:** 80 minutos  
**Puntaje total:** 100 puntos

---

## Requisitos previos

Asegúrate de tener configurado Git con tu nombre y correo:

```bash
git config --local user.name "Tu Nombre"
git config --local user.email "tu.correo@ejemplo.com"
```

---

## Tareas

### Tarea 1 — Clonar el repositorio (10 pts)

Ya lo hiciste al aceptar la asignación en GitHub Classroom. ✓

Verifica que estás dentro del repositorio:

```bash
git status
```

Debes ver algo como: `On branch main, nothing to commit`.

---

### Tarea 2 — Crear tu archivo de presentación (20 pts)

Crea un archivo llamado `presentacion.md` con el siguiente contenido (reemplaza con tus datos reales):

```
# Mi Presentación

- **Nombre completo:** Tu Nombre Aquí
- **Número de Matricula:** 000000000
- **Carrera:** Tu Carrera
- **Fecha:** 08/05/2026
```

Luego agrega y confirma el archivo:

```bash
git add presentacion.md
git commit -m "feat: agrego mi archivo de presentacion"
```

---

### Tarea 3 — Modificar un archivo existente (20 pts)

Abre el archivo `tareas/mis_respuestas.txt` y responde las preguntas que están dentro.

Guarda los cambios, luego:

```bash
git add tareas/mis_respuestas.txt
git commit -m "feat: respondo las preguntas de git"
```

---

### Tarea 4 — Revisar el historial (10 pts)

Ejecuta el siguiente comando y guarda su salida (cópiala) en un archivo llamado `historial.txt`:

```bash
git log --oneline
```

```bash
git add historial.txt
git commit -m "feat: agrego historial de commits"
```

---

### Tarea 5 — Sincronizar con GitHub (20 pts)

Primero descarga los últimos cambios del repositorio remoto:

```bash
git pull origin main
```

Luego sube todos tus cambios a GitHub:

```bash
git push origin main
```

---

### Tarea 6 — Verificación final (20 pts)

Confirma que tus cambios están en GitHub visitando la URL de tu repositorio en el navegador. Debes ver todos los archivos que creaste.

Captura de pantalla del repositorio en GitHub (adjúntala en `evidencia/captura.png` si es posible, de lo contrario el profe revisará el repositorio directamente).

---

## Resumen de commits esperados

Al terminar, tu historial debe tener **al menos** estos commits (en cualquier orden):

| Commit | Descripción |
|--------|-------------|
| 1 | `feat: agrego mi archivo de presentacion` |
| 2 | `feat: respondo las preguntas de git` |
| 3 | `feat: agrego historial de commits` |

---

## Criterios de evaluación

| Criterio | Puntaje |
|----------|---------|
| Archivo `presentacion.md` con datos correctos | 20 pts |
| Respuestas en `tareas/mis_respuestas.txt` | 20 pts |
| Commits con mensajes descriptivos | 20 pts |
| Historial subido (`historial.txt`) | 10 pts |
| Push exitoso a GitHub | 20 pts |
| Repositorio visible en GitHub | 10 pts |
| **Total** | **100 pts** |

---

> **Nota:** El timestamp de los commits y el historial de GitHub son visibles para el profesor. Trabaja de forma individual y honesta.
