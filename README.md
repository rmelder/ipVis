# ipVis
# README
I am playing around with Unity and C# to make a 3d visualizer of interaction points in a position-sensitive
HPGe detector medium

Essentially each interaction point has 3 pieces of information - energy, position, time.   
Step 1 - read a file that has the interaction point information
Step 2 - place a sphere at each position
Step 3 - represent the energy at each position intuitively (a light with brightness proportional to energy?)
Step 4 - make some sort of playback interface so that interaction points appear according to the time param
          - and can replay, pause, resume, skip to the next set of ip's and back.  
          - and let user move camera in 3d space
Step 5 - Let user click on each ip and set some information for each
          - ie: label what "gamma-ray" it belongs to, or neutron event.
          - and write this information.  
