# Análise Exploratória de Dados - Pesquisa de Percepção de Tecnologia

Este notebook tem como objetivo realizar a análise exploratória dos dados da Pesquisa de Percepção de Tecnologia. O projeto tem como objetivo analisar as informações sobre como as pessoas percebem e utilizam a tecnologia, incluindo suas opiniões sobre os benefícios e riscos associados, bem como sua probabilidade de adotar e recomendar novas tecnologias. A análise da percepção de tecnologia é fundamental para entender como as pessoas percebem e utilizam a tecnologia em suas vidas diárias. Essas informações são valiosas para empresas e governos que desejam desenvolver produtos e serviços que atendam às necessidades e expectativas dos usuários. Além disso, a análise de percepção de tecnologia pode fornecer insights sobre as tendências do mercado e as preferências dos consumidores, o que pode ajudar na tomada de decisões estratégicas.

## Obtenção dos dados

Os dados utilizados nesta análise estão disponíveis no Kaggle através do seguinte link: [Technology Perception Survey](https://www.kaggle.com/datasets/mrcalvinwhite/technology-perception-survey). Os dados foram coletados por meio de uma pesquisa aplicada a uma amostra aleatória com o objetivo de medir padrões de uso de tecnologia, benefícios percebidos, riscos percebidos, barreiras percebidas, probabilidade de adoção, probabilidade de recomendação, etc. A pesquisa foi direcionada principalmente para a Índia, com alguns respondentes (<10) sendo de outros países. A coleta foi realizada através de amostragem aleatória online usando o Google Forms.

## Dicionário de Variáveis

A tabela abaixo apresenta um dicionário das variáveis disponíveis no conjunto de dados:

| Coluna                              | Descrição                                         |
|-------------------------------------|---------------------------------------------------|
| Age                                 | Idade do respondente                              |
| Gender                              | Gênero do respondente                             |
| EducationLevel                      | Nível de educação do respondente                  |
| HouseholdIncome                     | Renda familiar em INR lakhs por ano (valor completo) |
| Frequency_LaptopDesktop             | Frequência de uso de Computador Pessoal (Notebook/Desktop) |
| Frequency_Smartphone                | Frequência de uso de Smartphone                   |
| Frequency_Tablet                    | Frequência de uso de Tablet                       |
| Frequency_SmartHomeDevices          | Frequência de uso de Dispositivos Inteligentes para Casa (Smart TV, Alexa, Iluminação Inteligente) |
| Frequency_WearableDevices           | Frequência de uso de Dispositivos Vestíveis (Smartwatches, Rastreadores de Fitness, etc.) |
| Frequency_GamingConsoles            | Frequência de uso de Consoles de Jogos            |
| Frequency_HomeSecuritySystem        | Frequência de uso de Sistema de Segurança Residencial |
| LikelinessToAdopt                   | Probabilidade de adoção de novas tecnologias      |
| Benefit_ProductivityEfficiency      | Benefício percebido em relação à produtividade e eficiência |
| Benefit_CommunicationConnectivity   | Benefício percebido em relação à comunicação e conectividade |
| Benefit_EasyAccessToInfo            | Benefício percebido em relação ao fácil acesso à informação |
| Benefit_Entertainment               | Benefício percebido em relação ao entretenimento   |
| Risk_SecurityPrivacy                | Risco percebido em relação à segurança e privacidade |
| Risk_ExcessScreenTime               | Risco percebido em relação ao tempo excessivo de tela |
| Risk_ComplicatedToUse               | Risco percebido em relação à complexidade de uso    |
| Risk_Addiction                      | Risco percebido em relação à dependência           |
| Risk_Health                         | Risco percebido em relação à saúde                 |
| Risk_LossOfConnection               | Risco percebido em relação à perda de conexão      |
| Influence_FamilyFriends             | Influência de amigos e familiares na adoção de tecnologia |
| Influence_PromoActivities           | Influência de atividades promocionais na adoção de tecnologia |
| Influence_SocialPopularity          | Influência da popularidade social na adoção de tecnologia |
| Influence_ExpertRecommendation      | Influência de recomendações de especialistas na adoção de tecnologia |
| Influence_Endorsements              | Influência de endossos na adoção de tecnologia      |
| Barrier_HighPrice                   | Barreira percebida em relação ao alto preço         |
| Barrier_TechKnowledge               | Barreira percebida em relação ao conhecimento técnico |
| Barrier_PrivacySecurity             | Barreira percebida em relação à privacidade e segurança |
| Barrier_ReliableInternet            | Barreira percebida em relação à internet confiável   |
| Barrier_ChangeReluctance            | Barreira percebida em relação à relutância em mudar  |
| LikelinessToRecommend               | Probabilidade de recomendar tecnologia             |

## Como Utilizar

1. Clone o repositório em sua máquina local.
2. Instale o servidor MySQL e crie um banco de dados e uma tabela com base no script fornecido no notebook de análise exploratória.
3. Importe o arquivo CSV do conjunto de dados fornecido pelo Kaggle para o banco de dados criado.
4. Abra o notebook de análise exploratória no MySQL e execute as consultas para realizar a análise dos dados.

## Contato

Desenvolvedora do Projeto: Isabela Vitoriano

• Linkedin: [https://www.linkedin.com/in/isabela-vitoriano/](https://www.linkedin.com/in/isabela-vitoriano/)

• E-mail: [isabelavitoriano.ss@gmail.com](isabelavitoriano.ss@gmail.com)
