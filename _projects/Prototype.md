---
layout: project
title: Open Design Project
description: Thermodynamics
image: /assets/images/ODP.png
---

# Client Pitch

## Airborne Egg Detection & Removal System

**Team:** Breadwinners  
**Client(s):** Cals extension, E&J Gallo Winery, National Grape  

---

## Table of Contents

- [Client Pitch](#client-pitch)
- [Functional Prototype](#functional-prototype)
- [Client Report](#client-report)


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

# Client Report

## Breadwinners Cable-Tension Scraper - Chris, Fatima, Sean, Dylan, Calvin

### Context & Problem Statement 

Spotted Lanternfly (SLF) eggmasses are difficult to remove because they are often located high on trees in hard to reach surfaces or at odd angles. Our group has chosen to focus specifically on the mechanical removal of egg masses where accessibility is a key limitation. We believe that solving this sub problem of removing SLF egg masses is the critical step that reduces SLF population growth and prevents further infestation cycles. Furthermore, this sub problem was also chosen because existing methods such as manual scraping are labor intensive, inconsistent, and potentially unhealthy for the tree bark if it gets damaged. These challenges highlight the need for a more effective and practical removal approach that also takes into consideration the impact our our device on trees leading us to form these specific design constraints:

•        Lightweight & durable for repeated field use  
•        Simple to operate with minimal fatigue  
•        Conforms to curved surfaces  

---

### Design Goal: 

Develop a lightweight, durable, and easy-to-use scraper mechanism that allows agricultural workers to effectively remove spotted lanternfly (SLF) egg masses from curved, hard-to-reach surfaces at varying heights. The device must not cause crop/surface damage, cause excessive operator fatigue,  or require specialized training.

---

### Final Prototype and Application:

Our final prototype consists of three major components. The first is an off-the-shelf twelve foot extendable pole, which allows an operator to extend the scraper head to reach high-up surfaces. It also means that users may not have to purchase an extendable pole if they already have one, saving money.

The second major part is a 3d-printed tooth and gear mechanism designed to integrate with the adjustable hinge from the extendable pole. The original hinge mechanism used two toothed components held together by a screw and bolt. Loosening the screw allowed the mechanism to be turned freely, and it could then be re-tightened to lock it. The new part copied one of the original toothed components, and added a mounting block for the scraper head. This allows the head to take on a variety of angles, further extending the flexibility of the design and allowing for scraping at hard to reach angles.     

The last component is a custom-built scraper head. The head uses a fishing line tensioned by a pair of linear springs to scrape SLF eggs off of curved surfaces. The tensioned line is specifically designed to maintain a firm contact and scraping force while wrapping around irregularly shaped surfaces. Fishing line is used for its availability and low chance of surface damage. The line is mounted on a pair of 3d-printed pulleys and held in place by guides made from 3/8ths inch standoffs. The entire assembly is mounted on a fabricated aluminum plate. These design choices were made primarily for durability, precision, and a lower chance for the system to jam, improving overall ease of use.

In order to use the scraper, the user first adjusts the pole to the required length, and adjusts the hinge to the required angle. They then push the scraper head at an angle against the surface, and slide the head to remove SLF eggs. The cable conforms to the surface, sliding under SLF eggs, destabilizing their connection with the surface, and scraping them loose.

As the spotted lanternfly continues to spread across North America, our cable-tension scraper represents a first step toward scalable, chemical-free pest removal. We envision the tool being refined for mass production with weatherproof materials, ergonomic designs, and improved mechanisms, then distributed through agricultural extension programs to reach workers across affected regions. 

![Photo of Design Intent]({{ "/assets/images/3DPart.png" | relative_url }}){: .inline-image-l}
<p style="text-align: center; font-size: 0.9em;"><em>Figure 1: CAD model of the custom 3D printed scraper assembly.</em></p>

![Photo of Design Intent]({{ "/assets/images/finalPrototype.png" | relative_url }}){: .inline-image-l}
<p style="text-align: center; font-size: 0.9em;"><em>Figure 2: Final assembled prototype mounted on extendable pole.</em></p>


---

### Parts List:
![Photo of Design Intent]({{ "/assets/images/partsList.png" | relative_url }}){: .inline-image-l}

---

### Conclusion and Recommendations: 

Our goal was to develop a lightweight, durable, and easy-to-use cable-tension scraper mechanism mounted on an extendable pole that allows agricultural workers to effectively remove spotted lanternfly (SLF) egg masses from curved, hard-to-reach surfaces at varying heights- without damaging crops, causing excessive operator fatigue, or requiring specialized training. We set out to achieve this with a goal range of rotation of 120°, a goal range of cable motion of 3 inches, and an emphasis on durability and user-friendliness. 

The initial prototype performed relatively well, functionally reaching 110° range of motion, and the cable ran smoothly at first. We encountered trouble after repeated usage, as resistance rose, the cables became misaligned on their rockers, and the springs began to slip. 

In our final design, we changed the frame material from wood to aluminium, improving the frame’s precision and durability. Pulleys were added to improve the stability of the cable, while guides were added to the linear springs to prevent jamming. These three improvements improved durability and reliability, while extending the cable’s range of motion.

We also redesigned the hinge to reach our goal range of rotation of 120°, and added an adjustable and removable counterweight at the base of our final prototype in order to improve ergonomics when the rod is fully extended. Finally, our tests using clay as an egg mass substitute were effective and promising.

---

### Recommended Improvements.

Add a catcher/net to capture egg masses when scraped off  
Stronger fasteners or fully machined mounting block to exceed 5–8 N threshold  
Weatherproof components to prevent outdoor degradation  
Redesigned springs based on a tape measure, which maintain cable tension even as the cable loosens and are more resistant to jamming.  
Grabber mechanism that can wrap around a wider variety of surfaces, reducing the total number of passes needed to fully scrape areas.

---

### Testing and Results : 

#### 1. Range of Motion - Partial (Improvements Required)

Cable should be able to stretch about 3 inches without jamming, derailment, or permanent deformation. Achieving this design constraint would allow users to reach and fully engage egg masses located at uneven or angled surfaces while maintaining smooth motion necessary for effective scraping. Our group chose 3 inches as a target because the exact dimensions and surface profiles of SLF egg masses vary significantly in the field and are difficult to standardize. We selected an approximation of 3 inches as it provides sufficient flexibility to accommodate this variability while still maintaining control, structural integrity, and consistent force transmission during operation.

During testing, the cable on the final prototype could stretch about 3 in. As a result, for surfaces that did not fit within the prongs of the scraper head, the cable could conform to almost 90° angles. For surfaces that fit into the scraper head, including small curved surfaces like a water bottle, around 110° of the surface could be scraped in one pass.

#### 2. Cable Retention - Partial (Improvements Required)

The device should have 0 derailments over 20 consecutive motion cycles. Spotted lantern fly egg masses come in large volumes which means our device needs to have sufficient structural integrity across many scraping motions. Ensuring consistent cable retention minimizes interruptions and prevents the need for adjustments, allowing users to operate efficiently. We selected the value of 20 cycles as it represents a realistic short duration use case in which a user would perform repeated scraping actions in successions. If our designs are able to pass the 20 consecutive tests, we can realistically conclude that the mechanism is capable of maintaining consistent performance and is unlikely to experience frequent failures.   

During testing, the cable would derail if scraping happened at angles close to perpendicular to the surface. Further analysis determined that this was the result of lateral forces that pushed the cable out of the pulley, and improvements in pulley designs are recommended. Spring mechanism performed up to standard during testing.

#### 3. Usability & Stability - Pass

Five different users should each be able to complete full scraping motions without experiencing excessive wobble or loss of control. This ensures the device is accessible and functional across a range of users, regardless of strength or experience level, reflecting our commitment to a tool that requires no specialized training.

#### 4. Reach - Pass

The tool should be able to reach at least 10 feet into the air, so it can access egg masses that are located high up on trees. A favorite location for spotted lanternflies to lay eggs are Trees of Heaven. These trees can reach heights of up to 50 feet but most juvenile trees are between 10-15 feet tall and the locations where spotted lanternflies lay their egg masses are often in this range, even when the trees are taller than this. Therefore, our group chose a goal length of 10 feet for our scraper length, so that most egg masses are accessible from the ground.

The final device had a reach slightly over 12 feet, when accounting for operator height.

#### 5. Durability of Hinge Mechanism - Pass

The turning point of the tool can undergo ≥20 adjustments without noticeable change in stability or wear. Despite concerns of shear weakness in the 3d-printed hinge, the hinge was able to undergo many cycles without issues.

---

### Testing Details: 

#### Range of motion:

Our design utilized fish lines attached to linear springs that were aligned along aluminum tracks. Each linear spring would be pulled out as tension was applied to the line drawn across the head of the scraper, and would retract once that tension was relieved. The linear springs were picked specifically to undergo moderate movement between forces of 0-10 Newtons, which was the estimated amount of force it would take to scrape lanternfly egg masses off of trees. This was chosen so that the deformation would allow the scraper to remove egg masses from uneven surfaces as well as not damaging the actual surface. 	

#### Cable Retention:

In our original experiment, our cable derailed constantly and the linear spring became tangled after only a few uses. A main focus of our final prototype was to ensure that the cable would remain seated in the rollers and also the linear spring would remain on track after repeated use. In this regard, we utilized larger rollers with a track that the fish line could sit in, and also used guide rails to keep the linear springs moving in only one plane. When testing, one cycle consisted of scraping a clay mass from an uneven surface successfully. We were successful in performing 20 cycles with the linear springs staying in line and the cable not unseating from the rollers.

#### Usability and Stability:

One main goal of our project was to create a tool that anyone could use. In this regard, we employed things like our counterweight and using light materials like aluminum in the prototype. To make sure that our product was usable in the field, we picked different people with different builds (height, weight, etc) to test our scraper both at its shortest and longest length to ensure that it was usable for anyone. 

#### Reach:

We obtained an extendable pole that satisfied our success criteria without any modifications to its extendable function needed. The only changes to this was the addition of the counterweight on the bottom, and a modification to the connection between the pole head and the scraper head, which is detailed in the final prototype and application section.