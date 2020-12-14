# mysql-container
### Documentação de construção de container oracle database:
https://www.oracle.com/br/technical-resources/articles/database-performance/oracle-db12-2-no-docker.html

Fazer o download da versão _LINUX.X64_193000_db_home_ no site da oracle e jogar na pasta _19.3.0_ deste projeto: https://www.oracle.com/webapps/redirect/signon?nexturl=https://download.oracle.com/otn/linux/oracle19c/190000/LINUX.X64_193000_db_home.zip

Executar o comando para buildar a imagem conforme a documentação da oracle:

    ./buildDockerImage.sh -v 19.3.0 -e

Após o download jogar o _LINUX.X64_193000_db_home.zip_ na pasta 19.3.0 e executado comando para subir o container:

    docker-compose up 
