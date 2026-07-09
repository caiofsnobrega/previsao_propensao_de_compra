# Previsão de Intenção de Compra em E-commerce

## 📋 Descrição do Projeto
Este projeto tem por objetivo criar um sistema preditivo para antecipar a intenção de compra de clientes no e-commerce, baseando-se em seu perfil demográfico e histórico de consumo. A solução visa otimizar estratégias de marketing, identificar perfis de alta conversão e melhorar a experiência do usuário.

## 🛠 Metodologia (Pipeline de Dados)
O desenvolvimento seguiu as etapas fundamentais de Ciência de Dados:

**Preparação e Exploração (EDA)**: Análise da distribuição dos dados e identificação de correlações.

**Pré-processamento**: Tratamento de valores ausentes, limpeza e engenharia de features.

**Modelagem**: Aplicação de algoritmos de classificação para prever a intenção de compra.

**Avaliação**: Validação do desempenho do modelo utilizando métricas como Precisão, Recall e Matriz de Confusão.

## 📊 Principais Insights da Análise Exploratória (EDA)
**Comportamento de Compra**: Categorias como Vinhos e Carnes são as que apresentam maior volume financeiro e maior taxa de conversão online, sugerindo que o e-commerce é um canal forte para estes nichos.

**Perfil do Cliente**: Clientes com renda acima de 50 mil anuais demonstram maior propensão a compras online, enquanto consumidores de renda mais baixa (até 40 mil) convertem menos.

**Fidelidade**: Existe uma correlação positiva entre o número de compras na loja física e a propensão à compra online. Clientes frequentes na loja física são mais propensos a migrar para o digital.

**Comportamento de Navegação**: Foi identificado um grupo relevante que visita o site frequentemente (até 8 vezes/mês) sem realizar compras, sugerindo o uso da plataforma para pesquisa de preços antes da decisão de compra.

## 🛠 Modelagem Preditiva

Foram testados dois algoritmos de classificação: **Regressão Logística e Random Forest**.

- Modelo Vencedor: O Random Forest superou a Regressão Logística, atingindo 90% de acurácia média via validação cruzada.

- Features Mais Importantes: As 5 variáveis que mais influenciaram as previsões foram:
Gastos com vinhos, Gastos com carnes, Renda, Nº de compras na loja física e Nº de acessos mensais ao site

- Performance: O modelo final apresentou um excelente equilíbrio, com 95% de recall para a classe positiva, demonstrando alta capacidade de capturar os clientes com real intenção de compra.

## 💡 Conclusões e Recomendações

**Conversão**: Ações de marketing direcionadas (descontos exclusivos no site) podem converter clientes de renda mais baixa ou aqueles que apenas consultam preços.

**Fidelização**: Clientes com baixo histórico de compras na loja física devem ser alvo de campanhas de engajamento para torná-los mais frequentes e habituá-los ao canal online.

**Eficiência**: A simplificação do modelo utilizando apenas as 5 features mais importantes manteve a robustez (89% de acurácia), provando ser uma solução eficiente para implementação.
