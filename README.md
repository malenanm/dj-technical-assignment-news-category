# dj-technical-assignment-news-category

# News Category Semantic Search with Generative AI

## Overview

Este proyecto tiene como objetivo desarrollar un sistema de **búsqueda semántica** utilizando **Generative AI (GPT-4o)**, implementando un pipeline que incluye:

- **Búsqueda semántica**: Utilización de embeddings para la búsqueda de artículos de noticias.
- **Generative AI**: Integración de GPT-4 para tareas como generación de resúmenes o respuestas a preguntas.
- **Expansión escalable**: El sistema está diseñado para ser ampliado a tareas como clasificación, recomendaciones, modelización de temas, etc.

## Problem Definition

El propósito de este proyecto es abordar la dificultad de **búsqueda de información semántica en grandes volúmenes de noticias**. Usando el **News Category Dataset**, implementaremos un sistema de búsqueda eficiente y escalable que también pueda generar respuestas o resúmenes de acuerdo con la relevancia semántica.

## Dataset

**News Category Dataset** de Kaggle: Un conjunto de datos que contiene artículos de noticias categorizados en diferentes temas. Es adecuado para tareas de **búsqueda semántica** y **clasificación**.

- [Descarga del dataset](https://www.kaggle.com/datasets/rmisra/news-category-dataset)

## Approach

### 1. **Dataset Sourcing**:
   - Se utiliza el **News Category Dataset** para entrenar el modelo de búsqueda semántica.

### 2. **Modeling**:
   - Usaremos embeddings para búsqueda.
   - Utilizaremos GPT-4o para tareas de generación como resúmenes y respuestas.

### 3. **Evaluation**:
   - El modelo será evaluado en términos de precisión y efectividad en la generación de respuestas y resúmenes.

## Installation

Para ejecutar este proyecto, necesitas tener las siguientes dependencias instaladas:

## Requirements

Para instalar las dependencias, ejecuta:

```bash
pip install -r requirements.txt
