# Proposed-BuildingBlocks

Landing page for all proposed building blocks; use the README to navigate through all the Building Blocks.

New BB should be implemented using the [BB_Template](/utils/BB_Template.md).

## BB Tags

- First tag of BB defines its location in git repo

|Tag|Description|
|----|----|
|BB-SC|Building Block Stack Component (In-Vehicle / On-Board)|
|BB-CSC|Building Block Cloud Stack Component (Cloud / Off-Board)|
|BB-MU|Building Block Mockup Unit (In-Vehicle / On-Board Component)|
|BB-CMU|Block Cloud Mockup Unit (Cloud / Off-Board Component)|
|BB-EST|Building Block Engineering & Support Tools (for In-Vehicle / On-Board Components)|
|BB-CEST|Building Block Cloud Engineering & Support Tools (for Cloud / Off-Board Components)|
|S-BB|Supporting Building Blocks (Standards, API & Interface Definitions, standardized Data Model)|
|FC|Functional Cluster – Logical group of technically similar BBs|
|BB-SC-TC|Building Block Stack Component ToolChain (contains compatible set of Engineering & Support Tools and Mockup Units for In-Vehicle dev)|
|BB-CSC-TC|Building Block Cloud Stack Component ToolChain ToolChain (contains compatible set of Engineering & Support Tools and Mockup Units for Cloud dev)|
|BB-WE|Whatever Tag / Whitecard|

## Navigation

### Cloud

- #### [BB-CSC](/BB-CSC/BB-CSC.md)

- #### BB-CEST

- #### BB-CSC-TC

- #### BB-CMU

***

### In-Vehicle

- #### [BB-SC](/BB-SC/BB-SC.md)

- ##### AppLayer

- ##### [MWLayer](/BB-SC/MWLayer/MWLayer.md)

  - Platform Health Management
    - [Distributed Health Management](/BB-SC/MWLayer/Platform-Health-Management/BB_Distributed_Health_Management.md)
    - [Watchdog]
  - Power Management
    - [Power Management](/BB-SC/MWLayer/Power-Management/BB_Power_Management.md)
  - Runtime
    - [State Management](/BB-SC/MWLayer/Runtime/BB_State_Management.md)
    - [Diagnostic Services Applications](/BB-SC/MWLayer/Runtime/BB_State_Management.md)
  - Time
    - [Time Service](/BB-SC/MWLayer/Time/BB_Time_Service.md)

- ##### [OSLayer](/BB-SC/OSLayer/OSLayer.md)

  - Time
    - [Automotive Edge Runtime](/BB-SC/OSLayer/Time/BB_Automotive_Edge_Runtime.md)

- ##### HWLayer

- #### [BB-EST](/BB-EST/BB-EST.md)

- #### [BB-SC-TC](/BB-SC-TC/BB-SC-TC.md)

- #### BB-MU

***

### Other

- #### S-BB
