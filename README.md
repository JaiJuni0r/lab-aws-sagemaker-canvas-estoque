# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Bem-vindo ao desafio de projeto "Previsão de Estoque Inteligente na AWS com SageMaker Canvas. Neste Lab DIO, você aprenderá a usar o SageMaker Canvas para criar previsões de estoque baseadas em Machine Learning (ML). Siga os passos abaixo para completar o desafio!

🚀 Para realização do projeto:

Seleção do Dataset

Analisei e selecionei um dataset adequado para treinar o modelo de previsão de estoque.
Realize o upload do dataset no SageMaker Canvas.
No contexto deste projeto, utilizamos um dataset em formato .csv. É importante ressaltar que a AWS oferece uma variedade de fontes de dados, incluindo serviços como DynamoDB.

Construção do projeto

Configure as variáveis de entrada e saída de acordo com os dados disponíveis.
Inicie o processo de treinamento do modelo.
![image](https://github.com/user-attachments/assets/d6918108-8aed-445b-8c5d-8b9810365682)


Análise do projeto

Avalie as métricas de desempenho do modelo obtidas durante o treinamento.
Identifique as características fundamentais que influenciam as previsões geradas.
![image](https://github.com/user-attachments/assets/7513976d-bb6c-4775-a322-562eeaeccb83)

Previsão do projeto

Utilize o modelo treinado para realizar previsões de estoque com base nos dados analisados.
Exporte os resultados para posterior utilização.

Por exemplo, ao escolher o produto 1, temos as metricas de previsões. 
Sendo: 
- P10 uma previsão pessimista; 
- P50 uma previsão neutra;
- P90 uma previsão otimista. 
![image](https://github.com/user-attachments/assets/4a33915a-abcf-4b1a-98dc-9f839a58ba89)

📈 Análise das Métricas

Para o estoque dos produtos, foram gerados três percentis de previsão (P10, P50 e P90). Essas previsões possibilitam uma visão ampla das possíveis variações no comportamento do estoque, permitindo a formulação de estratégias adequadas para a gestão do negócio. Devido ao uso da versão Free Tier da AWS, foi implementada uma versão simplificada da predição (single prediction)
