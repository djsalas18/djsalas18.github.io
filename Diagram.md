# Fictional Character Relationships

```mermaid
classDiagram
    Damian *-- Hinx : In-Love
    Jon-Hudson *-- Damian : Foster Son
    Hinx -- Jon-Hudson : Associated
    Damian o-- Hunter-Hudson : Foster brother & Rival
    Hunter-Hudson *-- Jon-Hudson : Father
    Hinx o-- Hunter-Hudson : Dislikes

    class Damian {
        +Fighter
        +Wise
        -Reckless
    }
    class Hinx {
        +Inventor
        +Trigger Happy
        -Crazy
    }
    class Jon-Hudson {
        +Fighter
        +Experience
        -Out of his prime
    }
    class Hunter-Hudson {
        +Fighter
        +Strong will
        -Arrogant
    }
