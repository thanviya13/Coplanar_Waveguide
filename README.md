## COPLANAR WAVEGUIDE (CPW) 

Transmission Line for RF & Microwave Circuits 

1. Aim 
To study and understand the structure, design principles, electromagnetic behavior, 
mathematical model, advantages, and applications of the Coplanar Waveguide (CPW)
used in high-frequency circuits. 

2. Apparatus / Requirements 

Reference textbook on Electromagnetic Theory 
CPW structural diagram 
Graphical diagram showing field distribution (optional) 
Calculator or design software (HFSS, CST, MATLAB,ADS – optional) 
A4 sheet or PDF editor 

3. Introduction 

A Coplanar Waveguide (CPW) is a planar transmission line commonly used in microwave, RF, millimeter-wave, and high-speed digital circuits. 

Unlike microstrip lines (where ground plane is on the back of the substrate), CPW has: 

Center conductor 
Two ground planes 
All on the same surface of the dielectric substrate. 
This unique geometry allows excellent performance for modern communication circuits such as antennas, filters, mixers, phase shifters, and integrated circuits. 

4. Structure of CPW (Elaborated) 

A CPW consists of: 

1. Center Conductor (Width = w) 

This is the main signal-carrying strip. Its width determines impedance and field confinement. 

2. Gaps (Spacing = g) 

Narrow gaps separate the center strip from both ground planes. 
These control impedance, field distribution, and loss. 

3. Ground Planes (Two Sides) 

Placed symmetrically on both sides of the strip. 
Provide stable return path and reduce radiation. 

4. Dielectric Substrate 

The substrate has relative permittivity εᵣ. 
Common materials include FR-4, Rogers RT/Duroid, Silicon, GaAs, etc. 

5. No Backside Ground Plane (Important) 

All elements lie on the same plane, making CPW different from microstrip. 


5. Modes of Propagation 

CPW primarily supports: 

✔ Quasi-TEM Mode 

Main mode of operation 
Similar to Transverse Electromagnetic mode 
Suitable for wide frequency operation 
Why Quasi-TEM? 

Because fields are not perfectly transverse due to finite substrate height. 
But still very close to TEM → low dispersion. 

6. Mathematical Formulation (Detailed) 

(a) Propagation Constant 

 

 

Where: 

α → attenuation (loss per unit length) 
β → phase constant (phase shift per unit length) 

(b) Characteristic Impedance (Z₀) 

CPW characteristic impedance is given by: 

 

(c) Effective Permittivity 

 

This determines the velocity of wave propagation. 

7. Characteristics of CPW (Elaborated) 

Supports quasi-TEM mode 
Low radiation loss compared to microstrip 
Less dispersion → good for wideband applications 
Provides better grounding symmetry 
Easy shunt and series mounting for components 
Higher isolation → reduces interference 
Suitable for high-power and high-frequency circuits 
Works well even on thick substrates 
 

8. Advantages 

Fabrication Advantages 

No backside metallization 
Single-layer processing 
Less machining complexity 
Suitable for monolithic ICs 
Electrical Advantages 

Low radiation loss 
Wide impedance control 
Good isolation 
Suitable for wideband & high-frequency designs 
Efficient integration with active components 

9. Applications of CPW 
CPW is widely used in: 

RF & Microwave integrated circuits (RFIC, MMIC) 
5G and UWB antennas 
Microwave filters and couplers 
Power dividers 
Phase shifters 
RFID tags 
Communication systems 
High-frequency sensors 
Radar and satellite communication circuits 
 

10. Conclusion 

Coplanar Waveguide (CPW) is a highly efficient transmission line that combines easy
fabrication, low loss, excellent isolation, and compatibility with integrated microwave
circuits. Its planar structure makes it ideal for modern RF, microwave, and millimeter-wave
applications. Because of its versatility and performance, CPW remains one of the most
widely used transmission line structures in communication engineering. 
