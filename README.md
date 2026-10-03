# Facility Layout Optimization for FMCG Production Line

An optimized facility layout model for a fast-moving consumer goods (FMCG) manufacturing plant, developed via construction-based and CRAFT algorithms.

## About the Project
The project focuses on a production line with high-volume manufacturing. The primary challenge was the physical disconnection between the baking oven exit and the coating unit. This required transferring semi-finished, fragile products across long distances, increasing transport risks and operational delays. Additionally, the line ends with manual packaging operations that require adequate space integration.

## Methodology
* **Flow Analysis & Digitization:** Production flow was mapped and digitized using a From-To chart (Trip Matrix) based on a 3-shift, 1200 boxes/day assumption.
* **Activity Relationship Chart (REL Chart):** Qualitative proximity requirements were assigned based on flow continuity, product fragility, hygiene, and manual operation density.
* **Construction-Based Initial Layout:** A starting block layout was generated in an 8x4 grid, satisfying critical proximity goals.
* **CRAFT Algorithm:** The improvement-based CRAFT algorithm was applied to test for a lower total material handling cost using rectilinear (Manhattan) distance. The initial layout was proven to be a local optimum.

## Results
* **Current Layout Transport Cost:** 28,800
* **Optimized Layout Transport Cost:** 21,600
* **Achievement:** A 25% reduction in total material handling cost, minimized product damage risk by shortening transfer distances, and better integration of manual operations.

## Author
Mustafa Cesmeli 
Industrial Engineer 
(LinkedIn: https://www.linkedin.com/in/mustafacesmeli/) | (Mail: cesmelimustafa0@gmail.com)]
