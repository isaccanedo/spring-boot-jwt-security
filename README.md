# Spring Security usando JWT (Json Web Token) no Spring Boot

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

💡 Este projeto usa JWT para proteger os endpoints REST.

Este projeto usa JWT para proteger endpoints REST.
- `/token` - Gera o token JWT com base no JSON enviado. É um método POST que espera o JSON: `{ "username": "name", "id": 123, "role": "admin"}` 
- `/rest/hello` - Requires a JWT Token with Header `key - "Authorisation"` and `value - "Token <JWT_Token>"`
