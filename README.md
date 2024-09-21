# dio_docker-compose
![website picture](/Images/image1.jpg)

:point_right:[**Visite o website do projeto**](http://18.208.175.63/)<br />

## Começando

- Crie uma instância EC2 do Linux Ubuntu 22.04 na AWS, habilitando os protocolos SSH e HTTP.
- Acesse a instância EC2. Você pode fazer o acesso via "putty.exe" no windows ou via linux.
- Vá para a pasta "/root" e crie uma subpasta com um nome de sua escolha. Copie para esta pasta o arquivo "compose.yml".
- Dentro da nova pasta crie outra subpasta com o nome "website"; copie para essa pasta o arquivo "index.html" ou crie na mesma um arquivo "index.html" de sua preferência.
- Volte para a primeira pasta que você criou e instale o Docker Compose ($ apt install docker_compose).
- Suba o Docker Compose com o comando "$ docker-compose up -d". Para verificar se o container está rodando, use o comando "docker container ls".
- Acesse a sua aplicação web através do endereço público disponibilizado na página da sua estância EC2 no site da AWS.
- Bom trabalho!!
