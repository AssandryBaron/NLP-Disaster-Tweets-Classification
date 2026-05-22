# NLP Disaster Tweets Classification

**Autor:** Assandry Barón Rodríguez  
**Curso:** Fundamentos de Deep Learning  
**Universidad:** Universidad de Antioquia — 2026  

## Video de presentación
[Ver video en YouTube](https://youtu.be/TU-LINK-AQUI)

## Descripción
Clasificación binaria de tweets para detectar desastres reales
usando Bidirectional LSTM. Dataset de Kaggle:
[NLP Getting Started](https://www.kaggle.com/competitions/nlp-getting-started)

## Cómo reproducir
1. Descargar train.csv, test.csv y sample_submission.csv desde Kaggle
2. Subir los CSV a Google Drive en: `Mi unidad/NLP_Disaster_Tweets/data/`
3. Ejecutar los notebooks en Google Colab con GPU activada, en orden: 01 → 02 → 03

## Estructura
| Archivo | Descripción |
|---|---|
| `01 - exploración de datos.ipynb` | EDA del corpus |
| `02 - preprocesado.ipynb` | Limpieza y tokenización |
| `03 - arquitectura de linea de base.ipynb` | Modelo BiLSTM + resultados |
| `INFORME_PROYECTO.PDF` | Informe ejecutivo |
| `ENTREGA1.PDF` | Primera entrega del proyecto |

## Resultados
- F1-Score en validación: ~0.79
- Arquitectura: Embedding(128) → BiLSTM(64) → Dropout(0.4) → Dense(1)
