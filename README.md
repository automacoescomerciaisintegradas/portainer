
## ⚠️ Pré-requisitos

Você deve criar 3 dominios do tipo 'A' na Cloudflare
*Status do Proxy deve esta desligado

<p>portainer</p>
<p>www.portainer</p>
<p>traefik</p>
<p>www.traefik</p>
<p>edge</p>
<p>www.edge</p>



## 💽 Instalação

Opção 1 - Comando em uma linha (Recomendado)

git clone https://github.com/automacoescomerciaisintegradas/portainer.git

# 1. Baixar o script de instalação

curl -fsSL https://github.com/automacoescomerciaisintegradas/portainer install.sh > install.sh

permiçoes do script de instalaçao:
sudo chmod +x install.sh
chmod +x install.sh


# 2. Executar o script com privilégios de root
permiçoes do script de instalaçao:
sudo chmod +x install.sh
sudo bash install.sh

# 3. Entrar na pasta portainer e digitar:

- Para iniciar os serviços, use o seguinte comando:

./install.sh

Após a instaçao portainer está em modo  "standalone" 

para mudar para modo swarm

docker swarm init --advertise-addr= SEU IP

## Corra !!!! pra Acessar sua stack via brosser !!!! 
Caso  instância do Portainer expire.

Abra o terminal e rode os seguintes comandos:

<p>cd Portainer

<p>docker compose down --remove-orphans
<p>docker compose pull portainer
<p>docker compose up -d

> 🚀 Bem-vindo a Automaçoes Comerciais Integradas 


        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||



