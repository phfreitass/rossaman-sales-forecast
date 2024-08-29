# Rossamann Sales Predict

![Rossamann Sales Predict](/img/rossmann2.png)

## Visão geral:

### Projeto de Previsão de Vendas para uma Rede Farmacêutica.

A Rossmann opera mais de 3.000 drogarias em 7 países europeus. Atualmente, os gerentes de loja da Rossmann têm a tarefa de prever suas vendas diárias com até seis semanas de antecedência. As vendas da loja são influenciadas por muitos fatores, incluindo promoções, competição, feriados escolares e estaduais, sazonalidade e localidade. Com milhares de gerentes individuais prevendo vendas com base em suas circunstâncias únicas, a precisão dos resultados pode ser bastante variada.

Os dados utilizados neste projeto são reais, e foram disponibilizados pela própria Rossmanm através do site Kaggle, para uma competição de ciência de dados. Foram disponibilizados 1.017.209 registros de vendas, contendo 18 variáveis que detalham cada venda.

O contexto de negócios é fictício, porém descreve um problema real de uma grande varejista: prever com assertividade suas vendas.

## Problema de negócio

Em uma reunião mensal de resultados da Rossmann, o CFO solicitou aos gerentes das lojas a previsão de vendas (faturamento) para as próximas 6 semanas, pois ele precisa saber quanto cada loja pode contribuir financeiramente para uma reforma na rede, que está padronizando suas lojas.

## Estratégia de solução
Minha estratégia para resolver esse desafio, baseado na metodologia CRISP-DS, é:
1. Compreender com clareza o modelo e o problema de negócios, através da estatística descritiva;
2. Tratar os dados (formatos, dados faltantes, outliers), realizando a sua limpeza.
3. Levantar junto ao time de negócio quais são as features que impactam nas vendas. Formular e validar hipóteses gerando insights de negócio.
4. Preparar os dados para a criação do modelo de previsão de vendas, realizando transformações, separação do dataframe entre treino e teste, e seleção de features automatizada.   
5. Treinar algoritmos de aprendizado de máquina (lineares e não lineares), comparar sua performance, e selecionar o de melhor desempenho.
6. Encontrar o conjunto de parâmetros que maximiza o aprendizado do modelo selecionado, reduzindo o seu erro nas previsões.
7. Interpretar o erro do modelo e traduzir em resultado financeiro para a empresa.
8. Avaliar se a previsão de vendas construída já entrega valor ao time de negócios, publicando em produção em caso positivo, ou realizando um novo ciclo de melhorias pontuais em caso negativo.
9. Após a publicação, criar robô no Telegram que acesse a previsão em tempo real, de qualquer lugar.
10. Apresentar e disponibilizar o bot do Telegram aos gerentes e CFO, detalhando o funcionamento do modelo e esclarecendo as suas dúvidas.

## Ferramentas
Quais ferramentas serão usadas no processo?
- Python 3.9.17;
- Jupyter Notebook;
- Git e Github;
- Heroku Cloud; 
- Algoritmos de Regressão;
- Bibliotecas de Machine Learning Sklearn;
- Técnicas de Seleção de Features;
- Flask e Python API's.