# Overall Evaluation and Grading
Submissions will be assessed not only on how the analysis was implemented, but also by the supporting documentation justifying and explaining your implementation. The documentation will culminate in a (15 minute) presentation during the final day of the event. Teams with more people can achieve greater feats more effectively than solo teams, so be sure to drag along friends to come contribute!

## Minimum Requirements and Exceeding Standards
To be eligible for the cash prize, your submission must contain each of the elements from the general spec. A key part of meeting this requirement is the associated documentation often requiring a justification or explanation of your implementation. Beyond the general spec, teams must choose a detailed spec. These detailed specs have a 5 analyses/simulations to choose from. A team must complete at least one of these. These are the minimum requirements for the submission.

Beyond this, there are opportunities to go beyond the minimum requirements. The first and most simple route is to perform more than one of the analyses in the detailed spec. Each section also has some examples of qualitative ways that the minimum standard can be exceeded. Often, these involve making the analysis more complex or extensive. The items laid out in these sections are just some examples; teams are encouraged to expand beyond those that are mentioned. Extra points will be awarded for implementations that are particularly efficient, clear, large-scope, and technically advanced.

## Evaluation and Submission Items
The submission will be evaluated equally between the analyses you submit and the documentation that you write. It is not possible to meet the minimum requirements for any section with no documentation! Furthermore, a large part of the qualitative evaluation is based on how the implementation is described and justified. The overall scoring breakdown is below, giving a maximum score of (30 Points). 
1. General Spec Minimum Requirement (5 Points) - Description TBD
2. Detailed Spec Minimum Requirement (3 Points each, up to 15) - Description TBD
3. General Spec Qualitative Evaluation (0-5 Points) - Description TBD
4. Detailed Spec Qualitative Evaluation (0-5 Points) - Description TBD

# General Spec
This is the place where we go over the baseline each team needs to do. For now, we have: 
* High-Level Overview of the Mission, including the following details: 
* Rudimentary Physical Architecture, consisting of a brief description of the elements that compose the satellite.
* Block Diagrams showing the Physical Architecture and (one other thing)
* A Day in the Life chart showing what operational phases the satellite goes through based on the preliminary information that we gave them. This will involve doing some basic math on power generation, imaging, and link windows.
* Presentation of the Above Materials. This presentation will be 5-10 minutes (pending participant count).

(We should also define standards for the qualitative assessment here.)

# Detailed Specs
In addition to the general specification, each team must choose one detailed specification to tackle. These consist of 5 analyses that go more in-depth on one area of the satellite's design. The first few analyses in each section are the simplest, with following ones gaining complexity or scope. It's expected that teams will update the baseline information in the general spec deliverables with the new info they get from these detailed spec simulations. 

## Space Vehicle Engineering spec
1. Structural CAD Model in Solidworks - students are given a number of premade components and they're tasked to put them together in an assembly.
2. Electrical CAD Model in Solidworks - students are given a number of premade components and they route the wires between them. This prerequires #1
3. Thermal Simulation in Solidworks - students run a thermal simulation on the assembly that they put together in the first bullet point. This prerequires #2
4. Vibration Simulation in Solidworks - students run a vibration simulation on the assembly that they put together in the first bullet point. This prerequires #1
5. ADCS Simulation in Simulink - run through the adcs simulation example from the matlab website
## Mission Engineering spec
1. Orbital Simulation in Ansys STK - students configure the baseline orbital simulation and then do a basic coverage analysis
2. Power Budget in Ansys STK - building off of the orbital sim, the students build up a power budget and export the data to excel. This prerequires #1
3. Link Budget in Ansys STK - building off of the orbital sim, the students build up a link budget and export the data to excel. this prerequires #1
4. Concept of Operations in Excel - students use their general spec deliverables and the above deliverables to compare and contrast multiple different scenarios. this prerequires #1-3
5. Interconnect Diagram in draw.io and Excel - the students reference the spec sheets for a handful of components to show electrical, communications, and physical interfaces between components
## Simulation spec
1. Power Budget Simulation with Basilisk - the students walk through the power simulation from the basilisk documentation, with a few modifications
2. Link Budget with Basilisk - the students walk through the link budget simulation from the basilisk documentation
3. Telemetry Simulation with F Prime - the students walk through a tutorial on f prime showing some representative telemetry
4. Processing Budget with Opencv  - the students walk through a hyperspectral data compression tutorial, possibly with some classification thrown in there for fun
5. Onboard Data Handling with Basilisk - the students synthesize the results from the processing and link budgets to perform the onboard data handling simulation from the basilisk documentation. This prerequires #2 and #4

(We should also define standards for the qualitative assessment here.)
