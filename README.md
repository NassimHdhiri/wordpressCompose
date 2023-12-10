# wordpressCompose
  ##note : before run docker-compose , must have "mon_reseau_docker" and "wordpress_data" and "mysql_data"
    ### create docker network "mon_reseau_docker"
      cmd ->>>> docker network create mon_reseau_docker
      
    ### create docker volumes "wordpress_data" "mysql_data"
      cmd ---> 
        docker volume create wordpress_data
        docker volume create mysql_data

    ### run docker-compose.yml
      cmd ->>> 
        docker-compose up -d
