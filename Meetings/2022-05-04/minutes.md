# Meeting May 4, 2022

### Present
- Alan Aspuru-Guzik
- Riley Hickman
- Ben Blaiszik
- Phil Maffettone
- David Marquez-Gamez
- Haoping Xu
- Animesh Garg
- Naruki Yoshikawa
- Marta Skreta

### Minutes
1. Round table introduction. 
2. Introduce core concepts 
   1. Consortium, open organization. Github organization where roadmap minutes and common repositories are shared. 
      1. Check in for concerns RE minutes, allow people to contact post-hoc. 
      2. Complementary to ROS industrial, but not reinventing the wheel 
   2. Looking to construct a paper and code repository inspired by the Human-Robot interaction paper. Overleaf. 
   3. The authors would include, but not be limited to, the people on this call. Love a big tent. 
3. What experimental orchestration are people using.
   1. Some ChemOS in Toronto. Chemspeed python API. Need for engagement with Griffin or optimization algorithms
   2. Bluesky at BNL/NSLS2
4. What do we want to interface with vs what we want to build? 
5. ROS-1 vs ROS-2
   1. General quorum was that using ROS-2 would be more sensible for an early project.
   2. Currently all of Haoping's work is ROS1, but migrating to ROS2 is in sight. 
6. What kind of equipment is there of relevance? Animesh noted it is better to build by function than by device to promote usability.
    - liquid dispensing
    - solid dispensing
    - hplc
    - laser systems
    - heaters
    - stirrers
    - electro
    - thermocouples
    - autocolumns
    - syringe pumps
7. SILA does much of what is in 6. 
   1. Open source and not for profit. 
   2. Already a standard for onboarding specific equipment
   3. Systems can be connected to  SILA--ROS bridge
   4. It is important to consider what is not in SILA but still needed? And whether this should be contributed to ROSLab or SILA. 
8. Notably, PhD students and Post-docs operate on project development foucs. 
   1. There should be no expectation of them being engineers. 
   2. Relevant projects can help rein in initial focus.
9. MINIMIZE LINES OF CODE!
   1. Don't reinvent the wheel.
10. Animesh raised some good points about the purpose/relevance of ROS:
    1. Interfaces to learning based models
    2. Perception
    3. Planning (i.e. OMPL integration with ROS)
    4. Interoperability
12. Communication format:
    1. Marta to make a slack
    2. Ben sent around link to the Overleaf. 
    3. Github organization for shared tools and dev.


## Next Steps
1. Marta to create slack
2. Riley to dig into SILA (everyone encouraged to do this as well)
3. Alan's team to organize a seminar with speakers from SILA through the acceleration consortium (eta ~3 weeks). This will be the next large group meeting.
4. Use slack to communicate about more specifics or get into the weeds. 
5. Leverage the seminar to begin an open discussion and expand the tent to be inclusive. 