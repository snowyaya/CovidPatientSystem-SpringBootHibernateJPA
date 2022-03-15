# CovidPatientSystem-SpringBootHibernateJPA
This project allows `admin`
- register new Covid patient information to the system
- delete the patient information from the system
- patient information is stored in a `PostgreSQL` database via `Hibernate`

### Structure
```
--- src
    |---main
    |     |---java
    |     |       |---Application.java
    |     |       |---com.covid.info
    |     |                 |---controller
    |     |                 |        |---HomeController
    |     |                 |        |---PersonController
    |     |                 |---domain
    |     |                 |        |---Person
    |     |                 |---repository
    |     |                 |        |---PersonRepository
    |     |                 |---service
    |     |                          |---PersonService
    |     |                          |---PersonServiceImplementation
    |     |---resources
    |          |---templates
    |                      |---addUser.html
    |                      |---home.html
    |                      |---patients.html
    |                      |---update.html
    |---test
         |---java
               |---PersonServiceUnitTest             
```

### How it works like - Demo
![covid-patient-system](https://user-images.githubusercontent.com/75382121/158299306-4f91d4b3-134d-4434-9d13-37e02adacf60.gif)
