# Olimpic Case 

![image](https://user-images.githubusercontent.com/104689597/196760913-afdd31e4-1c43-4b65-852c-20789952c868.png)

 # Olimpic Case

Esse Case foi um dos cases de avaliação para finalização do curso Web Full stack da Labenu, sendo uma api desenvolvida em Node JS com Typescript e programação em POO.

Documentação: https://documenter.getpostman.com/view/21555306/2s847LMBGM

## Entidades (TypeScript)

### Competitions (Competidores)

Representa os competidores da competição

- `id(string) é gerado pela própria aplicação`
- `competition_name(string)`
- `atleta(string)`
- `value(number)`
- `unidade(string)`

### Tabelas (MYSQL)

# Olimpic_Name_Comp

- `competition varchar(255) PRIMARY KEY`

# Olimpic_Competitor

- `id varchar(255) Primary Key`
- `competition_name varchar(255) NOT NULL`
- `foreign key (competition_name) REFERENCES Olimpic_Name_Comp(competition)`
- `atleta varchar(255) NOT NULL,`
- `value float not null,`
- `unidade varchar(255) not null`

# Olimpic_Status

 - `status varchar(255) NOT NULL default "incomplete",`
 - `competition_name varchar(255) NOT NULL,`
 - `foreign key (competition_name) REFERENCES Olimpic_Name_Comp(competition)`
 
## Instruções
 
 ### Instalando as dependências:
 
 `npm install`:
 Instale todas as dependências listadas no `package.json`


### Criando o arquivo .env:

Criar o arquivo `.env` e configurar com as informações de seu banco de dados.

```
DB_HOST = host
DB_USER = usuario
DB_PASSWORD = senha
DB_SCHEMA = nome-do-banco-de-dados
```

### Tecnologias utilizadas

-   NodeJS
-   TypeScript
-   MySQL
-   Knex
-   Express
-   Cors
-   UUID
-   Markdown

### Programas utilizados

-   Git
-   VSCode
-   WorkBanch Studio
-   Postman API Platform

### 🧑‍💻 Desenvolvedores:

</h2>
<table align="center">
  <tr>
    </td> <td align="center"><a href="https://github.com/LucasMagalhaesPacheco"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/104689597?v=4" width="100px;" alt=""/><br /><sub><b>Lucas Magalhães Pacheco</b></sub></a>
  </tr>
</table>

 [![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lucas-magalhaes-pacheco/)


