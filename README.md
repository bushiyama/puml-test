# puml-test

```uml
@startuml

participant 1 order 10
participant 2 order 20
participant 3 order 30
participant 400 order 40
1 -> 2 :say
2 -> 400 :error
2 -> 3 :hi

@enduml
```
