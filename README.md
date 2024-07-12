# VAAlugar-Docker-Compose
Repositório do Projeto VAAlugar para abrigar o Docker-Compose

# Passo a Passo para construção do docker-compose:
1. Clone este repositório git para algum diretório em sua máquina.
2. Agora clone os repositórios dos microsserviços, usando os comandos a seguir no terminal
git clone https://github.com/fabioFernandesBR/VAAlugar-MS-gateway.git
git clone https://github.com/fabioFernandesBR/VAAlugar-MS-gerir_canoas_2.git
git clone https://github.com/fabioFernandesBR/VAAlugar-MS-reservar.git
git clone https://github.com/fabioFernandesBR/VAAlugar-MS-avaliacoes.git

3. Executar os seguintes comandos:
docker-compose build
docker-compose up

4. Os 4 microsserviços já devem estar em execução no Docker Desktop. Lá você pode chamar cada um deles.
