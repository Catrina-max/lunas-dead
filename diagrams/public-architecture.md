# Luna's Dead — Public Architecture

```mermaid
flowchart TB
    CORE["LUNA'S DEAD\nStory World"]

    CORE --> GAME["Interactive Game"]
    CORE --> SCREEN["Film / Series"]
    CORE --> ART["Visual Art"]
    CORE --> FASHION["Fashion + Objects"]
    CORE --> GALLERY["Gallery / Installation"]
    CORE --> RETAIL["Retail Experience"]

    GAME --> LAB["Perception / Evidence Lab"]
    ART --> LAB
    GALLERY --> LAB

    LAB --> H["Hoffman\nInterface / Perception"]
    LAB --> O["Olea\nValue / Information / Context"]

    H --> SYSTEMS["Game Systems"]
    O --> SYSTEMS

    SYSTEMS --> P["Perception Layers"]
    SYSTEMS --> C["Case Theory"]
    SYSTEMS --> I["Information Weighting"]
    SYSTEMS --> M["Memory Networks"]

    FASHION --> COLLAB["Scoped Collaborations"]
    ART --> COLLAB
    GALLERY --> COLLAB

    COLLAB --> OBJECT["Canonical Physical Objects"]

    OBJECT --> GAME
    OBJECT --> SCREEN
    OBJECT --> GALLERY
    OBJECT --> RETAIL
```

## Boundary

The public repository documents the research and systems architecture.

The private repository preserves unreleased canon, complete character histories, story solutions, and confidential collaboration material.
