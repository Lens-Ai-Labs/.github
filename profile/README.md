# ?? Lens AI Labs — LungPath AI

Research prototype for AI-powered digital pathology and microscopy object detection using **YOLOv8**, **FastAPI**, and a static **Web Workspace**.

## ??? Organization Architecture

| Repository | Role | Deployment Target |
| :--- | :--- | :--- |
| [**lungpath-frontend**](https://github.com/Lens-Ai-Labs/lungpath-frontend) | Static Web UI & Bounding-Box Visualizer | **Vercel** |
| [**lungpath-backend**](https://github.com/Lens-Ai-Labs/lungpath-backend) | FastAPI Inference Server, SQLAlchemy DB & YOLOv8 Container | **Railway** |
| [**lungpath-ml-training**](https://github.com/Lens-Ai-Labs/lungpath-ml-training) | Roboflow YOLOv8 Training & Evaluation Notebook | **Google Colab** |

> ?? **Research Disclaimer:** LungPath AI is an educational research prototype and must not be used for clinical diagnosis.
