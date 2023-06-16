# MVP 1: Análise de Dados e Boas Práticas

Este projeto foi feito como avaliação para o _sprint_ "Análise de Dados e Boas Práticas" do curso de pós-graduação "Ciência de Dados e Analytics" da PUC-Rio.

## Como rodar

Para rodar esse projeto, é necessário o download das pastas e a instalação do jupyter notebook, junto com a mais nova versão do python, pandas, matplotlib e scikit-learn.

1. Clone o repositório para sua máquina local
2. Abra o arquivo .ipynb com o jupyter notebook ou em alguma IDE com a extensão do jupyter notebook
3. Clique em "Run all".

## Fonte dos dados

Os dados foram adquiridos no [Kaggle](https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers) que, segundo o autor do problema, adquiriu-os [neste link](https://leaps.analyttica.com/). Fiz uma pequena alteração, mencionada pelo próprio autor. No dataset original, haviam duas colunas "a mais" ("NAIVE BAYES CLAS…"). Eu as deletei previamente para manter a fluidez do exercício.

## Problema

Retirado do Kaggle e traduzido livremente: "Um gerente em um banco está incomodado com a quantidade crescente de clientes abandonando as linhas de crédito e serviços do banco. Eles agradecerão quem puder prever quem serão os próximos a abandonarem, para que eles possam agir proativamente em direção ao cliente de maneira a fornecer melhores serviços, modificando a decisão dos clientes'.

## Resultados e conclusões

É possível, a partir de visualizações, identificar comportamentes que parecem ser preditivos quanto à mudança de chave do cliente que pretende se tornar ex-cliente. Enquanto não é desenvolvido um modelo preditivo, algumas medidas podem ser recomendadas a partir da exploração dos dados:

- Focar nos grupos de menor renda do universo observável: embora o poder de compra seja individualmente menor, a maioria da clientela do banco possui rendimentos inferiores a 60 mil dólares, o que equivale a 52,6%. Por isso, estratégias focalizadas nesse grupo podem fortalecer a base de clientes.

- Buscar estratégias de comunicação para grupos de maior renda: Quanto mais diversificada for a base de renda dos clientes, mais blindado o banco será aos padrões de comportamento de um determinado setor social.

- Agir proativamente quando a atividade estiver baixa: Existe uma maior incidência de níveis de atividades reduzidos no grupo de ex-clientes analisados, de maneira que é inteligente focalizar ações proativas para retenção em grupos de clientes em que a redução da atividade nos últimos 12 meses seja visível.

- Fortalecer a integração de produtos: Vimos que quanto menos produtos os clientes utilizam, mais eles tendem a abandonar os serviços do banco. Desas maneira, quanto mais integrados forem os produtos, mais os clientes se envolverão no ecossistema de serviços do banco e tenderão a permanecer.

- Crie formas de incentivar o uso do cartão de crédito pelos clientes: Uma forma de recompensa ou de pontuação, por exemplo, pode ser a diferença significativa entre um cliente que abandona o banco e um cliente que permanece cliente.

- Desenvolvimento de melhor estratégia de comunicação: Vimos que há uma maior incidência de contatos entre o banco e o cliente no universo analisável dos ex-clientes. Podemos inferir que a estratégia de comunicação do banco não está sendo eficiente para retê-los. É interessante que se investigue os problemas e a comunicação seja melhorada.

## Autor

Leonardo Laurindo, leolaurindorj@gmail.com

## Licença

[CC0](https://creativecommons.org/publicdomain/zero/1.0/)
