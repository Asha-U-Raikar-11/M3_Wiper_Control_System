FINAL REPORT:

# ABSTRACT:

Vehicle windshield wipers play a important role during extreme weather conditions by wiping the rain water, dust, fog, mist continuously over the course of time and they help us give a clear vision to the driver. Wipers are designed and made to clear the unwanted dust, water etc. from a windscreen. It is Prime duty to improve the safety facilities in all automobiles and vehicles. The system is used to activate the Wipers manually. Due to this issue many engineers and designers and developers have contributed to the research and developement of Automatic Windshield Wiper Functionality in automobiles. The Windshield Wiper Functionality of domestic cars primarily consists of three systems,

#Two wipers and theis respecive arms
#A mechanism
The concept of this proposed wiper system is similar to that of all the other exesting wiper systems. A wiper normally consists of metal arm, one end pivots and the other end has a long rubber blade-attached to it. The purpose of the project is to design the windshield wiper control system for the safetiness of the people who drive heavy automobiles and domestic four-wheeler vehicles.

RESEARCH PROGRESS:

The automated Wiper system is used to detect rainfall and activate the wiper system automatically without the drivers inuput contol

KEY TERMS:

STM32 Discovery Board
Microcontroller

# BASIC REQUIREMENTS:

INTRODUCTION:

Wiper system is a inseperable aspect is modern automobiles especially 4-wheelers. They are designed and made to clear the dust, water, fog, mist from the windshield and give driver a better and clear vision of the road ahead. The parts are visible from outside the car. It has a rubber blade made of silicon, wiper arm attached to the silicon blade, extendable linkage, pivots. Existing system used manually used to activate the wiper and the process of pulling up wiper and the driver needs to switch ON and OFF the control system.

HIGH LEVEL REQUIREMENTS:

ID	     DESCRIPTION    	       STATUS
HR_01   Car in ACC mode 	    Implemented 
HR_02	  Car in ignition mode 	Implemented 
HR_03	  Turning on the wiper  Implemented
HR_04	  Turning off the wiper Implemented
 
LOW LEVEL REQUIREMENTS:

 ID	    DESCRIPTION	            STATUS
 LR_01	ON                  	 Implemented
 LR_02	Press wiper switch 	   Implemented
 LR_03	Microcontroller supply  Implemented
 LR_04	Activating wiper blades Implemented
 LR_05	OFF                    	Implemented 

# TEST PLAN:

HIGH LEVEL TEST PLAN:

TEST ID	          DESCRIPTION	                    TEST TYPE	             OUTPUT EXPECTED     	    FINAL STATUS
H_01    	Moving the wiper along windshield 	   Secnario based test	           PASS 	            IMPLEMENTED
H_02	    wiper comes back to the rest position  Boundary value based test       PASS	              IMPLEMENTED 

LOW LEVEL TEST PLAN:

TEST ID         	DESCRIPTION	          TEST TYPE	            OUTPUT EXPECTED	         FINAL STATUS
L_01           	Powering ON the Car	  Secnario based test   	     PASS 	              IMPLEMENTED
L_02	          Powering OFF the Car	Boundary value based test 	 PASS	                IMPLEMENTED 

FINAL OUTPUTS:

1. EXECUTION WHEN BUTTON IS PRESSED ONCE FOR 2 SECONDS:
Ignition mode and Car in ON
<img width="646" alt="image1" src="https://user-images.githubusercontent.com/101738700/168485496-b7fe6133-10da-41ed-b60a-87724dd6a174.png">


2. EXECUTION WHEN BUTTON IS PRESSED ONCE AGAIN FOR 2 SECONDS:
AC mode and Car is OFF
<img width="625" alt="image2" src="https://user-images.githubusercontent.com/101738700/168485511-e2f5eea6-01f3-4a51-b0ce-72415b2220fd.png">


3. EXECUTION WHEN BUTTON IS PRESSED FOR SECOND TIME:
Turning ON the wiper
<img width="881" alt="image3" src="https://user-images.githubusercontent.com/101738700/168485527-67e22082-f471-4871-8482-f72b084ee2e8.png">


4. EXECUTION WHEN BUTTON IS PRESSED FOR THIRD TIME:
Turning OFF the wiper
<img width="940" alt="image4" src="https://user-images.githubusercontent.com/101738700/168485540-2a216894-d967-495e-af1f-3b7140dbb935.png">


