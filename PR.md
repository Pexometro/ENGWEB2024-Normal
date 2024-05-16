# Teste 2024

## Autor : Pedro Azevedo
## Número : A100557


## EX1

Incialmente fiz os seguintes passos:

1. Converter para json usando https://csvjson.com/csv2json
2. Criar um arquivo `dataset.json` com o conteúdo do json
3. Trocar o nome do campo do identificador para `_id`
4. Correr o script python `convert_dataset.py` para resolver formato do preço em caso de decimal.
4. Executar o container que já conta com o mongo import


onde obtive

```bash
mongo-seed-1  | 2024-05-16T13:12:24.299+0000    36377 document(s) imported successfully. 0 document(s) failed to import.
```

Para a seguinte pergunta 

`GET /contratos?entidade=EEEE`

foi escolhido o NIPC.

## EX2

Basta `http://localhost:16001` para aparecer a 2 parte do enunciado.

é também possível ver todos os campos do contrato e volta a pagina incial clicando no logo.

