
```
gradle-test-resource
├─ build.gradle
└─ src
   └─ main
      ├─ java
      │  └─ Hello.java
      └─ resources
         ├─ note.xml
         └─ test
            └─ otherNote.xml

```

this is the final jar structure
```
jar
|   note.xml
|
----main
|   ----java
|           Hello.class
|
----META-INF
|       MANIFEST.MF
|
----test
        otherNote.xml
```

