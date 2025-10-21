# jenkins
Jenkins Practice
after cloning this repo we need to create folder in present working directory as jenkis_home
then we need to set permission as below
Fix permissions on the host directory(Run this in your host machine (in the same folder as your docker-compose.yml)
chown -R 1000:1000 jenkins_home
chmod -R 775 jenkins_home
1000:1000 = user and group ID Jenkins uses inside container.
chmod 775 allows owner and group write access
