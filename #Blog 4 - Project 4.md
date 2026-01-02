# Project Part #4: Prototyping and Evaluation
## 1.0 Introduction
To test the usability of the ParkMate indoor smart parking application, a controlled indoor parking environment was used to resemble the scenario of a shopping mall parking. Since the testing tasks for users are conducted by different members, the time will be depending on their free slot. During the project evaluation phase, the tools that were used to evaluate the prototype included a mobile phone to access the interactive prototype, the ParkMate prototype interface on figma, and the task instruction scripts, which are the index cards. 

The testing focused on three main tasks which are locating an empty parking spot, finding the car after leaving the mall, and access ladies' parking with the help of verification features. Three participants were involved in the testing, each corresponding to one of the user personas created in the project, which are elderly driver, female driver and lone driver.

Chan Siew Ching was in charge of testing elderly driver’s user group, Chia Thung Thung was responsible for the female driver user group, and Wong Ya Jing was responsible for the lone driver user group. To assess usability, the smoothness of navigation, and the overall customer experience, the participants were observed while they were finishing the tasks that were given to them.



## 2.0 Screenshots of Prototype
### 2.1 Welcome Page
<img width="181" height="405" alt="Image" src="https://github.com/user-attachments/assets/504c283b-da40-403d-8e26-d8575be5da29" />	


### 2.2 Home Page

<img width="174" height="367" alt="Image" src="https://github.com/user-attachments/assets/8a3e19a8-fe76-4f02-ace4-19d1f175c0bb" />


The prototype provides a clear Home Screen, allowing users to initiate their parking-related tasks without prior system knowledge. The Home Screen functions as the main navigation hub, presenting essential features in a simple and intuitive layout.
The interaction flow is designed to support three core user tasks:
* Find Parking – enabling users to locate available parking spaces efficiently.
* Find My Car – assisting users in navigating back to their parked vehicle.
* Ladies Parking – providing access to designated parking spaces tailored for female users.

A persistent bottom navigation bar (Home, Notifications, Profile, Wallet, Settings) is included to ensure consistent and easy navigation throughout the system.



### 2.3 Task 1 - Find Parking

<img width="677" height="443" alt="Image" src="https://github.com/user-attachments/assets/daf7c86a-a8c6-4e01-8bc1-ebaed082c084" />


Interaction Flow:

Home Page (Find Parking) → Indoor Parking Map → Select Floor and Parking Zone → Search for Available Parking Spaces








Display Parking Slot:

<img width="601" height="400" alt="Image" src="https://github.com/user-attachments/assets/32f797a8-ecc3-4878-8f40-f8fc0edcc4ea" />




Interaction Flow:

Display Colour-coded Parking Slot Map → Select Empty Parking Slot → Success Message Displayed (“ You have selected Floor _ , Zone _ , Slot _ ”)
If a selected slot is occupied (red) → Error message displayed → Prompt user to choose again




AR Navigation to Selected Parking Slot:

<img width="714" height="371" alt="Image" src="https://github.com/user-attachments/assets/3a388f32-40bf-4fc3-a52b-6a8cbed81347" />


Interaction Flow:

Request Camera Access → Start AR Navigation → Navigate to Selected Parking Slot → Arrival Confirmation Message Displayed (“ You have arrived! Exit Find Parking? ”)

### 2.4 Task 2 - Find My Car

<img width="632" height="426" alt="Image" src="https://github.com/user-attachments/assets/e4f7c8ca-35c7-415e-84b1-4ca0346b0f67" />


Flow 1: Locate Car

Home Page (Find My Car) → Auto Retrieve Car Location → User chooses to locate car

<img width="587" height="405" alt="Image" src="https://github.com/user-attachments/assets/70d1f52d-a66f-4547-a2f7-4ae16d08236e" />


Flow 2: Payment

Select Parking Slot Payment → Choose Payment Method → Payment Confirmation →
* Success Message
* Error Message → Prompt User to Retry

<img width="707" height="362" alt="Image" src="https://github.com/user-attachments/assets/c3cd8432-9ad9-4e1c-a183-594128dc2c30" />


Flow 3: Find Car with AR Navigation

Display Car Location (Floor _, Zone _, Slot _) → Request AR Camera Access → Start AR Navigation → Navigate to Parked Car → Arrival Confirmation Message (“You have arrived!”)

### 2.5 Task 3 - Ladies Parking

<img width="667" height="676" alt="Image" src="https://github.com/user-attachments/assets/33767dbe-752a-4ad1-a9ae-11068e437b68" />


Flow 1: Register

Home Page (Ladies Parking) → Enter Personal Details → Upload Personal Profile & IC Picture → Verified Success Message → Profile Updated with Details

<img width="584" height="386" alt="Image" src="https://github.com/user-attachments/assets/5acf94c7-f66d-4345-848a-122586f207ad" />


Flow 2: Navigate to Ladies Parking

Navigate to Ladies Parking → Request AR Camera Access → Start AR Navigation

<img width="714" height="370" alt="Image" src="https://github.com/user-attachments/assets/029f32ad-b47a-4aa0-a703-1a9886dc340b" />


Flow 3: Barrier Authentication

Arrived at Ladies Parking → Request Face Scan at Barrier →
* Success Message → Proceed to Select Parking Slot
* Failed Message → Retry (up to 3 attempts) → More than 3 attempts → Redirect to General Parking

<img width="720" height="369" alt="Image" src="https://github.com/user-attachments/assets/309b599b-5074-404e-8e63-d46dbf2be003" />


Flow 4: Select Parking Slot & Navigation

Display Ladies Parking Map → User Selects Slot → Start AR Navigation → Arrival Confirmation Message (“ You have arrived! Exit Ladies Parking? ”)



Prototype Link: 

https://www.figma.com/proto/0dZH1pbdCYCbmHTKx1VnnR/HCI-Final-Prototype?node-id=4-109&p=f&t=TXBcAkgZjmxfjxBW-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=4%3A109 

## 3.0 Briefing Notes - Prepared by Ung Yii Jia

Thank you for taking part in this usability testing session.


Today, you are going to try out ParkMate - an indoor smart parking and navigation app that helps you find your way in indoor multi-level parking areas of places like malls. This app is basically meant to make things quicker, less stressful and less confusing when you park, locate your vehicle and use ladies' parking in big indoor car parks.

Without being informed about available parking spaces, drivers in many indoor parking facilities usually enter and spend time driving around to find a free space. Furthermore, after shopping, some drivers forget the exact spot where they parked their cars, especially in cases of weak GPS signals indoors. Another problem is the misuse of ladies' parking areas which lowers the safety and comfort of female drivers.

ParkMate aims to solve these problems by:
* Giving users timely updates on available parking slots
* Locating your car after the shopping trip
* Making ladies' parking charge safe and fair


Conceptually, the system utilizes such technologies as sensors, indoor positioning, and navigation support to enhance the parking experience. This testing session is not a test of you but a test of the application design. There are no right or wrong answers.

Kindly behave as you would in a normal situation, talk if you can about your thoughts, and flag anything that troubles or puzzles you. Your input will contribute to making the system more user-friendly and better designed.


## 4.0 Testing with users
### 4.1 Task 1 - Finding Car Park
4.1.1 User 1 - (Elderly) 
https://drive.google.com/file/d/1u4IYEevKOWOgN14J-GPbCdE-FvaMCaTw/view?usp=drive_link 

4.1.2 User 2 - (Female) 
https://drive.google.com/file/d/1K8cXEj2STLriVjWf1XZY0PUgwPVHKVic/view?usp=drive_link

4.1.3 User 3 - (Lone)
https://drive.google.com/file/d/1R8eEocAZoR5T6la0LCM0W4VAkY6K3UCe/view?usp=drive_link 

### 4.2 Task 2 - Find My Car
4.2.1 User 1 - (Elderly)
https://drive.google.com/file/d/17YXwLn1KI6hxcMSrld7U0Ht7FIq1PA-W/view?usp=drive_link 

4.2.2 User 2 - (Female)
https://drive.google.com/file/d/14Z7yyBov69dfFryjq5bqy1UUQXBQfQAW/view?usp=drive_link

4.2.3 User 3 - (Lone)
https://drive.google.com/file/d/1CB6t9FCTO2DP0wU2CiQ7633YWp5zYMQd/view?usp=drive_link 

### 4.3 Task 3 - Find Ladies’ Parking
4.3.1 User 1 - (Elderly) 
https://drive.google.com/file/d/1lvWFEGacKRMccE9WGVmVSlQUYklnb0gO/view?usp=drive_link 

4.3.2 User 2 - (Female) 
https://drive.google.com/file/d/1ghvWWdDznUQ0cFDjoebxjkiMsCPrpLPL/view?usp=drive_link

4.3.3 User 3 - (Lone)
https://drive.google.com/file/d/1tbtjYY_yF-7nwogoJCsdHCRmU7cvvBto/view?usp=sharing 

## 5.0 Observation
### 5.1 Elderly Driver - Prepared by Chan Siew Ching
Interview Video: https://drive.google.com/file/d/1mGw6dcW-mCKaqre5PrLJyOZ4SvKhoGp8/view?usp=drive_link 

Task 1 - Find Parking

The user opens the ParkMate app and looks for an available parking space. She selects a vacant slot shown on the map and starts following the AR navigation provided by the system. This distance indicator helps her confirm that she is moving in the correct direction and getting closer to the selected parking space. The user realizes she has arrived at the correct parking slot once the meter countdown reaches zero, 

Task 2 - Find My Car

After parking, the user wants to save the location of her car. She uses the “Find My Car” function to check the current parking details. She views the floor level and zone that are detected at that moment. She carefully reads the parking information to make sure it matches where she parked. She then checks the parking duration, her personal details, and the parking fee before proceeding with payment. This helps her feel confident that the information is correct before leaving.

Task 3 - Ladies Parking

The user follows the navigation guidance and drives toward the ladies’ parking zone while watching the distance indicator decrease as she gets closer. When she arrives at the entrance, she understands that she must scan her face at the barrier. She scans her face and sees a green tick, which tells her that access is granted. After entering, she uses the app to look for an available ladies’ parking slot, and parks her car successfully.

Post-Task Interview Highlights
* The interface is clear, simple, and easy for the user to understand at a glance.
* Find it helpful for locating a parking space compared to traditional parking methods.
* The user feels secure using face recognition that is linked to her personal profile.
* The colors and icons are intuitive and straightforward, making navigation easier.
* The distance indicator is helpful to detect how close the selected parking location is.

### 5.2 Female Driver– Prepared by Chia Thung Thung
Interview Video: https://drive.google.com/file/d/1Sf9tCAQY6aDjPDdRIMboKuetl-1vx9gU/view?usp=drive_link

Task 1 – Find Parking

User 2 completed the task smoothly. She immediately recognized the color-coded parking slots and correctly identified green as available and red as occupied. She selected a green slot without hesitation and received clear confirmation feedback. The AR navigation prompt was intuitive, and she allowed camera access without confusion. The arrival confirmation message was noted and acknowledged before exiting the task.

Task 2 – Find My Car

The user appreciated the automatic car location retrieval, which required no manual input. She initiated AR navigation and found the directional arrows and distance indicators clear and helpful. She commented that the guidance was “straightforward” and did not feel lost at any point. The payment flow was also completed without error, and she understood both success and error messages clearly.

Task 3 – Find Ladies’ Parking

User 2 successfully navigated to the Ladies’ Parking section. She understood the face verification requirement and proceeded confidently. The green checkmark after successful verification was immediately recognized as “access granted.” She mentioned that the process felt secure and well-integrated. 

Post-Task Interview Highlights
* Found the interface visually clear and consistent.
* Liked the use of pink for Ladies’ Parking, which felt intuitive and gender-inclusive.
* Expressed trust in the facial recognition system for security.
* Suggested that voice guidance during AR navigation could be helpful for hands-free use.

### 5.3 Lone Driver- Prepared by Wong Ya Jing
Interview Video: 
https://drive.google.com/file/d/1FxfJYFawddRydQw8u5uShHaezUvnvQjv/view?usp=drive_link


Task 1 - Find Parking

The user was able to identify available spots quickly thanks to the Green/Red Pin metaphor. She selected a green slot without hesitation. She is able to find the parking spot quickly by following the navigation. She spent about 5 seconds to confirm the parking slot she arrived is aligned to the parking slot she chose.

Task 2 - Find My Car

The user is aware that she usually forgot where she parked her car after shopping. Therefore, she used the “Find My Car” feature to pin her parked slot. The user needed about 5 seconds to confirm the receipt information when she wanted to pay the parking fee. The AR navigation gives clear direction, so the user didn’t feel lost when using the “Find My Car” feature.

Task 3 - Find Ladies’ Parking

The user successfully navigated to the Ladies’ Parking feature. The user understands the needs of uploading a selfie and Identification Card for verification. The user is aware that she enters the Ladies’ Parking page when the interface changes to Pink. The user is able to find a parking spot easily in the Ladies’ Parking Zone.

Post-Task Interview Highlight
* Use of pins, symbols, and color codes was intuitive and easy to understand
* The apps save time as it helps locate parking slots and cars easily.
* Facial recognition verification made the parking experience feel more secure
* AR navigation was very helpful as it showed real-time images, so it's easy to recognize landmarks along the way

## 6.0 Findings
### 6.1 Elderly Driver - Prepared by Yeoh Huey Ting

During usability testing, the elderly user was able to complete all three ParkMate functions smoothly, showing that the app is intuitive and easy to navigate. For Find Parking, she quickly spotted and selected an available slot on the color-coded map, which made it immediately clear which spaces were vacant, occupied, or reserved for ladies. The AR navigation guided her step by step, with live distance indicators that helped her feel confident she was heading in the right direction, and the instructions made it easy to know what to press next without any hesitation. In Find My Car, the app provided confirmation details like floor level and zone, giving her reassurance that her vehicle had been correctly located. Following the AR directions back to her car felt effortless, and the distance updates allowed her to track progress and navigate without confusion. For Ladies Parking, she completed the sign-up process easily and then followed the app’s guidance to reach the designated zone, successfully selecting a parking slot. Across all three tasks, the consistent interface, clear visual cues, and step-by-step AR guidance helped her move confidently from one feature to another, applying what she had learned in earlier tasks and making the overall experience feel intuitive and stress-free.

Although her experience was largely positive, a few small adjustments could make the app even easier and more comfortable to use. Slightly larger buttons and more spacing for interactive elements, like “Confirm” and AR navigation controls, would reduce hesitation and make interactions smoother. The Find My Car confirmation screen, which displays multiple pieces of information at once, could benefit from showing only the most important details first and revealing additional information when needed. These simple refinements would build on ParkMate’s already user-friendly design and make it even more accessible, reassuring, and efficient for elderly drivers.


Positive Findings:
* Color-coded parking maps allowed quick understanding of parking status.
* Step-by-step guidance clearly indicated what to press next.
* Find My Car confirmation reduced uncertainty and increased user confidence.
* Distance indicators and AR real-time feedback helped the user gauge progress and navigate effectively.
* The consistent interface and visual cues made moving between tasks smooth and reassuring.

### 6.2 Female Driver - Prepared by Chia Thung Thung
Usability Problems Identified:
The usability testing with User 2 yielded overwhelmingly positive feedback, demonstrating that the core design of ParkMate is both intuitive and highly effective. The color-coded parking system using green for available, red for occupied, and pink for ladies' parking was immediately understood without any explanation, effectively translating real-world visual conventions into a seamless digital experience. The Augmented Reality (AR) navigation was particularly praised for its clarity and practicality; the directional arrows and live distance indicators provided confident, step-by-step guidance that completely eliminated the stress and confusion typically associated with navigating large, multi-level indoor parking lots. Furthermore, facial recognition verification for ladies' parking was strongly endorsed, as it not only streamlined access but also significantly enhanced the user's sense of safety and exclusivity, a critical factor for female drivers. The consistent and clean interface design received notable appreciation for its learnability, with uniform navigation patterns and visual cues enabling the user to move effortlessly between tasks without confusion or delay.
While the overall experience was rated highly, a few thoughtful refinements could elevate the app from excellent to exceptional. Incorporating optional voice guidance during AR navigation would provide a valuable hands-free alternative, enhancing safety and accessibility for users who are actively driving. Clarifying the error recovery path after multiple failed verification attempts by offering clear options such as "Try Again Later" or "Contact Support" would improve user confidence during edge-case scenarios. Finally, slightly increasing the tappable area for parking slot selection would ensure interaction accuracy for all users, including those interacting while on the move. These minor enhancements align with the user-centered design principles already evident in the app and would further improve ParkMate as a leading solution in smart parking navigation.


Positive Findings:
* Color coding (green/red/pink) was universally understood.
* AR navigation was considered intuitive and helpful.
* Face verification enhanced perceived security.
* The interface was consistent and easy to learn.

### 6.3 Lone Driver – Prepared by Ung Yii Jia
Usability Issues Identified:
User 3's usability testing with ParkMate showed that the user had a predominantly positive reaction which suggests that the main functions of ParkMate are quite straightforward and with only a few usability problems. The parking availability feature was extremely comprehensible, since the green and red boxes gave the user the immediate and unambiguous understanding of the availability of parking and the labels merely confirmed the understanding. AR navigation to your car was a big success as well, the directions were very clear and the user received additional information of distance and was given the opportunity to use real life references so that the feeling of being lost never came. Moreover, the facial recognition security check for ladies' parking was not only a necessary security feature but also strengthened user’s trust. A smooth run of the application with the consistent use of icons, symbols, and navigation layout further resulted in a straightforward and less time-consuming experience.
Despite the overall high usability, a small opportunity for improvement was identified in the process of locating available parking, as reflected by the 4/5 ease-of-use rating. In larger parking areas, users may still spend a short amount of time scanning the map to identify the most suitable parking spot. This could be improved by adding a brief availability summary by level or zone, or by slightly enhancing the visual emphasis on nearby available spaces. These minor refinements would further reduce user effort and improve efficiency, strengthening ParkMate’s already effective and user-centered design.

Positive Findings:
* Parking availability indicators were clear and easy to understand.
* AR navigation provided accurate, stress-free guidance.
* Facial recognition increased perceived security and trust.
* Icons, labels, and overall interface design were intuitive and consistent.
