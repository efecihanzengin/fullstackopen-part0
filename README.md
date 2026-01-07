## Exercise 0.4
```mermaid
sequenceDiagram
    note right of Client: After entering text and press the button
    Client->>+Server: POST https://studies.cs.helsinki.fi/exampleapp/notes
    
    Server-->>-Client: HTTP Status 302, URL Redirect to /notes

    Client->>+Server: GET Request on Responser Headers Location /notes
    
    Client->>+Server: GET main.css
    Server-->>-Client: returns main.css

    Client->>+Server: GET main.js
    Server-->>-Client: returns main.js

    Client->>+Server: GET data.json
    Server-->>-Client: returns data.json
```
## Exercise 0.5
```mermaid
    
```
