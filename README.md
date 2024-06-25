# <a> Classificação usando Scikit Learn e XGBoost</a>



## <a> Motivação </a>

Muitos problemas da vida real na carreira de cientista de dados são modelados como classificação. Quando a variável dependente é discreta, temos uma classificação. As classes podem ser somente duas (variável dependente binária) ou problemas multiclasse. 




## <a> Objeto de Estudo </a>

Um problema muito recorrente para muitas empresas é qual a melhor forma de reter seus clientes. Saber de antemão se um cliente vai cancelar os serviços é uma grande vantagem competitiva para qualquer empresa. A estratégia de marketing, CRM e as equipes de vendas podem se beneficiar muito se tiver informações de quais clientes tem mais chances de deixar de contratar os serviços de uma empresa.

Esse tipo de problema é chamado de previsão de churn (de churn rate ou % de clientes que deixam a empresa num determinado tempo). Para resolver esse tipo de problema precisamos ter uma base histórica com clientes que saíram e não saíram da empresa, bem como suas características. 

Bancos, telefônicas, varejo, qualquer empresa que presta algum tipo de serviços e possui informações sobre seus clientes pode se beneficiar de modelos preditivos similares ao que irei construir aqui.

Nesse projeto irei trabalhar com uma empresa telefonica onde queremos saber se seus clientes possuem chance de cancelar os serviços ou não, para isso vou classificar 
o Churn como 0 caso não va sair ou 1 caso vá sair. 


A base utilizada pode ser obtida no [Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn) e se trata de uma empresa telefônica fictícia com dados demográficos e de serviços contratados pelos  clientes com a informação se saiu ou não da empresa.
