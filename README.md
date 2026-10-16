# YieldGrid — Farm-to-Retail Inventory Management

This repository contains the system analysis and design deliverables for YieldGrid, a farm-to-retail inventory management application. It includes eight StarUML diagrams, PNG previews, prototype screenshots, and a presentation.

## Repository contents

```text
.
├── README.md
├── YieldGrid_CBP_Presentation.pptx
├── diagrams/                 # Editable StarUML project files (.mdj)
│   ├── 01_Use_Case_Diagram.mdj
│   ├── 02_Activity_Diagram.mdj
│   ├── 03_Class_Diagram.mdj
│   ├── 04_Sequence_Diagram.mdj
│   ├── 05_Communication_Diagram.mdj
│   ├── 06_State_Chart_Diagram.mdj
│   ├── 07_Component_Diagram.mdj
│   └── 08_Deployment_Diagram.mdj
└── images/
    ├── 01_Use_Case_Diagram.png
    ├── 02_Activity_Diagram.png
    ├── 03_Class_Diagram.png
    ├── 04_Sequence_Diagram.png
    ├── 05_Communication_Diagram.png
    ├── 06_State_Chart_Diagram.png
    ├── 07_Component_Diagram.png
    ├── 08_Deployment_Diagram.png
    └── prototype_images/      # Application prototype screenshots
```

## UML diagrams

Open a PNG preview or download the matching `.mdj` file to view and edit it in StarUML.

| # | Diagram | Editable StarUML file | PNG preview |
|---|---|---|---|
| 01 | Use Case | [`diagrams/01_Use_Case_Diagram.mdj`](diagrams/01_Use_Case_Diagram.mdj) | [View](images/01_Use_Case_Diagram.png) |
| 02 | Activity | [`diagrams/02_Activity_Diagram.mdj`](diagrams/02_Activity_Diagram.mdj) | [View](images/02_Activity_Diagram.png) |
| 03 | Class | [`diagrams/03_Class_Diagram.mdj`](diagrams/03_Class_Diagram.mdj) | [View](images/03_Class_Diagram.png) |
| 04 | Sequence | [`diagrams/04_Sequence_Diagram.mdj`](diagrams/04_Sequence_Diagram.mdj) | [View](images/04_Sequence_Diagram.png) |
| 05 | Communication | [`diagrams/05_Communication_Diagram.mdj`](diagrams/05_Communication_Diagram.mdj) | [View](images/05_Communication_Diagram.png) |
| 06 | State Chart | [`diagrams/06_State_Chart_Diagram.mdj`](diagrams/06_State_Chart_Diagram.mdj) | [View](images/06_State_Chart_Diagram.png) |
| 07 | Component | [`diagrams/07_Component_Diagram.mdj`](diagrams/07_Component_Diagram.mdj) | [View](images/07_Component_Diagram.png) |
| 08 | Deployment | [`diagrams/08_Deployment_Diagram.mdj`](diagrams/08_Deployment_Diagram.mdj) | [View](images/08_Deployment_Diagram.png) |

## Open and edit the diagrams

1. Open StarUML.
2. Select **File → Open...** and choose a `.mdj` file from the `diagrams/` folder.
3. Edit the diagram in StarUML. The corresponding PNG previews are stored in `images/`.

## Visual design palette

The diagrams use a consistent palette:

- Canvas: light neutral grey (`#F3F4F6`)
- System boundary and headers: deep navy or charcoal (`#1E3A8A`, `#0F172A`)
- Farmer responsibility: light olive green with forest-green border (`#D9F99D`, `#4D7C0F`)
- Customer responsibility: light cyan with dark-cyan border (`#A5F3FC`, `#0891B2`)
- Administrator responsibility: soft lavender with royal-purple border (`#EDE9FE`, `#7C3AED`)
- Application and UI: pale blue with royal-blue border (`#BFDBFE`, `#2563EB`)
- Business services: mint green with green border (`#DCFCE7`, `#16A34A`)
- Domain models: warm pastel yellow with amber border (`#FEF3C7`, `#D97706`)
- Persistence and DAOs: lavender purple with purple border (`#EDE9FE`, `#7C3AED`)
- Database and storage: soft peach/orange with deep-orange border (`#FFEDD5`, `#FED7AA`, `#EA580C`, `#C2410C`)
- Neutral containers: neutral grey with grey border (`#E5E7EB`, `#F3F4F6`, `#6B7280`)
