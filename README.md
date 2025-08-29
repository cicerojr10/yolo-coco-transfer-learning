# 🚀 Projeto YOLO - Transfer Learning com Dataset COCO

## 📌 Descrição
Este projeto foi desenvolvido como parte da disciplina de [nome da disciplina].  
O objetivo foi aplicar **transfer learning** utilizando a rede **YOLOv3** e o dataset **COCO**, para treinar a detecção de pelo menos duas classes específicas.

Foram utilizados recursos do **Google Colab** para facilitar a execução do treinamento, sem necessidade de rotulação manual, aproveitando as anotações já existentes no dataset COCO.

---

## 🛠️ Tecnologias e Ferramentas
- [Google Colab](https://colab.research.google.com/)
- [Darknet YOLO](https://pjreddie.com/darknet/yolo/)
- [COCO Dataset](https://cocodataset.org/)
- Python 3

---

## 🧪 Classes utilizadas
Neste trabalho, foram selecionadas as seguintes classes do COCO Dataset:
- 🐶 **Dog**
- 🚲 **Bicycle**

---

## 🔧 Como reproduzir o projeto

1. **Clonar o Darknet e compilar:**
   ```bash
   git clone https://github.com/pjreddie/darknet
   cd darknet
   make
Executar o notebook disponível neste repositório:

notebook_colab.ipynb

Modelo treinado:
O arquivo final de pesos do modelo (yolov3_final.weights) pode ser baixado aqui:
👉 Download do modelo treinado
 (adicione o link do seu Drive ou GitHub Releases)

## 📊 Resultados

## 📂 Estrutura do repositório

Exemplo de detecção obtida após o treinamento:

yolo-coco-transfer-learning/
│
├── README.md                # Explicação do projeto
├── notebook_colab.ipynb     # Código do Colab
├── yolov3_final.weights     # Modelo treinado (se couber, senão link no README)
├── requirements.txt         # Dependências utilizadas
├── /results                 # Imagens de resultados
│   ├── exemplo1.jpg
│   ├── exemplo2.jpg
│
└── /config                  # Arquivos de configuração YOLO
    ├── obj.data
    ├── obj.names
    └── yolov3.cfg

## 👨‍💻 Autor

 ### Cícero Quintino Junior
### Estudante de Ciência da Computação
