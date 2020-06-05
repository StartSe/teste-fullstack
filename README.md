# Teste fullstack

Leia primeiro todo o projeto, faça sua estimativa de horas para o desenvolvimento e envie um email com o título `[Teste Fullstack] Estimativa` para thiago.barcelos@startse.com

Quando finalizar o teste, publique tudo no seu [Github](https://github.com) e envie um email com o link do repositorio para thiago.barcelos@startse.com

## Missão backend

Desenvolver uma **API JSON RESTful** em **Node**, que utilize todos os métodos (`GET`, `POST`, `PUT`, `PATCH`, `DELETE`).  
Faça o teste unitário da **API** (Bônus :star:)

### Especificação

Monte uma base de cursos com a seguinte estrutura:

```
title:       string
subtitle:    string
startedAt:   datetime
description: text
isActive:    bool
created:     datetime
updated:     datetime
```

Utilize **MongoDB** ou **MySQL** para armazenar os dados que a **API** irá consumir.

### API endpoints

`GET /courses`

Retorna todos os cursos

---

`GET /courses/find`

Retorna os cursos de acordo com o termo passado parâmetro `q`

---

`GET /courses/{id}`

Retorna os detalhes do curso

---

`POST /courses`

Adiciona um novo curso

---

`PUT /courses/{id}`

Atualiza os dados de um curso

---

`PATCH /courses/{id}`

Atualiza apenas alguns dados do curso

---

`DELETE /courses/{id}`

Apaga o curso


## Missão frontend

Desenvolver uma **UI (User Interface)** em **ReactJS** utilizando a sua criatividade, deve conter no minimo:

- tela de listagem/busca
- tela de edição/novo

### Especificação

- Cross browser support (IE11+)
- Consumir **API** criada acima
- Criar uma tela que tenha...
    - Listagem de cursos
    - Detalhe do curso
    - Busca
    - Formulário de novo/edição de curso
    - Deletar curso

### Dica

Utilize algum framework para auxiliar no desenvolvimento da interface, por exemplo:

- https://getmdl.io/
- https://material-ui.com/
- http://getbootstrap.com/

## Dúvida

Se tiver qualquer dúvida sobre esse teste, envie um email com o título `[Teste Fullstack] O assunto que vc deseja` para thiago.barcelos@startse.com
