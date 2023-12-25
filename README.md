# Parking_Assistance_on_a_Crowded_Streets_Using_Embedded_Systems_and_IoT

Overview

Traffic congestion caused by vehicles is a dire drawback on a world scale and it's been growing exponentially. Automotive parking drawback may be a major contributor and has been, still a serious drawback with increasing vehicle size within the luxurious phase and confined parking areas in urban cities. Finding a car parking zone may be a routine (and typically frustrating) activity for several individuals in cities around the world. This search burns a huge amount of fuel each day. Because the world population continues to urbanize without a well-planned system, the automotive scenario can worsen. 

There are three popular methods of vehicle detection systems: 

•	Overhead level detector  
•	Ground level detector  
•	Underground level detectors

Working

The overhead level detector system comprises surveillance video cameras. Video camera sensors have accuracy issues in recognizing a tiny low vehicle (e.g., a traveler car) behind a giant vehicle (e.g., Toyota Innova or Xylo) in engorged conditions and area units laid low with illumination issues, atmospheric condition conditions, shadows, water, etc. Whereas Vehicle detection using ground detectors is done by using different types of sensors like Pneumatic sensors, magneto sensors, video image processors, IR sensors, etc. However, this has the downside that if 2 vehicles cross the tubes at an equivalent time then the direction cannot be accurately determined. Therefore, the foremost economical methodology to find a vehicle is by underground level detector that uses inductive loops to detect a vehicle whose detection zone is most, cheap, and insensitive to any climate. Underground-level detectors that are installed beneath paved surfaces have the advantage of accuracy in investigation high capability in classifying vehicles of every type and need less maintenance. 


This method eliminates all the issues associated with parking on jam-packed roads. The proposed system uses inductive loops that help in detecting the vehicle and conjointly classify the categories of vehicles e.g., bicycle, motorbike, car, or bus. Sampling the loop at a high frequency ends up in a singular signature for every vehicle granting classification of the build. The setup consists of RF transmitters that transmit the data to the gateway. If the loop detects the vehicle the RF module sends the data to the gateway and classifies the car park as vacant or occupied. Gateway consists of ATMEGA16 which allows us to interface the RF module and conjointly provides enough fixed storage to store the information about the status of the loop. 



To access the information regarding the occupancy of the parking slots an internet page has got to be designed which can be accessed by GPRS-enabled handsets. The gateway sends the information to the cloud which may be accessed by the web page. The webpage can show the status of parking slots by indicating the areas as vacant or occupied and conjointly classifies the type of vehicle already parked. The conclusion of the good town is currently turning into potential with the emergence of the Net of Things (IoT) that radically evolves the present internet into a network of interconnected objects, like sensors, parking meters, energy mensuration devices, and actuators. Wherever each object is unambiguously identiﬁed and accessible to the network, its position and standing are renowned.

