# github-markdown

try github's markdown features


## Mermaid

### flowchart LR

``` mermaid
flowchart LR

a(((Beginning))) -- time goes by --> b(((End)))
a -- things go wrong --> f(((Failure)))
```

### flowchart UD

```mermaid
flowchart TD

Alice --> Bob
```

### graph

```mermaid
graph

Alice --> Bob
```

### erDiagram

```mermaid
erDiagram

ORDER ||--|{ ITEMS: "consists of"

```

### sequenceDiagram

```mermaid
sequenceDiagram
actor User
User ->> Client: uses
Client ->> Server: calls
Server -->> Client: responds
Client -->> User: shows response
```

### gitGraph

```mermaid
gitGraph

commit
commit
branch develop
checkout develop
commit
commit
checkout main
merge develop
```

### C4Context

```mermaid
C4Context

Enterprise_Boundary(c0, "Big Company") {
  Person(p_user, "User")
  System(s0, "The System")
}

System_Ext(s1, "External System")

Rel(p_user, s0, "uses")
BiRel(s0, s1, "interacts")
```
