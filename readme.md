# Protect your machine learning related application with Endoqa


## with Kotlin DL or tensorflow-java

```kotlin
injars { 
    jars = // your jars
}

exclusion {
    matchClassName {
        "org.tensorflow.*"()
    }
}
```
