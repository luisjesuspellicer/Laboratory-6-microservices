# Web Engineering 2015-2016 / Microservices

# Two microservices are running and registered
https://github.com/luisjesuspellicer/Laboratory-6-microservices/blob/master/Web3.png
https://github.com/luisjesuspellicer/Laboratory-6-microservices/blob/master/Web4.png

# Service registration service has the two microservices registered
https://github.com/luisjesuspellicer/Laboratory-6-microservices/blob/master/Web1.png

# Second account microservice is running in the port 4444 and it is registered
https://github.com/luisjesuspellicer/Laboratory-6-microservices/blob/master/Web2.png

# What happens when you kill the microservice with port 2222
When you kill the microservice with port 2222, all web requests to the microservice web wich require data from account microservice can´t get information in the first few seconds. But after a while, the registration service enables the web microservices can access the new  accounts microservice.
