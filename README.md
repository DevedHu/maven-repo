# maven-repo

## Used

### set maven url
```
    repositories {
        maven {
            setUrl("https://raw.githubusercontent.com/DevedHu/maven-repo/main/repository")
        }
    }
```

#### lib-base
```
dependencies {
    implementation("ex.ss.lib:base:1.0.4")
}
```

#### lib-components
```
dependencies {
    implementation("ex.ss.lib:components:1.0.5")
}
```

#### lib-net
```
dependencies {
    implementation("ex.ss.lib:net:1.0.0")
}
```

#### lib-tools
```
dependencies {
    implementation("ex.ss.lib:tools:1.0.4")
}
```