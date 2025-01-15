# Detector de Sorrisos

Este é um simples projeto de detecção de rostos e sorrisos usando OpenCV. O código utiliza dois classificadores em cascata Haar para detectar faces e sorrisos em tempo real usando a câmera do dispositivo.

## Funcionalidades

- Detecta faces e sorrisos em tempo real.
- Conta o número de pessoas sorrindo no frame.
- Exibe a contagem de pessoas sorrindo na tela.
- Marca a área de cada rosto e sorriso detectado com retângulos coloridos.
- Considera que o sorriso de uma pessoa dura até um máximo de 5 segundos.

## Dependências

- Python 3.x
- OpenCV

Instale o OpenCV com o seguinte comando:

```bash
pip install opencv-python
