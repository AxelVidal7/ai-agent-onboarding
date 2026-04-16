# ai-agent-onboarding

Material de formación progresiva para nuevos integrantes del equipo del PID LLMs, orientado al desarrollo de un agente conversacional con RAG (Retrieval-Augmented Generation).

---

## Contexto

El proyecto consiste en un agente conversacional personalizado con RAG multi-base de conocimiento, gestión de usuarios, conversaciones e hilos, y streaming de respuestas. Este repositorio contiene el material de onboarding estructurado para que los nuevos integrantes puedan alcanzar el nivel operativo del equipo de forma progresiva y autónoma.

El stack principal del proyecto incluye Python, LangChain, LangGraph, vLLM, ChromaDB/Qdrant, FastAPI y Docker.

---

## Estructura del repositorio

```
ai-agent-onboarding/
├── etapa1_python_solido/
│   ├── etapa1_documento.docx       # Teoría y conceptos
│   └── etapa1_practica.ipynb       # Ejercicios prácticos
│
├── etapa2_fundamentos_llm/
│   ├── etapa2_documento.docx
│   └── etapa2_practica.ipynb
│
├── etapa3_langchain_rag/
│   ├── etapa3_documento.docx
│   └── etapa3_practica.ipynb
│
├── etapa4_stack_proyecto/
│   ├── etapa4_documento.docx
│   └── etapa4_practica.ipynb
│
└── etapa5_integracion_avanzada/
    ├── etapa5_documento.docx
    └── etapa5_practica.ipynb
```

Cada carpeta contiene:
- **`.docx`** — documento explicativo con el *por qué* y el *qué* de cada concepto, y criterios de aprobación de la etapa.
- **`.ipynb`** — notebook de práctica con celdas ejecutables, explicaciones inline y ejercicios marcados con **→ Tu turno** para completar.

---

## Roadmap de aprendizaje

| Etapa | Tema | Contenido principal |
|-------|------|-------------------|---------------------|
| 1 | Python Sólido | OOP, type hints, async/await, manejo de errores, entornos virtuales |
| 2 | Fundamentos LLM | Modelos de lenguaje, tokens, embeddings, búsqueda vectorial, ChromaDB/Qdrant |
| 3 | LangChain y RAG | Chains, retrievers, memoria, RAG básico, prompt engineering |
| 4 | Stack del proyecto | FastAPI, vLLM, Docker, gestión de usuarios, streaming |
| 5 | Integración avanzada | RAG multi-KB, gestión de conversaciones, hilos, intro a LangGraph |



---

## Cómo usar este material

### Orden recomendado

1. Leé el documento `.docx` de la etapa completo antes de abrir el notebook.
2. Abrí el `.ipynb` y ejecutá cada celda en orden con `Shift + Enter`.
3. Completá los ejercicios **→ Tu turno** antes de continuar a la siguiente celda.
4. Si una celda falla, entendé el error antes de avanzar.
5. Al completar el checklist de cierre de cada etapa, estarás listo para pasar a la siguiente etapa.

### Requisitos previos

- Python 3.10 o superior instalado.
- Jupyter Notebook o JupyterLab (`pip install jupyterlab`).
- Git configurado localmente.

### Setup inicial

```bash
# Clonar el repositorio
git clone https://github.com/AxelVidal7/ai-agent-onboarding.git
cd ai-agent-onboarding

# Crear y activar entorno virtual
python -m venv .venv
source .venv/bin/activate       # Linux / macOS
# .venv\Scripts\activate        # Windows

# Instalar dependencias de las etapas iniciales
pip install jupyterlab notebook

# Abrir Jupyter
jupyter lab
```

---

## Criterios de aprobación por etapa

Cada etapa tiene un checklist de cierre en el notebook. El criterio no es temporal sino de comprensión: no se avanza a la siguiente etapa hasta poder cumplir todos los ítems del checklist sin ayuda.

---

## Progresión del entorno

- **Etapas 1 a 3:** entorno local aislado, sin conexión al stack del proyecto.
- **Etapa 4:** primera conexión al entorno real (vLLM, FastAPI).
- **Etapa 5:** trabajo directamente sobre componentes del proyecto.

---

## Estado del material

| Etapa | Documento | Notebook |
|-------|-----------|----------|
| 1 — Python Sólido | ✅ Disponible | ✅ Disponible |
| 2 — Fundamentos LLM | 🔄 En desarrollo | 🔄 En desarrollo |
| 3 — LangChain y RAG | ⏳ Pendiente | ⏳ Pendiente |
| 4 — Stack del proyecto | ⏳ Pendiente | ⏳ Pendiente |
| 5 — Integración avanzada | ⏳ Pendiente | ⏳ Pendiente |

---

## Contribuciones

Este repositorio es mantenido por el equipo de LLMs. Si encontrás un error en el material, abrí un Issue con el número de etapa y una descripción del problema.
