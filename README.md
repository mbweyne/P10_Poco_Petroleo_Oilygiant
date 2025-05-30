![Banner do Projeto](banner.png)

📊 Projeto 10 – Modelagem de Risco e Lucro na Exploração de Petróleo  
Autora: Marcia Bayardino Weyne  
Data: 2025

📝 Descrição do Projeto  
Este projeto, desenvolvido para a companhia fictícia OilyGiant, visa aplicar técnicas de aprendizado de máquina para prever reservas de petróleo e identificar as regiões com maior retorno financeiro na abertura de novos poços.

📑 Tabela de Conteúdo  
- Objetivo  
- Resultados  
- Ferramentas Utilizadas  
- Metodologia  
- Como Executar o Projeto  
- Aprendizados  
- Contato  

🎯 Objetivo  
Construir um modelo preditivo de volume de reservas de petróleo a partir de características geológicas e selecionar as regiões com maior potencial de lucro, utilizando técnicas de modelagem e simulação de risco com Bootstrapping.

🏁 Resultados  
📈 Modelo de Regressão Linear com bom desempenho preditivo  
💰 Cálculo do lucro esperado e risco por região  
📊 Simulação de 1000 amostras para avaliar a distribuição de lucro (Bootstrapping)  
🥇 Seleção da região com maior potencial de retorno ajustado ao risco  

🧰 Ferramentas Utilizadas  
- Caderno de desenvolvimento: Jupyter Notebook  
- Linguagem: Python  
- Bibliotecas: pandas • numpy • scikit-learn • matplotlib • seaborn  

🔍 Metodologia  
1. **Preparação dos Dados**  
   - Leitura dos dados das três regiões (geo_data_0, geo_data_1, geo_data_2)  
   - Análise exploratória e verificação de correlação  

2. **Modelagem Preditiva**  
   - Treinamento de modelo de regressão linear para prever o volume de reservas  

3. **Seleção de Poços Promissores**  
   - Seleção dos 200 poços com maiores valores preditos em cada região  

4. **Análise de Risco e Lucro**  
   - Cálculo de lucro com base em valores reais e preditos  
   - Simulação com Bootstrapping (1000 iterações) para estimar risco e lucro  

💽 Como Executar o Projeto  
Pré-requisitos:  
- Python 3.10+  
- Jupyter Notebook  

Instalar dependências:  
```bash
pip install -r requirements.txt
Executar:

bash
Copiar
Editar
jupyter notebook
Abra o notebook projeto_poco_petroleo_oilygiant_modelagem_risco_lucro.ipynb e siga a ordem das células.

📝 Aprendizados
Técnicos:

Treinamento de modelos preditivos com dados tabulares

Análise de risco com Bootstrapping

Seleção de amostras mais lucrativas com base em predições

Profissionais:

Documentação técnica de projetos

Estruturação de notebooks e pastas para GitHub

Uso integrado de Git, VS Code e GitHub

😄 Contato

[![GitHub](https://img.shields.io/badge/-GitHub-000?style=for-the-badge&logo=github)](https://github.com/mbweyne/P11_ML_Seguro)

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marcia-bayardino-weyne)




