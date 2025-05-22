# tp4
Le tp4 de docker
# Projet Docker : Déploiement de Odoo avec PostgreSQL et pgAdmin

Ce projet utilise Docker Compose pour déployer Odoo 18, PostgreSQL 16, et pgAdmin 4.

## Contenu
- `docker-compose.yml` : Configuration des services.
- `commands.txt` : Historique des commandes utilisées.
- `screenshot.png` : Capture d’écran de l’application Odoo.

## Instructions
1. Assurez-vous que Docker et Docker Compose sont installés.
2. Clonez ce dépôt :
git clone https://github.com/bengo2024/tp4.git
cd  

3.Lancez les services :
docker-compose up -d
5. Accédez aux services :
- Odoo : `http://localhost:8069`
- pgAdmin : `http://localhost:8080` (identifiants : `admin@admin.com` / `admin_password`)

## Liens
- Image sur Docker Hub : 
