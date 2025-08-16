---
title: "FC-ABSS"
author: "Ali Essam"
description: "A feedback-controlled microalgae-bacteria system for tilapia wastewater purification"
created_at: "2025-06-23"
---

## Total Time Spent: 83 Hours

---

### Day 1 – June 23  
**Time Spent:** 6h  

I started the day scribbling down the initial concept of the project. The main idea was to build a feedback-controlled system that combines microalgae and bacteria to clean tilapia wastewater. At first, it felt like a wild idea, but as I dug into papers on aquaculture water contents, it slowly started to make sense.  

I spent hours researching what’s actually in tilapia wastewater – nitrates, phosphates, organic matter. I wrote down a list of objectives and began sketching out how such a system would look if simulated.  

Honestly, it felt less like “work” and more like an exploration. I was excited, but also a little overwhelmed. My notebook is already messy with arrows and random thoughts that don’t fully connect yet.  

---

### Day 2 – June 24  
**Time Spent:** 5h  

The big decision today was finalizing the system’s conceptual design. I decided to integrate light and temperature feedback because both strongly affect algae growth. That felt like a breakthrough moment.  

I drew out the block diagram and played around with a couple of options for how to represent the tank structure digitally. The diagram looked pretty abstract at first, but it gave me a sense of direction.  

Had tea while doodling some layout ideas – felt strangely calm, like piecing together a puzzle.  

- ![3d design for the prototype](images/image.png)  

---

### Day 3 – June 25  
**Time Spent:** 7h  

I dug deep into finding which electronics would realistically work in such a setup. Even though I wasn’t actually buying hardware, I wanted the simulation to feel grounded. I spent hours comparing light setups and thinking about how photosynthetic rates respond under different CRI (color rendering index) values.  

After a while, my brain felt cooked from staring at graphs, but I forced myself to document every variation. It reminded me of how much patience science requires — sometimes it’s just you and a dozen “almost but not quite” results.  

- ![the 3d with rough texture](images/porr.jpg)  

---

### Day 4 – June 26  
**Time Spent:** 6h  

Temperature sensors became the focus. I searched for accurate waterproof options and simulated how a small heater would behave inside a sealed tank. The thermal response curves were slower than I expected, and I spent extra time calculating the delay between heater activation and water reaching equilibrium.  

It was tedious, but satisfying once the numbers started matching up. In the middle of this, I found myself wondering: if I actually built this, would the heater hum loudly? Funny how your brain wanders.  

---

### Day 5 – June 27  
**Time Spent:** 5h  

Today I designed the heating loop and simulated relay activations. Watching the heater profile change under different time controls was oddly entertaining. Energy consumption calculations were straightforward, but I caught myself overthinking whether I accounted for heat losses correctly.  

At some point, I realized I was listening to the same song on repeat for almost an hour. Guess that means I was in the zone.  

---

### Day 6 – June 28  
**Time Spent:** 5h  

Light enclosure simulations took over today. I tested LED placement against the algae’s effective surface area. It was surprisingly tricky to find a “sweet spot” where light was distributed evenly.  

I also searched for light sensors with fast analog response times — not that I’ll be wiring them physically, but it helps to keep things realistic.  

Sometimes I wish I could actually see how the algae would glow under the lights I simulated.  

- ![the 3d on simulation](images/por.jpg)  
- ![Light intensity control circuit](images/image-2.png)  

---

### Day 7 – June 29  
**Time Spent:** 5h  

Electrical wiring and enclosure design were today’s tasks. I mapped everything out digitally and simulated the connections. Power draw calculations based on spec sheets gave me confidence that the design could, in theory, run efficiently.  

Still, I laughed a little at how abstract this all is — running numbers on something that doesn’t physically exist in front of me.  

- ![circuit diagram for the feedback system of light intensity and temperature](images/image-1.png)  

---

### Day 8 – June 30  
**Time Spent:** 6h  

Aeration patterns were the star of the day. I modeled oxygen pump placements and simulated water flow, then calculated oxygen diffusion curves. The data showed how oxygen availability directly affects bacterial uptake efficiency.  

It was one of those satisfying days where the simulation results aligned with my expectations. I rewarded myself with a late-night snack while reviewing the diffusion graphs.  

---

### Day 9 – July 1  
**Time Spent:** 5h  

I experimented with light shielding using foil-based enclosures. It was fascinating to see how light fluctuation could be reduced by adding reflective surfaces. I even looked up whether foil frames could stay structurally stable long-term.  

The results made me smile — such a simple material making such a big difference in simulation.  

- ![fully 3d colored](images/Picture51.png)  
- ![temperature control circuit](images/image-3.png)  

---

### Day 10 – July 2  
**Time Spent:** 5h  

The control box layout was my focus. I simulated how it would behave under environmental stress, like blocked airflow or external heat exposure. Internal temperature rise was steeper than I expected.  

It’s funny, but designing the “box” was one of the most satisfying parts — maybe because I could imagine physically holding it.  

---

### Day 11 – July 3  
**Time Spent:** 5h  

Simulated data logging today. I drafted CSV outputs for temperature and light data across a 30-day run. At one point, I accidentally simulated a storage failure and laughed at how realistic it felt — like even my digital systems have bad days.  

---

### Day 12 – July 4  
**Time Spent:** 5h  

Researched nutrient measurement methods. Mostly dug into nitrate and phosphate sensing techniques. Simulated how each one responds over time.  

At some point I stopped and thought: I’ve been staring at “nutrient removal efficiency” graphs on July 4th while most people are out enjoying fireworks.  

---

### Day 13 – July 5  
**Time Spent:** 5h  

I designed a 48-hour test cycle simulation and tracked nutrient drop rates every 6 hours. It was cool watching nitrogen and phosphorus levels graph out smoothly.  

The graphs looked satisfying, like progress bars slowly filling up.  

- ![Results of removal rates and adjustment values](images/image-7.png)  

---

### Day 14 – July 6  
**Time Spent:** 4h  

Ran post-treatment simulations. The system achieved about 67% nitrate reduction, which felt like a real milestone. I charted the before-and-after values and compared them against similar studies.  

It wasn’t perfect, but seeing numbers drop is always encouraging.  

- ![removal rate of the pollutants.](images/image-4.png)  
- ![Light intensity and temperature before adjustment](images/image-5.png)  
- ![Light intensity and temperature after adjustment](images/image-6.png)  

---

### Day 15 – July 7  
**Time Spent:** 4h  

Finalized all 3D models and rendered some visuals for documentation. I also simulated failure scenarios — like what happens if the heater fails or light goes off unexpectedly. Watching the system “recover” in simulation felt like testing resilience in a game.  

- ![the 3d with soft texture](images/porrr.jpg)  

---

### Day 16 – July 8  
**Time Spent:** 5h  

I wrapped everything up today. Compiled the README, organized the journal, BOM, and schematics. I also went through all the images and references to make sure everything was in place.  

Looking back, this project felt more like a personal journey than a technical requirement. It was just me exploring an idea at my own pace, sometimes getting lost in details, sometimes daydreaming while running simulations.  

---

