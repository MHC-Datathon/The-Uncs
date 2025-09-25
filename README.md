# Datathon Documentation: Automated Camera Enforcement (ACE) & Bus Lane Violations  

## 1. Problem Statement  
New York City buses are frequently slowed by vehicles blocking bus lanes and bus stops. Even with the implementation of **Automated Camera Enforcement (ACE)** and the start of congestion pricing in January 2025, violations continue to occur.  

This creates **Delays** in bus travel times and **Reduced reliability** for commuters  

---

## 2. Approach  
Our team examined the **MTA Automated Camera Enforcement (ACE) dataset** (tens of millions of violation records) and policy reports from the NYC Comptroller, DOT, and MTA.  

**Steps we took:**  
- Filtered violations by **exempt status** (e.g., `EXEMPT – EMERGENCY VEHICLE`, `EXEMPT – COMMERCIAL UNDER 20`) to study repeat offenders  
- Mapped **violation locations** across boroughs and corridors (e.g., 14th Street Busway)  
- Analyzed **timing of violations**, identifying peak hours for commercial vehicles  
- Cross-referenced with **congestion pricing policies** to assess interaction with enforcement  
- Reviewed **equity & accessibility implications** using Comptroller audits and advocacy reports  

---

## 3. Key Findings  
- **Exempt vehicles drive repeat violations**: Ambulances and commercial trucks under 20 make up a large share of recurring offenders.  
- **Hotspot routes** for repeat exempt violators:  
  - **M101** – ~1,516 violations  
  - **Bx36** – ~1,332 violations  
  - **Q54** – ~814 violations  
-  Exempt violations are heavily concentrated in **Mid-Town Manhattan**, especially along corridors like **3rd Avenue (M101)** and **14th Street Busway (M14)**. Bronx (Bx36) and Queens (Q54) also show repeat exempt violators.  
-  Vehicle volumes dropped, but violations increased again - suggesting wealthy drivers treat fines as a **cost of convenience**.   
- **Vertical bus routes outperform horizontal routes**:  
  - Crosstown buses (M14, M34, M42, M50, M66) average **~6.3 mph**.  
  - Vertical routes (M1, M2, M101, etc.) average **~7.4 mph**.  
  - Despite barriers on the M14, crosstown routes still lag behind vertical routes due to intersections and heavier congestion.  

---

## 4. Recommendations  
- Since the implementation of the ACE system, more vehicles have stayed out of bus lanes. Continue expanding ACE cameras to the outer boroughs.
- Use traffic guards or crossing guards in major areas to further discourage vehicles from blocking bus lanes.
- Violations have increased since congestion pricing. Implement stricter penalties and launch educational campaigns to make drivers more aware of bus lane rules.
- Take advantage of the “street space dividend” by adding more bus lanes, especially offset or center-running lanes. Physical barriers can also help prevent vehicles from entering bus or bike lanes.
- Consistently reinforce ADA training for MTA drivers to ensure seamless boarding for wheelchair users and other riders with accessibility needs.
- Continue advocating for more seamless transit infrastructure by engaging with community boards and elected officials.

---

## Notes from Team Discussion  
- Barriers on **M14** show measurable impact: fewer violations and faster speeds vs. other routes  
- Violations dropped in **Feb 2025** (likely due to cold weather + lower bus usage) but spiked again after  
- Data showed **cross-town routes** (like M34) sometimes outperforming expected “flagship” routes  

ACE enforcement speeds buses, but gaps (especially exempt vehicle behavior, equity issues, and enforcement consistency) still slow NYC transit. Pairing cameras with physical design, higher penalties, and accessibility-first policies will help buses move faster and fairer.  

**LINK TO VIDEO:** https://youtu.be/WF67d6-HHjo
