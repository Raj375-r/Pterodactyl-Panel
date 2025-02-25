# Pterodactyl-Panel
For Install Panel
use this commands
1. git clone https://github.com/YoshiWalsh/docker-pterodactyl-panel
2. cd docker-pterodactyl-panel
3. docker-compose up -d
4. docker ps
5. docker-pterodactyl-panel_php-fpm_1
dont focus on the error doesn't matter
for create admin account
6. docker exec -it docker-pterodactyl-panel_php-fpm_1 php artisan p:user:make
and done ✅ 
