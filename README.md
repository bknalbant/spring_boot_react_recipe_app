# Recipe App Backend 
<ul>
	<li>Spring Boot CRUD Application</li>
	<li>Spring Security</li>
	<li>Spring Rest</li>
	<li>Spring Boot CORS configuration </li>
	<li>Spring Boot CSRF configuration </li>
	<li>JUnit</li>
	<li>Swagger</li>
	<li>Slf4j</li>
</ul>

# Recipe App Frontend 
<ul>
	<li>React</li>
	<li>React Router</li>
	<li>React Redux</li>
	<li>Npm</li>
</ul>


# Requirements
<ul>
	<li>Maven 3+</li>
	<li>Java JDK 11</li>
	<li>Docker (Engine 18.06.0+)</li>
	<li>npm</li>
</ul>

# Getting Started

	1) You should enter the /backend folder and execute the below commands.
		a) mvn clean install
		b) docker build -t backend .
		
	2) You should enter the /frontend folder and execute the below command.
		a) docker build -t frontend.
		
	3) After all, you should go back to the parent folder /recipe_app project for composing docker.
		a) docker-compose up.
		You will be able to see the application is started on :
		http://localhost:3000/
		
	The system has defaulted a user to log in to the recipe application.
	You can use this user to log in to our system.

	username: demo
	password: 12345



