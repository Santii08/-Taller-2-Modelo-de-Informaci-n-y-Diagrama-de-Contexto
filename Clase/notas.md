# 🗒️ Registro de Trabajo en Clase - Taller 2jj ## 📆 Fecha de la sesión 19 de febrero de 2026 --- ## 👥 Integrantes presentes

- Daniel Santiago Ramírez Chinchilla  
- Juan Pablo Aponte Veloza
- Julian Andres Pedraza Padilla

---

## 🧠 Actividades realizadas en clase

Durante la sesión de clase, el equipo analizó el caso base de la Clínica Salud Viva con el objetivo de identificar las entidades principales del sistema y sus relaciones. Se discutió cómo se gestiona la información dentro de una clínica, especialmente en el proceso de agendamiento de citas médicas, la asignación de médicos y la generación de facturas.

Se identificaron las entidades principales del sistema: **Paciente, Médico, Cita, Especialidad y Factura**, ya que estas representan los elementos más importantes del dominio del problema. También se determinó que la entidad **Cita** funciona como el núcleo del sistema, porque conecta a los pacientes con los médicos y permite la generación de facturación.

Una de las decisiones de modelado más importantes fue crear una entidad intermedia llamada **Especialidad_Medico**, con el fin de resolver la relación muchos a muchos entre médicos y especialidades. Esto permite que un médico tenga varias especialidades y que una especialidad pueda estar asociada a varios médicos.

Además, se definieron las claves primarias para cada entidad y las claves foráneas necesarias para establecer las relaciones entre ellas. Por ejemplo, la entidad Cita contiene las claves foráneas del paciente y del médico, mientras que la entidad Factura contiene la clave foránea de la cita.

Para desarrollar el modelo, se utilizó la herramienta **draw.io**, ya que permite crear diagramas entidad-relación de forma clara y organizada.

Durante la clase, el equipo logró desarrollar el modelo entidad-relación inicial con sus entidades, atributos principales y relaciones.

---

## 🧩 Boceto inicial del modelo

El equipo desarrolló un primer modelo entidad-relación que incluye las siguientes entidades:

- Paciente
- Médico
- Cita
- Especialidad
- Factura
- Especialidad_Medico

La entidad **Cita** se definió como la entidad central, ya que conecta al paciente con el médico y permite generar una factura.

El modelo también incluye la entidad intermedia **Especialidad_Medico**, que permite representar la relación muchos a muchos entre médicos y especialidades.

<img width="614" height="608" alt="image" src="https://github.com/user-attachments/assets/901e7dcd-aed5-46cb-8283-cba234fc254c" />
 
<img width="948" height="670" alt="image" src="https://github.com/user-attachments/assets/bb4c0f28-2da9-4de2-a457-484f43322f49" />

---

## 🔁 Tareas definidas para complementar el taller

| Tarea asignada | Responsable | Fecha estimada |
|----------------|-------------|----------------|
| Modelado final en draw.io | Daniel Santiago Ramírez | 19/02/2026 |
| Redacción del informe | Juan Pablo Aponte Veloza | 20/02/2026 |
| Investigación y referencias | Julian Andres Pedraza Padilla | 20/02/2026 |
| Revisión final del modelo | Todo el equipo | 20/02/2026 |

---

Este documento resume el trabajo colaborativo realizado durante la sesión del Taller 2 en el curso Arquitectura Empresarial (AREM) - Universidad de La Sabana.