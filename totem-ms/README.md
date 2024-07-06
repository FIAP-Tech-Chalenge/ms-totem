Para conseguir acessar os serviços da API, é necessário seguir os seguintes passos:

1. Ter o docker instalado na máquina
2. Ter o docker-compose instalado na máquina
3. Clonar o repositório
4. Acessar a pasta do projeto
5. Executar o comando `docker-compose up`
6. Acessar o endereço `http://localhost:8000/` para acessar a documentação da API do Kong
7. Acessar o endereço `http://localhost:1337/` para acessar o painel administrativo do Konga
8. Fazer o cadastro de um usuário no painel administrativo com seus dados
9. Preencher o campo `Name` com o Kong e o campo Kong Admin URL com `http://kong:8001`
10. Entrar no menu do Konga
11. Entrar na aba `SNAPSHOTS`
12. Fazer o upload do arquivo `totem.json` que está na raiz do projeto
13. Clicar em `IMPORT FROM FILE`
14. Selecionar o arquivo `totem.json` que foi feito o download
15. Clicar em `DETAILS`
16. Clicar em `RESTORE`
17. Selecionar a opção `services` e `routes`
18. Clicar em `IMPORT OBJECTS`
19. Acessar o endereço `http://localhost:8000/admin/swagger-ui/index.html#` para acessar a API de admin
20. Acessar o endereço `http://localhost:8000/cliente/swagger-ui/index.html#` para acessar a API de cliente
21. Acessar o endereço `http://localhost:8000/pedido/swagger-ui/index.html#` para acessar a API de pedido
