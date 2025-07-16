# PluviaPlus

## 📖 Descrição

O PluviaPlus é uma solução tecnológica, portátil e sustentável, projetada para fornecer água potável a comunidades que enfrentam os desafios de eventos climáticos extremos e colapso hídrico. O sistema funciona captando e purificando a umidade presente no ar, utilizando fontes de energia limpa e acessível para garantir o acesso à água potável.

## 🛠️ Tecnologias utilizadas

* **Linguagem Principal:** Python
* **Análise e Modelagem:** Jupyter Notebook
* **Machine Learning:** O projeto utiliza um modelo pré-treinado (`modelo_treinado.pkl`), sugerindo o uso de bibliotecas como Scikit-learn, TensorFlow ou PyTorch.
* **Dependências:** Todas as bibliotecas Python necessárias para a execução do projeto estão listadas no arquivo `requirements.txt`.

## 📂 Estrutura de pastas

O repositório está organizado da seguinte forma:

```
/
├── backend/
├── data/
├── frontend/
├── notebooks/
├── .gitignore
├── Documentação-IA (1).pdf
├── README.md
├── integrantes.txt
├── modelo_treinado.pkl
└── requirements.txt
```

* **`backend/`**: contém o código do lado do servidor da aplicação.
* **`data/`**: armazena os conjuntos de dados utilizados para treinar e validar o modelo de machine learning.
* **`frontend/`**: contém o código do lado do cliente, responsável pela interface do usuário.
* **`notebooks/`**: abriga os notebooks Jupyter utilizados para análise de dados, experimentação e desenvolvimento do modelo.
* **`Documentação-IA (1).pdf`**: documento com detalhes sobre a implementação da Inteligência Artificial no projeto.
* **`integrantes.txt`**: lista dos membros da equipe do projeto.
* **`modelo_treinado.pkl`**: arquivo do modelo de machine learning já treinado e pronto para uso.
* **`requirements.txt`**: arquivo que lista todas as dependências Python do projeto.

## 🚀 Como executar o projeto

Para executar este projeto em sua máquina local, siga os passos abaixo:

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/GabrielRossi01/gs-ia.git
    cd gs-ia
    ```

2.  **Crie um ambiente virtual (recomendado):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows, use `venv\Scripts\activate`
    ```

3.  **Instale as dependências:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Explore os notebooks:**
    Para entender a análise e o modelo, você pode iniciar o Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
    Em seguida, navegue até a pasta `notebooks/` e abra os arquivos `.ipynb`.

5.  **Execute a aplicação:**
    *(Esta seção pode precisar de mais detalhes, dependendo de como o backend e o frontend são iniciados. Verifique os arquivos nessas pastas para encontrar o comando de execução, como `python app.py` ou similar).*

## 👥 Contribuidores

A lista de integrantes que contribuíram para este projeto pode ser encontrada no arquivo `integrantes.txt`.
