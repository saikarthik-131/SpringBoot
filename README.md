# SpringBoot
## Inversion of Control with XML Configuration
### In Interface "Coach.java" contains abstract method getDailyWorkout();
### Create a concrete class "Baseball.java" whcih implements the abstarct method getDailyWorkout() from the Coach.java
## Note : we can create multiple concrete classes which implements the Coach.java interface
### "applicationContext.xml" contains the bean for which the implementation need to be get displayed 
### A bean is a simple java Object which contains the beanid where we can give the Interface object and class attribute where we can pass the fully qualified name of the class for which output has to be displayed
### HelloSpringApp.java contains 2steps primarily 
#### Step-1 Load the config file "applicationContext.xml"
#### Step-2 retrieve bean from spring container using "getBean" method which contains two atributes beanid and classname
