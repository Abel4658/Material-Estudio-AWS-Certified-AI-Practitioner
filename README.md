# 🚀 Guía Completa de Preparación: AWS Certified AI Practitioner (AIF-C01)

Este repositorio contiene un ecosistema completo de estudio diseñado para dominar los 5 dominios del examen **AWS Certified AI Practitioner**. El material combina resúmenes técnicos profundos, guías de arquitectura avanzada y un banco de **750 preguntas de práctica** tipo examen.

---

## 📑 Contenido del Repositorio

El material está organizado siguiendo el esquema oficial de AWS (CLF-C02 / AIF-C01):

### 📁 01 - Fundamentos de IA y Machine Learning
* **Teoría:** Conceptos de ML/DL, tipos de aprendizaje (supervisado, no supervisado, refuerzo), e infraestructura básica de datos (S3, Glue).
* **Avanzado:** Arquitectura interna de **Transformers** (Autoatención, Codificación Posicional) y niveles de madurez de **MLOps**.
* **Práctica:** 150 preguntas de fundamentos.

### 📁 02 - Fundamentos de IA Generativa
* **Teoría:** Modelos Fundamentales (FM), LLMs, y Modelos de Difusión (Stable Diffusion).
* **Arquitectura:** Diferencia entre redes antagónicas (GANs), VAEs y la lógica del espacio latente.
* **Práctica:** 150 preguntas sobre GenAI.

### 📁 03 - Aplicaciones de Modelos Fundacionales
* **Teoría:** Ingeniería de Peticiones (Prompt Engineering), RAG (Generación Aumentada por Recuperación) y Agentes.
* **Técnico:** Parámetros de inferencia (Top-P, Top-K, Temperatura) y bases de datos vectoriales (OpenSearch, pgvector).
* **Práctica:** 150 preguntas de aplicaciones técnicas.

### 📁 04 - IA Responsable
* **Teoría:** Ética, mitigación de sesgos (Bias), transparencia y explicabilidad.
* **Herramientas:** SageMaker Clarify, Amazon A2I y RLHF (Aprendizaje por refuerzo con feedback humano).
* **Práctica:** 150 preguntas sobre marcos éticos y AWS AI Service Cards.

### 📁 05 - Seguridad, Conformidad y Gobernanza
* **Teoría:** Modelo de Responsabilidad Compartida, IAM, cifrado (KMS) y cumplimiento global (EU AI Act, NIST).
* **Avanzado:** Ataques específicos (Inyección de prompts, Envenenamiento de datos) y gobernanza con SageMaker Model Cards.
* **Práctica:** 150 preguntas de seguridad y cumplimiento.

---

## 🛠️ Cómo usar este material

1. **Estudio por Dominios:** Cada carpeta contiene un archivo `.tex` con el resumen detallado del dominio. Puedes compilarlo en [Overleaf](https://www.overleaf.com/) o cualquier editor LaTeX para obtener un PDF limpio.
2. **Refuerzo Estratégico:** Revisa la **Guía de Escenarios de Decisión** para entender cuándo elegir Bedrock vs SageMaker y cómo funcionan los modelos de precios.
3. **Simulacro Intensivo:** Al final de cada dominio, realiza el cuestionario de 150 preguntas. Se recomienda una puntuación mínima del **80%** antes de pasar al siguiente tema.

---

## 🎯 Puntos Clave para el Examen

* **Amazon Bedrock:** Enfoque en rapidez, APIs y serverless.
* **Amazon SageMaker:** Enfoque en control total, entrenamiento personalizado y MLOps.
* **RAG vs Fine-tuning:** RAG para datos dinámicos; Fine-tuning para estilo y dominio específico.
* **Seguridad:** Los datos del cliente **nunca** se usan para entrenar los modelos base de AWS.

---

## ✒️ Formato de los Archivos
Todos los documentos técnicos están escritos en **LaTeX**, lo que permite:
* Representaciones matemáticas precisas.
* Estructura de tablas comparativas profesional.
* Exportación a PDF de alta calidad para impresión o lectura en dispositivos móviles.

---

## ⚖️ Licencia
Este material ha sido generado con fines educativos basados en la documentación oficial de AWS y guías de estudio expertas. 

_¡Mucha suerte en tu certificación!_ ☁️🤖
