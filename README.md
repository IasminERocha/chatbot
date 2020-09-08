# Chatbot - Olist

Segue o JSON e o CSV do Chatbot criado, para testar acesse https://www.facebook.com/Olist-Teste-103883128126835/ 

### Objetivo

O Chatbot da Olist foi criado com o intuito de atender o máximo de cliente em menos tempo, será possível realizar vendas e até mesmo dar suporte para futuros e atuais clientes. Para isso criamos uma inteligência artificial, que treinada é capaz de entender e responder a qualquer dúvida dos usuários, deixand assim o bot cada vez mais humazinado.
 ### Organização

 - Fluxo terá que ser criado na horizontal
 - Criar fluxos por ordem cronologica, sendo que tudo que for sucesso segue a linha do inicio (Meio), tudo que for
 API estará na parte superior, e tudo que for erro na parte inferior.
 - Utilizar padrao camelCase
 - Criação de váriaveis e nomes das caixas em Ingles.


 ### Personalização das tags

 - ASK (Verde) - Caixa que espera a resposta do usuário
 - API (Azul escuro) - Caixas onde realizam uma chamada para o backend
 - ERROR - 400 (Vermelho) - Caixas onde exibe mensagem de erro do status 400
 - ERROR - 500 (Laranja claro) - Incluir nas caixas que exibem um texto onde o status da API for 500
 - SCRIPT (Rosa escuro) - Incluir em todas as caixas que possuírem um script
 - REDIRECT - SERVICE (Roxo) - Incluir nas caixas que fazem um redirecionamento para um serviço


 ### script

 - Utilizar try catch em todos os scripts


# Variaveis

- Colocar JS no final das váriaveis que tem um retorno de uma script.
- Manter o titulo das ações, acrescentando o nome posteriormente. Ex.: REQUISIÇÃO HTTP - BATATA
- Para URLs e tokens incluir nas variaveis de configuração.
- Criar variaveis de contato extra somente nos bots de ATH e se for exibir para o atendente.