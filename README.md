# asterisk Multicast
asterisk multicast implementation on Ubuntu 20.04 and Grand stream GXP 1615 IP sets

# Project Scenario
We have a security control room, which is controlling the security aspects of a large premises located over an area of few hundred square kilometers (like a small town). Optical Fiber based security cameras are available all along the peripherary. The management wants to talk to their secrurity guards deployed along the periphary at different locations in a realtime manner and also broadcast them pre-recorded messages or live announcements, whenever they want. Note: No public landline or wireless network like GSM etc is to be used  

# Requirement
1. An intercom system for the security guards & Control room to talk to each other.
2. A way to broadcast pre-recorded messages to all the security personals (guards), perhaps through the same intercom system. The broadcast message must over ride any intercom call if its already running between two subscribers. 
3. Ability to do live announcements on the same intercom system & it also must over ride the any ongoing call.

# Solution 

The problem at hand looked trickier but was easy to solve. I used the power asterisk to provide all the required provisions i.e, intercom facility, pre-recorded broadcast as well live announcement. I deployed asterisk on ubuntu 20.04 using a Dell Server (PowerEdge R630) and used Grand Stream IP Phones (GXP 1615). Extended the Ip phones to the location of security guards using already laid optical fiber & it all worked like a charm! The code along with explanation is avaialable in the files sip.conf & extensions.conf. I have tried to explain the code inside the files. you can use it freely & do give me feedback, how you used this code. 

Cheers
Happy Coding

