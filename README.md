# Biomechanical-Analysis-of-Unilateral-Landing
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

Key Engineering Findings
✅ Significant asymmetry in COP position
→ Indicates differences in force vector application and system loading
❌ No significant difference in joint kinematics (knee varus)
→ Suggests geometric similarity despite dynamic differences
🧠 Engineering Interpretation
The system (human body) maintains kinematic consistency while allowing kinetic variability
Asymmetry originates during force generation (take-off phase), affecting downstream system behaviour

➡️ Key Insight:

Dynamic loading conditions can differ significantly even when structural motion appears symmetrical

🚀 Engineering Applications
Biomedical Engineering: Injury risk modelling, prosthetics, rehabilitation systems
Mechanical Engineering: Multi-body dynamics, load distribution analysis
Data Science / Analytics: Time-series analysis, signal processing, modelling complex systems

