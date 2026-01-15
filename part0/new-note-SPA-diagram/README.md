```mermaid
sequenceDiagram
    participant browser
    participant server

    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/spa with body {"content":"test","date":"2026-01-15T13:10:45.322Z"}
    activate server
    server-->>browser: 201 Created
    deactivate server
```