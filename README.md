# 🧩 Proyecto PGPI – Práctica 9  
### *Gestión colaborativa del proyecto con Git, GitHub y Jira*

Este repositorio contiene el desarrollo completo de la **Práctica 9** de la asignatura de *Proyecto y Gestión de Proyectos Informáticos (PGPI)*.  
El objetivo de esta práctica es simular un flujo de trabajo profesional utilizando:

- **Git y GitHub** para control de versiones  
- **Ramas paralelas** para trabajo individual  
- **Integración y resolución de conflictos**  
- **Gestión del proyecto mediante Jira (Kanban)**  
- **Versionado y publicación de una release (`v1.0.0`)**

El trabajo fue realizado de manera colaborativa por:  
- **Carlos Alberto Gutiérrez Rondón**  
- **Jorge Arley Castaño Rodríguez**

---

## 📁 Estructura del proyecto
pgpi-practica9/
│
├── src/
│ ├── ui_mock1.txt
│ ├── ui_mock2.txt
│ ├── panel_docente1.txt
│ ├── panel_docente2.txt
│ └── (archivos correspondientes a cada tarea)
│
├── README.md
└── Tag v1.0.0 – versión estable del proyecto


---

## 🚀 Flujo de trabajo implementado

### 1️⃣ Inicialización del repositorio  
Se creó el repositorio local, se añadió un `README.md` inicial y se hizo el primer commit.

### 2️⃣ Creación de ramas por tarea y por integrante  
Cada integrante trabajó en su propia rama:

- `tarea1-carlos`
- `tarea1-jorge`
- `tarea2-carlos`
- `tarea2-jorge`
- Rama integradora final: `tarea1-ui-accesible` y `tarea2-panel-docente`

### 3️⃣ Simulación de desarrollo paralelo  
Cada rama añadió archivos mock independientes simulando trabajo real del proyecto.

### 4️⃣ Resolución manual de conflictos  
Se forzaron conflictos al fusionar cambios de Carlos y Jorge en la misma sección de código para aprender a resolverlos correctamente.

Ejemplo de conflicto gestionado:

```text
<<<<<<< HEAD
Cambio 1 de Carlos en Tarea 1
=======
Cambio 1 de Jorge en Tarea 1
>>>>>>> tarea1-jorge


Tras resolverlos, se logró una versión consolidada de ambas tareas.

5️⃣ Fusión final en master

Una vez integradas todas las ramas funcionales, se realizó:

git merge tarea2-panel-docente


Obteniendo una versión estable y funcional del proyecto.

6️⃣ Creación de release v1.0.0

Se generó una etiqueta con la versión final de la práctica:

git tag -a v1.0.0 -m "Versión 1.0.0: Tarea 1 y Tarea 2 completadas"
git push origin v1.0.0

📌 Gestión del Proyecto con Jira (Kanban)

Se configuró un espacio Jira llamado TaTo_Matematicas donde se gestionaron todas las tareas mediante un tablero Kanban con estados:

To Do

In Progress

In Review

Done

Tareas gestionadas:

Clave	Título	Estado
KAN-1	Tarea 1	To Do
KAN-2	Tarea 2	In Progress
KAN-4	Mejorar accesibilidad de la interfaz UI	To Do
🧪 Resultados de la práctica

✔ Trabajo colaborativo realista entre dos desarrolladores
✔ Uso profesional de Git: ramas, merges, conflictos y release
✔ Repositorio limpio y estructurado
✔ Tablero Kanban funcional en Jira
✔ Proyecto presentado como simulación de entorno empresarial

👥 Autores

Carlos Alberto Gutiérrez Rondón

Data Engineer & Cybersecurity Specialist

Universidad de Granada (UGR)

GitHub: https://github.com/CarlosGutierrezR

Jorge Arley Castaño Rodríguez

Colaborador del proyecto

GitHub: https://github.com/jorgekast18

🏁 Estado del proyecto
✔ Versión estable: v1.0.0
📦 Práctica completada con éxito
