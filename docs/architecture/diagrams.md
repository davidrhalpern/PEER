```mermaid

flowchart LR
  A[External Documents<br/>Policy • Law • EO • Frameworks] --> B[PEER Repository]
  B --> C[Obligation Tagging<br/>(Corn Kernels)]
  C --> D[Role Assignment & Acknowledgment]
  D --> E[Inbox & Messaging<br/>Clarifications • Evidence]
  E --> F[Reporting & Governance Pulse<br/>Leadership View]

flowchart TB
  subgraph Admin[Authorized Admins]
    C1[Tag Obligations]
    C2[Adjudicate Kernels]
  end
```
```mermaid
  subgraph Users[Assigned Role Holders]
    U1[Acknowledge Role]
    U2[Respond to Inquiries]
    U3[Provide Evidence / Status]
  end
```

```mermaid
 subgraph Leadership[Leadership / Oversight]
    L1[View Reports]
    L2[See Assignment Health]
  end

  C1 --> U1
  U2 --> C2
  U3 --> C2
  C2 --> L1
  L1 --> L2


flowchart LR
  P[Policy Issued] --> K[Obligation Tagged]
  K --> R[Role Assigned]
  R --> A[Role Acknowledged]
  A --> Q[Inquiry / Clarification]
  Q --> E[Evidence or Status Provided]
  E --> S[Obligation Satisfied or Closed]
  S --> G[Included in Governance Reporting]
```
