# spring-vs-springboot
Created this repository to document differences between spring and spring boot.


# Dependency resolution
In spring we used to have issue with respect to compatibilities of dependencies.
But in Spring boot spring-boot-starter-parent takes care of dependency versions.



# Minimum configuration
Spring with hibernate scenario:
Enable data source,session factory,transaction,component scan etc have to configured in configuration file.
With Spring boot:
Properties files(database related) and Annotations.



# Embedded server
To be added...



#  Bean auto scan.
In case of Spring:
we have configure component scan in configuration file.
With spring boot:
Just follow package structure.



#  Health metrics
With  spring:
We have to use third party libraries for analysing memory usage,Heap dump etc.
With spring boot:
It provides actuator for the same.





