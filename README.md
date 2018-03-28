# Dockerize Jira Service Desk Server v3.11.1
https://www.atlassian.com/software/jira/service-desk/update

#start container run in background
cd jira_docker/
docker-compose up -d
navigate to: http://localhost:8080 and set up the JIRA


docker-compose down
docker-compose rm

docker volumes ls
docker volumes inspect jiradocker_mysql
