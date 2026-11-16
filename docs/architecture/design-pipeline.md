# Pipeline Architecture Diagram
```mermaid
flowchart LR
    Source[Source data] --> Bronze[Bronze layer]
    Bronze --> Silver[Silver layer]
    Silver --> Gold[Gold layer]
```
