<p>
  <img width="250" align='center' src="https://github.com/Prashantsaini25/PrashantSaini25/blob/main/Images/banner.jpg?raw=true">
</p>
##### build the project

    ./gradlew build

##### build Docker image called java-app. Execute from root

    docker build -t java-app .
    
##### push image to repo 

    docker tag java-app demo-app:java-1.0
    
