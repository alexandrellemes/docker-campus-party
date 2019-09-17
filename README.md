# Instalação

Utilize os scripts: `install-docker-linuxmint.sh` e `install-docker-compose.sh`, para o Linux Mint.

ou

Baixe os scripts de instalação do docker: `https://github.com/docker/docker-install`.

Após a instalação, utilize o script `./run.sh` para criar o ambiente docker.

Para desmontar os volumes e apagar os containers, utilize o comando: `docker-compose down --volumes`.

Há dois scripts para o gerenciamento de volumes: `volume-backup.sh` e `volume-restore.sh`.

##Portas:
####8000 - Web
####8080 - PhpMyAdmin
####3306 - MySQL
####11211 - MemCached
####8081 - Portainer
####8001 - Joomla
####8002 - WordPress

A configuração de rede dos containers estão em modo bridge.
Daí poderão ser acessados via rede.

Divirtam-se!!!