Step1 : Run docker-compose up in machine-1 to start rabbitMQ
Step2 : mvn clean install -DskipTests (eureka-server) in machine-1
Step3 : mvn clean install -DskipTests (configuration-service) in machine-1
Step4 : mvn clean install -DskipTests (CRUD) in machine-1
Step5 : mvn clean install -DskipTests (eureka-server) in machine-2                                
                
