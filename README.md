# Proposed-BuildingBlocks

Landing page for all proposed building blocks; use the README to navigate through all the Building Blocks.

## Implementation of new BBs

When Implementing a new BB please follow these [implementation guidelines](/other/utils/BB_Implementation_guideline.md).

## BB Tags


First tag of BB defines its location in git repo

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
- [BB-CEST](/BB-CEST/00_BB-CEST.md)
    - _Not_Clustered
        - [BB_Car_Simulator](/BB-CEST/_Not_Clustered/BB_Car_Simulator.md)
- [BB-CMU](/BB-CMU/00_BB-CMU.md)
- [BB-CSC](/BB-CSC/00_BB-CSC.md)
- [BB-CSC-TC](/BB-CSC-TC/00_BB-CSC-TC.md)
- [BB-EST](/BB-EST/00_BB-EST.md)
    - Build-and-Implementation
    - Deployment
    - Design
    - Implementation
    - Lifecycle-Management
    - Monitoring-and-Diagnostics
    - Requirements
        - [BB_DocAsCode](/BB-EST/Requirements/BB_DocAsCode.md)
    - Testing
        - [BB_OpenDUT](/BB-EST/Testing/BB_OpenDUT.md)
- [BB-MU](/BB-MU/00_BB-MU.md)
- [BB-SC](/BB-SC/00_BB-SC.md)
    - [AppLayer](/BB-SC/AppLayer/00_AppLayer.md)
        - Communication
            - [BB_AOSP_Push_Notification_Service](/BB-SC/AppLayer/Communication/BB_AOSP_Push_Notification_Service.md)
    - HWLayer
    - [MWLayer](/BB-SC/MWLayer/00_MWLayer.md)
        - Communication
            - [BB_Communication_Server_S2S](/BB-SC/MWLayer/Communication/BB_Communication_Server_S2S.md)
            - [BB_Gateway_Mirroring](/BB-SC/MWLayer/Communication/BB_Gateway_Mirroring.md)
            - [BB_Network_Management](/BB-SC/MWLayer/Communication/BB_Network_Management.md)
            - [BB_SecOS](/BB-SC/MWLayer/Communication/BB_SecOS.md)
            - [BB_Smart_Charging_Communication](/BB-SC/MWLayer/Communication/BB_Smart_Charging_Communication.md)
            - [BB_Standard_Android_VHAL](/BB-SC/MWLayer/Communication/BB_Standard_Android_VHAL.md)
            - [RTPS-Container](/BB-SC/MWLayer/Communication/RTPS-Container/00_RTPS-Container.md)
                - cycloneDDS
                - embeddedRTPS
                    - [BB_Constraint_DDS_embeddedRTPS](/BB-SC/MWLayer/Communication/RTPS-Container/embeddedRTPS/BB_Constraint_DDS_embeddedRTPS.md)
                - FastDDS
                - OpenDDS
        - Configuration
            - [BB_Local_Update_Manager](/BB-SC/MWLayer/Configuration/BB_Local_Update_Manager.md)
            - [BB_OTA_Master](/BB-SC/MWLayer/Configuration/BB_OTA_Master.md)
        - Diagnostics
            - [BB_Policy_Manager](/BB-SC/MWLayer/Diagnostics/BB_Policy_Manager.md)
        - Platform-Health-Management
            - [BB_Distributed_Health_Management](/BB-SC/MWLayer/Platform-Health-Management/BB_Distributed_Health_Management.md)
            - [BB_Watchdog](/BB-SC/MWLayer/Platform-Health-Management/BB_Watchdog.md)
        - Power-Management
            - [BB_Power_Management_Coordination](/BB-SC/MWLayer/Power-Management/BB_Power_Management_Coordination.md)
        - Runtime
            - [BB_Diagnostic_Services_Applications](/BB-SC/MWLayer/Runtime/BB_Diagnostic_Services_Applications.md)
            - [BB_State_Management](/BB-SC/MWLayer/Runtime/BB_State_Management.md)
        - Security
            - [BB_Crypto_Service_Manager](/BB-SC/MWLayer/Security/BB_Crypto_Service_Manager.md)
            - [BB_Internet_Protocol_Security](/BB-SC/MWLayer/Security/BB_Internet_Protocol_Security.md)
            - [BB_Intrusion_Detection](/BB-SC/MWLayer/Security/BB_Intrusion_Detection.md)
            - [BB_Secure_Onboard_Communication](/BB-SC/MWLayer/Security/BB_Secure_Onboard_Communication.md)
            - [BB_Security_Event_Manager](/BB-SC/MWLayer/Security/BB_Security_Event_Manager.md)
            - [BB_Security_Transport_Layer](/BB-SC/MWLayer/Security/BB_Security_Transport_Layer.md)
        - Storage
            - [BB_Vehicle_Data_Collector](/BB-SC/MWLayer/Storage/BB_Vehicle_Data_Collector.md)
            - [BB_Vehicle_Data_Persistency](/BB-SC/MWLayer/Storage/BB_Vehicle_Data_Persistency.md)
            - [BB_Vehicle_Logging_and_Recording](/BB-SC/MWLayer/Storage/BB_Vehicle_Logging_and_Recording.md)
        - Time
            - [BB_Time_Service](/BB-SC/MWLayer/Time/BB_Time_Service.md)
        - Tools-and-Methods
            - [BB_Key_Management_System](/BB-SC/MWLayer/Tools-and-Methods/BB_Key_Management_System.md)
    - [OSLayer](/BB-SC/OSLayer/00_OSLayer.md)
        - Time
            - [BB_Automotive_Edge_Runtime](/BB-SC/OSLayer/Time/BB_Automotive_Edge_Runtime.md)
- [BB-SC-TC](/BB-SC-TC/00_BB-SC-TC.md)
    - Testing
        - [BB_Shadowing](/BB-SC-TC/Testing/BB_Shadowing.md)
    - Virtualization
        - [BB_Digital_Twin](/BB-SC-TC/Virtualization/BB_Digital_Twin.md)
- [S-BB](/S-BB/00_S-BB.md)
    - [AppLayer](/S-BB/AppLayer/00_AppLayer.md)
        - [BB_Standardization_of_Vehicle_API](/S-BB/AppLayer/BB_Standardization_of_Vehicle_API.md)
        - [BB_Standardized_Architectural_Patterns_for_Cross_Platform_Data_Service_Infrastructure](/S-BB/AppLayer/BB_Standardized_Architectural_Patterns_for_Cross_Platform_Data_Service_Infrastructure.md)
        - [BB_Standardized_Description_of_Data_from_Related_Domains](/S-BB/AppLayer/BB_Standardized_Description_of_Data_from_Related_Domains.md)
        - [BB_Standardized_Procedure_and_Tooling_for_Combining_Data_from_Different_Domains](/S-BB/AppLayer/BB_Standardized_Procedure_and_Tooling_for_Combining_Data_from_Different_Domains.md)
        - [BB_Standardized_Procedure_and_Tooling_for_Modelling_Data_from_Different_Domains](/S-BB/AppLayer/BB_Standardized_Procedure_and_Tooling_for_Modelling_Data_from_Different_Domains.md)
    - HWLayer
    - [MWLayer](/S-BB/MWLayer/00_MWLayer.md)
        - [BB_SOA](/S-BB/MWLayer/BB_SOA.md)
        - [BB_sSOA](/S-BB/MWLayer/BB_sSOA.md)
        - [BB_Standardized_Data_Conversion_Tools_for_Info_Knowledge_Layers](/S-BB/MWLayer/BB_Standardized_Data_Conversion_Tools_for_Info_Knowledge_Layers.md)
        - [BB_Standardized_Data_Description_for_Vehicle_Sensors_Attributes_Actuators](/S-BB/MWLayer/BB_Standardized_Data_Description_for_Vehicle_Sensors_Attributes_Actuators.md)
        - [BB_Standardized_way_for_Reasoning_on_Data_Streams](/S-BB/MWLayer/BB_Standardized_way_for_Reasoning_on_Data_Streams.md)
- UseCases
    - Scenarios
        - [BB_Template_filled_FleetData_WP3](/UseCases/Scenarios/BB_Template_filled_FleetData_WP3.md)
        - [BB_Template_filled_RemoteVehicleInteraction_WP3](/UseCases/Scenarios/BB_Template_filled_RemoteVehicleInteraction_WP3.md)
        - [BB_Template_filled_ServiceMesh_WP3](/UseCases/Scenarios/BB_Template_filled_ServiceMesh_WP3.md)

***
generated using [README Generator](/other/scripts/readme_generator.py)

