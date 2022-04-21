# Meeting April 21, 202

### Present
- Ian Foster
- Ben Blaiszik
- Phil Maffettone

### Minutes
- Whole bunch of time doing robnotic experiemtns. Starting up again soon.
- No ROS code written for about 6 months. Where does it belong, where is it inappropriate? 
- Immediate activities:
  - Opentrons (some python interface)
  - Proprietary equipment (provides API, but nothing else)
  - UR5
- Lab management is interested

- Paper concept
  - Use cases?
  - Where ROS belongs, where it doesn't belong?

- Multi Lab good concept. Who else?
  - Working from a big tent
  - SLAC
  - Nagia Row @ Oak Ridge
  - Tonio Buonasisi @ MIT
  - Alan Aspuru Guzik @ Toronto 

- Deadline for Answers to Questions in PPT
  - Ben will set up an overleaf and send around 
  - MAy 5, 10am central time.
  - Phil will reach out to Alan. 
  - Ben will raise this with Tonio. 


### Propsed questions to answer in paper

1. What are current example use cases where automation and robotics matter to your laboratory? 
2. What current infrastructure exists and where does this fit? 
   1. What is worth interfacing with (i.e., well supported/widely adopted)? 
   2. What is worth superseding, replacing, or duplicating? 
3. What are the core laboratory components that need to be abstracted? 
   1. What objects currently exist in your workflow (e.g., vials, capillaries, wafers, etc)
   2. What automation or unit operations currently exist in your workflow, and how does they communicate with each other or humans?
4. How are the concepts proposed in 2, best implemented in ROS?
