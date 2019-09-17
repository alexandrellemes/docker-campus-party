# Instalação

Utilize os scripts: `install-docker-linuxmint.sh` e `install-docker-compose.sh`, para o Linux Mint.

ou

Baixe os scripts de instalação do docker: `https://github.com/docker/docker-install`.

Após a instalação, utilize o script `./run.sh` para criar o ambiente docker.

Para desmontar os volumes e apagar os containers, utilize o comando: `docker-compose down --volumes`.

Há dois scripts para o gerenciamento de volumes: `volume-backup.sh` e `volume-restore.sh`.

Configuração das portas dos containers:

|------------|-------|
| Server     | Port  |
|------------|-------|
| MySQL      | 3306  |
| PHPMyAdmin | 8080  |
| Nginx      | 8000  |
| Nginx SSL  | 3000  |
| Memcached  | 11211 |
| Portainer  | 8081  |
| Joomla     | 8001  |
| WordPress  | 8002  |
|------------|-------|


A configuração de rede dos containers estão em modo bridge.
Daí poderão ser acessados via rede.

Divirtam-se!!!