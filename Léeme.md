---
version: 2.0.0
---
---

Este Vault de ejemplo ha sido creado por [[Rafa Campos]], usando el principio KISS.

## Objetivo

Todos los componentes han sido creado para facilitar la gestión de trabajo en proyectos con entornos complicados y/o cambiantes. 

> No es una herramienta de gestión de equipos, solo de gestión de trabajo propio.

## Componentes

- Gestor de [[ℹ️ Inbox]], para notas desordenadas que se toman rápidamente, con la idea que sean procesadas al resto de componentes tarde o temprano
- Gestor de datos:
	- [[ℹ️ Personas]]: Documenta relaciones laborales y compañeros
	- [[ℹ️ Reuniones]]: Facilita la toma de notas y organización de reuniones
	- [[ℹ️ Diario]]: Facilita el control de trabajo diario y los progresos conseguidos
- Gestor de trabajo:
	- [[ℹ️ Tareas]]: Documenta el trabajo en unidades mínimas llamadas tareas. Las tareas tienen estados globales, que se indican su nivel de progreso.
- Control de desarrollos
	- [[ℹ️ Proyectos]]: Control de trabajo en desarrollos con principio y fin
	- [[ℹ️ Áreas]]: Control de trabajo en desarrollos permanente
	- Cada proyecto y área tiene una base de datos propia para documentar las tareas, equipo y reuniones, de forma que se centralice la información sin repetir los contenidos

## Cómo usar

1. Da de alta tus proyectos y áreas siguiente los pasos indicados en [[ℹ️ Proyectos]] y [[ℹ️ Áreas]]. 
2. Completa tu base de datos de personas en [[ℹ️ Personas]]
3. Cada día, genera una nota diaria usando la funcionalidad de Obsidian y aplica la plantilla de nota diaria
	1. Ve a Ajustes > Plantillas
	2. Coloca la ruta de la carpeta `999 - Plantillas` como directorio de plantillas
		1. Cuando crees Reuniones o Personas, usa las plantillas apropiadas en usando el botón del menú lateral "Insertar plantilla" con el icono📄
		2. Modifica con el tiempo estas plantillas para adaptarlas a tu caso
	3. Ve a Ajustes > Notas diarias
		1. Configura la ubicación del nuevo archivo en `050 - Diario / Items`
		2. Configura la ubicación de la plantilla base como `999 - Nota diaria`
4. Añade propiedades personalizadas para tu contexto de trabajo
5. Contacta con [[Rafa Campos]] para solicitar o compartir posibles mejoras