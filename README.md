# README.md

# 📑 App Registro Jurídico (España/UE)

Aplicación en **Streamlit** para juristas sobre **B2 Registro: prioridad, publicidad, oponibilidad, tracto**.  
Permite capturar hechos de caso, evaluar reglas desde YAML, generar dictamen descargable en Markdown y calcular su hash SHA-256 como evidencia de integridad.

---

## 🚀 Pasos para desplegar en la web

1. **Crear repositorio en GitHub**
   - Ve a [GitHub](https://github.com) y crea un repo nuevo, por ejemplo: `registro-app`.
   - Sube los archivos indicados en este proyecto con la misma estructura de carpetas.

2. **Estructura mínima de archivos**
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
├── data/
│ ├── rules.yml
│ └── templates/
│ └── dictamen.md
└── .streamlit/
└── config.toml
