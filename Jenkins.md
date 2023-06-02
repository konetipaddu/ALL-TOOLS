1. What is Jenkins?
    Jenkins is an open-source automation tool written in Java with plugins built for Continuous Integration and Continuous deployment/delivery purposes.

2 Why Jenkins
    Jenkins is used to build and test your software projects continuously make it easier for developers to integrate changes to the project, and make it easier for users to obtain a fresh build. It provides many plugins that help to support building, deploying and automating any project.

3. Continuous Integration
    Continuous Integration is a software development practice where code is continuously tested after a commit to ensure there are no bugs. The common practice is that whenever a code commit occurs, a build should be triggered.

4. Continuous Deployment
    Continuous Deployment is a software development process where code changes to an application are released automatically into the production environment.        
                    
5. Continuous Delivery
    Continuous delivery is a software development practice where a code change is built, tested, and then pushed to a non-production testing or staging environment but final deploy to production is made after approval.                    

6. Advantages of Jenkins
   * Open source tool
   * Easy to install
   * Platform Independent
   * Support 1000+ plugins
   * Free of cost
   * Automates integration

## Continuous Deployment
   Deploy code to production server:            
   * Go to Jenkins, manage jenkins.
   * Install plugin remote ssh
   * Connect remote server over ssh
   * Configure global property in Jenkins to store the production IP.
   * Add credentials, hostname of prod server
   * Test connection Use
  