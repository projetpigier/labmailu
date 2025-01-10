# labmailu
Pour installer un serveur MAILU simplement, suivez les instructions suivantes

sudo su
mkdir /mailu
cd /mailu
git clone https://github.com/projetpigier/labmailu.git
cd labmailu
docker compose up -d
# Test de Mailu
Connecter sur le port 80 avec
user: admin@magir.lan
Pass: pigierci
