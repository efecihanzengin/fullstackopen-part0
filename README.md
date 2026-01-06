```mermaid
graph TD
  A[Start] --> B{Choice}
  B -->|Yes| C[Do thing]
  B -->|No| D[Do other thing]
  C --> E[End]
  D --> E[End]
