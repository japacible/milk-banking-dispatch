# Meeting Notes; Correspondence

## 2.6.2013: Meeting  
Present: Jennifer, Emily, Jim, Mihir, Ruth, Gaetano, Kate, Beth  

### App Functions:  
* Help with pick up/delivery schedules  
* Notifies when delivery will be made  

### App Features:  
* Cross platform (Android, Windows, iOS, text, web)

### Things to think about:  
* Interactive Voice Response (IVR)  
* [MixIt](http://site.mxit.com/pages/moola-country)  
* Low cost SMS that runs over GPRS  

### Contacts:  
* Rohit (rohitc@): contacts in S. Africa, Path
* Nathan (nbnate@): sms services

### //TODO:  
* Email Rohit [DONE]  

## 2.13.2013:  Meeting  
Present: Jennifer, Emily, Jim, Mihir, Ruth, Gaetano, Kate, Beth

### Things we should be doing now:  
Applications in the wild? (Search within App Stores)  
* Dispatch  
* Delivery  
* Pick Up  
* Taxis/Car dispatching  
* Courier services  

What are other lines of work where this application could be used?  
* Messenger services  
* How does UPS/FedEx communicate?  
* What information do these services need?  

What media articles / what has been written about this topic/services?  

Email Nathan:  
* What tools are out there?  
* What does he think would be useful for us?  

Logistics:  
* When pick up/drop off, what information do we need?  
* What functionality do we need?  

### //TODO:  
* Email Rohit; cc Borriello (URGENT) [DONE]  
* Email Nathan [DONE]  
* Research (on our own) [ONGOING]    

## 2.14.2013: Email (Rohit)

### Possible Interview Group Members:  
* PATH Seattle  
* South Africa  

### Winter 2013 Goals:  
* Brainstorm & evolve idea
* Learn about processes from partners to guide implementation

### Summary of Problem & Idea:  
This comes from an email thread between Rohit, Penny, and Lizzie. Open questions have been documented under the Open Questions section rather than this section.

#### Current Process:  
* Word about milk banking and donating BM spreads by mouth  
* Phone calls from moms & hospitals  
* Coordinate & rush to pick up BM (2-5 people in Durban)  

#### Potential Expansion of Program:  
* Expand to 20-50 people / spread across larger area  
* Use of technology for DBM collection by location tracking
* Scale up to be implemented across the country

#### Current Use of Technology:
* Server that archives pasteurization data

#### Potential Use of Technology:  
* Location-aware mobile phones  
* Phone could tell if/when DBM is available for collection near your location  
* Server could also track location via mobile  
  * Hospital/donor mothers send message to the server when they have extra BM  
  * Server sends message to whomever is closest to location for BM collection  

#### Situations Eliminated by Location Tracking Implementation:  
* You just get back from an area and someone calls to say they have milk for you too... so back you go.  

#### Situations:  
* So the donor moms just access the server via internet and then a message is sent to the person collecting.  
* The donor mom and collector communicate to know what time the milk could be collected, as moms are often not at home. 
  * Moms could select a time slot when they message to say milk is ready  
* Multiple volunteers for area  

### New Open Questions:  
* How do they recruit mothers?  
* How do donor mothers tell our partners when they have extra BM for collection? 
* How do our partners coordinate and pick up the BM? What interaction happens during BM collection (i.e. data collection about the donor mother etc )?  
* What happens after the BM is collected (in terms of record keeping, milk processing etc)?  
* Do all the phones have to be android phones?  
* Would it be possible for the person collecting to send a message to the server to confirm milk has been collected?  
* How do we allow donor mothers and collectors communicate?  

### //TODO:  
* Set up a meeting time (Rohit + team) [DONE]  

## 2.15.2013: Email (Rohit)  
Next Meeting: 2.20.2013: 1630 @ Atrium  

### Similar Idea In Place: Taxi Dispatch  
* 2-way radios  
* Might not have a location tracking component  
* Similar idea:  
  * Customer calls cab company  
  * Dispatcher finds a cab closest to pickup location  

## 2.20.2013: Meeting  
Present: Jennifer, Emily, Jim, Mihir, Rohit, Nathan

### Project Goals:  
* Simplify work of people who are collecting milk
* Coordination problem between couriers and mothers
  * Currently, no system exists
* Find the closest courier
* Create a scale-able solution

### Current System (S. Africa):  
* Started with developing cell phone base method 
  * Currently introduced in a few hospitals
* Each pasteurization procedure is uploaded
* Current system in infant stages
  * Staff is small
  * Phone/email communication works
    * Current staff may say they don't need help with scaling
* Goal is to scale this in the future
* Volunteers collect donor milk
* 5 operational facilities (2 starting up)
* Currently varying amount of donor milk coming in based on area
  * Thus, want to expand areas where couriers cover
* Milk collectors get call, then figure out how/when to collect milk

### Technology Involved:  
* Mobile: 
  * What capabilities do these phones have?
  * Donor mothers: no assumptions on types of phones
    * Can assume communication via calls or SMS
  * Couriers: assume they have android phone
    * Can assume SIM card with data
* Location
* Server
* IVR based backend
* Voxeo (IVR, SMS)
  * Free for developers
* Operation costs?
* Database with all donor information needed (DNE)
  * Currently, lots of data replication

### Flow Proposition:  
* Donor mother calls coordinator
* Coordinator figures out who the closest person to pick up is
  * Or automated

### Organizations:
* Human Milk Banking Assoc of S. Africa
* Human Milk Bankers

### New Open Questions:  
* Currently, how do people in South Africa figure out how to allocate communities to couriers?
* How is milk banking implemented?
* What budget do we have for operation costs?

### //TODO:
* Get workflow information/documentation from Rohit [DONE]
* Talk to the people at PATH [DONE]
  * How is milk banking implemented?
  * How do you recruit donor mothers?
  * Figure out what questions is best to ask people in South Africa
* Talk to people who actually do milk banking [DONE]

## 2.20.2013 Meeting  
Present: Jennifer, Emily, Jim, Mihir, Ruth, Gaetano, Kate

### Technology:
* Would it make sense to have an SMS front end?
  * Pick up instead of calls
* Have a server side to track everything
* Map based (See where couriers are)
* Be flexible in using SMS or calls for mothers
  * Different places, pricing structure might be different

### Current Dispatching Services:
* ie. Emergency response, Taxi
* What features do they have?
* What interface do the users see?
* What interface does the couriers see?

### Use Cases: 
* Dispatcher: website
* Courier: cheap Android phone
* Mothers: ???? any type of phone goes

### End of Quarter Work: 
* Final presentation + poster session in Atrium
  * Mock ups, charts
  
### Open Questions:  
* Who are our stakeholders? (dispatcher, courier, mothers)
* How does the communication flow work?
* Are we using Voxeo?
* Would it make sense to have an SMS front end?
* What interfaces do users and couriers currently see in existing dispatching services?

### //TODO:
* Decide work flow  
* Communication with PATH [URGENT] [DONE]  
* Communication with S. Africa [DONE]  
  * Send diagrams/charts to them for feedback (QUESTIONS SENT, WAITING FOR RESPONSE) 
* Send an update every time we do a major change on github [ONGOING] 

## 2.28.2013 Meeting
Present: Jim, Lizzie (S. Africa)

### Questions

#### General
* Describe the current workflow
* Describe the problem as you see it
* Describe possible solutions / what has been brainstormed so far

#### Stakeholders - Mothers, Couriers, Dispatchers:

* what is the his/her role in the system – what does he/she do now?
* what would simplify his/her task?
* what role would he/she play in the new system?
* what are his/her constraints (technology, time, etc)?

#### Logistics
* How are the mothers and the curriers recruited?
* How well do curriers know the neighborhood?
* How much area do they cover?
* Any other major points that we’ve missed…
 
### Answers

#### Two Main Points
* The system (or lack of system) is very ad-hoc at the moment.  Individual roles (such a courier and dispatcher) don’t exist.  It’s a collection of volunteers working with the university.  Kiersten seemed to think that the lack of organization would make implementing this project in the current environment impossible.
* This is something we might want to target at Cape Town rather than Durban (which is where PATH is operating).  Cape Town has much stronger infrastructure in place, which could possibly (though we don’t know) support this system.

#### Further Communication
* Lizzie would know the answers to workflow problems (the first section on the list), although would probably have difficulty with the later questions (because a system just doesn’t exist).  Worth talking to her, but mostly about the general nature of the system.
* We need to speak with Rohit further about the workflow that he sees at the moment, and where specifically he’s talking about setting this system up.
* Kiersten suggested it’s worth having Rohit contact people before we talk to them so he can describe more specifically what we’re proposing.

#### Other
* Donating mothers are usually healthy mothers who are staying in the hospital
* There are some wealthy donors who donate from home, though they are not common
* Simplifying the process for the donor would be useful
* Couriers are volunteers who get a phone and must interrupt what they’re doing
* In relation to the above, there are a number of different workflows among the different organizations
* South Africa probably isn’t ready for this system at this point in time.  Lack of infrastructure as well as a concrete “system/workflow” prevents implementation.  However, it’s something worth considering for a few years down the road and could be quite helpful when the milk banking operation is scaled.

## 3.4.2013 Meeting  
Present: Mihir and Noah (PATH)

### Noah's Role
* Involved in process after milk arrived to milk bank
  * He can help us understand what happens to the milk after the milk has already arrived. Also the procedure the milk goes through before/after it has pasteurized. 

### What Noah Knows
* Does not know how coordination between mother, courier, and dispatcher takes place
* There was clear infrastructure in place in milk bank
  * There is no courrier or dispatcher currently that exists in bringing the milk to the milk banks. 

### //TODO
* Contact Lizzie and Rohit for details on current workflow [ONGOING]

## 3.4.2012 Meeting
Present: Jennifer, Emily, Jim, Mihir

### Open Questions:
* Can we get in contact with someone from Capetown instead of Durban?
* Does it make sense to go forward with the project?

### //TODO:
* Communicate with Rohit, S Africa, and project leaders [ONGOING]
* Diagrams [ONGOING]
* Complete powerpoint [ONGOING]
