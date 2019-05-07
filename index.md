## Synopsys Cloud Operations Coding Exercise
An exercise for Cloud Operations candidates.

### Goals
The goals of the exercise are the following:

1. Show that the candidate is hands on and can write code that configures and builds cloud resources.
2. Show that candidates can think about big picture topics like microservices.
3. Give us a vehicle for a deeper discussion in a face to face interview setting.

### Overview
The purpose of this exercise is to demonstrate that you can write code that launches the needed infrastructure to run a simple Nginx container. When accessing the container web interface it should display the hostname of the container and some sample database data.

### What to Submit
A link to a github repository with code that accomplishes the following:

1. Provisions the needed infrastructure to satisfy the following:
  * Creates a relational database with provided postgres or mysql database dump
  * Runs a Nginx container that outputs the hostname of container, and output from a simple database query (from sample database dump)
  * Accessible to the world on port 443 or 80
  
2. Demonstrates that it is functioning, provide a README file with the following information:
  * Instructions that allow us to run your code
  * A description of your solution noting interesting choices you made and why you made them
  * A list of resources you consulted to accomplish the exercise
  * Feedback on the exercise and some information about how long you spent on it

### Requirements
* Must use Google Cloud. The Google Cloud $300 free credit should be sufficient to compete this project. If your ideal solution would use additional services please include that information in your README
* All parts of the infrastructure setup should be automated.


### Extra Credit
* Secure the connection between Nginx and your Database.
* Secure the web interface. 

### Questions (to facilitate discussion when we get together):
- How did you choose your tool to build your infrastructure?  Why?
- How did you choose your platform to run the container? Why? 
- How would you monitor this instance?  What metrics would you monitor?
- Could you extend your solution to run multiple containers?  What would need to change to support this use case?
- Could you make this secure more secure? How? 
- Was it a priority to make your code well structured, extensible, and reusable?
- What sacrifices did you make due to time?
