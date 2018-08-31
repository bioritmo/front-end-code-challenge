![Bio Ritmo / Smart Fit](biodevteam-2018.png)

# Teste de Front-end
Este teste é apresentado aos candidatos as vagas de desenvolvimento Front-end para avaliar os quesitos técnicos. **Faça um fork deste repositório.**

### O Desafio

Seu objetivo é criar um app simples que deve conter ao menos duas páginas, uma que exibe um formulário com os campos abaixo, e outra que liste os dados cadastrados.

* Nome completo
* Username
* Email

### Pré-requisitos: 
 - Deve ser possível criar, listar e excluir os dados cadastrados pelo formulário;
 - Os inputs de texto devem ser validados;
 - Fazer a persistência dos dados no `localStorage` ou `IndexedDB`;
 - Você está livre para escolher qualquer framework/biblioteca

Para ter o estado inicial da lista de usuário utilizar este recurso abaixo:

> GET https://jsonplaceholder.typicode.com/users	

Response:

```json

[
  {
    "id": 1,
    "name": "Leanne Graham",
    "username": "Bret",
    "email": "Sincere@april.biz",
    "address": {
      "street": "Kulas Light",
      "suite": "Apt. 556",
      "city": "Gwenborough",
      "zipcode": "92998-3874",
      "geo": {
        "lat": "-37.3159",
        "lng": "81.1496"
      }
    },
    "phone": "1-770-736-8031 x56442",
    "website": "hildegard.org",
    "company": {
      "name": "Romaguera-Crona",
      "catchPhrase": "Multi-layered client-server neural-net",
      "bs": "harness real-time e-markets"
    }
  }
  ...
]
```

A partir deste ponto utilizar o `localStorage/IndexedDB` para persistir localmente as informações.

### Plus:
 - A página ser responsiva;
 - Permitir edição;
 - Uso de pré-processador css;
 - Testes End to End;
 - Consistir no Firebase
 - Utilizar React + Redux|Mobx|Context Api
 - Webpack/Parcel

### O que esperamos:
 - Testes, no mínimo testes unitários;
 - Padrão de Projeto e boas práticas de Orientação a Objetos;
 - Utilizar ECMAScript 6+;
 - Criar uma documentação de como rodar sua aplicação 
 - Criar uma breve descrição da solução utilizada.
