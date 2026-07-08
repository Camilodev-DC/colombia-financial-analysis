# Colombia Financial Analysis

Análisis financiero de datos económicos de Colombia, con foco en la tasa de cambio del peso colombiano (COP).

## Estructura del proyecto

```
colombia-financial-analysis/
├── Data/
│   ├── raw/          # Datos originales sin procesar (no versionados)
│   └── processed/    # Datos limpios y transformados (no versionados)
├── notebooks/        # Jupyter notebooks de análisis exploratorio
├── scrips/           # Scripts de procesamiento y análisis
├── requirements.txt  # Dependencias de Python
└── README.md
```

> **Nota:** La carpeta `Data/` está excluida del control de versiones (ver `.gitignore`). Los datos se mantienen localmente.

## Instalación

```bash
python -m venv .venv
source .venv/bin/activate   # En Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

## Uso

1. Coloca los datos originales en `Data/raw/`.
2. Ejecuta los notebooks en `notebooks/` o los scripts en `scrips/`.
3. Los resultados procesados se guardan en `Data/processed/`.
