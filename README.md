# test-mermaid
Test mermaid

```mermaid
flowchart LR
    Start --> Stop
```

## Simple Graph

```mermaid
flowchart TD
    A((A)) -->|7| B((B))
    A -->|2| C((C))
    B -->|3| A
    B -->|5| C
    C -->|1| A
    C -->|3| B
```
