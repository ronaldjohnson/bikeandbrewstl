Run GAE/J locally
```
mvn clean appengine:devserver -Denv=<environment>
mvn clean appengine:devserver -Denv=dev
```

Upload to GAE/J (default app)
```
mvn clean appengine:update -Denv=<environment>
mvn clean appengine:update -Denv=dev
```

Upload to GAE/J (another app)
```
mvn clean appengine:update -Dapp.id=<application-id> -Denv=<environment>
```

http://<environment>.<application-id>.appspot.com
http://dev.bikeandbrewstl.appspot.com/
