```mermaid
sequenceDiagram
  participant User
  participant App
  participant Server

User->>App: Lauch the application
App->>User: Show Login Screen
  User-->>App: Entr with email and password e click send button
  App->>Server: Send credenciais
  Server-->>App: Autenticate and replay
  App-->>User: Redirect the user to the Home Screen
```
