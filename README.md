# Contact-Tracker
ABSTRACT
The World Health Organization (WHO) has declared the COVID-19 to be a pandemic. Mobile applications (‘apps’) can support health authorities at national and EU level in monitoring and mitigating the ongoing COVID-19 pandemic, facilitate the organization of medical follow-up of patients and provide direct guidance to citizens on playing their part in the control of the disease. In a few countries, both within the EU and worldwide, national authorities or developers have announced the launch of apps offering varying levels of functionality to support the fight against the virus. Member States recognize the value of such apps needs to be considered within the context of wider public health measures and the stage of the spread of the contagion. Apps that support contact tracing have emerged as the most promising, from a public health perspective. These apps offer the possibility of alerting/ warning citizens that they have been in close proximity with an individual who has been confirmed positive for Covid-19. This report aims at coming up with an effective application that can help with contact tracing to control the COVID-19 pandemic worldwide without individuals having to be on long queues at stores just to write down their contact information. This application focusses more on doing away with the need for pen and paper. The mobile apps were used to monitor self-isolated individuals, identify individuals not wearing masks, whether they had close contact with an infected person, provides exact time and place of the encounter, and possible risk of infection. Contact tracing is found to be an essential public health approach to fight the spread of COVID-19 pandemic and other novel infectious diseases. However, caution is warranted to generalize the usability of apps, especially in the lower middle-income countries, and to address the concerns regarding data anonymizing, data privacy and usage, and data rights. 
 
INTRODUCTION
Governments and health authorities across the world, are working together to find solutions to the COVID-19 pandemic, to protect people and get society back up and running. Since COVID-19 can be transmitted through close proximity to affected individuals, public health officials have identified contact tracing as a valuable tool to help contain its spread. Even if most physical distancing measures are continued, other public health measures will be needed to control the epidemic. Contact tracing via conventional methods or mobile app technology is central to control strategies during de-escalation of physical distancing. Therefore Software developers’ are contributing by crafting technical tools to help combat the virus and save lives.  Contact tracing is a widely adopted surveillance system that is used to identify, evaluate, and handle people who have been exposed to novel infectious diseases. The mobile phone apps using a digital technological system is used as a surveillance system to control the COVID-19 pandemic, digital contact tracing apps have been proposed as a method of controlling the spread of Covid-19. The effectiveness of digitalizing contract tracing depends largely on adequate levels of uptake thus whether the user downloads and registers on the application and engagement, such as the extent to which the application is used and its components. The issue at hand is, despite the efforts put in place by institutions for individuals to observe and or follow regulations put forth by the ministry of health and the charges people can face if they don’t obey regulations, individuals still act against this rules. One may wonder if this is because of ignorance or not believing if corona virus really exists or the world is just being pranked. Contact tracing is normally carried out manually by public health authorities. This is a time-consuming process where cases are interviewed to determine who they remember being in contact with from 48 hours before symptom onset and up to the point of self-isolation and diagnosis. Longer contact duration and closer proximity means a higher risk of infection. This process relies on the recall of the case by the patients – who may be very ill at the time of interview – both in terms of who they have met and the proximity and duration of that meeting, as well as the ability to produce names and phone numbers of these people. Such manual processes rely on the patient’s memory and obviously cannot trace individuals who have been in contact with the patient but are who are unknown to him/her. Hence, I come with a solution that can help with contact tracing automatically using a mobile application that will be mostly dependent on Bluetooth instead of the pen and paper method that is mostly used across the country (Botswana).

OBJECTIVES
-	To evaluate the already existing COVID-19 applications and monitor their performances
-	To come up with the most effective way of solving loopholes of the existing apps
-	To help identify who an individual has been in contact with.
SCOPE 
This common approach applies to apps that are voluntarily installed, and alert people who have been in proximity for a certain duration to an infected person, to get tested or to self-isolate. The app is liable to be used by both individuals and institutions. A common approach to other functionalities, in particular on information and symptom tracking functionalities, is likely to be developed in future iterations of the toolbox.

 
LITERATURE REVIEW
Corona Tracer BD
Corona Tracer BD is an initiative by the ICT Division and DGHS with the objective of bringing the people of Bangladesh together in the combined fight against COVID-19. The technology is powered by Shohoz Ltd. This app utilizes Bluetooth signal to understand if you are near another Tracer app user. It will help you in identifying whether you are at risk of COVID-19 infection, by checking if you have been in recent contact with an infected individual. If your case seems risky, you will be able to seek medical help at the earliest and go into self-isolation.
It also has the following features:

-	Information on various topics such as symptoms, what to do in case of suspected infection, etc
-	Locating nearby health and testing units.
-	In case of a suspected infection, the citizen can check if the symptoms are compatible with COVID-19's, and if so, they will be instructed and sent to the nearest basic health unit.
-	Official news area of the government for viewing the latest statistics on the pandemic.
Disadvantages:
-	 It doesn't specify zone wise number of corona patients and how someone will know if there's anyone infected nearby him.
-	 The process requires users to log corona data manually.

Bsafe
BSafe is the Official Digital Contact Tracking Application by Govt. of Botswana. This app records entry and exit of persons who have valid permits around the country so that contact tracing is made easier when a user is diagnosed with the disease. 
Benefits: 
-	it will help us get rid of paperwork
-	it cuts time from queuing for long hours
Disadvantages: 
-	when you view register some staff members visitors scanned earlier, do not appear in the register but only those recently scanned, hence making it difficult to monitor its usage by large organizations with many staff members or visitors.
-	Developers should not restrict users from editing our personal details in case we mistyped without realizing or when we later change phone numbers. As it stands once you confirm details you will not be able to edit anything 
-	 I wanted to scan the QR code and the app prompted me to update it because a newer version was available. There was no option of "update later". 
TECHNOLOGY ASSESSMENT
Bluetooth Auto Connect is a solution to your Bluetooth connection problems. It automatically tries to connect to your Bluetooth devices when Bluetooth has been turned on or when your device screen goes on. First, connect and pair with your Bluetooth device manually (this is a requirement) and then just turn off and on Bluetooth (or leave Bluetooth on and turn the screen on) and it will auto connect. The Global Positioning System (GPS) is a satellite-based navigation system made up of at least 24 satellites. GPS works in any weather conditions, anywhere in the world, 24 hours a day, with no subscription fees or setup charges. The contact tracker app utilizes Bluetooth and some elements of GPS services so, I concluded that since it is a mobile application which means it will be installed on smartphones especially android phones as apple does not support Bluetooth, it will be a success as most people own smartphones and the good thing is it not entirely internet intensive. Studies have shown that over 60% of people in Botswana own smartphones and are able to use them. Therefore, the technological aspect of the mobile app is doable.
CHALLENGE DEFINITION

Id
Challenge 001
Category
Health
Title
Contact Tracker
Background
 In December 2019, a mysterious case of pneumonia was first reported in Wuhan, Hubei Province. The source of transmission of this case is still unknown, but the first case was linked to the fish market in Wuhan. So to trace covid-19 we are currently using the pen and paper method where people are required to write down their contact information so that they can be contacted in case a covid-19 positive case has been confirmed and it has been traced back to a certain place. So contact tracker application comes in handy to try and replace the use of pen and paper.
Description 
This application provides the users with a opportunity to track down who they have been in contact with and it also shows the location of where they met everyone whose information is recorded into their contacted users table. It uses Bluetooth and GPS services.  This sharing of contact information occurs on users who use smartphones which are Bluetooth enabled. If users become 2 meters or less close to each other their mobile apps will then share information with each other, thus each record information about another one in their contacted users’ tables. This application aims at bettering the weaknesses of the already developed apps.
Skills required
-	Problem solving
-	Analytic skills
-	Programming language skills
-	Creativity 
Hardware and software needs
-	Flutter 
-	Flutter plugins
-	Android studio
-	A computer (laptop)
-	Android phone
Stakeholder
Public
