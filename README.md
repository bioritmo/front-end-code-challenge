![Bio Ritmo / Smart Fit](biodevteam-2018.png)

# Teste de Front-end
Este teste é apresentado às pessoas que estão se candidatando às vagas de desenvolvimento Front-end para avaliar os quesitos técnicos. 

## Como enviar seu teste

* Faça um fork deste repositório
* Abra um Pull Request

### O Desafio

Seu objetivo é criar um app simples que deve conter ao menos duas páginas: uma que exiba um formulário com os campos abaixo, e outra que liste os dados cadastrados.

* Nome completo
* Username
* Email

### Pré-requisitos: 

- Deve ser possível criar, listar e excluir os dados cadastrados pelo formulário;
- Os inputs de texto devem ser validados;
- Fazer a persistência dos dados no `localStorage` ou `IndexedDB`;
- Você está livre para escolher qualquer framework/biblioteca

Para obter o estado inicial da lista de users utilizar este recurso abaixo:

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
 - Uso de pré-processador CSS;
 - Testes End to End;
 - Persistir no Firebase
 - Utilizar React + Redux|Mobx|Context Api
 - Webpack/Parcel

### O que esperamos:
 - Testes, no mínimo testes unitários;
 - Padrão de Projeto e boas práticas de Orientação a Objetos;
 - Utilizar ECMAScript 6+;
 - Criar uma documentação de como rodar sua aplicação 
 - Criar uma breve descrição da solução utilizada.
