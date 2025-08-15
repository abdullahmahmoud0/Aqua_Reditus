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

It all started when I noticed how much greywater from washing and cooking just disappears down the drain. I thought: *if there’s a way to treat this before it’s lost, we could cut our water waste massively*.  

Sitting at my desk with a notebook, I mapped out what an ideal solution should look like: compact, easy to maintain, and fully modular so that anyone could swap out parts without dismantling the whole unit.  

I sketched a block diagram of the system:
1. **Sedimentation chamber** – large particles sink out.
2. **Sand + gravel filtration** – traps smaller debris.
3. **Activated carbon chamber** – removes chemical impurities and odors.
4. **UV sterilization** – neutralizes bacteria and viruses.  

The goal wasn’t just to “make a model” — it was to build a **visual proof of concept** that could guide a future physical build. I decided to make it 3D-visualized in CAD so every detail was crystal clear.

---

## Day 2–3: Research on Filtration Stages  
**Date:** *27/6–28/6*  
**Time Spent:** 10 hours  

I dove deep into case studies of rural water treatment and small-scale purification plants. What struck me was how old, low-tech methods like gravel filtration are still relevant today — they just need to be integrated smartly.  

I decided on a **four-stage path** for my design:  
1. **Gravel & Sand Filtration** – cheap, effective, low maintenance.  
2. **Activated Carbon Chamber** – handles chlorine, odors, and organic compounds.  
3. **Fine Mesh Filtration** – polishes the water before UV.  
4. **UV LED Disinfection** – provides that final safeguard.  

While researching, I also studied **flow rates** and **chamber sizing**. A mistake here could cause backflow or insufficient UV exposure. I made notes to ensure each stage was balanced for small-scale home use.  

---

## Day 4–6: CAD Design (Chamber Modeling)  
**Date:** *29/6–1/7*  
**Time Spent:** 15 hours  

I moved to Fusion 360 and started with the **outer shell** — compact but with enough internal room for serviceability.  

Every chamber was **color-coded**:
- Blue for sedimentation.
- Yellow for gravel/sand.
- Black for activated carbon.
- Purple for UV sterilization.  

I made the chambers slide out like drawers so cleaning or replacing media would be effortless. Each chamber also had **sensor ports** for future upgrades.  

The 3D model quickly became more than just a shell — it was a **maintenance-friendly unit** anyone could operate.  

![fully organized and colored 3d model](assets/image.png)  
![3d model](assets/iii.jpg)  
![3d model](assets/iiiii.jpg)  

---

## Day 7–8: Electronics + Sensor Integration  
**Date:** *2/7–3/7*  
**Time Spent:** 10 hours  

I shifted focus to the “smart” part.  
I set up:
- **Water flow sensors** – to detect when water is passing through.  
- **Turbidity sensors** – to measure clarity.  
- **UV LED drivers** – so the light only activates when needed (saves power and prolongs life).  

Everything was first wired on a breadboard. I used an **Arduino Mega** for more I/O pins since I was running multiple sensors at once. The firmware handled:
- Continuous sensor logging.  
- Automatic UV activation on flow detection.  
- Warning buzzer + LED alerts if turbidity or pH went off-range.  

Once I was sure the readings were consistent, I moved the circuit to a **custom PCB** for durability.  

![Measured voltage and current intensity of system components](assets/image-4.png)  

---

## Day 9–10: BOM, Testing, and Documentation  
**Date:** *4/7–5/7*  
**Time Spent:** 11 hours  

This was when the project really came to life. I ran several test cycles with slightly dirty water to simulate greywater conditions.  

**Key findings:**
- **TDS (Total Dissolved Solids)**: dropped steadily after filtration.  
- **pH**: stabilized near neutral after carbon filtration.  
- **Turbidity**: major drop after fine mesh and UV.  

I logged everything and plotted graphs for clarity:  

![Measured TDS through treatment process](assets/image-1.png)  
![Measured pH through treatment process](assets/image-2.png)  
![Measured NTU (turbidity) through treatment process](assets/image-3.png)  

Finally, I created the **Bill of Materials (BOM)** with prices, prepared wiring diagrams, annotated CAD images, and documented every connection for future reference.

---

## Final Touches and Polish  
**Date:** *6/7*  
**Time Spent:** 8 hours  

I set up a GitHub repository with:
- **BOM in CSV** with links.  
- CAD source files.  
- This detailed journal.  
- Test result graphs.  
- Annotated renders of the 3D model.  

When I stepped back and looked at the final design, I realized this was more than just a student-style build log — it was a small, fully thought-out system that could genuinely help save water if manufactured.

---
