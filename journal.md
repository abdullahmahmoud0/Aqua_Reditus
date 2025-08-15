---
title: "Aqua Reditus"
author: "Abdullah Mahmoud"
description: "A smart and compact wastewater treatment unit with a 3D visualization design."
created_at: "26-6-2025"
---

**Total Time Spent: 60 hours**

---

## Day 1: Ideation & Objective Definition  
**Date:** *26/6*  
**Time Spent:** 6 hours  

This project started after I realized how much greywater is wasted at home every day. I thought — why not design something small, modular, and easy to maintain that can recycle household water before it’s lost?  

I sketched my first rough concept on paper while sipping tea, deciding on a **3D-visualized modular wastewater treatment unit**.  

The treatment flow draft:
1. Sedimentation stage for large particles.
2. Filtration chamber.
3. Activated carbon absorption.
4. UV sterilization for microorganisms.  

---

## Day 2–3: Research on Filtration Stages  
**Date:** *27/6–28/6*  
**Time Spent:** 10 hours  

I studied rural and emergency water treatment setups, noting how each stage works:
- Gravel & sand for mechanical filtration.
- Activated carbon for chemical removal.
- Fine mesh for polishing.
- UV LEDs for sterilization.  

The concept sketch evolved into a more refined plan. I kept modularity in mind so the chambers could be replaced without taking apart the whole system.  

---

## Day 4–6: CAD Design (Chamber Modeling)  
**Date:** *29/6–1/7*  
**Time Spent:** 15 hours  

I built the model in Fusion 360 — a compact but accessible outer shell, removable chambers, and built-in sensor ports. Each stage got a distinct color in the 3D design so even a non-technical user could identify them.  

![fully organized and colored 3d model](assets/image.png)  
![3d model](assets/iii.jpg)  
![3d model](assets/iiiii.jpg)  

---

## Day 7–8: Electronics + Sensor Integration  
**Date:** *2/7–3/7*  
**Time Spent:** 10 hours  

I wired the water flow sensors, turbidity sensors, and UV LED drivers on a breadboard first. An Arduino Mega handled:
- Continuous logging of sensor data.
- Automatic UV activation when water flows.
- Alerts via buzzer and LEDs for unsafe readings.  

Once stable, I moved everything to a custom PCB to keep it neat.  

![Measured voltage and current intensity of system components](assets/image-4.png)  

---

## Day 9–10: BOM, Testing, and Documentation  
**Date:** *4/7–5/7*  
**Time Spent:** 11 hours  

I assembled the full prototype and ran test cycles with slightly dirty water. The readings confirmed it worked:
- **TDS** dropped after filtration.  
- **pH** stabilized after treatment.  
- **Turbidity** decreased significantly post-carbon and UV stages.  

![Measured TDS through treatment process](assets/image-1.png)  
![Measured pH through treatment process](assets/image-2.png)  
![Measured NTU (turbidity) through treatment process](assets/image-3.png)  

I finalized the BOM with prices, documented the wiring diagram, and annotated CAD screenshots.

---

## Final Touches and Polish  
**Date:** *6/7*  
**Time Spent:** 8 hours  

I uploaded everything to a well-organized GitHub repository containing:
- The BOM in CSV format with links.
- CAD source files.
- Annotated 3D model images.
- This journal.  

This wasn’t just a build — it felt like creating something that could genuinely help save water.

---
