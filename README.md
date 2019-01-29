# Simple Boot App
This is a very basic spring boot app which is readily deployable to PCF.

#### Package the app.
    mvn clean package -DskipTests
    
#### Push the app.
    cf push -f cloudfoundry/dev.yaml
