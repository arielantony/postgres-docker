# Postgres Docker Image

> Use o repositório para baixar uma imagem diretamente do DockerHub contendo as modificações que autorizam todos os usuários e IPs a acessarem o banco local.

> Para rodar o container, é necessário o uso do comando `docker-compose` na pasta raiz da seguinte forma: `docker-compose up`.

> Caso você deseje acessar o container diretamente para utilizar a linha de comando fornecida pelo Postgres (psql) você pode utilizar o script `access_postgresql_container.sh`. Para isso, altere o campo que indica o nome da pasta local (a qual você clonou) e execute o comando. Após a execução, você estará dentro do container e poderá acessar o Postgres normalmente através da linha de comando.