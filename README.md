# Dockerize Jira Service Desk Server v3.11.1
https://www.atlassian.com/software/jira/service-desk/update

# install docker, docker-compose
# cd jira_docker/
# docker-compose up -d
navigate to: http://localhost:8080 and set up the JIRA

# docker-compose down
# docker-compose rm

- inspect the mysql volumes mapping
# docker volumes ls
# docker volumes inspect jiradocker_mysql
