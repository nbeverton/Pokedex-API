## Objetivo do Projeto

O objetivo principal deste projeto foi criar uma integração com uma API e consumir as informações disponibilizadas por ela.

# Configuração de Ambiente

## Bibliotecas Instaladas

- **Node.js e npm:**
  - `node -v` (para verificar a versão do Node Package Manager)
  - `npm -v` (para verificar a versão do npm)

- **http-server:**
  - Instalação global: `npm install -g http-server`
  - Utilização: `npx http-server`
  
- **Normalize.CSS:**
  - Instalação: `npm install normalize.css`
  - Utilização: Link referenciado no cabeçalho HTML.

## Comandos

- `http-server`: Inicia o servidor e cria um IP para acesso.

## Fetch API

Foi utilizado a biblioteca Fetch API. Não é necessário instalar nada, pois já vem pré-instalada e pronta para uso no navegador.

# Teoria

## Integração com a API - Pokedex

- **Protocolo HTTP (cliente-servidor):**
  - URL: `http://pokeapi.com/api/v2/pokemon?type=fire&name=c` (neste exemplo, é uma pesquisa por nome)
  - Métodos de Requisição: GET | POST | PUT | DELETE
  - Headers de Requisição:
    - `content-type: application/json`
  - Corpo da Requisição:
    ```json
    {
        "name": "test"
    }
    ```
  - Códigos de Status: 100-500

## Técnica Mobile First

É importante ajustar o layout para dispositivos móveis, como Pixel 5 ou iPhone 12 Pro.
