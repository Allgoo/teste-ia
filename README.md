# Teste IA Allgoo

Caros candidatos, leiam atentamente as instruções neste README para realizar o teste.

> Antes de começar, prepare seu ambiente.

**Este teste requer:**
- Sua IDE favorita
- Ambiente de desenvolvimento com Python 3.5+ 
- Banco de dados (MongoDB, MySQL) [avaliar a necessidade para uso de banco relacional ou não]

--------

## Tarefas do teste:

**Funções necessárias:**
  - Normalizar a base de dados, identificar possíveis outliers e dados espúrios (arquivo [data.csv](https://github.com/Allgoo/teste-ia/blob/master/data.csv));
  - Modelar uma rede neural utilizando keras e tensorflow;
  - Utilizando o framework Flask ou Sanic desenvolver uma API e/ou microserviço para a manutenção das informações na base de dados e obtenção da previsão da rede neural;
  - Documentação de toda a metodologia, algoritmos, ideias em um notebook Jupyter.
    
## O que queremos de você nesse teste
- Crie em API e/ou microserviços;
- Documente muito bem seu sistema; (pode usar a ferramenta que achar adequada)
- Use docker;
- Implemente testes;
- Faça o deploy do seu sistema em algum server em cloud; (heroku, etc)

## Instruções adicionais

- Faça um fork do repositório
- Testes não são opcionais
- Depois de terminado, envie-nos o link do repositório, a documentação e o link da aplicação.
- Deixe comentários, caso tenha alguma dúvida.
- Implementações sem um README serão automaticamente rejeitadas.

## Bonus / Atividades Opcionais

- Código limpo
- Conhecimento do fluxo da aplicação
- Conhecimento das melhores práticas.
- Criar um endpoint para healthcheck 
   - para a rota `/healthcheck`
   - proponha quais seriam as informações essenciais em um healthcheck ou se não tem necessidade.
