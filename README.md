# detector-inteligente-yolov5
# 🚀 Treinamento de Rede Neural com YOLOv5 – Desafio DIO

Este projeto foi desenvolvido como parte do **Desafio de Projeto da DIO (Digital Innovation One)**.  
O objetivo é treinar uma rede neural de **Detecção de Objetos** utilizando o **YOLOv5** no Google Colab.

---

## 📌 Objetivos do Desafio
O desafio consistiu em implementar todas as etapas do pipeline de treinamento de um modelo de visão computacional:

1. ✅ Configurar o ambiente no Google Colab  
2. ✅ Preparar o dataset de imagens com anotações  
3. ✅ Criar o arquivo de configuração `data.yaml`  
4. ✅ Treinar o modelo YOLOv5  
5. ✅ Avaliar os resultados do treinamento  
6. ✅ Realizar inferência em imagens de teste  

---

## ⚙️ Tecnologias Utilizadas
- [Python 3](https://www.python.org/)  
- [PyTorch](https://pytorch.org/)  
- [YOLOv5](https://github.com/ultralytics/yolov5)  
- [Google Colab](https://colab.research.google.com/)  

---

## 📂 Estrutura do Dataset

### 🔹 Dataset COCO128 (padrão YOLOv5)
Para validação do projeto foi utilizado o **dataset COCO128**, já disponibilizado pelo próprio repositório do YOLOv5.  
Ele contém **80 classes** do conjunto COCO original em uma versão reduzida (128 imagens).  

Estrutura após o download:
