# Série temporal da modelagem ao 'deploy' com Prophet e MLFlow

Neste post, vou explicar como o uso os pacotes python do Prophet e do MLFlow para melhorar a previsão e o gerenciamento de modelos em um projeto de ciência de dados que faz a previsão de vendas de uma loja de varejo. 
	O Prophet é uma biblioteca desenvolvida pelo Facebook que permite fazer previsões baseadas em séries temporais de forma simples e robusta. O MLFlow é uma plataforma de código aberto que facilita o ciclo de vida dos modelos de aprendizado de máquina, desde o treinamento até a implantação, passando pelo monitoramento e a otimização. Combinando essas duas ferramentas, é possível criar um fluxo de trabalho eficiente e escalável de ciência de dados (O tal do MLOps).

Neste post, meu objetivo é mostrar como servir uma API com o nosso modelo de previsão. No entanto, há vários passos necessários para publicar um modelo em produção de forma sustentável. Por isso, este post será o primeiro de uma série que visa construir uma solução completa para isso. Vamos servir a API, mas também vamos melhorá-la e automatizá-la em posts futuros. Por enquanto, vamos considerar que este post é a primeira sprint do nosso projeto liderado pelo cientista de dados que será passado para uma equipe de engenharia de dados e/ou um engenheiro de machine learning.

_Dito isso, nosso alvo de negócio é;_
>	**_Montar a previsão de como as vendas se comportarão no próximo mês e servir isso como uma API para que analistas de negócio possam através de BI gerenciar estoque, fazer estimativa de receita e outras analises operacionais de curto prazo._**

[Link do post](https://www.wimyd.com.br/post/s%C3%A9rie-temporal-da-modelagem-a-api-com-prophet-e-mlflow)
