# Vineyard Pest Control System – MAE 2250 Project

This project focuses on mitigating the impact of Spotted Lantern Flies (SLFs) on vineyards during the pre-harvest period. Our team, Newton’s Nightmares, developed and tested a boundary-level interception system designed to reduce crop contamination and yield loss.

The project progressed through three major milestones: initial client pitch, functional prototyping, and a final client report with recommendations for deployment.

## Table of Contents

- [Client Pitch (O3)](#client-pitch-o3)
- [Functional Prototype (O5)](#functional-prototype-o5)
- [Client Report (Final)](#client-report-final)

## Client Pitch (O3)

### Overview
We identified SLF contamination during pre-harvest as a major cause of crop rejection and yield loss.

### Proposed Solution
A 60 Hz-based trap designed to attract and eliminate SLFs at vineyard boundaries.

### Outcome
This phase helped refine the problem scope and identify key risks such as environmental variability and insect selectivity.

👉 [View O3 Document](../O3_ClientOutline/O3_ClientOutline.md)

---

## Functional Prototype (O5)

### Overview
We developed a functional prototype, the *HertzTrap*, to test a pre-harvest interception strategy for Spotted Lantern Flies (SLFs). The design builds on a lure-and-kill approach, combining frequency-based attraction with an electrified mesh to eliminate insects before they reach grapevines.

### How it works
- A speaker generates a 60 Hz signal intended to attract SLFs  
- Insects are drawn toward a dual-layer electrified mesh  
- Contact with the mesh completes the circuit and neutralizes the insect  
- Adjustable legs allow positioning at vine canopy height  

### Prototype Design
The system integrates electrical, acoustic, and structural subsystems into a compact enclosure. Key components include a speaker and amplifier, an Arduino-controlled signal generator, and a repurposed bug zapper circuit powering the mesh. The enclosure was designed for outdoor durability and easy deployment.

### Testing & Key Results
- **Durability:** Withstood drops up to 4 ft with no damage to core electronics :contentReference[oaicite:0]{index=0}  
- **Structural strength:** Supported expected field loads with a safety margin :contentReference[oaicite:1]{index=1}  
- **Adjustability & portability:** Single-user setup in under ~15 seconds with stable height adjustment :contentReference[oaicite:2]{index=2}  

### Limitations
While mechanical and electrical functionality were validated, biological performance was not fully tested. The effectiveness of 60 Hz attraction and reliable SLF neutralization remain key unknowns. 

👉 [View Full Prototype Document](https://docs.google.com/document/d/1XZs67pz1uXwsk_c_KgqRa_zyqyVG85ekyARUZDBJ0BQ/edit?usp=sharing)

---

## Client Report (Final)

### Final Design
The *HertzTrap* is a scalable, pesticide-free system designed to intercept Spotted Lantern Flies before they reach grapevines during the pre-harvest migration period. It combines frequency-based attraction with an electrified mesh to reduce crop contamination and yield loss.

### How it is used
- Deployed along vineyard boundaries or near vine canopies  
- Operates continuously during peak SLF migration  
- Requires minimal user interaction after placement  

### System Description
The device consists of a compact, weather-resistant enclosure housing a 60 Hz acoustic system and a dual-layer electrified mesh. When SLFs are attracted to the frequency stimulus, they contact the mesh and are neutralized. Adjustable legs allow positioning across uneven terrain and varying canopy heights.

### Key Findings
- The prototype is mechanically robust, lightweight, and deployable at scale  
- Electrical functionality was validated through arc discharge testing  
- Core uncertainties remain in SLF attraction strength and capture efficiency  

### Conclusion
The HertzTrap demonstrates a promising pre-harvest pest mitigation strategy that could reduce reliance on chemical pesticides and minimize crop rejection due to contamination. However, its effectiveness depends on validating biological performance in real vineyard conditions.

### Next Steps
- Conduct controlled field testing with live SLFs to measure attraction range and capture rate  
- Optimize mesh geometry and voltage for reliable neutralization  
- Improve selectivity to minimize impact on beneficial insects  
- Integrate solar power for continuous, low-maintenance operation  


👉 [View Full Client Report](https://docs.google.com/document/d/1h-l6_diPJMO7-GBV3eRitwVYInhbqRJskmhMhxcM8-A/edit?usp=sharing)
