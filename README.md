Hello Play Gradle
-----------------

Run Local Dev:

```
./gradlew runPlay
```

Check it out: [http://localhost:9000](http://localhost:9000)

Jib it:
```
./gradlew jibDockerBuild -Djib.to.image=hello-play-gradle
```

Run Jib'd App:
```
docker run --rm -p 9000:9000 -e APPLICATION_SECRET=asdf1234asdf1234 hello-play-gradle
```
