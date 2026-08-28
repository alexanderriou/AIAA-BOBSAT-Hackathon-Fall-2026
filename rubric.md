# Overall Evaluation and Grading
Submissions will be assessed not only on how the analysis was implemented, but also by the supporting documentation justifying and explaining your implementation. The documentation will culminate in a (5-10 minute) presentation during the final day of the event. Teams with more people can achieve greater feats more effectively than solo teams, so be sure to drag along friends to come contribute!

## Minimum Requirements and Exceeding Standards
To be eligible for the cash prize, your submission must contain each of the elements from the general spec. A key part of meeting this requirement is the associated documentation often requiring a justification or explanation of your implementation. Beyond the general spec, teams must choose a detailed spec. These detailed specs have a 5 analyses/simulations to choose from. A team must complete at least one of these. These are the minimum requirements for the submission.

Beyond this, there are opportunities to go beyond the minimum requirements. The first and most simple route is to perform more than one of the analyses in the detailed spec. Each section also has some examples of qualitative ways that the minimum standard can be exceeded. Often, these involve making the analysis more complex or extensive. The items laid out in these sections are just some examples; teams are encouraged to expand beyond those that are mentioned. Extra points will be awarded for implementations that are particularly efficient, clear, large-scope, and technically advanced.

## Evaluation and Submission Items
The submission will be evaluated equally between the analyses you submit and the documentation that you write. It is not possible to meet the minimum requirements for any section with no documentation! Furthermore, a large part of the qualitative evaluation is based on how the implementation is described and justified. The overall scoring breakdown is below, giving a maximum score of (30 Points). 
1. General Spec Minimum Requirement (5 Points)
2. Detailed Spec Minimum Requirement (3 Points each, up to 15)
3. General Spec Qualitative Evaluation (0-5 Points)
4. Detailed Spec Qualitative Evaluation (0-5 Points)

# General Spec
The general specification is the baseline that all teams will complete. As a result, it consists mostly of compiling the preliminary materials in a digestible and presentable format. Note that as each team makes progress on their detailed specification, they will update some or all of these materials with the data they create. There are four main deliverables in the general spec, each of which will go into the presentation at the end. 
1. High-Level Overview of the Mission
2. Rudimentary Physical Architecture
3. Block Diagrams
4. A Day in the Life Chart

## Mission Overview
**Minimum Requirement**: The mission overview is the background and justification for your satellite. The mission overview covers (at a high level) what your satellite is trying to do, how it is accomplishing that, and why what it's doing is important or valuable. Much of the info needed here can be found in the customer documentation (HERE), but you will need to fill in some of the gaps with your own research. The mission overview constitutes one slide in your presentation, and it's best placed right in the beginning! 

**Qualitative Evaluation**: The mission provided by the customer is intentionally left vague! Your team can provide a more compelling case for your work if you give more details than are provided to you. This could take the form of context gained by the analyses you've done in your general specification. It could also take the form of comparisons to other satellites that've been launched or planned to launch. 

## Physical Architecture
*Minimum Requirement**: The physical architecture is a description of what components make up the satellite and how they're composed together. For this event, you will need to interpret the customer documentation (HERE) to get this info. Then, you'll need to concisely present the physical architecture on a dedicated slide in your presentation. Note that the customer documentation will have only preliminary information on each of these components. The analyses you conduct during the detailed specification may give you more information that you should put in the physical architecture. This could be a trade-off between different components or a more advanced component. A  
piece of advice for this section: a picture is worth a thousand words!

**Qualitative Evaluation**: Going above-and-beyond in this section is pretty easy! One example would be to attach your conceptual physical architecture to a 3D CAD model. Another example would be to show the physical interfaces (fasteners, electrical connectors) between each of the components in an interface matrix. Finally, you could make a logical (alternatively called a functional) architecture and show its correspondence with the physical architecture.  

## Block Diagrams
**Minimum Requirement**: Block diagrams are the bread and butter of communicating how space systems are laid out. As part of the general specification, you must have at least one block diagram that explains some part of your satellite system. One option would be to represent the physical architecture as a block diagram, which is pretty natural in-industry. Another option would be to use a block diagram to capture the sequence of events the satellite takes, also called the concept of operations (CONOPS). Furthermore, many of the analyses in the detailed specification lend themselves to representation via block diagram. 

**Qualitative Evaluation** Block diagrams that are exceptionally clear, concise, and illustrative merit additional points. Beyond that, (TBD).

## Day in the Life Chart
**Minimum Requirement**: A Day in the Life Chart shows what operational phases the satellite goes through in a 24 hour window. A preliminary sketch of this information can be found in the customer documentation (HERE), but this information is by-and-large incomplete. You will have to perform some basic math on power generation, imaging, and link windows in order to fill this out. The detailed specifications each give more accurate ways to calculate the info underpinning this chart!

**Qualitative Evaluation**: One of the most insightful ways to compare the effect of some trade-off is to see its impact on the satellite operation. For instance, a selection of a different solar panel or battery may free up extra time for imaging. Showing this trade-off with the day in the life chart could be a good way to get extra points. On the other hand, different operational profiles could be compared. I'm sure there's more that could be done here (TBD). 

## Final Presentation
**Minimum Requirement**: Each team will present the end result of their work during the final day of the event. This presentation should include one slide for each of the prior deliverables, plus any additional slides that you deem necessary to present your work. Each team will be limited to (10) minutes to deliver their presentation, and you'll have to submit your presentation before (TBD) on the final day. 

**Qualitative Evaluation**: Extra points in this category entirely correspond with the quality of the presentation. Good presentations will generally have the following: Balance of contribution from each team member, preference for visuals over text where appropriate, little dead time and smooth flow of presentation narrative, sufficient detail *and* sufficient summarization, and appropriate pace (don't take too long). 

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
