### hidden

関連を -[hidden]- とすると、線が表示されなくなるのでレイアウト用に使える。

```plantuml
@startuml
left to right direction
A -- B
B -- C
C -- D
E -- F
B -[hidden]- E
@enduml
```
