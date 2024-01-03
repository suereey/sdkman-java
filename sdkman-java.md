# Use sdkman to install java
[sdkman](https://sdkman.io/)

## Download sdkman
```
curl -s "https://get.sdkman.io" | bash
```

```
sdk version
```

## Install Java

```sdk list java``` shows all available Java Versions for macOS ARM 64bit

Install specific java version, for example:
```
sdk install java 17.0.9-oracle   
```


## Other Important Commands
```
sdk version

sdk list
sdk list java

sdk install java ${version}
sdk unstall java ${version}

sdk use java version
sdk default java version ; set default java version
sdk current java
```

## sdk and java paths
```
➜  ~ cd .sdkman
➜  .sdkman ls
bin        contrib    ext        src        var
candidates etc        libexec    tmp
➜  .sdkman cd candidates/java 
➜  java ls
17.0.9-jbr current
```




