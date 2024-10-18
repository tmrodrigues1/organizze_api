# Introdução
Este repositório reúne scripts que criei para extrair informações dos meus gastos financeiros que estão concentrados no aplicativo [Organizze](https://www.organizze.com.br/). Os dados extraídos são salvos em arquivos CSV, facilitando a criação de Dashboards e análises mais apuradas.

# Organizze API
Entendo um pouco sobre a API do Organizze:

A autenticação de todas request é via Http Basic com o Username e Password descritos abaixo:
- Username: Email da conta do Organizze
- Password: Token de acesso (Clique aqui para criar sua [API KEY](https://app.organizze.com.br/configuracoes/api-keys))

Todas as requisições são criptografadas, o Organizze não aceita requisições feitas com HTTP simples, apenas HTTPS.
A URL base da API é https://api.organizze.com.br/rest/v2

Exemplo abaixo:
```
username: thiago@gmail.com
password: h12flkjfmaljfssj42842uj2480795a877as7798fsa77987
```

(Em construção)
