# jussi_ruby_on_rails_challenge
Construção de API de heróis da Marvel

Você deverá criar uma conta no site "https://developer.marvel.com" e gerar uma api key para consumo desta. Feito isso, construa uma estrutura de api utilizando Ruby on Rails que deverá ter endpoints que listarão os personagens, e outro endpoint que exibirá os detalhes desse personagem com as HQ's que os mesmos pertençam. Lembre-se de persistir esses dados em banco e construir os devidos relacionamentos.

# Estrutura do banco
Personagem: deverá ter ao menos o id marvel, nome, imagem e "modificado em" (todos disponibilizados na api externa)
Quadrinho: título, número da capa e imagem (todos disponibilizados na api externa)

Será interessante dispor de endpoints de um CRUD para sua própria API. Todos os requests deverão ter o mínimo de segurança aceitável por parte da API.

Não utilize nenhuma gem externa para a construção da API e é importante utilizar o Rails a partir da versão 3 ou 4 (5 é um diferencial).

Como fator diferencial, pedimos para espetar essa API no Elasticsearch e utilize a gem oficial do Elasticsearch:
* 'elasticsearch-model', git: 'git://github.com/elasticsearch/elasticsearch-rails.git'
* 'elasticsearch-rails', git: 'git://github.com/elasticsearch/elasticsearch-rails.git'

Para esse caso, ao menos disponibilize o endpoint de listagem no Elasticsearch.

# Exigências:
- Rails 3, 4 ou 5
- Ruby a partir do 2.2.2
- Elasticsearch
- Sidekiq
- API REST (JSON)
- Documentação explicando como subir o projeto em desenvolvimento, e o funcionamento de seu sistema assim como execução dos testes

É permitido a utilização de qualquer banco relacional que esteja habituado em ambiente de desenvolvimento, entretanto, é necessária a utilização do Postgres em produção.

Pedimos que abra o pull request para o repositório assim que o teste for finalizado.

# Diferencial:
- Sidekiq para eventualmente gerenciar jobs assíncronos
- Disponibilizar um link para a aplicaço hospedada no Heroku
- Habilitar algum tipo de busca no elasticsearch

Lembre-se que seu código será avaliado tanto em funcionalidade quanto em estética (clean code sempre).

Uma boa cobertura de testes será avaliada. Utilize o framework/gem de sua preferência.

Boa Sorte!
