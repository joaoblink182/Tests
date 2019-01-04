# Desafio de FrontEnd!

## Objetivo
Desenvolver uma página onde o usuário possa pesquisar disponibilidade de hotéis através de um critério e possa visualizar os resultados em uma lista **ordenada pelo hotel mais barato**, pelo desktop ou mobile. 

## Arquivos de ajuda
Está disponível na pasta **Data** um exemplo de **requisicao.json** e **resposta.json** que deve ser utilizado para efetuar a comunicação com a API.
Está disponível também os seguintes arquivos: 

 - **1003944_hotels_static_data.json** - Arquivo de conteúdo estático de detalhes de hotéis de MIAMI. 
 - **1010106_hotels_static_data.json** - Arquivo de conteúdo estático de detalhes de hotéis de Orlando.

Os arquivos acima, serão utéis para mostrar informações sobre o hotel, você conseguirá cruzar os dados através do ID do hotel que retorna na resposta da pesquisa e o ID do hotel contido no arquivo estático em cada nó de hotel.

## API
Utilize a nossa API REST para efetuar a pesquisa por disponibilidade de hotel, segue abaixo a URL e a credencial de acesso.

URL de Pesquisa: https://pp.cangooroo.net/ws/rest/hotel.svc/Search

Usuário: **candidato_t4w**  
Senha: **candit@!2019**

### Estrutura de campos da requisição:
|Nome do Campo| Descrição |
|--|--|
| Credential → Username | Usuário de acesso |
| Credential → Password	| Senha de acesso   |
| Criteria → DestinationId | Id da Cidade (Utilize os códigos **1003944** (MIAMI) ou **1010106** (ORLANDO) |
| Criteria → NumNights	| Quantidade de noites da estádia   |
| Criteria → CheckinDate | Data de Checkin no hotel (Formato: **YYYY-MM-DD**)  |
| Criteria → MainPaxCountryCodeNationality | Nacionalidade do passageiro (Deixar fixo **BR**) |
| Criteria → SearchRooms | Lista de Quartos a ser pesquisados |
| SearchRoom → NumAdults | Quantidade de adultos no quarto | 
| ChildAges | Lista de idades das crianças |
| Quantity | Quantidade de quartos |

Na **requisicao.json** o critério usado foi: 
 - Pesquisa em ORLANDO (1010106) - Duas noites - Data de checkin 10/01/2019 - 1 quarto com um adulto e uma criança de 5 anos.


# Critério de Avaliação
Para desenvolvedores FrontEnd, vamos avaliar os seguintes critérios:
 - Performance no carregamento da página - utilizando ferramentas específicas de performance e otimização;
 - Layout e responsividade do design; 
 - Legibilidade de código;
 - Documentação de código;
 

# Tecnologias utilizadas
Fica a critério do desenvolvedor escolher qual linguagem utilizará para desenvolver, desde que explique como executar e testar o projeto.

# Tempo de Desenvolvimento
O Desenvolvedor terá um tempo de **1 semana** para desenvolver o desafio este tempo contará a partir do momento que o link para o desafio foi enviado.
# Entrega
O Desenvolvedor poderá disponibilizar o código em seu próprio github ou enviar para o e-mail atila.santos@t4w.com.br o .zip do projeto.

**IMPORTANTE** : Não esquecer de enviar um arquivo explicando como executar/testar o projeto

# Dúvidas
Entrar em contato através do e-mail: **atila.santos@t4w.com.br**.
