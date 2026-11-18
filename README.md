# trabalho-mineracao-de-dados
Classificação de evasão e sucesso acadêmico com KNN, SVM e MLP. Inteligência de Negócios, BSI, IFES Campus Serra, 2026-2

## Como executar localmente

1. Clone o repositório e acesse a pasta do projeto:
   ```bash
   git clone https://github.com/DaviComerio/trabalho-mineracao-de-dados.git
   cd trabalho-mineracao-de-dados
   ```

2. Crie e ative um ambiente virtual:
   ```bash
   python -m venv .venv
   ```
   - **Windows (PowerShell):**
     ```powershell
     .\.venv\Scripts\Activate.ps1
     ```
   - **Linux / macOS:**
     ```bash
     source .venv/bin/activate
     ```

3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

4. Inicie o Jupyter Notebook:
   ```bash
   jupyter notebook codigo/notebooks/
   ```
   Abra o notebook desejado (`01_analise_exploratoria.ipynb`, `02_svm.ipynb`, `03_knn.ipynb` ou `04_mlp.ipynb`) e execute todas as células.
