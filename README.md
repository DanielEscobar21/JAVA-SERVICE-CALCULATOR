<div align="center">
  <h1>JAVA-SERVICE-CALCULATOR</h1>  
  <p>
    A api for a simple calculator made in JAVA.
  </p>
</div>

<!-- Getting Started -->
## Getting Started

<!-- Prerequisites -->
### Prerequisites

Apache Netbeans 14
https://netbeans.apache.org/

This project uses JDK 18
https://www.oracle.com/java/technologies/javase/jdk18-archive-downloads.html

Apache Tomcat 8.5.82
https://tomcat.apache.org/download-80.cgi

<!-- Run Locally -->
### Run Locally

Clone the project

```bash
  https://github.com/DanielEscobar21/JAVA-SERVICE-CALCULATOR.git
```

Go to the project directory

```bash
  cd JAVA-SERVICE-CALCULATOR
```

Add the Apache Tomcat server on the services part on Apache Netbeans

![image](https://user-images.githubusercontent.com/70600889/187322615-7fa43e68-cd58-40c7-994f-8f270b07decf.png)

For testing you can use the nexts paths on Postman
```bash
  http://your-host:8080/JAVA_SERVICE_CALCULATOR/service/operation/sum  --for Sum
  http://your-host:8080/JAVA_SERVICE_CALCULATOR/service/operation/subs  --for Sum
  http://your-host:8080/JAVA_SERVICE_CALCULATOR/service/operation/multiply  --for multiply
  http://your-host:8080/JAVA_SERVICE_CALCULATOR/service/operation/divide  --for Sum
```
And the next exaple for a json
```bash
{
    "number1": 123,
    "number2": 420
}
```

<!-- Contact -->
## Author

Daniel Escobar - danesc21@gmail.com
