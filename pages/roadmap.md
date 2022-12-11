---
title: Roadmap
layout: page
nav_order: 2
has_children: true
permalink: /roadmap/
last_modified_date: 2022-12-09 10:40
---

# General Roadmap

----------------

- [ ] **The Base**

    _The basic framework for the CityOS ecosystem including the common elements for both layers, digital & virtual._

    No particular order (yet).

    - [ ] _User Management_
    - [ ] _Tokens Management_
    - [ ] _Organizations Management_
    - [ ] _City Spaces Management_
      - [ ] _Check-in Interactions_
      - [ ] _Participation Framework_
      - [ ] _Content Framework_
      - [ ] _Command Framework_
    - [ ] _Digital Rewards Framework_
    - [ ] _Intelligent Agents Management_
    - [ ] _Teams Management_
    - [ ] _Project Management_
    - [ ] _Context Management_



- [ ] **The Prototypes** (PoCs) (v0.0.1)

    _A proof of concept approach is adopted for each main branch of features._
    
    No particular order (yet).

  - [ ] _Venue PoC_
    - [ ] _Idea Stream_ 
    - [ ] _Orders_
  - [ ] _Info Desk PoC_
    - [ ] _Orientation_
    - [ ] _Support_
    - [ ] _News_


- [ ] **The MVP** (v0.1.0)

    _The minimum viable product for the CityOS ecosystem for each layer._

  - [ ] _Digital City Layer_
  - [ ] _Virtual City Layer_

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