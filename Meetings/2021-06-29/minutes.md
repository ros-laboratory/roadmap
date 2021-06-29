# Meeting June 29, 2021

### Present
- David Marquez-Gamez
- Hatem Fakhruldeen
- Ian Foster
- Ben Blaiszik
- Phil Maffettone

### Minutes
1. DMG presented slides describing proposed project motivation and scope
2. Hatem presented slide describing proposed project in Liverpool 
3. Discussion regarding problem framing, end-user needs,
   potential solutions, needs, and methodolgies. 
   
### Deliverables
1. All attendees to describe a potential use case that will require 
   development through some combination of ros-laboratory and ros-industrial. 
   This will inform the primary scoping of ros-laboratory. 
   

## General notes
### Problem Framing
- Intercommunication in scientific labs
- Need to describe specific needs for Liverpool/BNL/APS/Oxford

### Proposed Solutions
Always avoiding reinventing the wheel, each solution should be cross-checked with existing approaches.

Preference to ROS2 with a C++/Python mixture, favoring Python when closer to user-facing. 
- Drivers for experimental equipment outside the scope of ROS-Industrial. 
  I.e. not mobile manipulators, but scientific equipment (reagent dispensing, reactors, measurements)
- Standard messages, objects, URDF for the above
- Medium abstractions: experimental planning, operations
- High level abstractions: languages describing experiments, AI/ML 



