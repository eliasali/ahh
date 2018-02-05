# Finalization IoT Idea:

Hypothesis: We believe that through incentivizing membership registration through retrospected points collected with IoT devices that there will be an increase in membership acquisition. 
 

## Coffee Area Analysis

The purpose of this experiment is to demonstrate the collection of points before the customer has signed up. This experiment also collects valuable information about the customer which can be used for personalized marketing, population distributions and further customer analytics.

## Components: 

⁃	Distributed Ledger

⁃	Face Detection / Capture

⁃	Action Detection

   ⁃	Grab Coffee

   ⁃	Grab Cookies

   ⁃	Put dishes in washer

 
## Output / Data:

ID, Face, Environment, Events( Time, Floor, Duration), Points (Coffee, Cookies, Pretzels)


## Next Steps:

⁃	Experiment Design

   ⁃	Baseline?

   ⁃	Good vs. Bad Experiment 

   ⁃	Why you are doing this experiment? 

   ⁃	Look at Hypothesis Driven Model 

## Experiment Design:

1.	Facial Recognition on smaller devices

      ⁃	TX2 is too expensive
  
      ⁃	Raspberry Pi with computing sticks 
 
      ⁃	Raspberry Pi with SqueezeNet
  
      ⁃	Raspberry Pi with SqueezeNet and computing sticks
  
      ⁃	TX2 with computing sticks 
  
      ⁃	Reason for the experiment is to find the most effective method in order to do facial recognition 
  
 2.	 

## Things to think of:

⁃	Recording people’s coffee choice? Depends on the viewpoint of the camera and if the camera can pick up the text on the screen. In the scenario that the person is blocking the choice, there has to be some guessing system in place. Create a recommendation system from this in the future?

⁃	Not all coffee setups are the same. Need to figure out how we can differentiate between a person picking up cookies vs pretzels vs chips. Possible solutions include laser setup that goes at one end of the snack dispenser and using the distance at which it detects the hand to identify which snack was selected. Another option is using computer vision to identify which one by either training how a cookie or pretzel looks like or by putting a paper label on the dispenser. Another thing to think about is if the person actually took the cookie or just stood in front of it or if they changed their mind last second. The laser solution would be able to figure this out. 

⁃	Need to somehow take into account the outliers that wear hats or sun glasses when they go grab coffee. No points? Another means of identifying them would be to do a crosscheck with the wifi Mac addresses. Every time a face is registered the possible nearby Mac addresses can be recorded, therefore when the person cannot be identified, the points can be given to the matching MAC address

⁃	End result should be a profile with the photo, points, floor and stats. Person should be able to look at the camera and match their profile. Thus, claiming their points.
