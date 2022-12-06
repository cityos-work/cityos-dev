---
title: City Spaces
layout: page
nav_order: 10
parent: Elements
permalink: /elements/city-spaces/
last_modified_date: 2022-12-04 10:40
---

# City Spaces

----------------

## City Space interactions flow

```mermaid
graph TD;
    U(Smart Citizen)--Check-in->CS[City Space];
    CS-->CSC[City Space Content];
    CS-->CSI[City Space Interactions];
    CS-->CSP[City Space Participation];
    CSC-->DR[Digital Rewards"];
    CSI-->DR;
    CSP-->DR;
    style CS fill:#6df,stroke:#333,stroke-width:2px
    style CI fill:#fc9,stroke:#333,stroke-width:2px
    style DR fill:#f9f,stroke:#333,stroke-width:2px
```
