# **Travel Planner**

###### Travel planner is a electric map which indicate traffic condition by playing different music and lighting.
## **Summary**
  The goal of my project is to use the technology to help people identify the traffic situation and choose their 
routes.
  The reason I choose this subject is related to my commute experience. Since I need to drive to San francisco
campus from the east bay every weekday, it's hard to look at the map onmy phone to check the traffic condition.
Most of the time I listen to music while I am driving. So if there is a smart map that can tell drivers the traffic 
condition by playing different music, it will be much safer to look at the screen while driving. For some people who
like to check the traffic condition before they take off, I want to use different colors of LED lights with music 
to indicate the traffic condition.
  The ideal way is that user choose the route with their voice, and the smart map will tell the user how is 
the traffic condition with music and lighting.Because we only have 5 weeks to execute the project, I will start
by making the automatically-selected routes map with music.According to the real time traffic data, the program will
play various music. If I finish this before 3 weeks, I will build the user selection routes map. As user choose different
routes, the program will play different kinds of music. Then if there's still time, I will add some lighting on it. 

## **Component Parts**

On the hardware side, I will need some LED lights, Feather board and my computer.
- LED lights (output)

On the software side,I will need a mapbox to display map and traffic data API to play music.
- traffic data API (input)
- mapbox(output)
- a software with a few buttons to choose different route.(input)

## **Block Diagram**

https://github.com/RuitaoLiang/Final-Project/blob/master/block%20diagram.pdf

## **Challenges**

Finding the useful traffic data API is a challenge for me, since the data may not update very fast if it's free of charge.
If Using a mapbox to display my map is not supporting user selection, I will need to draw my own map, which is a big challenge for me.

Also building a software to let user choose the route is new to me.
Finally adding LED lights to feather board and connecting it to the traffic data is also quite complicated, so I expect to take a long time to try and make errors.

## **Timeline**

-Week 1: Write proposal,online search traffic data API,and learn what data it generate and which is useful to my project
-Week 2: use mapbox to display the map and write code to play music according the trafiic data
-Week 3: build a user selection route map and make code to play music
-Week 4: add lighting to the project and control it with code and traffic data.
-Week 5: Present complete project.
