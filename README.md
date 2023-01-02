##### build the project

    ./gradlew build

##### build Docker image called java-app. Execute from root

    docker build -t java-app .
    
##### push image to repo 

    docker tag java-app demo-app:java-1.0
    
    
##### References 

- actions market place: https://github.com/marketplace?type=actions
- actions used here for pushing on Docker: https://github.com/marketplace/actions/docker-build-push-action
- starting video: https://www.youtube.com/watch?v=R8_veQiYBjI

    
