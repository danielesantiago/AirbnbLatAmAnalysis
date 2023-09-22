# Análise do Airbnb - América Latina 🌎

Este projeto tem como objetivo analisar as operações do Airbnb nos quatro principais países da América Latina (Brasil, México, Argentina e Colômbia) e identificar tendências que possam influenciar a quantidade de diárias reservadas.

📄 [Veja a minha apresentação aqui](https://github.com/danielesantiago/AirbnbLatAmAnalysis/blob/master/An%C3%A1lise%20do%20Airbnb.pdf)

## 📂 Conteúdo

1. [Descrição dos Dados](#descrição-dos-dados)
2. [Insights Iniciais](#insights-iniciais)
3. [Projeções para 2023](#projeções-para-2023)
4. [Conclusão](#conclusão)
5. [Como Executar o Projeto](#como-executar-o-projeto)

## Descrição dos Dados

Os dados foram obtidos diretamente da plataforma Airbnb e contêm informações detalhadas sobre hospedagens e demanda. Aqui está um breve dicionário das variáveis presentes:

- **Nome do local:** Descrição breve da acomodação.
- **Localização:** Endereço ou área exata da propriedade.
- **País:** País de localização.
- **Tipo de acomodação:** Classificação da propriedade (e.g., Quarto Inteiro, Casa Inteira).
- **Classificação:** Avaliação média da propriedade.
- **Comodidades:** Serviços oferecidos.
- **Políticas de cancelamento:** Termos para cancelar uma reserva.
- **Preço:** Custo por noite.
- **Número de reservas no ano:** Quantas vezes a propriedade foi reservada.
- **Número de Fotos:** Quantidade de imagens da propriedade.

🔗 [Acessar dados completos](https://docs.google.com/spreadsheets/d/10XiW4y9bQ323wkCYh3gMvqP7SWgTsAAdpusxg_38krQ/edit?usp=sharing)

## Insights Iniciais

- A Colômbia tem o menor preço médio entre os países, mas o desvio padrão mais baixo.
- O Brasil apresenta a maior amplitude de preço.
- Distribuição de preços no Brasil segue uma distribuição normal.

Mais detalhes podem ser encontrados no Jupyter Notebook associado.

## Projeções para 2023

Realizamos uma projeção do número de reservas para 2023 baseando-nos nos dados de 2021 e 2022, aplicando um modelo de regressão linear. Os resultados mostraram uma tendência de aumento nas reservas para todos os quatro países.

## Conclusão

A análise proporcionou insights valiosos sobre o comportamento do mercado em cada um dos quatro países. Os modelos de regressão mostraram-se promissores para prever as tendências futuras. Mais detalhes e gráficos podem ser encontrados nos arquivos do projeto.

## Como Executar o Projeto

1. Clone o repositório:
```
git clone https://github.com/danielesantiago/AirbnbLatAmAnalysis.git
```

2. Instale as dependências necessárias (recomenda-se utilizar um ambiente virtual):

3. Execute os Jupyter Notebooks para visualizar as análises e resultados.

---

📌 Desenvolvido no contexto da divisão América Latina do Airbnb.

---
