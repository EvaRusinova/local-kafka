 local-utils
================================

**Overview**
These docker-compose files are related to:
 - Kafka
 - MongoDB
 - PostgreSQL
 - RabbitMQ

Each of these docker-compose-xxx.yaml file provides a base UI that can be accessed on the following URLs:
  - Kafka: http://localhost:8585/
  - MongoDB: http://localhost:8081/
  - PostgreSQL: http://localhost:8080/login?next=%2F
  - RabbitMQ: http://localhost:15672/#/
  

The credentials to log in with can be found in the xxx.yaml file itself and changed from there.

**Getting Started**

1. Install Docker
2. Clone the repository to your local machine.
3. Run the necessary command(s) in the terminal.

-  To run Kafka, use the command:
    ` docker-compose -f docker-compose-kafka.yml up -d --build ` 

-  To run MongoDB, use the command:
    ` docker-compose -f docker-compose-mongo.yml up -d --build `
-  To run PostgreSQL, use the command:
    ` docker-compose -f docker-compose-postgres.yml up -d --build ` 

-  To run RabbitMG, use the command:
    ` docker-compose -f docker-compose-rabbit.yml up -d --build ` 

-  To run all utils at once, use the command:
    ` docker-compose -f docker-compose-kafka.yml -f docker-compose-mongo.yml -f docker-compose-postgres.yml -f docker-compose-rabbit.yml up -d `
   
**IMPORTANT**
These are purely base examples that may need additional configurations for production use.


**License**
This project can be freely used :) 
