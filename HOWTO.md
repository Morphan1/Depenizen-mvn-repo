### How to create these files:

- Clone the source of the project
- Create a pom.xml if there isn't one already
- Edit the pom, add this:

```
  <distributionManagement>
  <repository>
    <id>internal.repo</id>
    <name>Internal Repository</name>
    <url>file://C:/PATH-TO/Depenizen-mvn-repo</url>
  </repository>
</distributionManagement>
```

- obviously, replace PATH-TO with the URL of the github repo
- open maven for that folder, run `mvn deploy`
- Commit :D
