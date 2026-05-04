This project applies engineering mathematics and biomechanical modelling to investigate inter-limb asymmetry during unilateral landing tasks. Using motion capture data, the study evaluates how kinetic (force-based) and kinematic (movement-based) variables differ between dominant and non-dominant limbs.

🎯 Engineering Objective

To model and analyse lower-limb biomechanics by comparing:

Kinetic variable: Centre of Pressure (COP) position
Kinematic variable: Knee joint angle (varus)

➡️ Framed as an engineering problem:

How do differences in force application and system dynamics manifest between two mechanically similar structures (limbs)?
🧪 Experimental Design
Participants: 10
System Input: Unilateral landing from a 40 cm platform
Trials: 2 familiarisation + 3 recorded trials
Measurement System: Vicon Nexus (3D motion capture)

⚙️ Engineering Data Pipeline
1. Signal Acquisition
Marker-based motion capture (3D spatial coordinates)
Ground interaction data (force distribution via COP)

3. Signal Processing
Noise reduction using low-pass filtering
Temporal alignment of movement events

3. Modelling & Computation
Rigid body modelling of lower-limb segments
Application of inverse dynamics to compute joint moments
Calculation of:
Centre of Pressure (COP)
Joint kinematics (angles)
4. Normalisation & Aggregation
Joint moments normalised to body mass (Nm/kg)
Trial averaging for reliability

Analysis of kinematic data showed no significant differences between dominant and non-dominant limbs for both knee varus and knee flexion during unilateral landing.
As illustrated in Figure 1, mean values for knee varus and knee flexion were comparable across limbs, with overlapping variability, indicating symmetrical joint kinematics.
This suggests that, despite differences observed in kinetic measures (e.g., COP), movement patterns at the joint level remained consistent, highlighting a potential limitation of kinematic variables in detecting inter-limb asymmetry.

Figure 1

Comparison of knee varus and knee flexion between dominant and non-dominant limbs (mean ± SD). No significant differences were observed (p > 0.05).


