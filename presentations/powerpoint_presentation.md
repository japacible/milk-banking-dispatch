### Cover Picture
* Potential ideas
  * Diagram of milk banking process from Rohit's paper
  * Stock photo

### Problem Space
* Couriers at the milk bank (MB) have to drop whatever their doing for pickup once notified of a donor having extra breast milk (BM)
* Currently there is no organization for who gets dispatched for the pickup
* Our hope is that this will make the couriers job easier during pickup
* We also hope it will standardize the way donors contact the MB

### Project Description
* Our project organizes the dispatching of couriers who collect the BM
* Donor mothers (DMs) and courriers will use it for deliveries
* DMs can have any phone that allows SMS
* Couriers will have a smartphone with internet access
* Hospital will use it to gather information

### Related work
* Idea comes from Decentralized Human Milk Banking with ODK Sensors by Rohit Chaudri and Gaetano Borriello among others
* Related Areas of Interest:
  * Taxi dispatch apps: Dispatch! App for taxi drivers in the Google Play Store is the most comprehensive
  * AceRoute, Amerilert First Responder (SMS), Comtekk, Digital-Dispatch, RapidSMS, TaskRabbit (Web & iOS), and Taxi Central are other examples

### Findings so far
* We have been communicating with
  * CSE Grad student Rohit
  * Seattle based NGO PATH
  * Human Milk Banking Association of South Africa in Durban
* Lack of infrastructure seems to be a central roadblock to this specific problem. We are therefore:
  * Investigating possibilities in Cape Town
  * Designing for a general scenario

### Basic scenario (should be diagrams)
* Donor mother calls the MB
* She uses an IVR system to tell the MB where she is
* Our app gets this information and determines which courier is best suited at the time
* Courier goes to donor's location
* Courier lets the mother know when (s)he is close
* Courier collects BM and any other information needed
* While the courier is out, if another pickup request is made, the courier will be notified

### Architecture
* +architecture diagram
* Details (split into two pages?)

### Design and Evaluation
* Things to take into account
  * Privacy of donor mothers
  * People who will be accessing any part of this
      * Courier (android device)
      * Mother (generic phone)
      * Will there be an Overseer of the website
* Information storage should be somewhere central and not any one of the clients should
  have to take a burden on hosting it
* Information to be stored:
  * Donor mother information
  * Courier information
  * Milk pick up / drop off points
  * All transactions (past, present, pending) 

### Plan for next quarter
* TBD - may need to broaden to pure courier services application
* Emily/Jim needs to chat to see what's happening here
