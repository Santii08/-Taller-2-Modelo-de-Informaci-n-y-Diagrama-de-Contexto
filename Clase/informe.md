#  Informe Técnico del Taller

##  Nombre del Taller

Taller 2 - Modelado de Arquitectura Empresarial para la Gestión de Información en la Clínica Salud Viva

##  Integrantes del equipo

* Daniel Santiago Ramírez Chinchilla (danielsramirez@unisabana.edu.co | Santii08)
* Juan Pablo Aponte Veloza (juanapve@unisabana.edu.co)
* Julian Andres Pedraza Padilla (julianpepa@unisabana.edu.co)

---

##  Descripción general del trabajo

El objetivo de este taller fue modelar la estructura de información de la Clínica Salud Viva desde el enfoque de Arquitectura Empresarial, identificando las entidades principales que intervienen en la gestión de servicios médicos, citas, pacientes y facturación.

La Clínica Salud Viva maneja múltiples flujos de información relacionados con la atención médica, incluyendo el registro de pacientes, la programación de citas, la gestión de médicos y la generación de facturas. Debido a esto, es fundamental contar con un modelo de información bien estructurado que permita organizar los datos y facilitar la interoperabilidad entre sistemas como el ERP clínico, la base de datos central y los sistemas de aseguradoras.

Durante el desarrollo del taller, se identificaron las entidades principales del dominio clínico y sus relaciones, permitiendo representar cómo fluye la información dentro del sistema. Este tipo de modelado es fundamental en sistemas reales del sector salud, ya que permite garantizar la integridad, disponibilidad y trazabilidad de la información clínica y administrativa.


---

##  Proceso de desarrollo

Para el desarrollo del modelo, el equipo utilizó principios de Arquitectura Empresarial enfocados en el modelado de información, identificando primero las entidades principales del sistema basadas en el contexto de la clínica.

Inicialmente, se analizaron los procesos principales de la clínica, como el agendamiento de citas, la atención médica y la facturación. A partir de este análisis, se identificaron las entidades clave: Paciente, Cita, Médico, Especialidad y Factura.

Posteriormente, se utilizó la herramienta Draw.io para construir el diagrama de entidades, representando las relaciones entre ellas. Se estableció, por ejemplo, que un paciente puede tener múltiples citas, que cada cita está asociada a un médico y a una especialidad, y que cada cita puede generar una factura.

Finalmente, el modelo fue revisado y ajustado para asegurar que representara correctamente el flujo de información dentro del sistema. Este proceso es similar al utilizado en el diseño de bases de datos clínicas reales, donde el modelo de información es la base para el desarrollo de los sistemas.

---

## 🧩 Análisis del modelo propuesto

El modelo propuesto está estructurado como un modelo de entidades de información, el cual representa los datos principales que utiliza el sistema clínico.

Las entidades identificadas fueron:

- Paciente
- Cita
- Médico
- Especialidad
- Factura

Estas entidades permiten representar la información fundamental del sistema y las relaciones entre ellas. Por ejemplo, un paciente puede tener múltiples citas, lo que refleja el funcionamiento real de una clínica, donde un paciente puede recibir atención médica en diferentes momentos.

Este modelo representa las necesidades de la clínica, ya que permite organizar la información médica, administrativa y financiera. Además, facilita la integración con otros sistemas como aseguradoras y sistemas ERP, lo cual es un requisito fundamental en el sector salud.

Se tomaron los siguientes supuestos:

- Cada paciente tiene un identificador único.
- Cada cita está asociada a un paciente, un médico y una especialidad.
- Cada factura está asociada a una cita.
- La información se almacena en una base de datos central.

Desde el punto de vista teórico, este modelo sigue los principios del modelado entidad-relación, el cual es ampliamente utilizado en el diseño de sistemas de información. Este enfoque permite garantizar la integridad de los datos y facilita el desarrollo de sistemas escalables y mantenibles.

En sistemas reales como SAP Healthcare o sistemas HIS, este tipo de modelado es esencial para asegurar la correcta gestión de la información clínica.

---

## 📈 Diagrama final entregado

Enlace al modelo:  
<img width="614" height="608" alt="image" src="https://github.com/user-attachments/assets/5058d102-3168-4167-be6d-961b0f9291c0" />
<img width="948" height="670" alt="image" src="https://github.com/user-attachments/assets/0ccb45ae-01d4-4d59-a8b9-4bef89991a0b" />


El diagrama incluye las siguientes entidades:

- Paciente
- Cita
- Médico
- Especialidad
- Factura

También muestra las relaciones entre ellas, como:

- Un paciente puede tener muchas citas.
- Un médico puede atender muchas citas.
- Una especialidad puede estar asociada a muchos médicos.
- Una cita genera una factura.

Este tipo de modelo es utilizado en sistemas reales de gestión hospitalaria, donde las entidades representan los elementos fundamentales del sistema.

---

## 📋 Tabla de entidades

| Nombre de la entidad | Tipo | Descripción | Responsable |
|----------------------|------|-------------|-------------|
| Paciente | Entidad | Representa a la persona que recibe servicios médicos | Clínica |
| Cita | Entidad | Representa una atención médica programada | Sistema |
| Médico | Entidad | Representa al profesional que atiende al paciente | Clínica |
| Especialidad | Entidad | Representa el área médica del servicio | Clínica |
| Factura | Entidad | Representa el registro de cobro por el servicio | Sistema |

---

## 🔍 Investigación complementaria

### Tema investigado:

Modelado de datos y Arquitectura Empresarial en sistemas de salud

### Resumen:

El modelado de datos es una parte fundamental de la Arquitectura Empresarial, ya que permite representar la estructura de la información dentro de una organización. Uno de los modelos más utilizados es el modelo entidad-relación, el cual permite identificar las entidades principales y sus relaciones.

En el sector salud, este tipo de modelado es especialmente importante debido a la gran cantidad de información que se maneja, como datos de pacientes, citas, médicos y facturación. Sistemas como los Electronic Health Records (EHR) utilizan modelos de entidades para organizar la información clínica y permitir su acceso seguro y eficiente.

Además, frameworks como TOGAF establecen que la arquitectura de datos es uno de los pilares fundamentales de la arquitectura empresarial, junto con la arquitectura de negocio, aplicación y tecnología. Esto permite asegurar que los sistemas estén alineados con los objetivos de la organización.

En el contexto del taller, el modelado de entidades permitió representar la estructura de información de la clínica, facilitando la comprensión del sistema y su funcionamiento.

---

## 📚 Referencias

* [1] The Open Group. TOGAF Standard, Version 10. 2022. https://www.opengroup.org/togaf
* [2] Object Management Group. Entity Relationship Modeling. https://www.omg.org
* [3] Sommerville, Ian. Software Engineering. 10th Edition. Pearson, 2015.
* [4] HealthIT.gov. Electronic Health Records Overview. https://www.healthit.gov

---

*Este documento hace parte de la entrega del taller 2 del curso AREM (Arquitectura Empresarial) - Universidad de La Sabana.*
