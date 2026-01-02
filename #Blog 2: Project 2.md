# Project Part #2: Establishing Requirements
## Gathering Requirements - User Analysis
### 1.0 Proposed Task
This​‍​‌‍​‍‌ section demonstrates the three most important tasks accomplished by the “ParkMate” – Indoor Smart Parking & Navigation App. Two tasks embody the system's primary functional capabilities, while the third one is a supplementary feature that makes the user experience more delightful. Each of the roles is picturized along with the corresponding background and target persona's expectations when doing the job.

Task​‍​‌‍​‍‌ 1: Find Parking

One of the first tasks for the ParkMate system is the user-help to locate free parking spots quickly in an indoor or a multi-level parking area. The implementation of this task is done through IoT technologies, wherein each parking space is equipped with sensors such as ultrasonic sensors, motion sensors, or smart cameras to detect its occupancy in real-time. Information gathered is sent to the central cloud server and updated in the ParkMate application where a color-coded digital parking map makes the user-friendly visual interpretation of the parking situation with green spaces for free parking, red for occupied, and pink for ladies’ parking areas. 
For the user to be able to walk or drive easily to a selected parking slot, the scheme uses GPS as a means for outdoor navigation and Bluetooth Beacons for super-accurate indoor positioning especially in underground or closed structures where signals coming from GPS satellites are weak or not available. In addition, AR visual overlays further assist the navigation by showing the directions in form of arrows and the distance, which are the live camera feed, and can be viewed. This is the main goal of the task, that is, the elimination of the time wasted in finding parking, a reduction in the use of fuel, and consequently in CO₂ emissions and an improvement of the whole driving experience.

Task 2: Find Car After Leaving the Mall

The second task deals with the problem of locating one's car after a trip to the mall is done. ParkMate with the help of the "Find My Car" option is automatically fixing the exact location of the vehicle in the parking lot by using a combination of GPS, the nearest Bluetooth Beacon, and user data containing floor and zone information. As the precision of the indoor GPS is quite limited, Bluetooth Beacons become extremely important for they allow highly accurate indoor localization depending on signal strength and beacon ID. 
To find their cars users just have to locate their car, the system finds the correspondence between the data that it recorded during parking and the present beacon signals and thus can determine not only the user's but the vehicle's location as well. The app can then lead the user through the indoor steps being assisted by AR overlays which show the direction in the camera view thereby helping users return to their vehicles with ease. This is important in relieving the feeling of being lost and the stress resulting from it, mostly in large or complicated parking lots, as well as aiding the memory-impaired in recalling directions to vehicles.

Task 3: Find Ladies’ Parking

ParkMate's third task is aimed at promoting safe, comfortable, and easy access for the users for the ladies' parking area goal. To overcome the rising trend of misuse of these spaces, the system offers a solution that includes a scientific and technological-based verification method that engages gender identification from IC-number and AI-driven facial recognition for authentication of the user. Upon registration, a female driver entering her data in the app will have her personal details securely kept in the central server. 
On the arrival of the ladies' parking gate, a driver's face undergoes recognition where its system then integrates the scanned information and the registered database, which results in the verified identity. The entry is open to confirmed females only, meanwhile, those unconfirmed will receive an alert audio message that they will be warned and lead to general and open parking spaces. To prevent the trickery of a person that pretends to be a female driver, ParkMate sets up the scanner on the driver's side thereby defeating the attempt. It does this task to raise the security level and trust of the female drivers and at the same time ensure the correct use and the fairness of the existence of ladies’ parking.

### 2.0 Persona
Persona​‍​‌‍​‍‌ 1: Chiam Lim Mui (Female Driver, Office Worker, 40 Years Old)


<p align="center">
<img width="251" height="321" alt="image" src="https://github.com/user-attachments/assets/1527441d-1b1f-405a-97bb-75387d7d9456" />
<br>
  <em>Figure 2.1 : Persona 1 (Chiam Lim Mui)’s picture</em>
</p>

Chiam Lim Mui is a female office worker who is 40 years old. She drives herself to work every day and is a frequent visitor of shopping malls during rush hours for lunch. As a somewhat tech-savvy user, she prioritizes the factors of convenience, safety, and time-saving in her daily schedule. Her greatest source of anxiety is the problem of parking that she encounters over and over again in large, heavily crowded multi-storey car parks. What she essentially wants to achieve is to look for available parking spaces in the shortest time possible, be sure that she is able to safely access ladies’ parking areas, and without a doubt, she can find her way back to her vehicle without getting into a panic or being lost. 
However, she is in the habit of running out of luck when it comes to finding a vacant parking space, especially during peak periods, and the saddest thing is that she is not comfortable in the situation where men occupy ladies’ parking spaces. Additionally, she has been through situations that caused her to be frustrated and embarrassed when after a long day of work she forgot where she had parked. Ms Chiam hopes to have a system that provides the benefits of obtaining real-time parking spaces availability, safe access to ladies’ parking facilitated by facial verification, and detailed indoor navigation that is very helpful in finding a way back to the car without any hassle. These benefits can profoundly improve her daily commuting experience, lessen the waste of fuel, and besides that, provide her with a stronger feeling of security and convenience.

Persona 2: Siau Hui Hui (Lone Driver, Coffee Shop Manager, 27 Years Old)
<p align="center">
  <img width="239" height="425" alt="image" src="https://github.com/user-attachments/assets/08f7a87b-b0bf-4000-aae5-cd3371bac07c" />
  <br>
<em>Figure 2.2 Persona 2 (Siau Hui Hui)’s picture</em>
</p>
Siau Hui Hui is a 27-year-old manager of a coffee shop who is also a solitary driver and is mostly on the road for work-related errands, supply runs, and personal activities. Being a confident technology user, she cares most about the following conditions that would lead to her independence, safety, and ease of navigation, as well as safety parking in the unknown areas is concerned. What she primarily strives for are the three things, namely, to park in a safe and well-indicated area, not lose her way in a large parking lot, and feel comfortable following a route even if GPS signals were weak indoors. 
Although she remains independent, the problem she faces more often is that she is anxious at the time of looking for safe parking spaces at night and she is also having a hard time finding her car when she is after shopping for groceries needed for her shop operation. Moreover, failures of indoor GPS and parking layout puzzles make her anxiety grow even more. Ms Siau wants the system to automatically save her parking location and deliver exact indoor navigation through Bluetooth Beacons so that she can find her car even in a big or crowded parking garage without any hassle. She believes that AR guidance will be able to give her clear, detailed visual instructions and hence, she will not have to worry about complex layouts or weak GPS signals inside the building. Moreover, she expects the facial-recognition verification for ladies’ parking to be the means of ensuring that these tightly secured spaces are utilized like that for which they are meant, thus making her feel safer and more confident while driving alone. 

Persona 3: Tan Lean See (Elderly Driver, Housewife, 55 Years Old)
				<p align="center">
        <img width="261" height="229" alt="image" src="https://github.com/user-attachments/assets/37c881d6-6a4d-4b44-a947-9433930e747b" />
          <br>
          <em> Figure 2.3 : Persona 3 (Tan Lean See)’s picture </em>
        </p>
     
Ms. Tan is a 55-year-old housewife who drives herself frequently to nearby shopping malls to buy groceries and attend to household errands. While she is independent and does not like to bother her children for transport, multi-level indoor parking often makes her anxious. To her, the repetitive layout and long rows of cars make distinguishing one floor from another very difficult. Even with the help of indicator lights, she still has to drive around repeatedly several times, as she either often misses the available spots or feels uncertain if she is in the correct lane. She considers herself fairly tech-savvy since she can use simple applications like WhatsApp and Google Maps, but anything with too many icons, menus, or multiple steps overwhelms her. She tends to drive slowly and cautiously, but the stress of finding parking in a crowded mall environment heightens her nervousness.

When leaving the mall, Ms. Tan often can't remember where her car is parked after a long session of shopping or if she happens to be parking really far from an elevator. She has used Google Maps to mark her parking location, but it hardly works when inside because of weak GPS signals. The constantly shifting map with incorrect directions grinds on her nerves as she walks around, trying to trace her steps. She cannot compromise on the safety aspect-mostly, she wants to use ladies’ parking for her peace of mind-but misuse by male drivers often leaves her unprotected and unsafe. Ms. Tan just hopes for a simple and clear solution to parking assistance that will help her find available parking quickly, locate her car afterward with the least fuss, and see to it that the ladies’ parking zone is well monitored so she will be confident and safe anytime.

### 3.0 Scenario

Task​‍​‌‍​‍‌ 1: Find Parking (Persona 1: Female Driver - Chiam Lim Mui)

At 12:30 PM on a busy weekday, Chiam Lim Mui was driving from her office for lunch at a city mall filled with people. She already knew from her past experience that it might take as long as 20 minutes to find a free spot during the rush hours, which in turn, would add more stress to her morning routine. Thanks to ParkMate, she launched the app, which immediately communicated a parking map with color codes indicating free slots in green, occupied slots in red, and ladies’ parking in pink. By employing IoT sensors, the system can be quite competent in confirming the availability of the parking spaces in real-time, and Ms Chiam decided to take a green slot that was nearby the elevator on the second floor. Then the app offers indoor navigation on entering the covered structure.

While she was driving on the floor, AR assistance was there to guide her. It shows directions and the distance to the live feed from her camera so that she finds her slot with ease and accuracy. Chiam feels great that she should not be driving endlessly or worrying about a free space being missed. Additionally, the system assures her that it is safe to park in a ladies’ parking area which, in turn, boosts her trust and lowers her anxiety level. By using ParkMate, Chiam was able to save some time and fuel with a feeling of being in control and convenience, and she succeeded in parking within a few minutes.

Task 2: Find Car After Leaving the Mall (Persona 2: Lone Driver - Siau Hui Hui)

After buying supplies for the coffee shop, Siau Hui Hui got out of the mall with a bag of groceries. She often finds her car in a huge multi-level parking lot after which she ends up wasting 10-15 minutes, the time that she is most at a loss of and it also increases her level of stress and anxiety. She immediately opened ParkMate and activated the "Find My Car" feature which indicated the location of her car at the time of parking through a combination of GPS, Bluetooth Beacons, and floor/zone data.
The system guides her to the beacons nearest to her with the help of the saved data and current location and thus the step-by-step indoor navigation starts. AR overlays show up on her mobile displaying arrows and distances in real-time helping her to find her car quickly and surely. Even though GPS signals are weak indoors, the Bluetooth Beacons are reliable enough to pinpoint the exact location. Hui Hui follows the directions given by the AR without hesitating and as a result, she gets to her car in no time and is free from the confusion or stress that usually accompanies this task. The app’s precise direction gives her the opportunity to use her time efficiently, lowers the level of her anxiety, and facilitates her leaving the mall thus, empowering her as a female driver who is ​‍​‌‍​‍‌alone.

Task​‍​‌‍​‍‌ 3: Find Ladies’ Parking (Persona 3: Elderly Driver - Tan Lean See)

On a Saturday morning, Tan Lean See, a 55-year-old housewife, drives to her local mall to buy groceries. Even though ladies’ parking has been created for security, she has often felt uncomfortable because a few male drivers have been misusing these reserved spaces, thus endangering her. Using ParkMate, she has already set up her account in the app where her IC number and a selfie for AI-based facial verification have been provided. All this data is kept securely in the central server. While driving towards the parking barrier, she looks at the driver's side scanner and her face is scanned. After that, the system cross-checks her identity with the database.
After the system confirms that Tan Lean See is a registered female driver, the barrier is lifted to allow her access to the ladies’ parking. If the identity from the scan didn’t match, the barrier would stay closed and a notification would be sent, redirecting unauthorized users to general parking. As the spot is safeguarded from being taken by someone else, Tan Lean See proudly heads to an empty place in the ladies’ parking lot. The machinery not only guarantees her safety but also provides her with the trust in the correct usage of the reserved spaces. It gives her freedom from the constraint of worrying during shopping, thus making her parking experience stress-free and secure.

## Gathering Requirements - Task Analysis
### 1.0 Introduction
This observation study focuses on evaluating the limitations of the existing car park infrastructure and commonly used parking-related applications in multi-level indoor car parks. Understanding these limitations is essential to establish a baseline of current user challenges, system inefficiencies, and behavioural patterns before designing improved solutions.
The existing systems and products evaluated in this study are the conventional mechanisms users rely on today:

* Task 1: Find Available Parking Space
  * Existing System: Conventional multi-level car parks featuring overhead sensor systems and LED indicator lights Green for Vacant, Red for Occupied at individual parking bays.
  * Limitation Observed: Drivers are forced to physically cruise the aisles, relying on visual cues and short-range indicators rather than receiving real-time, directional guidance, which leads to prolonged searching and congestion.

* Task 2: Find Parked Car
  * Existing Product: Generic mobile mapping and navigation applications, such as Google Maps (using its "Save your parking location" feature) or relying on memory.
  * Limitation Observed: These tools offer imprecise, above-ground GPS location tracking, which fails to provide the required accuracy or indoor, multi-level guidance needed to efficiently locate a vehicle in a complex parking structure.

* Task 3: Find Ladies' Parking
  * Existing System: Designated Ladies' Parking areas marked only by signage and distinct coloring (e.g., pink bays), often lacking robust access control mechanisms.
  * Limitation Observed: The current reliance on signage and general monitoring is ineffective against the common phenomenon of misuse by non-eligible drivers (e.g., male drivers or couples), which undermines the intended security and comfort for female drivers.

This task analysis systematically observes and investigates the behaviors of users performing parking-related tasks in a multi-level indoor car park. The main aim is to understand what types of tasks users perform, how they make decisions while navigating the parking environment, and to identify difficulties, inefficiencies, or sources of frustration in the current manual parking process. By closely examining user interactions, this study seeks to uncover patterns in behaviour that can inform the design of more effective parking solutions.

By using the Think Aloud technique, three representative users—Lone Driver, Elderly Driver, and Female Driver—were observed while completing three core parking tasks: finding an available parking space, locating a parked car, and finding a ladies’ parking slot. The users were asked to verbalize their thoughts, reasoning, and any difficulties they encountered while performing these tasks. This approach gives insight into user behavior, cognitive load, and interaction patterns during the parking process. 

The observations and the derived Hierarchical Task Analyses (HTAs) will highlight common patterns, decision points, and areas of frustration that form a basis to identify user requirements. These will be used later in the process as an input to the design of the proposed ParkMate system, ensuring that it addresses the inefficiencies of the current manual process, accommodates the diverse needs of different user groups, and enhances overall usability, safety, and user satisfaction in parking facilities.

---

### 2.0 Derivation of HTA
#### 2.1 HTA for Task 1 – Find Available Parking Space
User Type 1: Lone Driver

Video on Lone Driver finding available parking space:
https://drive.google.com/file/d/1dWZF-RzLDi5dpwFmuG485RxU1qkJRoOe/view?usp=sharing

_HTA (Textual Presentation) – Lone Driver Performs Task 1_
    
    0. Find parking space.
    
    1. Enter the mall parking entrance.
    
    2. Drive slowly and observe indicator lights.
      
      2.1 Look for red (occupied).
      
      2.2 Look for green (available).
    
    3. Check both left and right aisles for empty spaces.
    
    4. Turn into another lane if no free parking lot is found.
    
    5. Repeat scanning process (scan lights and check aisles).
    
    6. Identify a free parking spot.
    
    7. Drive towards the spot.
    
    8. Park the car.

	Plan 0: do 1-2-3. 
            
            if a green slot is found: do 6-7-8.
            
            if all red (full): do 4-5, then do 6-7-8 once a space is found.
            
            if still full after scanning the entire floor: go to the next floor and repeat 2-3-4-5-6-7-8.

	Plan 2: do 2.1 and 2.2 in any order repeatedly until a slot is found.


_HTA (Diagram Presentation) – Lone Driver Performs Task 1_
<p align="center">
<img width="1073" height="433" alt="Lone Driver Task 1 " src="https://github.com/user-attachments/assets/010e3498-51a2-42b7-937c-30915f7d03c7" />
<br> 
<em>Figure 2.1.1: HTA Diagram of Lone Driver doing Task 1</em>
https://drive.google.com/file/d/1f4HuwxozvPEZV9vymoaa-XVWi2qfu-9Z/view?usp=sharing</p>


User Type 2: Elderly Driver

Video on Elderly Driver finding available parking space: https://drive.google.com/file/d/1N2q9ODYTgYUbDfoCNFx5lhSpnsKO-6fj/view?usp=sharing

_HTA (Textual Presentation) – Elderly Driver Performs Task 1_

	
	0. Find Available Parking Space
	
	1. Drive into the parking building
	
	2. Slowly drive to a floor that seems less crowded
	
	3. Search for empty parking slots by driving lane-by-lane
	
	4. Reduce speed due to slower reaction time and vision limitations
	
	5. If no slot is found
	
		5.1 drive to another floor and repeat
	
	6. Once an empty slot is found 
		
		6.1 carefully park into the space
	
	7. Lock the car and walk to building entrance

	Plan 0: 
	
		Do 1 → 2 → 3 → 4 → 5 → 6 → 7  in order.

	Plan 5:
	
		Do 5.1 repeatedly until an empty slot is found.

_HTA (Diagram Presentation) – Elderly Driver Performs Task 1_
<p align="center">
<img width="1351" height="661" alt="image" src="https://github.com/user-attachments/assets/6e5d8872-2f44-42d8-ad32-81b11f9a901b" />
<br>
<em>Figure 2.1.2: HTA Diagram of Elderly Driver doing Task 1</em>
	https://drive.google.com/file/d/1pxXlimlxAMLlMotMhHl0CXOX-7W8lPE8/view?usp=sharing
</p>

User Type 3: Female Driver

Video on Female Driver finding available parking space: 

https://drive.google.com/file/d/1EOxAUZH5Bw9WAdBHkiN0ZbZXoTt4xGL7/view?usp=drive_link 

_HTA (Textual Presentation) – Female Driver Performs Task 1_
   
	
	0. Find Available Parking Space
	
	1. Drive through the first level.
	
	2. Drive through the first lane.
	
	3. Look for empty space
		
		3.1. Look for green sensor indicate empty lot
	
	4. Drive to another lane.
	
	5. Found parking lot for disability 
	
	5.1. Find another parking lot
	
	6. Found people who are leaving the building	
		
		6.1. Wait for them to remove their car 
	
	7. Park into the parking lot

	Plan 0: Do 1-2-3
		
		If found available parking lot, do 7
		
		If all parking lots are occupied, do 4 and repeat 2-3-4 until 7
		
		If found disabled parking lot, do 5 and repeat 2-3-4 until 7
		
		If someone is leaving, do 6-7
	
	Plan 3: 
		
		Do 3.1 repeatedly until a parking lot is found
	
	Plan 5: 
		
		Do 5.1 repeatedly until a parking lot is found
	
	Plan 6: 
	
		Do 6.1

_HTA (Diagram Presentation) – Female Driver  Performs Task 1_
<p align="center">
  <img width="1076" height="370" alt="image" src="https://github.com/user-attachments/assets/ea4de64c-d004-455c-a746-eca564988449" />
  <br>
<em>Figure 2.1.3: HTA Diagram of Female Driver doing Task 1 </em>
	https://app.diagrams.net/#G1qFrA9UIbTLxcWmda8nuJRQmjPM3UqJeo#%7B%22pageId%22%3A%22hMAyd972iGnsGYgStMXn%22%7D 
</p>

### Findings from the HTA for Task 1 – “Find Available Parking Slots”

_1. Information on HTAs and Thinking-Aloud across 3 personas_

Across all three users, the HTA reveals a common high-level structure: entering the parking area, scanning the environment, navigating through different lanes or floors, and finally 
identifying and occupying an available slot. 
Across all videos, the HTAs showed common cognitive patterns:
* Users continuously scan for indicator lights (red/green) while driving slowly.
* Users repeatedly check both sides of the lane, indicating a looping search process.
* Users rely heavily on visual cues, especially green indicators or people walking back to their cars.
* When they fail to locate a slot quickly, cognitive load increases, leading to frustration or slower decisions.

Thinking-Aloud reveals emotional responses that affect task efficiency. Users frequently expressed frustration, particularly when they could not locate a slot after several attempts. This frustration increased cognitive load and slowed down decision-making. Across the videos, users also misinterpreted visual cues, such as green indicators that corresponded to reserved slots (e.g., disabled parking), which resulted in wasted search time and increased mental effort. This suggests that the current car park environment does not adequately support users with clear, reliable feedback. 

_2. Differences of 3 personas perform on Task 1_

| Aspect                  | Lone Driver                                      | Elderly Driver                                             | Female Driver                                           |
|-------------------------|-------------------------------------------------|-----------------------------------------------------------|--------------------------------------------------------|
| Speed of Navigation      | Fast, moves quickly                             | Slow, cautious driving                                     | Moderate speed                                         |
| Scanning Behaviour       | Iterative scanning, fast left–right checks (may over-scan too quickly) | Slow and detailed scanning (sometimes struggles to see distant indicators) | Iterative scanning but more cautious, frequently checks for people returning to cars |
| Decision-Making          | Makes instant decisions upon seeing green lights | Takes longer to make decision                              | Makes instant decisions when someone leaving          |
| Reaction Under Pressure  | Shows frustration when lanes are full           | Higher cognitive load                                      | A bit frustration on finding empty slots when lanes are full |
| Use of Environmental Cues | Minimal, follows sensors more than human behaviour | Low, focuses on driving stability and visibility          | High, looks for people returning to cars and leave   |
| Common Issues Observed   | Difficulty scanning sensors quickly             | Difficulty scanning sensors quickly                        | Difficulty scanning sensors quickly                   |
| Overall Behaviour Style  | Confident, fast-paced, emotional under pressure | Safety-first, slower, methodical, higher mental effort    | Safety-oriented, socially aware, fast-paced           |

These differences highlight the importance of accommodating diverse user needs. While the lone driver benefits from fast, clear guidance, the elderly driver requires simplified navigation and reduced visual complexity. Meanwhile, the female driver prioritises safety and seeks reliable information on the availability of appropriate parking zones.

_3. Conclusions from Comparing the HTAs across 3 personas for Task 1_

Comparison of the three HTAs indicates several consistent issues in the current manual parking search process. All users depend heavily on visual scanning of lights and aisles, which is time-consuming and cognitively demanding.All users are caught in repetitive loops of scanning, lane switching and floor changes, demonstrating inefficiencies inherent in the environment. 

Furthermore, differences among users indicate that the current system does not effectively serve users with different levels of cognitive, perceptual and emotional needs. While younger (lone/female) drivers may deal with fast-paced scanning, elderly drivers have greater challenges, such as uncertainty, slower detection, and lower confidence in navigating busy floors. These findings show a need for system enhancements that could provide real-time guidance, clearer slot differentiation, and personalized navigation support for different user groups.

#### 2.2 HTA for Task 2 – Find Parked Car

User Type 1: Lone Driver

Video on Lone Driver finding parked car: 
https://drive.google.com/file/d/1wqkR3r1YT4ErMs5bk40CAqDqX666HBmC/view?usp=drive_link

_HTA (Textual Presentation) – Lone Driver Performs Task 2_

    0. Find the parked car
    
	1. Open Google Maps
		
		1.1 Open the app
		
		1.2 Select “Saved parking”
    
	2. Attempt to navigate using Google Maps
		
		2.1 Follow the on-screen directions
		
		2.2 Compare surroundings with the map
		
		2.3 Check if the route makes sense inside the building
    
	3. Confirm Google Maps failure
		
		3.1 Notice location inaccuracy
		
		3.2 Decide to switch to manual searching
   
	4. Recall human memory of parked location
    
	5. Navigate manually based on memory cues
		
		5.1 Walk toward the estimated zone
		
		5.2 Check each row left and right
		
		5.3 Look for car characteristics (color, number plate)
    
	6. Locate the car
		
		6.1 Confirm visually it is the user’s car
		
		6.2 Walk toward the vehicle
		
		6.3 Unlock the car

	Plan 0: do 1-2-3.
	
		If Step 2 fails, do 4-5 repeatedly until the car is found. 
	
		then do 6.

	Plan 1: Do 1.1 then 1.2.

	Plan 2: Do 2.1 then 2.2 then 2.3.

	Plan 3: Do 3.1 then 3.2.

	Plan 5: Do 5.1 then 5.2 then 5.3 repeatedly until the car is located.

	Plan 6: Do 6.1 then 6.2 then 6.3

_HTA (Diagram Presentation) – Lone Driver Performs Task 2_
<p align="center">
<img width="1028" height="580" alt="Lone Driver Task 2" src="https://github.com/user-attachments/assets/5d4a0f38-a425-4d42-8567-ac48c024d404" />
<br>
<em>Figure 2.2.1: HTA Diagram of Lone Driver doing Task 2</em>
https://drive.google.com/file/d/1p7kSUpuIJggXTdcXH_3M9HpyvDc7s5If/view?usp=sharing
</p>

User Type 2: Elderly Driver

Video on Elderly Driver finding parked car: https://drive.google.com/file/d/1BpcceHWyP-BJKJFH-6o6U2f8RB7qAUZl/view?usp=sharing

_HTA (Textual Presentation) – Elderly Driver Performs Task 2_
    
	0. Find the parked car
    
	1. Open Google Maps
		
		1.1 Open the app
	
		1.2 Select “Saved parking”
    
	2. Attempt to navigate using Google Maps
	
		2.1 Follow the app directions
	
		2.2 Compare surroundings with the map
	
		2.3 Check if the direction makes sense inside the building
    3. Confirm Google Maps failure
	
		3.1 Notice location inaccuracy
	
		3.2 Decide to switch to manual searching
    
	4. Try to use human memory to recall parked location
    
	5. Navigate manually based on memory cues
		
		5.1 Walk toward the estimated zone
		
		5.2 Check each row left and right
		
		5.3 Look for car characteristics (color, number plate)
    
	6. Locate the parked car
	
		6.1 Confirm visually it is the user’s car
	
		6.2 Walk toward the vehicle
		
		6.3 Unlock the car

	Plan 0: do 1-2-3.
	
		If Step 2 fails, do 4-5 repeatedly until the car is found. 
	
		then do 6.

	Plan 1: do 1.1 then 1.2.

	Plan 2: do 2.1 then 2.2 then 2.3.

	Plan 3: do 3.1 then 3.2.

	Plan 5: Do 5.1 then 5.2 then 5.3 repeatedly until the car is located.

	Plan 6: Do 6.1 then 6.2 then 6.3

_HTA (Diagram Presentation) – Elderly Driver Performs Task 2_
<p align="center">
<img width="1252" height="544" alt="image" src="https://github.com/user-attachments/assets/6eb172fc-8725-4fa4-a9f8-e91722afc9d2" />
<br>
<em>Figure 2.2.2: HTA Diagram of Elderly Driver doing Task 2</em>
https://drive.google.com/file/d/1OTTr3tFPSVipipDm0eicATxMTeV7tKVG/view?usp=sharing
</p>

User Type 3: Female Driver

Video on Female Driver finding parked car: https://drive.google.com/file/d/1Cs4jehPjnXRqSRH5KZxAOThBxTTgbMRA/view?usp=drive_link 

_HTA (Textual Presentation) – Female Driver Performs Task 2_
    
	0. Find the parked car
    
	1. Open Google Maps
	
		1.1 Open the app
		
		1.2 Select “Saved parking”
    
	2. Attempt to navigate using Google Maps
		
		2.1 Follow the app directions
		
		2.2 Compare surroundings with the map
		
		2.3 Check if the direction makes sense inside the building
    
	3. Confirm Google Maps failure
		
		3.1 Notice location inaccuracy
		
		3.2 Decide to switch to manual searching
    
	4. Try to use human memory to recall parked location
    
	5. Navigate manually based on memory cues
	
		5.1 Walk toward the estimated zone
	
		5.2 Check each row left and right
	
		5.3 Look for car characteristics (color, number plate)
    
	6. Locate the parked car
	
		6.1 Confirm visually it is the user’s car
	
		6.2 Walk toward the vehicle
		
		6.3 Unlock the car

	Plan 0: do 1-2-3.
		
		If Step 2 fails, do 4-5 repeatedly until the car is found. 
	
		then do 6.

	Plan 1: Do 1.1 then 1.2.

	Plan 2: Do 2.1 then 2.2 then 2.3.

	Plan 3: Do 3.1 then 3.2.
	
	Plan 5: Do 5.1 then 5.2 then 5.3 repeatedly until the car is located.

	Plan 6: Do 6.1 then 6.2 then 6.3

_HTA (Diagram Presentation) – Female Driver Performs Task 2_
<p align="center">
<img width="923" height="350" alt="image" src="https://github.com/user-attachments/assets/7da7dab0-de22-4982-83fe-7ac89e87b76f" />
<br>
<em>Figure 2.2.3: HTA Diagram of Female Driver doing Task 2</em>
https://app.diagrams.net/#G1qFrA9UIbTLxcWmda8nuJRQmjPM3UqJeo#%7B%22pageId%22%3A%22DAcXMnN_CmskjjDfOfph%22%7D 
</p>
      
### Findings from the HTAs for Task 2 - “Find Parked Car”
_1. Information on HTA and Thinking Aloud across the three personas_

Across all three users, the HTA for Task 2 shows a similar high-level structure: attempting to recall the parking location, trying to use digital tools (Google Maps or memory), navigating through different floors or lanes, and eventually relying on repeated searching until the car is found. Thinking-aloud observations reveal several common cognitive patterns. All users spent significant time trying to remember where they parked, followed by scanning the environment for familiar landmarks such as lift lobbies, wall colours, or pillar numbers. Users repeatedly walked through aisles or floors, indicating a looping search process when their initial assumption was incorrect. When memory failed or the environment looked too similar, cognitive load increased, which led to slower movement, hesitation, and uncertainty.

Thinking-aloud also shows emotional reactions that affect task performance. All users expressed frustration when their mental image of the parking location did not match reality. This frustration increased cognitive load and led to inefficient or repetitive walking patterns. Users occasionally misinterpreted cues, such as assuming they were on the correct floor because the pillars looked similar, which resulted in wasted time and unnecessary physical effort. These findings indicate that the current indoor parking environment does not provide adequate support or reliable feedback for users to locate their vehicles easily.

_2. Differences Across the three personas_

| Aspect                  | Lone Driver                                      | Elderly Driver                                             | Female Driver                                           |
|-------------------------|-------------------------------------------------|-----------------------------------------------------------|--------------------------------------------------------|
| Speed of Navigation      | Fast walking pace                               | Slow, careful walking                                      | Moderate pace                                          |
| Use of Memory            | Relies on quick recall                           | Weak recall, easily forgets floor                           | Relies on partial recall and environmental cues       |
| Scanning Behaviour       | Checks aisles quickly, walks in straight paths  | Slow, detailed scanning, backtracks often                  | Methodical scanning, looks for familiar objects      |
| Decision-Making          | Makes quick decisions on where to search next   | Hesitates, unsure if on the correct floor                  | Decides based on surrounding cues (lifts, colours)   |
| Reaction Under Pressure  | Shows annoyance, speeds up                       | Becomes anxious, slows down                                 | Mild frustration but stays cautious                  |
| Use of Environmental Cues| Low, depends on memory                            | High, relies heavily on lift numbers, colours              | Moderate, uses both memory and cues                  |
| Common Issues Observed   | Floors look identical, fast misjudgment         | Confusion due to repetitive layout, fatigue                | Misinterprets similar pillars and zones              |
| Overall Behaviour Style  | Confident, fast-paced, but easily frustrated    | Vulnerable, easily confused, high mental effort            | Safety-oriented, balanced between caution and speed |


These differences show that while the lone driver prioritises speed, the elderly driver requires stronger support for memory and navigation. The female driver places more emphasis on safety and clarity, preferring cues that make her feel secure while searching.

_3. Conclusions from Comparing HTAs Across the 3 Personas for Task 2_

Comparing the three HTAs reveals several consistent challenges in the current car-finding process. All users rely heavily on memory and environmental scanning because digital tools like Google Maps do not work accurately indoors. This results in repeated loops of searching, moving between floors, and checking aisles, which makes the task time-consuming and cognitively demanding. The indoor environment, with identical layouts and poor differentiation, contributes significantly to user confusion and inefficiency.
Furthermore, user differences show that the current system does not effectively support individuals with varied cognitive and physical abilities. Younger drivers can complete the task despite frustration, but elderly drivers struggle the most due to weak memory, slow movement, and difficulty interpreting cues. The female driver also demonstrates a strong need for safety and reassurance during the search. These findings highlight the need for improved indoor navigation, clearer floor identification, automatic parking location tracking, and personalised guidance that caters to different user needs.

#### 2.3 HTA for Task 3 – Find Available Parking in Ladies Parking

User Type 1: Lone Driver

Video on Lone Driver finding available ladies parking slot: 
https://drive.google.com/file/d/1-sLfs6sK5_Fy2-VSKEn81lzi5_C0JyjW/view?usp=drive_link

_HTA (Textual Presentation) – Lone Driver Performs Task 3_
    
	0. Find an available ladies parking slot 
    
	1. Enter ladies parking area 
	
		1.1 Drive into the ladies parking area 
		
		1.2 Look around for available slots 
    
	2. Confirm ladies parking is full 
		
		2.1 Scan all visible rows 
		
		2.2 Notice all slots are occupied 
    
	3. Exit ladies parking area 
	
		3.1 Move to general parking
		
		3.2 Move to another floor 

	Plan 0. Do 1-2-3

	Plan 1. Do 1.1 then 1.2

	Plan 2. Do 2.1 then 2.2

	Plan 3. Do 3.1 or 3.2 depending on user’s choice

_HTA (Diagram Presentation) – Lone Driver Performs Task 3_
<p align="center">
<img width="632" height="581" alt="Lone Driver Task 3" src="https://github.com/user-attachments/assets/fbcbab57-db2f-4b66-a863-082a90699861" />
<br>
<em>Figure 2.3.1: HTA Diagram of Lone Driver doing Task 3</em>
https://drive.google.com/file/d/1iUxsWue-c1tUSHz5PvqcvFhPHexL2k3U/view?usp=sharing
</p>

User Type 2: Elderly Driver

Video on Elderly Driver finding available ladies parking slot: https://drive.google.com/file/d/1dNmT1Adfk_309-W-vK2WrfzI-kqeSvzc/view?usp=sharing

_HTA (Textual Presentation) – Elderly Driver Performs Task 3_

	0. Access Ladies Parking
	
	1. Drive into parking building
	
	2. Drive slowly into the designated ladies parking area
	
	3. Check if slots are available
		
		3.1 circle around repeatedly
	
	4. Park at the nearest available ladies parking spot
	
	5. Lock car and walk toward entrance

	Plan 0:

		Do 1 → 2 → 3 → 4 → 5 in order.

	Plan 3:

		Do 3.1 repeatedly until an empty slot is found.

_HTA (Diagram Presentation) – Elderly Driver Performs Task 3_
<p align="center">
<img width="771" height="381" alt="image" src="https://github.com/user-attachments/assets/6cd4ce10-0207-4430-bf41-f66da06c4bb9" />
<br>
<em>Figure 2.3.2: HTA Diagram of Elderly Driver doing Task 3</em>
https://drive.google.com/file/d/1LsGduGhJSxvQH_E_7WnFrS45s4wQbhfq/view?usp=sharing
</p>

User Type 3: Female Driver 

Video on Female Driver finding available ladies parking slot: 
https://drive.google.com/file/d/1Uev0CEO2Ubj9hHkvwJ7c3ohpAvCHv-yQ/view?usp=drive_link 

_HTA (Textual Presentation) – Female Driver Performs Task 3_

	0. Find parking at Ladies Parking
	
	1. Look for Ladies Parking
		
		1.1. Look for area covering with pink
	
		
		1.2. Look for ‘Ladies Parking’ sign 
	
	2. Drive through the lane at Ladies Parking area
	
	3. Look for an empty parking lot.
	
	4. Found all parking lot are occupied
		
		4.1. Drive to the next lane
	
	5. Exit Ladies Parking area
	
	6. Park the car at the free parking lot

	Plan 0:

		Do 1 - 2 - 3,

		If all parking lots are occupied, perform 4, then repeat 2 - 3.

		If after checking all lanes no space is found, do 5, then do 6 to park at the normal parking lot.

		If found a parking lot at the Ladies Parking area, do 6.

	Plan 1:

		Do any 1.1 or 1.2

	Plan 4:

		Do 4.1. repeatedly until a parking lot is found.

_HTA (Diagram Presentation) – Female Driver Performs Task 3_
<p align="center">
<img width="804" height="326" alt="image" src="https://github.com/user-attachments/assets/b590b46c-6a89-4e64-8372-7d50952ef17b" />
<br>
<em>Figure 2.3.3: HTA Diagram of Female Driver doing Task 3</em>
https://app.diagrams.net/#G1qFrA9UIbTLxcWmda8nuJRQmjPM3UqJeo#%7B%22pageId%22%3A%22SxMs9lPztFu86AbuZzzO%22%7D 
</p>

### Findings from the HTAs for Task 3 – “Find Available Parking in Ladies Parking”

_1. Information on HTA and Thinking Aloud Across the Three Personas_
   
The Hierarchical Task Analysis (HTA) for finding available parking in the Ladies Parking area reveals a common high-level process across all female users: they drive to the designated zone, perform an initial assessment of space availability, then conduct a critical review to confirm the spot is not misused, and finally, they either park or initiate a new, prolonged search loop. Thinking-aloud observations clearly show that this task is dominated not by navigation, but by two external failures: the misuse of reserved spaces by ineligible male drivers and weak enforcement by facility staff. All users experienced prolonged and frustrating search loops when their intended area was found to be full or compromised, leading directly to wasted time and increased fuel consumption. The discovery of misuse significantly raises the users' cognitive and emotional load, replacing the simple act of parking with the stressful task of safety assessment. Users spent mental effort scrutinizing nearby vehicles and their occupants, indicating a profound lack of trust in the system’s security. This state of dissatisfaction and anxiety contradicts the fundamental purpose of the Ladies Parking facility.

_2. Differences Across the three personas_

| Aspect                  | Lone Driver                                                                 | Elderly Driver                                                                                  | Female Driver                                                                                  |
|-------------------------|-----------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|
| Primary Frustration      | Time and Inefficiency. Frustrated by the waste of time and fuel caused by others' misconduct. | Safety and Vulnerability. Acute concern over physical security and the failure of the system to protect them. | Fairness and Inconvenience. Focus on the injustice of paying for a facility that doesn't deliver the promised exclusivity/safety. |
| Reaction to Misuse       | Annoyance, likely confrontation. More prone to expressing dissatisfaction or seeking quick resolution | Anxiety and Withdrawal. Becomes anxious, may abandon the area quickly to find a safer spot elsewhere, prioritizing avoidance over confrontation. | Dissatisfaction, Reputation Damage. Leads to a negative view of facility management; less likely to confront but will vent frustration. |
| Critical Safety Cue      | Parking Proximity/Access. Concerns are linked to convenient access and quick exit paths. | Occupants and Enforcement. Highly sensitive to seeing multiple male occupants in one car, triggering high-level security fears. | Designated Signage/Lighting. Assesses the safety based on clear signs and good lighting, which are negated by weak enforcement. |
| Overall Behaviour Style  | Confident, expects rules to be followed, quickly frustrated when they are not. | Vulnerable, easily distressed when security is compromised, high mental effort spent on risk assessment. | Safety-oriented, prioritizes reserved spots for peace of mind, views misuse as a breach of trust. |


_3. Conclusions from Comparing HTA Across the three Personas for Task 3_

Comparing the HTAs for Task 3 reveals that the task's failure is rooted in security, equity, and trust, rather than physical navigation. The current parking system fails to deliver the promised value of a safer, reserved space because it cannot guarantee exclusivity. This failure creates a hazardous environment, especially for the vulnerable Elderly Female Driver, whose anxiety levels rise sharply when system integrity is compromised. For all users, the task shifts from finding a spot to assessing potential danger, making the environment actively unsupportive. The most critical finding is the urgent need for reliable, strict, and visible enforcement to address the root cause: ineligible usage. To make Task 3 efficient and secure, the key design intervention must be an Automated Enforcement System such as smart sensors or license plate recognition that guarantees only eligible drivers can use the reserved spots, thereby restoring the core elements of security and fairness.

---

### 3.0 Design requirements

**Task 1-Find Available Parking Space**

**Features/Processes to Keep:**

1. Indicator lights (red/green)

* Users rely heavily on visual cues from sensors to determine slot availability.

* Keeping colour-coded indicators ensures users have quick, intuitive information about each slot.

2. Lane and floor scanning

* Iterative scanning is a natural behaviour; the system should allow users to check multiple lanes/floors efficiently.

3. Reserved slot differentiation

* Users need to distinguish reserved/disabled slots from regular slots.

* Maintaining clear signs and indicators for special slots is important to prevent misuse.

**New/Enhanced Features:**

1. IoT-Based Real-Time Parking Availability
* Each slot has a sensor (ultrasonic, motion, or smart camera) to detect occupancy.

* Data is sent to a central cloud server and reflected in real-time on the app.

* Reduces cognitive load, unnecessary scanning, and frustration.

2. Interactive Mobile Application

* Displays an interactive, color-coded map showing available, occupied, and ladies’ slots.

* Slots are organized by floor and zone for easier navigation.

3. GPS & Indoor Positioning

* GPS provides initial location estimates for outdoor approach.

* Bluetooth Beacons enable accurate indoor positioning, compensating for GPS instability in underground or enclosed areas.

4. Augmented Reality (AR) Navigation

* AR overlays directional arrows and distance markers on the live camera feed.

* Guides users step-by-step to the selected parking slot.

* Reduces search time and cognitive effort.

**Task 2 - Find Parked Car**

**Feature/Processes to Keep:**

1. Location Saving Function:

* Keep the basic ability for users to digitally save or log their parking location

* Provides a necessary fallback and a starting point for navigation.

2. Walking Navigation:

* Maintain the core process of providing directional walking guidance from the user's current location to the saved car location.
* Users are familiar with following on-screen digital maps and routes.

**New/Enhanced Features:**

1. Automatic Location Logging:

* Implement automatic saving of the car's exact GPS coordinates, floor, and zone upon transaction confirmation, removing the need for error-prone manual user input.

2. Indoor Positioning Technology:

* Switch from unreliable conventional GPS to Bluetooth Beacons or Wi-Fi triangulation for accurate and precise indoor positioning.

* Accurately determine the car's location down to the specific bay and floor.

3. Augmented Reality (AR) Navigation:

* Introduce an AR overlay on the live camera feed that displays clear directional arrows, distance markers, and visual cues.

* Reduces search time and cognitive effort, offering a clear line of sight to the car.

4. Simplified Interface & Voice Guidance:

* Introduce a simplified "Find My Car" interface with large, clear buttons and supplementary voice guidance.

5. Step-by-Step Directions:

* Provide step-by-step guidance that incorporates changes in floor or zone, going beyond simple line routing to assist with orientation in complex structures.

**Task 3 - Find Ladies' Parking**

**Feature/Processes to Keep**

1. Reserved Slot Differentiation:

* The concept of a physically distinct and designated area which is pink for female drivers must be maintained.

* This differentiation is key to providing the necessary sense of security and priority.

2. Safety/Proximity Focus:

* Keep the process of placing Ladies' Parking in high-traffic, well-lit areas near entrances or security points.

* Supports the core purpose of minimizing risk and ensuring quick, safe access.

**New/Enhanced Features**

1. Biometric Access Barrier:

* Implement a physical entry barrier system at the Ladies' Parking zone entry.

* The barrier must execute a real-time facial scan of the driver for verification against a secure database.

2. Secure Registration & Verification:

* Introduce a mandatory in-app process for female drivers to register their identity by using IC and selfie verification to gain access eligibility.

3. Instant Access Denial Feedback:

* The barrier system must provide an immediate digital alert or audio message directing non-verified drivers to general parking to reduce conflict and increase enforcement.

4. Real-Time Slot Availability:

* Integrate IoT sensors in Ladies' Parking slots to detect occupancy and display the real-time available status on the ParkMate app map.

5. Direct Navigation Guidance:

* The app must offer turn-by-turn navigation specifically to an available and eligible Ladies' Parking slot once access is secured.

* Slots must be clearly coded Pink on the app map for quick visual identification.

### Functional Requirements (FR)

| ID   | Requirement Description |
|------|-------------------------|
| FR1  | The system must display the real-time availability status (Vacant/Occupied) of every parking slot on an interactive map. |
| FR2  | The map interface must use color-coding to differentiate slot types: Green (Vacant), Red (Occupied), Pink (Ladies’ Parking). |
| FR3  | The user must be able to filter the parking map view by floor and/or zone. |
| FR4  | The user must be able to select a vacant slot on the map and initiate turn-by-turn navigation directly to that spot. |
| FR5  | The system must automatically log the car’s GPS coordinates, floor, and zone upon confirmation of the parking transaction. |
| FR6  | The system must provide GPS-based walking navigation from the user’s current location to the logged car location. |
| FR7  | The system must offer an Augmented Reality (AR) overlay that guides the user back to their car, displaying real-world directional cues. |
| FR8  | The system must allow female drivers to register and verify their identity using their IC number (for gender check) and a live selfie (for AI verification). |
| FR9  | The parking barrier system must execute a real-time facial scan of the driver and cross-check it against the secure database for access to the ladies' parking area. |
| FR10 | The barrier system must provide a digital alert or audio message directing non-verified drivers (i.e., male drivers) to general parking upon denial. |


## Non-Functional Requirements (NFR)

| ID   | Requirement Description |
|------|-------------------------|
| NFR1 | The map interface must prevent the user from selecting or navigating to an already occupied (Red) or unverified (Pink) parking spot. |
| NFR2 | Upon successful logging of the car’s location, the app must provide an immediate, non-intrusive confirmation message showing the recorded location details. |
| NFR3 | The availability status displayed on the map must update within 2 seconds of the central server receiving data from the IoT sensors. |
| NFR4 | The Ladies’ Parking registration process must include a clear statement on how the IC number and facial data are securely stored and used only for access verification. |

---

## User Requirements

| User Group                        | Characteristics |
|----------------------------------|----------------|
| Lone Driver                        | Lone drivers who focus on quick, efficient parking. |
| Female Driver                      | Registered female drivers who prioritize security and convenience in designated spaces. |
| Elderly Driver / Low Spatial Awareness | Individuals who may struggle with complex interfaces, small text, or spatial orientation in large car parks. |
| Parking Facility Operator          | Staff responsible for monitoring the facility, ensuring smooth traffic flow, and managing the security of designated areas. |

---

## Environment Requirements

| Requirement Type           | Description                                                                                           | Design Implication |
|----------------------------|-------------------------------------------------------------------------------------------------------|------------------|
| Physical Environment (Indoor) | The application must function reliably within multi-level, covered parking structures where conventional GPS signal is weak or non-existent. | Requires reliance on indoor localization technologies (e.g., Bluetooth beacons when GPS is weak). |
| Network & Connectivity      | Users must be able to use the app in areas with variable cellular and Wi-Fi coverage, especially in underground levels. | Core features like “Find My Car” AR navigation should minimize reliance on constant network connectivity once the initial location data is logged. |
| Facial Recognition Station  | The Ladies’ parking barrier must operate reliably under varying conditions, including rain and low-light conditions. | Requires robust sensors and AI models capable of high accuracy despite environmental factors. |
| Social & Legal Context      | The system must comply with all data privacy laws regarding the storage and use of sensitive biometric and identification data (IC number / selfie). | Essential for defining the scope of transparency and security/encryption. |



