
# Clasificación binaria de imágenes con una CNN en PyTorch

Este proyecto demuestra, de forma breve y didáctica, cómo entrenar una **Red Neuronal Convolucional (CNN)** para la **clasificación binaria** de imágenes usando **PyTorch**. Incluye:
- Un `Dataset` personalizado que carga imágenes desde dos carpetas (clase 0 y clase 1).
- Un modelo CNN básico con dos capas convolucionales.
- División del dataset en **train/valid/test** (80/10/10).
- Cálculo de **accuracy** por conjunto y gráfico de evolución por épocas.
- Barra de progreso con `tqdm`.

> **Nota**: Este código se creó con fines demostrativos para ilustrar el flujo general de entrenamiento con CNNs.
