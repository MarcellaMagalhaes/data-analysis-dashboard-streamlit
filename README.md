# 📊 Tech Salaries Dashboard – Data Analysis & Streamlit

Um projeto inicial desenvolvido durante uma imersão em análise de dados, focado em explorar salários de profissionais de tecnologia ao redor do mundo.

## Sobre o Projeto

Este projeto foi criado como parte de uma imersão prática em **análise de dados**. Utilizamos uma base real de salários de profissionais de tecnologia para:
- Praticar limpeza e tratamento de dados
- Aplicar análise exploratória (EDA)
- Criar visualizações interativas
- Construir um dashboard funcional

**Importante**: Este é um projeto inicial, desenvolvido em contexto educacional, com foco na consolidação de fundamentos de análise de dados e visualização.

## 🛠️ Tecnologias Utilizadas

- **Python 3.12.3**
- **Google Colab** - Para análise inicial e tratamento dos dados
- **Pandas** - Manipulação e limpeza de dados
- **Streamlit** - Criação do dashboard web interativo
- **Plotly Express** - Visualizações gráficas interativas
- **VS Code** - Desenvolvimento do dashboard

## 🔄 Fluxo do Projeto
1. Carregamento da base de dados no Google Colab  
2. Análise exploratória inicial dos dados  
3. Tratamento e limpeza da base (tipos de dados, valores nulos e padronizações)  
4. Exportação do DataFrame tratado  
5. Desenvolvimento do dashboard interativo com Streamlit  
6. Criação de gráficos dinâmicos utilizando Plotly Express  

## 📈 Funcionalidades do Dashboard

### 1. **Métricas Gerais**
   - Salário médio anual em USD
   - Salário máximo registrado
   - Total de registros na base
   - Cargo mais frequente

### 2. **Visualizações Interativas**
  1. **Top 10 cargos por salário médio**
  2. **Distribuição dos salários anuais**
  3. **Proporção dos tipos de trabalho** (presencial, remoto e híbrido)
  4. **Salário médio de Cientista de Dados por país**

### 3. **Filtros Dinâmicos**
   - **Ano** (2020-2025)
   - **Senioridade** (Júnior, Pleno, Sênior, Executivo)
   - **Tipo de Contrato** (Integral, Parcial, Contrato, Freelancer)
   - **Tamanho da Empresa** (Pequena, Média, Grande)

### 4. **Dados Detalhados**
   Ao final do dashboard, é possível visualizar a tabela completa de dados filtrados, simulando a visualização de uma planilha interativa.

## ▶️ Como Executar o Projeto
```bash
pip install -r requirements.txt
streamlit run app.py
```
### 📚 Principais Aprendizados
- Importância da limpeza e padronização dos dados antes da análise
- Uso do Pandas para manipulação, filtragem e agregação de dados
- Criação de visualizações interativas com Plotly Express
- Estruturação de dashboards utilizando Streamlit
- Aplicação prática de filtros e métricas para exploração dos dados

## Próximos Passos
- Implementar novos filtros para maior flexibilidade de análise
- Aprimorar a organização visual e o layout do dashboard
- Adicionar novas análises comparativas entre cargos e senioridades
- Refatorar o código visando melhor organização e escalabilidade
