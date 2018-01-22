# levitics-parent
Parent POM which has to be inherited by all LEVITICS projects and modules 

Base your Maven projects on this artifact and you will get
many pre-configuration benefits, including up-to-date
`dependencies`, `plugins`, build `extensions`,
`repositories`, and more. All that you need to do is to
define our artifact as a parent of your project:

```xml
<project>
  <modelVersion>4.0.0</modelVersion>
  <parent>
    <groupId>io.github.levitics</groupId>
    <artifactId>levitics.arkhe.parent</artifactId>
  </parent>
  <groupId>your-group-id</groupId>
  <artifactId>your-artifact-id</artifactId>
  <version>1.2.3-SNAPSHOT</version>
  [...]
</project>
```
