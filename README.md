```mermaid
sequenceDiagram
  participant User
  participant App
  participant Server

  User->>App: Launch the application
  App->>User: Show Login Screen
  User->>App: Enter email and password, then click send button
  App->>Server: Send credentials
  Server->>App: Authenticate and reply
  App->>User: Redirect user to the Home Screen
```
classDiagram
    Animal <|-- Duck
    Animal <|-- Fish
    Animal <|-- Zebra
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
