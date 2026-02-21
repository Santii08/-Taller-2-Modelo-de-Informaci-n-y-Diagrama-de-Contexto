# Modelo de Información y Diagrama de Contexto - Clínica Salud Viva  

Este repositorio contiene el desarrollo del **Taller 2: Modelo de Información y Diagrama de Contexto** del curso de Arquitectura Empresarial.

---

## Descripción del Proyecto  

Modelado del dominio de información para la **Clínica Salud Viva**, incluyendo:

- Modelo Entidad–Relación (ERD)
- Diagrama de Contexto de Negocio

El objetivo es estructurar correctamente las entidades principales del sistema y representar los flujos de información entre actores y sistemas que intervienen en la operación clínica y administrativa.

---

## Objetivos  

- Modelar entidades del dominio utilizando diagramas ER  
- Definir relaciones y cardinalidades correctamente  
- Identificar actores y sistemas involucrados en el negocio  
- Representar flujos de información mediante un diagrama de contexto  
- Aplicar buenas prácticas de modelado de información  
- Documentar las decisiones de diseño de manera clara  

---

## Contexto del Caso Base  

La **Clínica Salud Viva** ofrece servicios médicos presenciales y virtuales.  

El sistema permite:

- A los pacientes agendar citas  
- A los médicos gestionar su agenda  
- Al personal administrativo validar información con aseguradoras  

La clínica opera con múltiples sistemas que deben interoperar, incluyendo:

- ERP clínico  
- Sistema de agendamiento  
- Base de datos central de pacientes  
- Sistemas externos de aseguradoras  
- Sistema de notificaciones  

Durante la clase se modelaron las siguientes entidades principales:

- Paciente  
- Cita  
- Médico  
- Especialidad  
- Factura  

Relaciones clave:

- Un paciente puede tener muchas citas.  
- Cada cita se asocia a un médico.  
- Cada cita corresponde a una especialidad.  
- Cada cita puede generar una factura.


---

## Documentación  

La documentación completa del proyecto se encuentra en la Wiki del repositorio, organizada en las siguientes páginas:

- **Home** – Introducción y contexto del taller  
- **Caso Base: Clínica Salud Viva** – Descripción del dominio modelado en clase  
- **Modelo ER** – Explicación técnica del modelo entidad-relación  
- **Diagrama de Contexto** – Descripción de actores, sistemas y flujos de información  
- **Aplicación al Cliente Real** – Adaptación del modelo al dominio asignado  
- **Investigación Complementaria** – Marco teórico y ejemplos de la industria  

---

## Entregables  

- Modelo ER final (`modelo-final-er.drawio`)  
- Informe técnico (`informe.md`)  
- Documento de investigación y referencias (`referencias.md`)  

---

## 👥 Equipo  

- Juan Pablo Aponte Veloza  
- Daniel Santiago Ramirez Chinchilla  
- Julian Andres Pedraza Padilla  

---

## Aclaración  

En este repositorio se encuentra el desarrollo del caso base trabajado en clase y la estructura preparada para la aplicación al cliente real.  

Actualmente, al ser uno de los equipos asignados a trabajar con la universidad, aún no contamos con la empresa definida. Por esta razón, la parte correspondiente al cliente real será completada cuando se asigne formalmente el dominio específico.  

---

##  Herramientas Utilizadas  

- Draw.io / diagrams.net – Modelado de diagramas ER y de contexto  
- GitHub – Control de versiones y documentación  
- Modelo Entidad-Relación (ERD) – Modelado de información  


---

## Fecha de Entrega  

FEBRERO 20 DE 2026  

---

**Institución:** Universidad de La Sabana  
**Curso:** Arquitectura Empresarial  
**Profesor:** Cesar Augusto Vega Fernandez  

---

## Estructura del Repositorio  
