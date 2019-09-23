Info:
----
Module `rest` packages into `war` file.
Module `test` packages into `jar` file.

Build:
---
Build project with lombok 1.16.12 (default profile):

```
mvn package
```

Build project with lombok 1.18.10:

```
mvn package -P lombok_1.18.10
```

Show all profiles:

```
mvn help:active-profiles
```