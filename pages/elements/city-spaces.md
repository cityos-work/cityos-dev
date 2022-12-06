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
    CS("City Space")-->CI["Check-in"];
    CI-->CSC["City Space Content"];
    CI-->CSI["City Space Interactions"];
    CI-->CSP["City Space Participation"];
    CSC-->DR["Digital Rewards"];
    CSI-->DR;
    CSP-->DR;
    style CS fill:#f9f,stroke:#333,stroke-width:2px
    style CI fill:#888,stroke:#333,stroke-width:2px
    style DR fill:#f8f,stroke:#333,stroke-width:2px
```
