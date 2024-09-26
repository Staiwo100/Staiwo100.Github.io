# DDos Attack Flowcharts
## Description
- DDos Attacks can be harmful towards websites as it can overload the target with many requests, forcing the website to go offline.
- This Mermaid Style Flowchart is a typical Sequence of what the attacker goes through to carry out the attack

```mermaid
flowchart TD
    A[Start DDoS Attack] --> B[Find Target]
    B --> C[Research & Gather Resources]
    C --> D[Attack Target]
    D --> E[Send Request Flood]
    E --> F[Overwhelm Target]
    F --> G[Monitor Impact]
    G --> H{Attack Successful?}
    H -->|Yes| I[Continue Attack]
    H -->|No| J[Change Strategy]
    J --> C
    I --> K[End Attack]
```

