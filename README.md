# 📰 Fake News Detection with Transformers

## 📌 Sobre o Projeto

Este projeto apresenta uma solução de Inteligência Artificial para **classificação automática de notícias falsas (Fake News)**, enfrentando um dos principais desafios da era da informação: distinguir conteúdos verídicos de desinformação.

A abordagem utiliza técnicas de **Processamento de Linguagem Natural (PLN)** baseadas na arquitetura Transformer, explorando modelos destilados como **DistilBERT** e **DistilRoBERTa**. A escolha por versões destiladas visa equilibrar **alto desempenho preditivo** e **eficiência computacional**, permitindo a execução em ambientes com recursos limitados.

Além de avaliar métricas como **F1-Score**, o projeto realiza uma **análise comparativa de robustez** entre as duas arquiteturas, investigando diferenças de desempenho e generalização.

---

## 🛠 Tecnologias Utilizadas

- Python
- PyTorch
- Transformers (Hugging Face)
- Scikit-learn
- Pandas
- NumPy

---

## 🚀 Como Executar

```bash
# Clone o repositório
git clone https://github.com/MarceloPMelo/fakenews-detection-NLP.git

# Entre na pasta
cd fakenews-detection-NLP

# Cie um venv
python -m venv venv

#Ative o venv
source venv/bin/activate

# Instale as dependências
pip install -r requirements.txt

# Entre na pasta de notebooks
cd notebooks
```

### ▶️ Executar diretamente pelo VS Code

Se estiver utilizando o VS Code:

1. Instale a extensão **Jupyter**.
2. Abra a pasta do projeto.
3. Navegue até `notebooks/pipeline.ipynb`.
4. Clique em **Run All**.

---

### ▶️ Executar no Google Colab (Recomendado para uso com GPU)

Caso prefira não configurar o ambiente localmente, é possível executar o projeto no Google Colab:

1. Acesse: https://colab.research.google.com
2. Clique em **"Upload"**.
3. Faça o upload do arquivo `pipeline.ipynb`.
4. Após abrir o notebook, vá em:
   - `Runtime` → `Change runtime type`
   - Em **Hardware accelerator**, selecione **GPU**
   - Escolha **T4 GPU**
   - Clique em **Save**

Depois disso, execute as células normalmente com `Run All`.

⚠️ Observação:
- será necessário fazer upload dos arquvos train.csv e test.csv no Colab 

---

⚠️ Certifique-se de que o ambiente virtual (`venv`) esteja ativado antes de rodar o notebook.