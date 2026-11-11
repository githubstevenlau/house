```mermaid
flowchart TD
    Start([Lonsdale Road]) --> House[Steven, Leanna, Georgia, Lydia]
    House --> Decide{BF moving in?} 
    Decide -->|No| House 
    Decide -->|Yes| HouseSH 
    HouseSH[Steven and Harrison live in flat.] --> HouseBF
    HouseBF[Leanna, Georgia, Lydia, BF live in house] --> BFout
    BFout{BF moving out?} --> |Yes| Hin 
    BFout{BF moving out?} --> |No| HouseSH 
    Hin[Harrison move into house] --> HouseKids
    HouseKids[Leanna, Harrison, Georgia, Lydia in house]
