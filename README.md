# SciVis_Mermaid
KI SciVis Course_Mermaid Exercise
```Mermaid
flowchart TD
    A[Hypothesis] -->|Get money| B(Do experiments related to the project) 
    A --> |Get money| H(Do experiments not related to the project) 
    H --> |One| E[Adjust]
    B --> C[Analyse Data]
    C --> D{Discussion}
    D -->|One try| E[Adjust]
    D -->|Two| F[Pursue]
    D -->|Three| G[fa:fa-x Abandon]
```
