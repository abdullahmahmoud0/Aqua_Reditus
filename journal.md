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

The whole idea started over a casual lunch when I noticed how much water we waste in our home without thinking twice. Washing vegetables, cleaning rice, even rinsing dishes — all that water just swirls away down the drain, never to be used again. It made me wonder how much of it could be reused if we treated it properly. That small observation snowballed into a bigger thought: what if we had a **personal-sized wastewater treatment unit** that could sit quietly in a corner, do its job, and help us recycle greywater for non-drinking purposes?  

I sat at my desk and began scribbling ideas in my notebook. I wanted something that was modular and easy to service, not one of those big industrial boxes that people are afraid to touch. My mind kept returning to a four-stage system: sedimentation to let the big stuff settle, a gravel/sand filter for smaller particles, activated carbon to handle smells and chemicals, and finally, UV sterilization to eliminate bacteria. I sketched it out like a flow diagram, imagining each chamber as a self-contained block that could be slid in and out for cleaning. The name came to me almost instantly — *Aqua Reditus*, meaning "water return." It felt right, like the project already had a personality.

---

## Day 2–3: Research on Filtration Stages  
**Date:** *27/6–28/6*  
**Time Spent:** 10 hours  

The next two days were basically me buried in articles, PDFs, and YouTube rabbit holes about small-scale water purification. I was surprised by how much of this technology is centuries old — gravel filtration has been around since ancient times — yet still highly effective when combined with modern methods like UV LEDs.  

One thing I quickly learned was that order and proportion are everything. If the gravel filter is too fine, water flow slows to a trickle. If the UV chamber is too short, microbes survive the pass. I kept imagining a family using this unit daily — it had to work without babysitting.  

By the end of the research phase, I had locked in my treatment path: start with **gravel and sand filtration**, then move to **activated carbon absorption**, follow with **fine mesh polishing**, and finish with **UV LED disinfection**. Each stage served a purpose, and all together they made a complete loop from dirty to safe. I also wrote down rough dimensions for each chamber, keeping in mind that I’d need enough room for sensors and maintenance access.

---

## Day 4–6: CAD Design (Chamber Modeling)  
**Date:** *29/6–1/7*  
**Time Spent:** 15 hours  

This was the creative phase — translating all the research and scribbles into a tangible 3D model in Fusion 360. I started with the outer casing, wanting it to feel modern and minimal, something that wouldn’t look out of place next to a kitchen appliance or a garden water tank. Then I began building the internal chambers, each with its own mounting points, flow paths, and access hatches.  

I decided to **color-code** the chambers so that even someone unfamiliar with the system could instantly understand the process: blue for sedimentation, yellow for sand/gravel, black for carbon, and purple for UV. I imagined opening the unit and being able to tell at a glance which stage needed attention.  

Every time I completed a section, I would rotate the model and think, *If I were actually holding this, could I clean it? Could I replace this filter without pulling the whole thing apart?* That constant mental check kept the design grounded in practicality instead of just looking pretty on screen.  

![fully organized and colored 3d model](assets/image.png)  
![3d model](assets/iii.jpg)  
![3d model](assets/iiiii.jpg)  

---

## Day 7–8: Electronics + Sensor Integration  
**Date:** *2/7–3/7*  
**Time Spent:** 10 hours  

With the physical model taking shape, I moved to the electronics that would make it "smart." I chose an **Arduino Mega** because I knew I’d be connecting multiple sensors and didn’t want to run out of pins halfway through. The plan was simple: the sensors would collect data, the Arduino would process it, and the system would respond automatically.  

I wired up a **turbidity sensor** to measure water clarity, a **flow sensor** to detect when water was moving through the system, and a small array of **UV LED drivers** that could be switched on and off depending on the readings. The firmware I wrote kept an eye on the numbers — if the turbidity rose above a certain threshold, it would trigger a buzzer and LED alert.  

I can’t lie, there were a couple of frustrating moments here. At one point, I accidentally swapped the wiring on the UV driver and thought I had burned out the entire board. Thankfully, it turned out to just be a loose jumper wire. Once the system was stable, I transferred it from the breadboard to a **custom PCB**, which felt like moving from a prototype into something that could be installed and forgotten.  

![Measured voltage and current intensity of system components](assets/image-4.png)  

---

## Day 9–10: BOM, Testing, and Documentation  
**Date:** *4/7–5/7*  
**Time Spent:** 11 hours  

Testing day was honestly the most satisfying part. I filled a container with murky water — a mix of kitchen rinse water and some added dust for realism — and ran it through the system in stages. Watching the turbidity drop with each chamber felt like watching a slow-motion magic trick.  

I tracked the **TDS (Total Dissolved Solids)** and **pH** using simple handheld meters, and as expected, the carbon stage had the most dramatic effect on chemical content while the UV stage ensured bacteria wouldn’t survive. The **turbidity** reading after the final mesh filter and UV stage was nearly crystal-clear.  

![Measured TDS through treatment process](assets/image-1.png)  
![Measured pH through treatment process](assets/image-2.png)  
![Measured NTU (turbidity) through treatment process](assets/image-3.png)  

Once I had the numbers, I spent hours creating a clean **Bill of Materials (BOM)** with prices and sourcing links. I also took annotated screenshots of the CAD design, drew up wiring diagrams, and made sure that if someone else ever wanted to replicate this, they’d have a complete guide.

---

## Final Touches and Polish  
**Date:** *6/7*  
**Time Spent:** 8 hours  

The last day was all about presentation. I uploaded everything to a neatly organized GitHub repository — CAD files, wiring diagrams, BOM, journal, and even the test result graphs. It wasn’t just about showing off the work, but about making it easy for anyone to take the idea and build on it.  

When I looked back at the first sketch from Day 1 and compared it to the final renders, I realized how much the project had evolved. What started as a quick “what if” idea had turned into a complete, functional concept with a clear purpose. *Aqua Reditus* might just be a model for now, but it’s ready for the day it becomes a real, working device.

---
