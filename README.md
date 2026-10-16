# YieldGrid CBP UML Documentation Package

This directory contains the professional, course-compliant UML documentation package for **YieldGrid — Application for Farm-to-Retail Inventory Management**.

## Directory Structure

```
YieldGrid-CBP-Final/
├── README.md                              <- Top-level project guide & instructions
├── reference/
│   └── style-only/                        <- Reference screenshots (visual formatting only)
├── batch-01/                              <- Batch 1 StarUML Models (Complete)
│   ├── 01_Use_Case_Diagram.mdj
│   ├── 02_Activity_Diagram.mdj
│   └── 03_Class_Diagram.mdj
├── batch-02/                              <- Batch 2 StarUML Models (Complete)
│   ├── 04_Sequence_Diagram.mdj
│   ├── 05_Communication_Diagram.mdj
│   └── 06_State_Chart_Diagram.mdj
├── batch-03/                              <- Batch 3 StarUML Models (Complete)
│   ├── 07_Component_Diagram.mdj
│   └── 08_Deployment_Diagram.mdj
├── previews/
│   ├── batch-01/                          <- Batch 1 Rendered High-Resolution PNGs
│   │   ├── 01_Use_Case_Diagram.png
│   │   ├── 02_Activity_Diagram.png
│   │   └── 03_Class_Diagram.png
│   ├── batch-02/                          <- Batch 2 Rendered High-Resolution PNGs
│   │   ├── 04_Sequence_Diagram.png
│   │   ├── 05_Communication_Diagram.png
│   │   └── 06_State_Chart_Diagram.png
│   └── batch-03/                          <- Batch 3 Rendered High-Resolution PNGs
│       ├── 07_Component_Diagram.png
│       └── 08_Deployment_Diagram.png
└── validation/
    ├── batch_01_validation.md             <- Comprehensive validation report for Batch 1
    └── batch_03_validation.md             <- Comprehensive validation report for Batch 3
```

## Complete UML Diagram Suite (8 Diagrams)

| # | Diagram Name | Batch | Native StarUML Project | Rendered Preview PNG |
|---|---|---|---|---|
| 01 | Use Case Diagram | Batch 1 | `batch-01/01_Use_Case_Diagram.mdj` | `previews/batch-01/01_Use_Case_Diagram.png` |
| 02 | Activity Diagram | Batch 1 | `batch-01/02_Activity_Diagram.mdj` | `previews/batch-01/02_Activity_Diagram.png` |
| 03 | Class Diagram | Batch 1 | `batch-01/03_Class_Diagram.mdj` | `previews/batch-01/03_Class_Diagram.png` |
| 04 | Sequence Diagram | Batch 2 | `batch-02/04_Sequence_Diagram.mdj` | `previews/batch-02/04_Sequence_Diagram.png` |
| 05 | Communication Diagram | Batch 2 | `batch-02/05_Communication_Diagram.mdj` | `previews/batch-02/05_Communication_Diagram.png` |
| 06 | State Chart Diagram | Batch 2 | `batch-02/06_State_Chart_Diagram.mdj` | `previews/batch-02/06_State_Chart_Diagram.png` |
| 07 | Component Diagram | Batch 3 | `batch-03/07_Component_Diagram.mdj` | `previews/batch-03/07_Component_Diagram.png` |
| 08 | Deployment Diagram | Batch 3 | `batch-03/08_Deployment_Diagram.mdj` | `previews/batch-03/08_Deployment_Diagram.png` |

## How to Open and Edit Diagrams in StarUML

1. Start **StarUML**.
2. Open **File -> Open...** and browse to `YieldGrid-CBP-Final/batch-01/`, `batch-02/`, or `batch-03/`.
3. Select any `.mdj` project file.
4. You can edit nodes, modify properties, adjust layouts, or re-export images at any time.

## Visual Design Standards

- **Overall Canvas:** Light neutral grey (`#F3F4F6`)
- **System Boundary / Header:** Deep navy / dark charcoal (`#1E3A8A` / `#0F172A`)
- **Farmer Responsibility:** Light olive-green (`#D9F99D`) with forest-green border (`#4D7C0F`)
- **Customer Responsibility:** Light cyan (`#A5F3FC`) with dark cyan border (`#0891B2`)
- **Administrator Responsibility:** Soft lavender (`#EDE9FE`) with royal-purple border (`#7C3AED`)
- **Application & UI:** Pale blue (`#BFDBFE`) with royal-blue border (`#2563EB`)
- **Business Services:** Mint green (`#DCFCE7`) with green border (`#16A34A`)
- **Domain Models:** Warm pastel yellow (`#FEF3C7`) with amber border (`#D97706`)
- **Persistence & DAOs:** Lavender purple (`#EDE9FE`) with purple border (`#7C3AED`)
- **Database & Storage:** Soft peach / warm orange (`#FFEDD5` / `#FED7AA`) with deep orange border (`#EA580C` / `#C2410C`)
- **Neutral Containers:** Neutral grey (`#E5E7EB` / `#F3F4F6`) with grey border (`#6B7280`)

---
*Created strictly for YieldGrid Farm-to-Retail Inventory Management.*
