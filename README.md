# jaxb4-test
Generate java classes with jaxb40-maven-plugin and jakarta.xml.bind

Use https://github.com/patrodyne/hisrc-basicjaxb to solve issues with `-Xinheritance`.

```
<!-- https://mvnrepository.com/artifact/org.patrodyne.jvnet/hisrc-basicjaxb-plugins -->
<dependency>
    <groupId>org.patrodyne.jvnet</groupId>
    <artifactId>hisrc-basicjaxb-plugins</artifactId>
    <version>2.1.0</version>
</dependency>
```

JAXB Maven Plugin: https://github.com/phax/maven-jaxb2-plugin

```
<plugin>
    <groupId>com.helger.maven</groupId>
    <artifactId>jaxb40-maven-plugin</artifactId>
    <version>0.16.1</version>
    <executions>
      <execution>
        <goals>
          <goal>generate</goal>
        </goals>
      </execution>
    </executions>
</plugin>
```


