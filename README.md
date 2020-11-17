# ARAMO - FALEMAIS

## Tecnologias utilizadas:
* JavaScript
* Node.js
* Vue.js
* Express
* MongoDB
* Quasar
* Stylus

### Resumo do projeto:
  Para o client foi contruido um SPA(Single Page Application) utilizando o framework JS Vue.js e Quasar. O client faz requisições à API, na qual foi desenvolvida com Node.js, como busca das regiões e calculo dos preços dos planos. Todas as informações são inseridas no banco de dados MongoDB uma unica vez ao rodar a API através dos seeds defenidos dentro do diretório database/seeds/data.js no repositório aramo-api.
 
### Como rodar o projeto:
  Todo este trabalho ja foi feito!  
  Deploy do client e da API foi realizado no Heroku (https://www.heroku.com/platform).  
  O banco de dados está sendo utilizado em nuvem (https://www.mongodb.com/cloud)  
  #OBS: CASO AS REGIÕES NÃO CARREGUEM NO PRIMEIRO ACESSO ATUALIZE  A PÁGINA;
  PELO FATO DO CLOUD SER GRATUITO A APLICAÇÂO FICA DESATIVADO, QUANDO NÂO HÁ ACESSO, E ACABA TENDO PROBLEMA DE CONEXÃO COM A API.  
  API: https://aramo-api.herokuapp.com/  
  CLIENT: https://falemais-client.herokuapp.com/  
  
### Clonando o projeto 
```
//clonando o repositório e os sub-repositórios
git clone --recursive https://github.com/arthur9010/aramo-workspace

//entrando no projeto
cd ./aramo-workspace

//mudando para a branch master
cd ./aramo-api && git checkout master  
cd ./falemais-client && git checkout master
```
## Endpoints da API que foram utilizados
GET: https://aramo-api.herokuapp.com/api/region   
GET: https://aramo-api.herokuapp.com/api/plan/calculate?origin=DDD&destination=DDD&time=minutes


