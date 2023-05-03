# [ROBOT-CENTRIC ELEVATION MAPPING WITH UNCERTAINTY ESTIMATES]
## Quick Look

**Authors & Affiliation**:  
[P. FANKHAUSER∗, M. BLOESCH, C. GEHRING, M. HUTTER and R. SIEGWART]
[Autonomous Systems Lab, ETH Zurich]

**Link** : [Paper link](https://doi.org/10.1142/9789814623353_0051)

**Comments:**  Published at Moblile Service Robotics

**TLDR:** This paper presents a robot-centric elevation mapping approach with uncertainty estimates, addressing pose estimate drift in autonomous robots.

## Research Topic
- Category (General) : Robotics
- Category (Specific) : Elevation Mapping

## Paper summary (What)
- The authors propose a novel approach for elevation mapping.
- The method is robot-centric and uses uncertainty estimates to address pose estimate drift.
- The approach is implemented and checked on the quadruped robot StarlETH.

## Issues addressed by the paper (Why)
- Autonomous robots often experience pose estimate drift, which can affect the accuracy of elevation maps.
- The paper aims to develop a real-time elevation mapping method that handles pose estimate drift.

## Detailed Information (How)

### Methodology
- The approach is based on robot-centric perspective, updating map data based on the robot's pose estimation uncertainty.
- The method is split into data collection (measurement and model update) and map fusion steps, lowering computational burden.

### Results
- The approach has been implemented on the quadruped robot StarlETH, showing well-preserved height information.

## Conclusions

### The author's conclusions
- The proposed method enables real-time elevation mapping with high update frequencies.

## Possible future work / improvements
- Evaluate and compare the proposed method on different robotic platforms.
- Explore the integration of other sensors or methods for enhancing elevation mapping accuracy.

---

