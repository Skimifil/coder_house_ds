# Data Science - Coder House

> Este projeto tem como objetivo desenvolver um Modelo Analítico de Machine Learning. Ele está sendo desenvolvido como parte das aulas na escola "Coder House" e contará com a colaboração de um time de 5 pessoas. O tema específico do modelo ainda será definido nos próximos dias, conforme as discussões e pesquisas realizadas pelo time.

### Colaboradores

- [Rafael P. de Carvalho](https://github.com/Skimifil)


## Projeto
O projeto é elaborado apartir dos conhecimentos adquiridos nas aulas. Com isso será projetado um modelo analítico de data Science em Jupyter Notebooks, de acordo com o assunto a ser tratado e sua respectiva documentação. Com isso, no final, deve ser entregue um modelo em Jupyter Notebook e o Documento executivo. 



## 💻 Pré-requisitos

Antes de começar, verifique se você atendeu aos seguintes requisitos:

- Você instalou a versão mais recente do `Python`
- Você deve instalar as bibliotecas:


## Objetivos gerais

- Entender o problema do negócio e identificar os elementos a serem considerados para o planejamento de um Modelo de Data Science.
- Descrever os dados de negócio e as relações entre dados através da Análise Exploratória de Dados.
- Escolher um algoritmo de treinamento e preparar os dados para o processo de treinamento do modelo.
- Avaliar os indicadores de desempenho preditivo do modelo e realizar otimizações.
- Elaborar uma apresentação executiva para a alta gerência mostrando os resultados do modelo.

## Obrigações no projeto

#### O modelo em Jupyter deve conter:
- Comentários de funções e processos
- Estrutura eficiente
- Aplicação dos conhecimentos vistos no curso
- Referências técnicas e da área pesquisada

#### O documento executivo deve conter:
- Capa: informará o título principal do projeto, nome dos integrantes, instituição e data de apresentação
- Tabela de conteúdos
- Descrição do caso de negócio: Contextualização e problema abordado
- Tabela de versionamento
- Objetivos do modelo
- Descrição dos dados a partir da perspectiva do Negócio: descrição do banco de dados usado, explicando: a temática, as variáveis selecionadas e a segmentação dos registros, se for aplicável. Além disso, incluir todas as decisões que foram tomadas para chegar ao dataset que servirá de input para o algoritmo
- Resultados encontrados pela EDA: análise univariada, bivariada e multivariada
- Algoritmo Escolhido
- Métricas de Desempenho do Modelo.
- Iterações de Otimização.
- Métricas finais do Modelo Otimizado.
- Linhas de ações futuras: breve descrição das possíveis iniciativas que podem ser postas em prática para complementar o projeto.
- Conclusões: contribuições do modelo aos objetivos propostos.

### Estrutura de pastas:

    data: Armazene seus dados brutos e processados (csv, json, etc.).
    src: Codifique seus scripts Python aqui.
    models: Salve seus modelos de Machine Learning.
    notebooks: Explore e visualize seus dados com Jupyter Notebooks.
    docs: Documentação do projeto, incluindo README, metodologia, resultados e insights.
    outputs: Resultados, figuras e outros arquivos gerados pelo projeto.
    tests: Teste seu código e garanta a qualidade do projeto.
    env: Armazene seu ambiente virtual Python (venv) para gerenciar dependências.


### Arquivo de 'requirements'

Dentro da estrutura do código, existe o arquivo "requirements.txt", nele vai constar todas as dependências do projeto.

```shell
pip freeze > requirements.txt
```


### Arquivo de informações sensíveis
Crie um arquivo de informações sensiveis, como usuários, senhas e 'secret's para serem acessados pelo projeto. Ele pode ser importado com "from configs import MONGODB_CONFIG"

O arquivo deve se chamar 'configs.py' e deve ter o seguinte conteúdo:
```python
MONGODB_CONFIG = {
    'MONGODBUSER': 'user',
    'MONGODBPASSWORD': 'senha',
    'MONGODBSERVER': 'server_dns',
}

MYSQL_CONFIG = {
    'MYSQLDBUSER': 'user',
    'MYSQLDBPASSWORD': 'senha',
}

SPOTIFY_CONFIG = {
    'CLIENTID': 'client_id',
    'CLIENTSECRET': 'client_secret',
}
```

## 📫 Contribuindo para Data Science - Coder House

Este é um projeto educacional, onde a ideia é aprender conforme cria executa o projeto. Com isso peço que a contribuição seja mais com explicações para melhorias e melhores práticas. Para contribuir com o projeto, siga estas etapas:

1. Bifurque este repositório.
2. Crie um branch: `git checkout -b <nome_branch>`.
3. Faça suas alterações e confirme-as: `git commit -m '<mensagem_commit>'`
4. Envie para o branch original: `git push origin <nome_do_projeto> / <local>`
5. Crie a solicitação de pull.

Como alternativa, consulte a documentação do GitHub em [como criar uma solicitação pull](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).
