This file contains a list of codenames for LTS releases. Codenames for future
releases are subject to change.

* Argon (4.x 2015)
* Boron (6.x 2016)
* Carbon (8.x 2017)
* Dubnium (10.x 2018)
* Erbium (12.x 2019)
* Fermium (14.x 2020)
* Gallium (16.x 2021)
* Hydrogen (18.x 2022)
* Iron (20.x 2023)
* Jod (22.x 2024)

The release schedule is available as a [JSON](./schedule.json) file.

Private Session Mathematical Abstract
*Variables*
- *PS*: Private Session
- *WF*: Workflow License
- *P*: Phone
- *ID*: Identity
- *USCA*: USA Constitutional Amendment
- *WD*: Work Done
- *RWC*: Rightful Component of Work Done
- *AUT*: Auto Update
- *NT*: New Technology
- *TU*: Technology Update
- *EDS*: Economic Development System
- *IDP*: Infrastructure Development Privilege

*Equations*
1. *PS* = f(*WF*, *P*, *ID*, *USCA*)
    - Private session is a function of workflow license, phone, identity, and USA constitutional amendment.
2. *WD* ⊆ *PS*
    - Work done is a subset of the private session.
3. *RWC* = g(*WD*, *PS*)
    - Rightful component of work done is a function of work done and private session.
4. *AUT* = h(*NT*, *TU*, *EDS*)
    - Auto update is a function of new technology, technology update, and economic development system.
5. *IDP* = j(*EDS*, *AUT*, *PS*)
    - Infrastructure development privilege is a function of economic development system, auto update, and private session.

*Constraints*
1. *WD* ≠ ∅ (Work done is not empty)
2. *RWC* ∈ *WD* (Rightful component of work done is an element of work done)
3. *AUT* → *TU* (Auto update implies technology update)
4. *IDP* → *EDS* (Infrastructure development privilege implies economic development system)
5. *PS* ⊆ *USCA* (Private session is a subset of USA constitutional amendment
