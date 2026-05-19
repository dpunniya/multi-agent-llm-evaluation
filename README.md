# 🤖 Multi-Agent LLM Evaluation System

A multi-agent orchestration system built with Semantic Kernel that evaluates LLM performance across three reasoning benchmarks using autonomous execution, verification, and recovery agents.

## 🏗️ Architecture
The system uses a 4-agent pipeline:
- **Execution Agent** — sends problems to the LLM and collects responses
- **Verification Agent** — validates answers against expected outputs
- **Classifier Agent** — categorizes failure types
- **Recovery Agent** — retries failed cases with improved prompts

## 📊 Benchmarks Evaluated
| Benchmark | Type | Size |
|-----------|------|------|
| GSM8K | Math reasoning | 1,319 problems |
| ARC-Challenge | Science reasoning | 1,172 problems |
| BoolQ | Reading comprehension | 3,270 problems |

## 📁 Project Structure
├── gsm8k.ipynb      # GSM8K benchmark evaluation
├── arc.ipynb        # ARC-Challenge evaluation
├── boolq.ipynb      # BoolQ evaluation
├── analysis.ipynb   # Results analysis and visualization
├── analysis/        # CSV results data
└── plots/           # Performance visualizations
## 🛠️ Tech Stack
- **Python** — core implementation
- **Semantic Kernel** — multi-agent orchestration
- **OpenRouter API** — LLM access
- **Jupyter Notebooks** — experimentation
- **Pandas + Matplotlib** — analysis and visualization

## 👩‍💻 Author
**Dharani Punniyamoorthi**
- LinkedIn: [linkedin.com/in/dharanipunniyamoorthi](https://linkedin.com/in/dharanipunniyamoorthi)
- Email: dharanimoorthi2002@gmail.com
