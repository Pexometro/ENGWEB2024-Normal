
#1.1 Setup
- comecei por usar um conversor online para conveter csv para json
- troquei o id das entradas para _id 
- depois corri o script script.py para criar um docker-compose com mongodb e as coleções
    - este script cria um container com mongoDB e outro container para o serviço a desenvolver
    - fornecidos o nome do dataset, da coleção e o ficheiro do import, o script automaticamente cria, com mongoimport, a coleção (no ficheiro dado) para o container do serviço

- ao acrescentar as entradas ao container com o script, verifiquei que deu o output "36377 document(s) imported successfully", logo foram importadas as entradas corretamente

 as queries corridas estao no ficheiro queries.txt

#1.3 API
Nesta pergunta

 "GET /contratos?entidade=EEEE:"

 utilizei o nome da entidade como nipc


#2 Interface
Para satisfazer no endereço "http://localhost:16001/entidades/:nipc" o requesito "somatório do valor dos contratos", inclui uma nova rota na API: "http://localhost:16000/contratos/entidadeTotal/:idEntidade", que chamo no serviço de interface