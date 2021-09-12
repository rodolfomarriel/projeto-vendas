# Projeto Dashboard de Vendas

Projeto Fullstack usando Java Springbott no backend e React no frontend.

Backend disponivel no Heroku [https://sharp-liskov-c50279.netlify.app/](https://sharp-liskov-c50279.netlify.app/)

Frontend disponivel no Netlify [https://sharp-liskov-c50279.netlify.app/](https://sharp-liskov-c50279.netlify.app/)

## Banco de dados local

Foi usada a imagem
```docker run -d --name postgresql_generico -e POSTGRESQL_PASSWORD=1234567 -e POSTGRESQL_USERNAME=postgres -e POSTGRESQL_DATABASE=postgres -p 5432:5432 bitnami/postgresql:latest```

Dentro do projeto backend existe um arquivo create.sql com os scripts para insercao e criacao das informacoes no banco de dados