![Microservice_structure](https://github.com/emregllce/K8S-phonebook-HELM/assets/93918344/093ca896-a75a-43ed-80fc-ab74caab9789)
![image](https://github.com/emregllce/K8S-phonebook-HELM/assets/93918344/6a7b49a8-2075-4e2a-970d-33a4fdef273d)


Phonebook Microservice Web Application aims to create a web application with MySQL Database using Docker and Kubernetes. 
In this application, we have a frontend service and a backend service to interact with database service. 
Each service will be managed by a Kubernetes deployment. 
The backend service will be a gateway for the application and it will serve the necessary web pages for create, 
delete and update operations while the frontend service will serve a search page in order to conduct read operations. 
To preserve the data in the database, persistent volume and persistent volume claim concepts should be adopted.
