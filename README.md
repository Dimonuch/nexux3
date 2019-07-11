# nexux3
Create and setup docker repository nexus3
1. Create structure directories and files as described above.
2. Need to change permission volume "chown -R 200 nexus/nexus-data"
3. In the current directory with file docker-compose.yml run command "docker-compose up -d"
4. Link to "https://your_site_nginx:8100" /*** password find "/nexus/nexus-data/admin.password" ***/
5. Create new user and disable user admin
6. Create "docker(hosted)" repository
5. Login to repository via command line "docker login address_your_repository"
