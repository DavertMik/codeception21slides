##  Module Parts

* module can be loaded partially into tester class
* use only specific actions of module

```
modules:
    enabled: 
        - Laravel4:
            part: ORM
        - REST:
            part: Json
            depends: Laravel4
```