Lista de comandos:
yarn sequelize migration:create --name=create-users
Esta função serve para criar uma nova migration e então definir nela a estrutura do banco

yarn sequelize db:migrate
Esta função serve para rodar as migrations e atualizar a estrutura do banco de dados

yarn sequelize db:migrate:undo
Esta função desfaz a última migration caso você tenha feito alguma migration errada

yarn sequelize db:migrate:undo:all
Esta função desfaz todas as migrations
