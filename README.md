# mermaid

```mermaid
---
title: Animal example
---
classDiagram
    note "From Duck till Zebra"
    Animal <|-- Duck
    note for Duck "can fly\ncan swim\ncan dive\ncan help in debugging"
    Animal <|-- Fish
    Animal <|-- Zebra
    Animal <|-- Tiger
    Animal <|-- Cat
    Cat <|-- MaineCoon
    Animal : +int age
    Animal : +String gender
    Animal: +isMammal()
    Animal: +mate()
    class Duck{
        +String beakColor
        +swim()
        +quack()
    }
    class Fish{
        -int sizeInFeet
        -canEat()
    }
    class Zebra{
        +bool is_wild
        +run()
    }
    class Tiger{
    +int numberOfScratches
    +eatHuman()
}
    class Cat{
    -int numberOfNapsInOneDay
    -beCute()
    -canPurr()
}
    class MaineCoon{
    - int hairLength  
    - toCoo()
    }
