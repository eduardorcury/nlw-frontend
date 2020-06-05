# Frontend do web-app Ecoleta

> Repositório do Frontend da aplicação Ecoleta, que permite o cadastro de pontos de coleta de materiais recicláveis. Agradecimentos à equipe da Rocketseat, 
que promoveu a semana gratuita de desenvolvimento de software *Next Level Week*. Backend da aplicação disponível [aqui](https://github.com/eduardorcury/nlw-backend).

![npm](https://img.shields.io/npm/v/npm?style=flat-square)

![](https://github.com/eduardorcury/nlw-frontend/blob/master/screenshots/Ecoleta%20-%20home.png)

## Ferramentas utilizadas

- Biblioteca [React](https://github.com/facebook/react).
- [Typescript](https://github.com/Microsoft/TypeScript).
- Cliente HTTP [Axios](https://github.com/axios/axios) para consumo da API.
- Biblioteca open-source para criação de Mapas [Leaflet](https://github.com/Leaflet/Leaflet).
- Acesso a rotas com [React Router](https://github.com/ReactTraining/react-router).

## Funcionalidades

Cadastro de um ponto de coleta através de preenchimento de um formulário com os seguintes campos:
- Seleção de imagem com o auxílio da ferramenta [Dropzone](https://github.com/react-dropzone/react-dropzone).
- Campos de texto: Nome, email, whatsapp.
- Seleção de um ponto no mapa criado com [Leaflet](https://github.com/Leaflet/Leaflet).
- Seleção de cidade e estado com integração com a [API de localidades do IBGE](https://servicodados.ibge.gov.br/api/docs/localidades?versao=1).
- Seleção dos itens de coleta.

<p align="center">
  <img width="734" height="2107" src="https://github.com/eduardorcury/nlw-frontend/blob/master/screenshots/Ecoleta%20-%20Cadastro.png">
</p>

**O botão de cadastro do ponto faz uma requisção POST à [API](https://github.com/eduardorcury/nlw-backend) com o [Axios](https://github.com/axios/axios).**

## Como testar a aplicação

Para usar a aplicação, faça o download (ou clonagem) do projeto. Na pasta do projeto, abra um terminal e instale as dependências do projeto digitando:
```
npm install
```
Em seguida, execute a aplicação com:
```
npm start
```
*Nota: É necessário que você tenha o [Nodejs](https://nodejs.org/en/download/) instalado na sua máquina.*

Para obter as funcionalidades da API, siga os passos descritos no [repositório do Backend](https://github.com/eduardorcury/nlw-backend).

#### Meus profundos agradecimentos à [Rocketseat](https://rocketseat.com.br/):rocket: (em especial ao @github/diego3g) por proporcinar esse incrível projeto :laughing:
