### File Download Example
Download the following funny Dilbert image.

```file
agile-dilbert.png
```

### Mermaid ER Diagram
```mermaid
erDiagram
    CAR ||--o{ NAMED-DRIVER : allows
    CAR {
        string rego
        string make
        string model
    }
    PERSON ||--o{ NAMED-DRIVER : is
    PERSON {
        string firstName
        string lastName
        int age
    }
```

### Mermaid Sequence Diagram
The following diagram is an example of using Mermaid.
```mermaid
sequenceDiagram
A->> B: Query 😆
B->> C: Forward querying
Note right of C: Thinking... Your problem is very important to us
C->> B: Response
B->> A: Forward response
```

### Sketch Example
```sketch
```