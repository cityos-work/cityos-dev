---
title: Roadmap
layout: page
nav_order: 2
has_children: true
permalink: /roadmap/
last_modified_date: 2022-12-09 10:40
---

{: .highlight }
The 2023 roadmap is planned considering the previously announced [2023 Approach Summary](https://docs.IM.CITY/2023-approach){:target=_blank}.


# General Roadmap
----------------

## Milestones Roadmap 

- [ ] **[Install IM.CITY](https://IM.CITY){:target="_blank"}** as a _Digital Spaces Platform_
- [ ] **[Develop DME](https://CityOs.dev/elements/decision-making-engine/)** (Decision-Making Engine)
- [ ] **Install CityOS.World**  as a _Digital Cities Platform_
- [ ] **Develop DRE** (Digital Rewards Engine)


## Roadmap elements

- [ ] **The Base**

    _The basic framework for the CityOS ecosystem including the common elements for both layers, digital & artificial._

    Here are the potential main modules and elements in no particular order (yet).
    The order for the main modules development will be determined by the PoC candidates and their needs.    


    - [ ] _User Management_
    - [ ] _Tokens Management_
    - [ ] _Organizations Management_
    - [ ] _City Spaces Management_
    - [ ] _Check-in Interactions_
    - [ ] _Idea Streams_
    - [ ] _Participation Framework_
    - [ ] _Content Framework_
    - [ ] _Command Framework_
    - [ ] _Digital Rewards Framework_
    - [ ] _Intelligent Agents Management_
    - [ ] _Groups Management_
    - [ ] _Project Management_
    - [ ] _Context Management_



- [ ] **The Prototypes** (PoCs) (v0.0.1)

    _A proof of concept approach is adopted for each main branch of features._
    
    These are the PoC Candidates in no particular order (yet).

  - [ ] _Decision-Making Engine (DME)_
  - [ ] _Digital Rewards Engine (DRE)_


- [ ] **The MVP** (v0.1.0)

    _The minimum viable product for the CityOS ecosystem for each layer._

  - [ ] _Digital City Layer_
  - [ ] _Artificial City Layer_

- [ ] **Beta Version** (V1.0.0)
    
    _The first version of the CityOS ecosystem for each layer._


# Ecosystem Flowchart

----------------

```mermaid
graph TB;
    USER[\Smart Citizen - User/]-- Check-In -->SPACE((City Space));
    SPACE-->CONTENT[Content Framework];
    SPACE-->PARTICIPATION[Participation Framework];
    CONTENT-->INFO([Info Desk]);
    PARTICIPATION-->VENUE([Venue]);
    INFO-->REWARDFRAMEWORK[Digital Rewards Framework];
    VENUE-->REWARDFRAMEWORK;
    REWARDFRAMEWORK-- Reward -->REWARDEDUSER[/Smart Citizen - User\];
    style USER fill:#6df,stroke:#333,stroke-width:2px
    style REWARDEDUSER fill:#6df,stroke:#333,stroke-width:2px
    style SPACE fill:#fc9,stroke:#333,stroke-width:2px
    style INFO fill:#CF5, stroke:#333,stroke-width:2px
    style VENUE fill:#CF5, stroke:#333,stroke-width:2px 
```