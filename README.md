# WordpressAndMysqlDB
Docker compose wordpress and mysql database


## Como rodar a aplicação
### Crie um .env e ajuste as variaveis como no .env.example

### wordpress image version
WP_TAG=latest
### mysql image version
MYSQL_TAG=5.7
### database user
DB_USER=wpusr
### database password
DB_PASSWORD=wppwd
### database user root password
DB_ROOT_PASSWORD=wproot
### database name
DB_DATABASE=wordpress


#### Na raiz do projeto rode:
docker-compose up -d

### Endereços e portas

<table>
  <tr>
      <td>Aplicacao</td>
      <td>Portas</td>
  </tr>
  <tr>
      <td>Wordpress</td>
      <td>localhost:8080</td>
  </tr>
   <tr>
      <td>Mysql</td>
      <td>127.0.0.1:3306</td>
  </tr>
</table>
