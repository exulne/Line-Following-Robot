# What is this?
This is the code I wrote that powered a simple line following robot that achieved the fastest base time overall, and second during Week E at the Robotics for Sustainable Economic Growth course held by the University of Toronto's CREATE program.

It was written in Arduino with three IR sensors, one Ultrasonic Sensor and two Motors in mind

# Major Challenges
- fine tuning speeds to ensure stable but quick traversal
- correct movement logic
- correct delay values for object detection and traversal

# How to use the code
- make sure your pin connections are set to the right sockets
- fine tune speeds based off both motor quality and weight being carried. The current speeds were tuned with 500g added weight in mind

# What can it do?
- can support up to 500g while still achieving under 20 second lap times (heavier weights have not been tested)
- Basic object detection. It's hardcoded to go around one side. There is code in thhis repository for theoretically more advanced object detection, which would involve a servo


### How did it perform?
- Allegedly the fastest bot throughout all weeks (Base Course)
- Second overall for Week E (Modified Course)

### Other Stuff
- Went through about 7 IR sensors before we found a working one
- POWER GUZZLER (will use up a 9V battery essentially per run)
