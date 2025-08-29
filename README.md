# 🚀 Projeto YOLO - Transfer Learning com Dataset COCO

## 📌 Descrição

Este projeto foi desenvolvido como parte da disciplina de **`[NOME DA DISCIPLINA AQUI]`**. 

O objetivo foi aplicar a técnica de **Transfer Learning** utilizando a arquitetura **YOLOv3** e o dataset **COCO**. O treinamento foi focado na detecção de duas classes específicas, aproveitando as anotações já existentes no dataset para evitar a necessidade de rotulação manual.

Para a execução e treinamento do modelo, foram utilizados os recursos do **Google Colab**.

---

## 🛠️ Tecnologias e Ferramentas

-   [Google Colab](https://colab.research.google.com/)
-   [Darknet YOLO](https://pjreddie.com/darknet/yolo/)
-   [COCO Dataset](https://cocodataset.org/)
-   [Python 3](https://python.org/)

---

## 🧪 Classes Utilizadas

Neste trabalho, foram selecionadas as seguintes classes do COCO Dataset para o treinamento:

-   🐶 **Dog**
-   🚲 **Bicycle**

---

## 🔧 Como Reproduzir o Projeto

Siga os passos abaixo para executar o projeto:

1.  **Clonar o repositório do Darknet e compilar o projeto:**
    ```bash
    git clone [https://github.com/pjreddie/darknet](https://github.com/pjreddie/darknet)
    cd darknet
    make
    ```

2.  **Executar o Notebook:**
    Abra e execute o notebook `notebook_colab.ipynb`, que contém todo o passo a passo do treinamento.

3.  **Utilizar o modelo treinado:**
    O arquivo final de pesos do modelo (`yolov3_final.weights`) pode ser baixado no link abaixo:

    👉 **[![Abrir no Colab]([https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cicerojr10/yolo-coco-transfer-learning/blob/main/notebook_colab.ipynb](https://colab.research.google.com/drive/1PW49FNu_Ns0CnYq9UzKOQln6X0Le4oKa?usp=sharing))**

---

## 📊 Resultados

Abaixo, um exemplo de detecção obtida com o modelo treinado:

---

## 📂 Estrutura do Repositório

```text
yolo-coco-transfer-learning/
│
├── README.md               # Explicação do projeto
├── notebook_colab.ipynb    # Código do Colab para treinamento
├── requirements.txt        # Dependências utilizadas
│
├── /results/               # Imagens com os resultados da detecção
│   ├── exemplo1.jpg
│   └── exemplo2.jpg
│
├── /config/                # Arquivos de configuração do YOLO
│   ├── obj.data
│   ├── obj.names
│   └── yolov3.cfg
│
└── yolov3_final.weights    # Modelo treinado (se for pequeno, senão use o link no README)
```

---

## 👨‍💻 Autor

| [<img src="https://avatars.githubusercontent.com/u/SEU_USER_ID_AQUI?v=4" width="100px;"/><br /><sub><b>Cícero Quintino Junior</b></sub>](https://github.com/cicerojr10)<br /> |
| :---: |

Estudante de Ciência da Computação.
