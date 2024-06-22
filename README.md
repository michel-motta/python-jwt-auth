# JWT Authentication em Python com FastAPI

Este repositório demonstra como implementar autenticação JWT (JSON Web Token) em uma aplicação Python usando FastAPI.

## Visão Geral

JWT (JSON Web Tokens) são uma forma compacta e segura de representar informações entre duas partes. São amplamente usados para autenticação e autorização em aplicações web.

## Tecnologias Utilizadas

- Python 3.x
- FastAPI (para a API web)
- PyJWT (biblioteca para manipulação de tokens JWT)
- Pydantic (para validação de dados)
- Uvicorn (para o servidor ASGI)

## Estrutura do Projeto

```plaintext
.
├── app
│   ├── auth.py
│   │    ├── __init__.py
│   │    ├── auth_bearer.py
│   │    └─- auth_handler.py
│   ├── __init__.py
│   ├── api.py
│   └─- model.py
├── .env
├── main.py
└── README.md
