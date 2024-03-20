# Food Tech Challenge FIAP
## Relational Database Service (Amazon RDS)
Este repositório é responsável por criar toda a infraestrutura do nosso banco de dados com TerraForm dentro da nuvem da AWS utilizando o serviço RDS, assim a aplicação Food Tech Challenge utilizará esse banco de dados..

## Escolha do banco
O Amazon RDS possibilita a execução do banco de dados relacional totalmente gerenciado e com todos os recursos, ao mesmo tempo em que reduz o trabalho de administração do banco de dados.
Escolhemos um banco de dados relacional devido a:
- Flexibilidade no armazenamento e recuperação de dados;
- Facilidade de manipulação dos dados
- Novas estruturas podem ser criadas sem afetar as existentes;
- Alto desempenho em buscas utilizando consultas de dados.

## Escolha da linguagem Utilizada / MySql
Há possibilidade de utilização em várias linguagens de programação;
Independentemente da quantidade de dados e números de consultas no sistema, o desempenho do MySQL é alto e eficiente;
O MySQL tem alta estabilidade, disponibilidade e confiabilidade no seu armazenamento e no gerenciamento dos dados inseridos no banco;

## MER
![MER](https://github.com/Tech-Challenge-FIAP-GLR/rds_techchallenge/assets/31673865/df3d68f5-c2a9-4bb6-ba23-eb978785fee6)

## Atualizando o RDS
Sempre que realizar uma atualização do código, deve-se criar um pull-request da branch utilizada para a branch "main", assim que realizar o merge, o github actions fará toda a atualizanção para a AWS.

## Requirements
* AWS account
* Configure aws access keys vars from Security Credentials:
  * export AWS_ACCESS_KEY_ID=[your-key-id]
  * export AWS_SECRET_ACCESS_KEY=[your-key-secret]
