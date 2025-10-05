# Análise Exploratória de Churn de Clientes Bancários 📊

## Introdução

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Status](https://img.shields.io/badge/Status-Concluído-green)

## Visão Geral do Projeto

Este projeto tem como objetivo realizar uma análise exploratória aprofundada sobre uma base de dados de clientes de uma instituição bancária. O foco é identificar os principais perfis e fatores que levam ao cancelamento de contas (churn), através da limpeza dos dados e da geração de insights visuais.

## Objetivos

- Identificar padrões comportamentais de clientes que cancelam serviços
- Analisar correlações entre variáveis demográficas e financeiras com o churn
- Desenvolver visualizações que facilitem o entendimento do fenômeno
- Fornecer insights acionáveis para redução da taxa de churn

## Metodologia

O projeto foi estruturado com foco em duas das etapas mais críticas de qualquer análise de dados: o tratamento dos dados brutos e a exploração para entendimento do negócio.

### Etapas do Projeto:

**1. Limpeza e Pré-processamento dos Dados:**
- Tratamento de valores ausentes (NaN) nas colunas Gênero e Salário
- Correção de inconsistências no domínio das variáveis categóricas (Estado e Gênero), padronizando as entradas
- Tratamento de outliers e valores inconsistentes na coluna Idade, substituindo-os pela mediana para garantir a robustez da análise

**2. Análise Exploratória de Dados (EDA):**
- Investigação da distribuição das principais variáveis numéricas (Score, Idade, Saldo, etc.)
- Criação de um mapa de calor (heatmap) para analisar a correlação entre as features e identificar relações lineares
- Geração de um pairplot para visualizar a relação entre pares de variáveis, segmentado por clientes que saíram (Churn = 1) e os que permaneceram (Churn = 0)

## 💡 Principais Insights da Análise

- **Perfil de Churn**: A análise inicial sugere que clientes com score de crédito mais baixo, maior número de produtos e que são mais velhos tendem a apresentar uma maior taxa de churn.

- **Impacto Geográfico**: A exploração dos dados indicou variações na taxa de churn entre os diferentes estados, sugerindo que fatores regionais podem ser relevantes.

- **Correlações**: O mapa de calor não revelou correlações lineares extremamente fortes entre as variáveis, indicando que o churn é provavelmente influenciado por uma combinação de fatores.

## Como Executar o Projeto

Para replicar a análise, siga os passos abaixo:

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/analise-churn-clientes.git
   ```

2. **Navegue até o diretório do projeto:**
   ```bash
   cd analise-churn-clientes
   ```

3. **Crie um ambiente virtual (recomendado):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # No Windows: venv\Scripts\activate
   ```

4. **Instale as dependências:**
   ```bash
   pip install -r requirements.txt
   ```

5. **Execute o Notebook:**
   Abra e execute o arquivo `praticaudemy_churn.ipynb` em um ambiente Jupyter.

## Ferramentas e Bibliotecas Utilizadas

- **Linguagem**: Python 3
- **Bibliotecas Principais**:
  - Pandas e NumPy para manipulação de dados
  - Matplotlib e Seaborn para visualização de dados
  - Statistics para cálculos estatísticos

## 📁 Estrutura do Projeto

```
analise-churn-clientes/
│
├── praticaudemy_churn.ipynb     # Notebook principal com a análise
├── requirements.txt             # Dependências do projeto
├── data/                        # Diretório para dados
│   └── (arquivos de dados)
└── README.md                    # Este arquivo
```

## 🙏 Agradecimentos e Origem do Projeto

Este projeto foi desenvolvido como parte do curso **"Formação Cientista de Dados: O Curso Completo - 2025"** ministrado pelo professor **Fernando Amaral** na plataforma **Udemy**. 

A base de dados e o problema de negócio foram fornecidos no contexto do curso, e o desenvolvimento deste notebook representa a aplicação prática dos conceitos de limpeza e análise exploratória de dados.

---

**Autor**: [@Nogfe4](https://github.com/Nogfe4)

**Última atualização**: Outubro 2025