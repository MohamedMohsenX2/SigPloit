# SiGploit
SiGploit a signaling security testing framework dedicated to Telecom Security professionals and reasearchers to pentest and exploit vulnerabilites in the signaling protocols used in mobile operators regardless of the geneartion being in use.
SiGploit aims to cover all used protocols used in the operator's interconnects SS7,GTP (3G), Diameter (4G) or even SIP for IMS and VoLTE infrastrucutres used in the access layer and SS7 message encapuslation into SIP-T.
Recommendations for each vulnerability will be provided to guide the tester and the operator the steps that should be done to enhance their security posture

SiGploit is developed on several versions

Note: In order to test SS7 attacks, you need to have an SS7 access or you can test in the virtual lab with the provided server sides of the attacks, the used values are provdided.

  Version 1: SS7
  -------------
  SiGploit will intially start with SS7 vulnerabilites providing the messages used to test the below attacking scenarios
    A- Location Tracking
    B- Call and SMS Interception
    C- Fraud
  
  Version 2: GTP
  ------------
  This Version will focus on the data roaming attacks that occurs on the IPX/GRX interconnects.
  
  Version 3: Diameter
  -----------------
  This Version will focus on the attacks occuring on the LTE roaming interconnects using Diameter as the signaling protocol.
  
  Version 4: SIP
  ------------
  This is Version will be concerned with SIP as the signaling protocol used in the access layer for voice over LTE(VoLTE) and IMS infrastructure.
  Also SIP will be used to encapsulate SS7 messages (ISUP) to be relayed over VoIP providers to SS7 networks taking advantage of SIP-T protocol, a protocol extension for SIP to provide intercompatability between VoIP and SS7 networks
  
  Version 5: Reporting
  ------------------
  This last Version will introduce the reporting feature. A comprehensive report with the tests done along with the recommendations provided for each vulnerability that has been exploited.
  
    BETA Version of SiGploit will have the Location Tracking attacks of the SS7 phase 1
