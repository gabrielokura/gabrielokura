## INTEGRAÇÃO ENTRE PLATAFORMAS DE VENDAS

Mais uma oportunidade de sistema que tive para desenvolver.

Aqui a ideia era juntar informações de diferentes plataformas de vendas através de webhooks e uma aplicação serverless que eu criei.

Por questões de sigilo, não disponibilizarei o projeto nesse repositório. Entretanto, alguns arquivos da arquitetura do sistema
podem ser consultados em
em: 
- integracao-plataformas/arquitetura/...

## STACKS

O serviço foi escrito em TypeScript, utilizando a ferramenta Serverless [https://www.serverless.com/]. Mesmo que uma aplicação 
serverless não precise de hospedagem, utilizei os serviços da AWS (como o AWS lambda, AWS cloud watch, AWS SQS Queue) para
construí-lo.