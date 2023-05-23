* To build your project and run test cases use command:
	mvn clean package

* To launch your application, move into the target folder (cd target). Run the following command to run the application:

	java -jar online-auction-system-0.0.1-SNAPSHOT.jar

* Default credentials for MySQL:
	Username: root
	Password: pass@word1

* To login to mysql instance: Open new terminal and use following command:
      a.	sudo systemctl enable mysql
      b.	sudo systemctl start mysql
      c.	mysql -u root -p
The last command will ask for password which is ‘pass@word1’

* Mandatory: Before final submission run the following command: 
	mvn test

