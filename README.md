## 私人maven仓库
## 使用方式：在pom.xml中加入
```
<repositories>
    <repository>
        <id>maven-repository</id>
        <url>https://raw.github.com/wbc505357999/maven-repository/master</url>
        <snapshots>
            <enabled>true</enabled>
            <updatePolicy>always</updatePolicy>
        </snapshots>
    </repository>
</repositories>
```
