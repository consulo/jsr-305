# JSR305 Annotations

Initial code from code.google.com/p/jsr-305

# Changes

 * added module-info for project, but this library can be used at JDK 8 too
 * project cleanup

# Maven dependency

```xml

  <repositories>
    <repository>
      <id>consulo</id>
      <url>https://maven.consulo.io/repository/snapshots/</url>
      <snapshots>
        <enabled>true</enabled>
        <updatePolicy>always</updatePolicy>
      </snapshots>
    </repository>
  </repositories>

...

  <dependency>
   <groupId>consulo.internal</groupId>
    <artifactId>jsr305</artifactId>
    <version>3.0.2</version>
  </dependency>
```