# Spring PetClinic 

## Running petclinic locally
```
	git clone https://github.com/harishchanderdalal/spring.git
	cd spring
        sudo ./mvnw clean package
        sudo java -jar  <path for .jar>
        sudo ln -s <path for .jar> /etc/init.d/<any name>
        sudo /etc/init.d/<any name> start
```

You can then access petclinic here: http://localhost:9000/

<img width="1042" alt="petclinic-screenshot" src="https://cloud.githubusercontent.com/assets/838318/19727082/2aee6d6c-9b8e-11e6-81fe-e889a5ddfded.png">
