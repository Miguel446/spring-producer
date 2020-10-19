# spring-producer

Java Spring project to produce messages to RabbitMQ
 - To send a message, start RabbitMQ on port 5672 (username and password = 'guest')
 - Start the spring boot project on port 8081
 - Send a post request to "/send" with a json body, example= {"text": "Your message"}
 - If anything goes wrong, the message is sent to the dead letter exchange
 - If it worked, you will see the message on your console
