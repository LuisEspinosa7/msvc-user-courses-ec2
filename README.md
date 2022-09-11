# Courses Users - EXAMPLE MICROSERVICES AWS ECS (BACKEND)

Courses Users are microservices for creating courses and add user to them. It's quite useful to play around with different architectures and technologies. They comunicate to each other by using feign client and are over AWS Elastic Container Service in this specific approach (repository and branch), you may find different deployment options on the other repositories in my github. This WEB APP's backend was developed by Luis Espinosa Llanos using a microservice approach and the following technologies and tools were used: 

<table style="width:100%">
  <tr>
    <td>
  	Core	
    </td>
    <td>
  	Java 11, Spring Boot 2, Data JPA, Hibernate, Loombok, Jackson Databinding, Feign client.
    </td>
  </tr>
  <tr>
    <td>
  	Databases
    </td>
    <td>
  	PostgreSQL 14, MySQL.
    </td>
  </tr>
  <tr>
    <td>
  	Service discovery	
    </td>
    <td>
  	Just DNS or docker name
    </td>
  </tr>
  <tr>
    <td>
  	Virtualization
    </td>
    <td>
  	Docker, docker-compose
    </td>
  </tr>
  <tr>
    <td>
  	Server	
    </td>
    <td>
  	Apache Tomcat Embebido (Spring Boot)
    </td>
  </tr>
  <tr>
    <td>
  	IDE	
    </td>
    <td>
  	Intellij IDE
    </td>
  </tr>
  <tr>
    <td>
  	Executable	
    </td>
    <td>
  	Jar
    </td>
  </tr>
  <tr>
    <td>
  	Cloud Provider	
    </td>
    <td>
  	Amazon Web Services (Elastic Container Service cluster)
    </td>
  </tr>
</table>

It was written using the best practices for instance, a controller, service and repository layer approach, code reusing, 
dependecy injection, inversion of control, abstractions, design patterns and more... 

## Video
A video exposing the functionality of the proyect in local environment as well as on AWS on a Desktop screen.

1. https://youtu.be/i33K4pKVkOE


## EC2 implementation on AWS
You will find the EC2 deployment implementation on the branch: 
- <b> master </b>

## Development Resources
I provide the following resources:

<table style="width:100%">
  <tr>
    <td>
  	Resources
    </td>
    <td>
	The UPDATED RESOURCES are in the documentation folder 
    </td>
  </tr>
</table>






## Pictures
Some pictures of the project:

<table style="width:100%">
  <tr>
    <td>
  		<img width="450" alt="Image" src="https://user-images.githubusercontent.com/56041525/189510734-b60f74b9-2b02-421a-837e-4a540e79c596.PNG">
	  </td>
    <td>
  	<img width="450" alt="Image" src="https://user-images.githubusercontent.com/56041525/189510741-9c6a7584-dd17-4554-ac55-b5dae8ebb1c8.PNG">
    </td>
  </tr>
</table>




<table style="width:100%">
  <tr>
    <td>
  		<img width="450" alt="Image" src="https://user-images.githubusercontent.com/56041525/189510753-61e43f94-c54d-49b8-8938-0b785b201196.PNG">
	  </td>
    <td>
	<img width="450" alt="Image" src="https://user-images.githubusercontent.com/56041525/189510762-f1d6ad88-796f-4f3b-a4eb-ad6b6fe53570.PNG">
    </td>
  </tr>
</table>


![6]()


<table style="width:100%">
  <tr>
    <td>
  		<img width="450" alt="Image" src="https://user-images.githubusercontent.com/56041525/189510779-6fe8723b-83b7-4234-b59b-522269e50a7b.PNG">
	  </td>
    <td>
	<img width="450" alt="Image" src="https://user-images.githubusercontent.com/56041525/189510782-01a0cc6b-62fe-428d-af23-63a8787948ec.PNG">
    </td>
  </tr>
</table>


<table style="width:100%">
  <tr>
    <td>
  		<img width="450" alt="Image" src="https://user-images.githubusercontent.com/56041525/189510784-1fb7d65c-a9e9-41b8-90ec-c680577978d3.PNG">
	  </td>
    <td>
	<img width="450" alt="Image" src="https://user-images.githubusercontent.com/56041525/189510789-77061fb6-5134-42ef-8f3d-ad9bfa2b101b.PNG">
    </td>
  </tr>
</table>



## Installation

This proyect should be installed using the following command on the base project's folder:
```bash
docker-compose up -d
OR DEPLOY IT on Elastic Container Service
```

## Usage
The recommendation by now is to import it in your favority IDE. And run the project the way I did.


## Contributing
This proyect is quite simple, and is part of my personal portfolio, so it is not intended to receive contributions.
