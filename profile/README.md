# Hello

Parent: [The Artificial Intelligence Unit](https://github.com/theartificialintelligenceunit)

<br>
<br>

```mermaid
stateDiagram-v2
    id1: Particulates
    id2: Notify Success
    id3: Notify Failure

    [*] --> id1
    
    id1 --> id2
    id1 --> id3: catch

    id2 --> [*]
    id3 --> [*]
```

<br>
<br>
