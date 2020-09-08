---
layout: post
title: HW3 - Chapter 11 & 12
---
11.4 What is the common characteristic of all architectural styles that are geared to supporting software fault tolerance? 

Common characteristics of all architectural styles that are geared to supporting software fault tolerance are redundancy and diversity. Redundancy allows for more dependable software since having multiple serves allows for better handling of software failure.

11.7 It has been suggested that the control software for a radiation therapy machine, used to treat patients with cancer, should be implemented using N-version programming. Comment on whether or not you think this is a good suggestion. 

I think N-version programming should not be used for treating cancer. When treating cancer it is best to not always go with the cheapest option. N-version programming is less expensive that self-checking softwares because it uses at least three different hardware componets to create output. N-programming takes the majority vote from the hardware to determine the output. However, in the case of a faulty hardware unit, the system could be told a wrong answer because one of the faulty units sways the majority vote.

11.9 Explain why you should explicitly handle all exceptions in a system that is intended to have a high level of availability. 
With a higher level of availability you will be able to build a robust system that will be able to recover quickly by telling the user that something went wrong and continuing operation instead of just quitting. 

12.5 A train protection system automatically applies the brakes of a train if the speed limit for a segment of track is exceeded, or if the train enters a track segment that is currently signaled with a red light (i.e., the segment should not be entered). There are two critical-safety requirements for this train protection system: 

The train shall not enter a segment of track that is signaled with a red light. 
The train shall not exceed the specified speed limit for a section of track. 

Assuming that the signal status and the speed limit for the track segment are transmitted to on-board software on the train before it enters the track segment, propose five possible functional system requirements for the onboard software that may be generated from the system safety requirements. 

1.	An alert will be sent to the driver to stop to tell him to apply the brakes.
2.	The train’s brakes are engaged when the trains speed exceeds the limit.
3.	If the train is going to slow, an alert will be sent to the driver to speed up.
4.	If the train enters a prohibited zone, the train captain is alerted to stop the train.
5.	When the brakes are applied, an alert will sound if the train does not begin to slow down.

