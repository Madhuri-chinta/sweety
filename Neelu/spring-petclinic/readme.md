HOW TO INSTALL SPRING-PETCLINIC ON UBUNTU:
------------------------------------------
* Manual steps:
  -------------
```
sudo apt update
sudo apt install -y openjdk-17-jdk
java --version
sudo apt install maven
mvn --version
git clone https://github.com/spring-projects/spring-petclinic.git
cd spring-petclinic
./mvnw package
java -jar target/*.jar

```
* process:
  --------
  * firstly created one ec2 instance and login to the machine through power shell
  * next execute the commands one by one
  ![preview](images.png/sp1.png)
  ![preview](images.png/sp2.png)
  ![preview](images.png/sp3.png)
  ![preview](images.png/sp4.png)
  ![preview](images.png/sp5.png)
  ![preview](images.png/sp6.png)
  ![preview](images.png/sp7.png)
  ![preview](images.png/sp8.png)
  ![preview](images.png/sp9.png)
  * goto browser give the publicip:application port number hit enter and opened our springpetclinic application
  ![preview](images.png/sp10.png)
  
  
  