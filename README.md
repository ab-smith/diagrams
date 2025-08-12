# features

| Compliance                      | Risk                          | Governance               | SecOps                     | Core                         | More                                          |
| ------------------------------- | ----------------------------- | ------------------------ | -------------------------- | ---------------------------- | --------------------------------------------- |
| Audit management                | Risk assessments and register | Policies                 | Incidents management       | Action plan tracking         | Data import wizard                            |
| Campaigns management            | Ebios RM module               | Exceptions management    | findings tracking          | Assets management            | Recommendation engine                         |
| +100 frameworks included        | Risk acceptance workflows     | Reports generation       | Vulnerabilities management | Dashboards and analytics     | KAFKA integration                             |
| Custom frameworks supported     | Third Party Risk Management   | Projects and intiatives* | Periodic checks            | Rest API (swagger available) | Automated quality check (x-rays)              |
| Automatic mapping               | Business Impact Analysis      | Custom KPI/KRI*          |                            | CLI  (automation)            | Single domain export/import (for consultants) |
| Evidences management            | Cyber Risk Quantification*    |                          |                            | Flexible RBAC                | MCP support                                   |
| GDPR processings                |                               |                          |                            | MFA with TOTP                | Email notifications                           |
| Project security questionnaires |                               |                          |                            | SSO with SAML/OIDC           | Available in +20 languages                    |
|                                 |                               |                          |                            | n8n node* (automation)       |                                               |

```mermaid
flowchart LR

  %% Column 1
  C1[Audit management]:::c1
  C2[Campaigns management]:::c2
  C3[+100 frameworks included]:::c3
  C4[Custom frameworks support]:::c4
  C5[Automatic mapping]:::c5
  C6[Evidences collection]:::c1

  %% Column 2
  C7[Recommendation engine]:::c2
  C8[API, CLI and Kafka integration]:::c3
  C9[Automated quality checks]:::c4
  C10[Dashboards and analytics]:::c5
  C11[Risk Assessment]:::c1
  C12[EBIOS RM module]:::c2

  %% Column 3
  C13[Data import/export capabilities]:::c3
  C14[GDPR processings]:::c4
  C15[Exceptions tracking]:::c5
  C16[Action plan tracking and prioritization]:::c1
  C17[Third Party Risk Management]:::c2
  C18[Business Impact Analysis]:::c3

  %% Column 4
  C19[Findings followup]:::c4
  C20[Incidents management]:::c5
  C21[SaaS, on-premises or workstation]:::c1
  C22[Flexible RBAC]:::c2
  C23[MFA with TOTP and SSO with SAML/OIDC]:::c3
  C24[Maturity tracking]:::c4
  C25[Available in +20 languages]:::c5
  C26[More coming soon!]:::c1

  %% Arrange columns
  subgraph Col1[ ]
    direction TB
    C1 --- C2 --- C3 --- C4 --- C5 --- C6
  end

  subgraph Col2[ ]
    direction TB
    C7 --> C8 --> C9 --> C10 --> C11 --> C12
  end

  subgraph Col3[ ]
    direction TB
    C13 --> C14 --> C15 --> C16 --> C17 --> C18
  end

  subgraph Col4[ ]
    direction TB
    C19 --> C20 --> C21 --> C22 --> C23 --> C24 --> C25 --> C26
  end

  %% Connect columns invisibly to keep them aligned
  Col1 --- Col2 --- Col3 --- Col4

  %% Color palette (rotates every 5 items)
  classDef c1 fill:#eef2ff,stroke:#6366f1,stroke-width:1px,color:#0f172a;
  classDef c2 fill:#ecfeff,stroke:#06b6d4,stroke-width:1px,color:#0f172a;
  classDef c3 fill:#fef9c3,stroke:#a16207,stroke-width:1px,color:#0f172a;
  classDef c4 fill:#dcfce7,stroke:#16a34a,stroke-width:1px,color:#0f172a;
  classDef c5 fill:#ffe4e6,stroke:#e11d48,stroke-width:1px,color:#0f172a;
```
