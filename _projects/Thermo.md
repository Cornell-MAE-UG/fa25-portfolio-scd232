---
layout: project
title: Heat Exchanger Analysis
description: Thermodynamics 
technologies: Pump, Thermometer, Heat Exchanger 
image: /assets/images/heatExchanger.avif

---









## 1. Introduction and Real-World Context 
Heat exchangers are devices designed to transfer thermal energy between two fluids at different temperatures without mixing them. They are widely used in real-world systems such as radiators, HVAC systems, power plants, refrigeration units, and industrial chemical processes. In this experiment, a water–water heat exchanger driven by two pumps was studied under different flow configurations to understand how design and operating conditions affect performance.

This experiment replicates real engineering challenges such as maximizing heat transfer, minimizing losses, and understanding the role of flow arrangement. The focus was on comparing parallel flow, cross flow, and counter flow–like behavior, using temperature measurements from hot and cold water reservoirs.

## 2. Device Description and Components
Components Used:  
Water–water heat exchanger, Two water pumps, Four water reservoirs (tupperware and insulated box), Immersion heater (hot reservoir), Ice and insulated cold reservoir, Styrofoam insulation, One thermocouple and four thermometers, Food dye (to visualize flow)

Qualitative Description:    
Hot water is circulated from a heated reservoir through one side of the heat exchanger while cold water is pumped from an insulated ice-water reservoir through the other side. Heat is transferred across the exchanger wall due to the temperature difference. The fluids exit into separate reservoirs where outlet temperatures are measured.

The system is open (mass crosses the system boundary) and operates approximately at steady state during each trial.

## 3. Experimental Setup

![Photo of old radio]({{ "/assets/images/experimentalSetup.jpeg" | relative_url }}){: .inline-image-l}

-Heat transfer occurs between the two flow channels  
-No intentional work interaction except pump work  
-Heat loss to surroundings is possible

## 4. System Diagram and Control Volume Analysis

**Control Volume (CV)**
The heat exchanger itself is selected as the control volume.

**Mass flows:** 
ṁ_hot in = ṁ_hot out  
ṁ_cold in = ṁ_cold out

**Energy interactions:**  

![Photo of old radio]({{ "/assets/images/energyBalance.jpeg" | relative_url }}){: .inline-image-l}

The performance of the heat exchanger was evaluated using energy balances, entropy balances, and heat exchanger effectiveness. For all trials, the system was modeled as a steady-flow control volume with negligible kinetic and potential energy changes. Water was treated as an incompressible fluid with constant specific heat, and because mass flow rates were not directly measured, all heat transfer quantities were calculated on a per-unit-mass basis. The heat transferred by the hot and cold streams was determined from measured inlet and outlet temperatures, and any imbalance between the two was attributed to heat loss to the surroundings, reflecting non-adiabatic operation.


## 5. Experimental Results and Discussion

**Trial 1**  
![Photo of old radio]({{ "/assets/images/trial1.jpeg" | relative_url }}){: .inline-image-l}

The first trial was conducted under parallel flow conditions and saw the hot stream experience a heat drop of 16 degrees celsius. This corresponded to a loss of 67.7 kJ/kg. On the other hand, the cold stream experienced an 14.4 degrees celsius increase in temperature equivalent to 60.2 kJ/kg of heat gained. The difference between these two Q values would mean that about 7.5 kJ/kg of heat was lost to the surroundings. This result is consistent with the uninsulated nature of the heat exchanger and connecting tubing. Despite this loss, the energy balance closed reasonably well, suggesting that the system was operating close to steady state during this trial.

![Photo of old radio]({{ "/assets/images/effectiveness1.jpeg" | relative_url }}){: .inline-image-l}

Using the definition of heat exchanger effectiveness as the ratio of actual heat transfer to the maximum possible heat transfer, and assuming equal heat capacity rates for the two water streams, the effectiveness for Trial 1 was calculated as 47.5%. This moderate effectiveness aligns with the expected performance of a small uninsulated parallel flow heat exchanger as it reflects the limited ability of this configuration to maintain a large temperature difference. 


![Photo of old radio]({{ "/assets/images/entropy1.jpeg" | relative_url }}){: .inline-image-l}

Entropy generation for Trial 1 was calculated by summing the entropy changes of the hot and cold streams and accounting for entropy transfer associated with heat loss to the environment. The hot stream experienced a decrease in entropy due to cooling, while the cold stream experienced an increase due to heating. Including entropy transfer at ambient temperature resulted in a positive entropy generation of approximately 0.013 kJ/kg·K. This calculated entropy generation reflects irreversible behavior consistent with the Second Law of Thermodynamics. The relatively small magnitude of entropy generation suggests that irreversibility was dominated by finite temperature differences rather than extreme losses.

**Trial 2**  
![Photo of old radio]({{ "/assets/images/trial2.jpeg" | relative_url }}){: .inline-image-l}

For the second trial, my group decided to implement cross flow conditions but found anomalous results that deviated from the behavior expected from that of a heat exchanger. Although the hot stream cooled significantly, the cold stream somehow had a decrease in temperature implying it also lost heat. The resulting energy balance suggested an unrealistically large heat loss to the surroundings of 110.3 kJ/kg. There were a variety of reasons for this odd result but I believe it could most likely be due to thermal stratification. Something that we did for the second trial that we didn't do previously was remix the resulting outlet waters back into the "reservoirs" resulting in this temperature difference. However, these outlet water temperature was very different in magnitude to the cold reservoir. Due to the density differences between warm and cold water, the reservoir may have developed vertical temperature layers rather than remaining well mixed. Since the pump was located near the bottom of the reservoir, it would draw colder more denser water even as the top of the reservoir had more accumulated warmer water. As a result, the inlet temperature we measured may not have represented the bulk average reservoir temperature. In addition, imperfect mixing of the cold outlet stream upon returning to the reservoir could have locally cooled regions near the pump inlet. These effects would cause the measured cold outlet temperature to decrease despite heat being transferred from the hot stream. This stratification indicates that the system was not operating at steady state due to changes we made before the start of the trial. 

![Photo of old radio]({{ "/assets/images/entropy2.jpeg" | relative_url }}){: .inline-image-l}

The entropy generation calculation further confirms this conclusion. The entropy change of the hot stream was calculated to be -0.313 kJ/kg·K. The cold stream entropy change came out to be -0.06 kJ/kg·K. Notably, both streams experienced entropy decreases which is inconsistent with physically valid heat exchanger operation and directly indiates a breakdown of steady state assumptions. When we factor in entropy transfer associated with the large heat loss to the surroundings, the entropy generation came out to be 0.001 kJ/kg·K. Although this value does not violate the Second Law, the fact that both fluid streams lose entropy demonstrates that the measured temperature do not correspd to a meaningful steady state process. 

**Trial 3**  
![Photo of old radio]({{ "/assets/images/trial3.jpeg" | relative_url }}){: .inline-image-l}

In response to the odd results from the experiment above, my group went back to the parallel flow setup and remeasured our values just to perform a sanity check and ensure our values were precise. Again, the inlet hot reservoir temperature was similar to the first trial of 38.9 degrees at 39.5 degrees. The same can be said for the cold reservoir at 4.5 degrees compared to the first trial value of 4.8 degrees. Something we couldn't actually control perfectly was the temperature difference between the hot and cold reservoir of this third trial. As a result, the calculated heat loss to the surrounding increased significantly between the system and ambient air. The hot stream temperature dropped by 17.4 degrees while the cold stream temperature increased by 11.2 degrees. This corresponded to a specific heat loss of 72.7 kJ/kg for the hot stream and 46.8 kJ/kg for the cold stream. The calculated heat loss to the surrounding came out to 25.8 kJ/kg, a significant increase. This behavior indicates that the larger temperature difference between the heat exchanger surfaces, connecting tubing, and air meant greater heat transfer amplifying non adiabatic effects. 

![Photo of old radio]({{ "/assets/images/effectiveness3.jpeg" | relative_url }}){: .inline-image-l}

The calculated value for effectiveness in the third trial was 49.714%. Although the effectiveness value is slightly higher numerically than that of trial 1, it does not represent an improvement in overall thermal performance. Instead, the increased effectiveness is primarily driven by the larger temperature drop of the hot stream resulting from the higher inlet temperature. The cold stream experienced a smaller temperature rise, indicating that a significant fraction of the thermal energy removed from the hot stream was lost to the surroundings rather than transferred to the cold fluid. This interpretation is consistent with the energy balance, which showed a substantially larger heat loss to the environment in trial 2. 

## 6. Conclusion  
All in all, these results highlight the sensitivity of heat exchanger performance to operating conditions, particularly inlet temperature, and underscore the importance of minimizing heat loss through insulation and careful thermal design in real-world applications. Throughout the experiment, deviations from ideal behavior such as heat loss to the surroundings, unsteady reservoir temperatures, and thermal stratification demonstrated how strongly experimental outcomes depend on practical considerations often neglected in theoretical analyses. While standard performance metrics such as effectiveness provided useful insight, their limitations became evident when steady-state and adiabatic assumptions were violated, emphasizing the need to interpret such quantities in the context of real system behavior. Future experiments could further improve understanding by systematically exploring additional flow configurations, including counterflow operation, varied flow rate ratios, and different levels of insulation, and by repeating trials after improving reservoir mixing and insulating the heat exchanger and tubing to allow more direct comparison with ideal theoretical predictions and isolate the effects of configuration from external losses. Additionally, longer run times to ensure steady-state operation and more precise temperature measurements at the heat exchanger inlets and outlets would reduce uncertainty and improve the reliability of energy and entropy balance calculations. Overall, this experiment provided valuable insight into the challenges of applying thermodynamic principles to real systems, reinforcing the importance of experimental design, measurement accuracy, and assumption validation when analyzing thermal devices, and illustrating that real-world performance is governed not only by ideal thermodynamic limits but also by irreversibilities, environmental interactions, and design tradeoffs.


