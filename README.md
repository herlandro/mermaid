```mermaid
sequenceDiagram
  participant User
  participant App
  participant Server

  User->>App: Entra com e-mail/senha
  App->>Server: Envia credenciais
  Server-->>App: Autentica e responde
  App-->>User: Acesso liberado
```
