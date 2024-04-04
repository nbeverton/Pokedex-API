########## Configuração de ambiente ##########

Biblioteca instalada:
- node -v (teste versão do node package manager)
- npm -v (versão do npm)
- http-server
    * npm install http-server (usei o global -g)
    * Só está funcionando com o comando npx http-server

- Normalize.CSS
    * npm install normalize.css
    * Usei o link refernciado. (no head do HTML)

Comando:
- http-server (vai rodar o servidor e criar um ip)

Fetch API:
- Foi utilizado a biblioteca Fetch API. Não precisa instalar nada pq já vem instalado e pronto para usar no navegador.

########## Teoria ##########

Foi criada uma integração com a API - Pokedex

Protocolo HTTP (cliente-servidor)
Composto por:
- URL: http://pokeapi.com/api/v2/pokemon?type=fire&name=c
nesse caso é por name query. Tudo qu evem depois da interrogação é pesquisa do tipo chave e valor.
- Rquest Method: GET | POST | PUT | DELETE
- Request Headers
    content-type: application/json
- Body:
    {
        "name": "test"
    }
- Staus Code: 100/500

Técnica Mobile First
- Ajustar para Pixel 5 / iPhone 12 Pro