graph TD
    subgraph Beginner [Beginner Level]
        A1[Fundamentals of Cloud Computing]
        A2[Azure Core Services]
        A3[Hands-On Labs]
    end
    
    subgraph Intermediate [Intermediate Level]
        B1[Advanced Azure Services]
        B2[Architectural Patterns and Best Practices]
        B3[Intermediate Certifications]
    end
    
    subgraph Advanced [Advanced Level]
        C1[Complex Solutions and Design]
        C2[Specialized Services and Industry Solutions]
        C3[Advanced Certifications]
    end
    
    subgraph Expert [Expert Level]
        D1[Continuous Learning and Staying Updated]
        D2[Mentoring and Sharing Knowledge]
        D3[Advanced Architect Certifications]
    end
    
    A1 -->|4 weeks| A2
    A2 -->|4 weeks| A3
    A3 -->|4 weeks| B1
    
    B1 -->|8 weeks| B2
    B2 -->|4 weeks| B3
    B3 -->|8 weeks| C1
    
    C1 -->|8 weeks| C2
    C2 -->|8 weeks| C3
    C3 -->|8 weeks| D1
    
    D1 -->|Ongoing| D2
    D2 -->|Ongoing| D3

    classDef beginner fill:#f9f,stroke:#333,stroke-width:4px;
    classDef intermediate fill:#bbf,stroke:#333,stroke-width:4px;
    classDef advanced fill:#bfb,stroke:#333,stroke-width:4px;
    classDef expert fill:#ffb,stroke:#333,stroke-width:4px;

    class A1,A2,A3 beginner;
    class B1,B2,B3 intermediate;
    class C1,C2,C3 advanced;
    class D1,D2,D3 expert;
