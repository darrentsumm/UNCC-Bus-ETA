# UNCC-Bus-ETA
Find your ETA for UNC Charlotte's Silver Line

DATA COLLECTION
  Data was collected on 12/2/2024 from 10:00 to 10:20 am, 11:30 to 12:30 pm, and 1:00 to 2:15 pm by screen recording the PassioGO app that has a map of all 4 buses, totaling 12+ hours of data.
  Data was entered manually.

  Some buses disappeared from the map and reappeared minutes later. To estimate their arrival and departure times at missing stops, I:
    Identified when and where the bus disappeared and reappeared.
    Assumed it followed the expected route, stopping at intermediate points.
    Used the average travel and stop times of other buses to proportionally distribute the missing bus’s travel time.
  To ensure a realistic estimate, I scaled each segment’s travel and stop time based on the total disappearance duration relative to the average time for that route.

PROGRAM USE
  Input your pickup and dropoff locations. 
  For a general estimate of eta at any given time, opt not to input data about the nearest bus. This option assumes there are 4 buses active on the route. For a specific estimate (if the user is waiting at the bus stop) input data about the nearest bus. 
  The program will deliver an estimated wait time, travel time, and combined trip time, as well as a normal curve showing the distribution of trip time.
 

FUTURE IMPROVEMENTS
  Develop an automated data collection program.
  Use more data to create a more accurate probability curve.
  Add Green, Gold, and Red routes.
  Take into account the  time of day, day of week, and number of buses.
  Use real-time data to give accurate estimates without user input, 

Author: Darren Summerlee, darrentsumm@gmail.com
Data Source: PassioGO app, UNC Charlotte campus
