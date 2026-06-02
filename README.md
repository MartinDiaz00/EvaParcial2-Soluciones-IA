# Trabajo Soluciones IA

## Descripción

Este proyecto fue desarrollado para la Evaluación Parcial 2 de la asignatura Ingeniería de Soluciones con IA.

La solución corresponde a una continuación del proyecto HealthTech RAG realizado en la primera evaluación. En esta etapa se incorporó un agente capaz de consultar información desde documentos internos, mantener contexto mediante memoria conversacional y generar respuestas considerando la información recuperada.

Además, el sistema incluye una planificación básica que permite definir los pasos utilizados para responder a cada consulta realizada por el usuario.

## Integrantes

* Martin Andrés Díaz González
* Mosiah Kolob Patricio Estrada Meneses

## Funcionalidades

* Consulta de información desde documentos internos.
* Memoria conversacional durante la ejecución.
* Generación de respuestas utilizando contexto recuperado.
* Planificación básica para la resolución de consultas.
* Evidencias y pruebas de funcionamiento.

## Estructura del Proyecto

```text
Trabajo_SolucionesIA
│
├── app
├── data
├── diagrams
├── evidencias
├── tests
├── main.py
├── requirements.txt
└── README.md
```

## Instalación

Crear entorno virtual:

```bash
python -m venv venv
```

Activar entorno virtual:

```bash
venv\Scripts\activate
```

Instalar dependencias:

```bash
pip install -r requirements.txt
```

## Ejecución

```bash
python main.py
```

## Ejemplos de uso

Consulta de información:

```text
¿Qué hace el sistema HealthTech RAG?
```

Uso de memoria:

```text
Recuerda que la prioridad es el soporte de pacientes.
```

```text
¿Qué recuerdas de la conversación?
```

Planificación:

```text
Analiza el sistema y crea un plan de mejora.
```

## Conclusión

La solución desarrollada demuestra el uso de recuperación de información, memoria conversacional y planificación básica dentro de un agente inteligente orientado al contexto organizacional de HealthTech.
