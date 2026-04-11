---
layout: project
title: Open Design Project
description: Thermodynamics
technologies: Pump, Thermometer, Heat Exchanger
image: /assets/images/heatExchanger.avif
---

# Client Pitch

## Airborne Egg Detection & Removal System

**Team:** Breadwinners  
**Client(s):** Cals extension, E&J Gallo Winery, National Grape  

---

## Table of Contents

- [Client Pitch](#client-pitch)
- [Functional Prototype](#functional-prototype)

---

## Problem Statement

Although insecticides, manual scraping, and even trap trees have been used to limit the spread of spotted lanternflies, a study by NYU found that despite these measures the spotted lanternfly population increased by at least 10 times from 2014 to 2022. Culling spotted lanternfly eggs proves to be a promising solution, yet several challenges remain. Since lanternflies are capable of flight and can lay their eggs on any surface, eggs can be laid high up in hard to reach areas. Additionally, eggs are often laid on surfaces that would be damaged by rough scraping. Lastly, eggs must be properly collected and destroyed after scraping, as they can still hatch on the ground. Our challenge is to design a tool that can effectively reach egg masses, minimize damage to the surface the eggs are on, and collect the removed eggs simultaneously.

---

## Why this matters

Vineyards, orchards, agricultural crops, and other forms of cultivated vegetation will suffer far less stress and long term damage. In addition, preventing hatching can stop thousands of lanternflies from emerging from a single egg mass, dramatically reducing population growth. The early removal of spotted lanternfly eggs reduces the need for pesticides or large scale treatments which can be more costly for small farmers, and fewer lanternflies prevent sticky honeydew buildup, curb harmful mold growth, and help preserve balanced local insect ecosystems.

---

## Proposed Direction (s)

We propose a series of egg scrapers that enhance the ability of the user to effectively remove egg masses in hard to reach areas. They also ideally protect the environment and collect/destroy the egg masses post removal. The concepts below are presented as a series of minimal viable prototypes designed to build towards the final project. 

### Long Range Adjustable Scraper  
Telescoping, manually operated scraping system designed to remove egg masses inaccessible from the ground containing an adjustable rod  
Utilizes an adjustable scraper head that can rotate allowing for most optimal use with a box beneath it that can catch the removed egg mass  

### Servo Assisted Collection System  
Servo integrated scraping device containing a tensioned cable that can more precisely remove the egg masses without damaging surface of the tree  

### Collection Mechanism  
A net or catch system surrounding the scraping mechanism that does not impede the effectiveness of the tool but captures the overwhelming amount of egg debris  
Can be easily unloaded of its contents so that the eggs can be properly disposed of between scrapes  

---

## Key risks / unknowns:

Containment Efficiency: A risk is the "box" failing to catch 100% of the scraped eggs. If eggs fall to the ground during the scraping process, they can still hatch.  

Surface Damage Risk: There is a high risk of damage to the tree bark if the scraper head is too sharp. If the removal harms bark or crops this would defeat the purpose of the prototype.  

Operator Ergonomics & Reach: Since the scraper is "adjustable in length" and uses a "manual pull", there is a risk of operator fatigue when reaching for high egg masses.  

---

## Client Questions

What is the maximum height requirement?  
Defines necessary length of the adjustable scraper.  

What level of bark damage is acceptable (if any)?  
Affects blade sharpness and compliance of the scraper head, and contact pressure design.  

Is manual operation acceptable, or is a powered/automated system preferred?  
Would help us determine whether to pursue the servo or the long-range approach  

---

## Source

https://www.nyu.edu/about/news-publications/news/2024/december/spotted-lanterflies-urbanization.html  

https://www.overleaf.com/read/hmzmvfqqfncb#8717d3  

---

# Functional Prototype

## Design Documentation

Original design  
Tensioned fishing line supported by springs, bearings, pulleys.  
Bearings and springs mounted on 3/8in shafts with shaft collars.  
Mounted on a frame consisting of 2 custom-fabricated plates held apart by 3/8in standoffs  
The entire assembly uses 4-40 screws.  

---

## Issues and improvements (Chronological order)

3d printed-pulleys were not delivered on time  
Shafts were slightly larger than 3/8in nominal diameter - Shafts had to be sanded down.  
The frame was poorly cut and screw holes were not in line - Use laser cut aluminum instead of a wooden frame.  
Tensioned fishing line kept slipping off of bearings - Use 3d-printed flanged pulleys  
Linear coil springs tangled easily and had to be manually adjusted - Create 3d-printed channel to serve as guide rail for springs.  

---

## Parts:

Bearing: MMC 6383k32 x2 ($26.14)  
3/8in diam shaft: MMC 8974T24 2ft x1 ($4.49)  
Shaft Collars: MMC 9414T8 x 8 ($16.80)  
Springs: MMC 9293K46 x 2 mounted on 8mm shaft ($26.92), Retracting reels like tape measure  
Two custom-fabricated plates (wood/aluminum) separated by 3/8ths standoffs w/ 4-40 screws  
Standoffs: MMC 91115A509 X12 ($15.36)  
4-40 Screw:  
https://www.mcmaster.com/92196A108/ ($6.42)  
Multipurpose aluminum (3ft):  
https://www.mcmaster.com/8975K54-8975K881/ ($14.84)  
Locking pins for adjustable hinge (2): ($12)  
https://www.mcmaster.com/90293A313/ ($64.52)  

---

## Illustration:

![Photo of Illustration]({{ "/assets/images/illustration.png" | relative_url }}){: .inline-image-l}

---

## Design Intent & Functionality:

![Photo of Design Intent]({{ "/assets/images/designIntent.png" | relative_url }}){: .inline-image-l}

---

## Assembly Process:

Sketch outline of each side of scraper assembly on wood plates
Sketch drill holes for screws and shafts on wood plate assemblies  
![Photo of Chris Sketching]({{ "/assets/images/chrisSketch.png" | relative_url }}){: .inline-image-l}

![Photo of Fatima Sketching]({{ "/assets/images/fatimaSketch.png" | relative_url }}){: .inline-image-l}
Drill press holes for screws and shaft on wood plate assemblies 
![Photo of Fatima Lathe]({{ "/assets/images/fatimaLathe.png" | relative_url }}){: .inline-image-l}

Cut out the wood plate assembly with bandsaw  
![Photo of Fatima Bandsaw]({{ "/assets/images/fatimaBandsaw.png" | relative_url }}){: .inline-image-l}

Assemble scraper mechanism using shafts and screws  
![Photo of Fatima Lathe]({{ "/assets/images/dylanBearings.png" | relative_url }}){: .inline-image-l}

Springs and rollers are on the shafts 
![Photo of Fatima Lathe]({{ "/assets/images/dylanShaft.png" | relative_url }}){: .inline-image-l}

Screws go through smaller screw holes  
![Photo of Fatima Lathe]({{ "/assets/images/halfAssembly.png" | relative_url }}){: .inline-image-l}
![Photo of Fatima Lathe]({{ "/assets/images/fullAssembly.png" | relative_url }}){: .inline-image-l}

Attach scraper mechanism to extendable rod  
![Photo of Fatima Lathe]({{ "/assets/images/finalAttachment.png" | relative_url }}){: .inline-image-l}


---

## Design Tests


---

## Motion and Interference

String should be able to “bend” to conform to area with no problem while maintaining force  
The mechanism successfully achieved a motion range of approximately 0° to 110°, slightly below the target of 120°  
The string was able to bend around contours down to an estimated radius of ~2–3 cm without significant loss of tension  
Minor friction was observed at extreme angles, but no jamming occurred during the first 8 cycles  
After repeated motion, slight resistance increased by about 10–15%  

Implication: Hard-install a maximum range of motion to minimize damage by extreme bending, and improve the consistency of motion by making better spring supports and using a roller with a built in track for the cable.  

---

## Repeated Use

The system was tested for 10 cycles total  
Performance remained consistent for the first 5 cycles  
After cycle 5, degradation began as the cable started to slip off the bearings and lose consistent tension, leading to less resistance against the motion.  

Implication: The cable needs to be attached to our bearings more securely  

---

## Assembly and Fastening:

Simulate pushing / pulling motion  
Assembly withstood forces of approx 5-8N  

Implication:  Either need instructions to prevent excessive force usage or increase the amount of force able to be withstood (higher quality parts, more accurate assembly)  

---

## Stability and Support:

When extending pole to different lengths, the user shouldn’t have issue simulating the same range of motion  
Noticed that at long lengths the pole becomes unstable and harder to control, there is instability caused by the increased torque created when force is applied at a greater distance from the base  

Implication: Need counterweight to prevent tipping of pole at applied force  

---

## Success Criteria

Context:  
This prototype is intended to act as a flexible scraper mechanism that can conform to curved surfaces while maintaining consistent cable tension and reliable motion. Success will be measured by how well the mechanism performs repeated scraping motion, maintains alignment of its components, and remains stable and usable when mounted on an extendable pole.  

---

### Criterias:

1. Range of Motion  
 The scraper mechanism should achieve a controlled cable stretch range of 3 inches from initial height without jamming, cable derailment, or permanent deformation of any component.  
 - Reaching 3 inches is a reasonable goal and will allow the cable to conform around the outer shape of the egg masses 
 - Any stretch length greater than 3 inches is not a high priority because we also do not want our device to stretch too much since   having high tension was also an essential aspect of our design
 - This will be measured by manually recording the maximum length reached before interference or excessive resistance occurs.


2. Cable Retention and Tracking  
 During operation, the cable must remain fully seated on its pulley/bearing path for at least 20 consecutive motion cycles with zero derailments.  
 - This criterion directly addresses the already observed issue of the fishing line potentially slipping off the bearings but will also ensure our overall structure and assembly can hold itself together under repeated loadings  
 - Achieving a zero derailment rate over more than 20 tested cycles is a high priority because maintaining proper cable tracking is critical to both the functionality and durability of the mechanism. 


3. Pole-Mounted Usability and Stability  
 When attached to the extendable rod at its intended operating length, the system should remain controllable enough that 5 different users can complete a full scraping motion without excessive wobble, tipping, or loss of alignment.  
 - Quantitatively, the pole should remain stable enough to allow 10 consecutive successful scraping strokes at full extension without much struggle .
 - This criteria will be quantitatively evaluated by asking different students in our lab section and people visiting us during showcase day
 - Improved stability at extremely long extension is a middle to high priority because while we believe it is crucial to make our device user friendly, we don’t expect the spotted lantern fly egg masses to be so high that stability will be an extreme issue. 


---

## Demonstration

The above listed criterias have the potential to be demonstrated during the exhibit day showcase through a live, interactive test in which users can operate the device to perform repeated scraping motions on mock egg masses. We have chosen to focus on criteria #2 as mechanical reliability is our primary priority which would allow the device to function smoothly under repeated use. Although it would be impossible to simulate what egg masses are like in real life, having a mock egg mass that one group member will hold up while a test user lightly “pushes” to “scrap” away will allow them to experience tension forces at work and see first hand how reliable our device is.  