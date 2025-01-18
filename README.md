
# 🧠 *Análise de Score de Cliente com Python e IA*

Este repositório contém o projeto desenvolvido na *3ª aula* da Jornada Python da Hashtag Treinamentos. O objetivo é construir modelos de classificação para prever o score de clientes em um banco, ajudando a identificar bons clientes para concessão de crédito e outros benefícios.

---

## 🧾 *Descrição do Projeto*

Imagine que você trabalha em um banco com uma base de dados de 100.000 clientes. É necessário analisar o score dos clientes para:

- Determinar se eles são bons pagadores.
- Decidir sobre empréstimos, limites de crédito e outros benefícios.

O projeto envolve tratamento de dados e a criação de *modelos de classificação* para prever o score dos clientes. O foco é encontrar o modelo mais eficiente e identificar as características mais importantes para a análise.

---

## 🛠️ *Etapas do Projeto*

1. *Importação da Base de Dados:*
   - Carregar a base de dados com informações sobre os clientes.
2. *Tratamento de Dados:*
   - Identificar e tratar valores ausentes.
   - Limpar e ajustar os dados para garantir a consistência.
3. *Seleção de Colunas de Treinamento:*
   - Escolher as variáveis mais relevantes para treinar os modelos.
4. *Treinamento de Modelos:*
   - Treinar dois modelos de classificação (exemplo: RandomForestClassifier e LogisticRegression).
5. *Comparação de Modelos:*
   - Avaliar qual modelo apresenta o melhor desempenho utilizando métricas como *accuracy, **precision, e **recall*.
6. *Identificação de Características Importantes:*
   - Analisar quais variáveis têm maior impacto na definição do score do cliente.

---

## ⚙️ *Como Rodar o Projeto*

### *Pré-requisitos*
- Python 3.x instalado.
- Bibliotecas necessárias:
  bash
  pip install pandas numpy scikit-learn matplotlib seaborn
  

### *Passos para Execução*
1. Clone este repositório:
   bash
   git clone https://github.com/seuusuario/analise-score-clientes.git
   cd analise-score-clientes
   

2. Execute o script:
   bash
   python analise_score.py
   

3. Siga as instruções no terminal para visualizar os resultados e gráficos gerados.

---

## ✅ *Resultados Obtidos*

### *Exemplo de Insights:*
- *Modelo com melhor desempenho:* Random Forest com *accuracy* de 92%.
- *Variáveis mais relevantes:*
  - Renda do cliente.
  - Tempo como cliente no banco.
  - Número de transações realizadas no último ano.

### *Conclusão:*
O modelo treinado ajuda o banco a tomar decisões mais assertivas sobre a concessão de crédito, reduzindo o risco de inadimplência e melhorando a eficiência.

---

## 📊 *Ferramentas Utilizadas*

- *Bibliotecas Python:*
  - pandas: Manipulação e análise de dados.
  - numpy: Operações matemáticas.
  - scikit-learn: Treinamento e validação de modelos de machine learning.
  - matplotlib e seaborn: Visualização de dados.

- *Técnicas de Machine Learning:*
  - Modelos testados: RandomForestClassifier, LogisticRegression.
  - Validação cruzada para avaliação de desempenho.

---

## 🌟 *Contribuições*

Contribuições são bem-vindas! Caso tenha sugestões ou melhorias, sinta-se à vontade para abrir *issues* ou enviar *pull requests*.

---

