# Initial Prompt

```text
Act as an expert frontend developer and experienced high school physics teacher. Create a complete, production-ready, single-file HTML5 page (including inline CSS and modern JavaScript) to teach Grade 10 (sophomore) students about the "Scattering of Light in the Atmosphere."

The page must be fully responsive, visually engaging, interactive, and completely self-contained with no external dependencies (use standard CSS/JS, no external frameworks like React, and use HTML5 Canvas or CSS graphics for visuals instead of external images).

### Educational Goals
1. Explain Rayleigh Scattering and why the sky is blue.
2. Explain why sunsets and sunrises look red/orange.
3. Keep the tone accessible, engaging, and dynamic for 10th graders (approx. 15-16 years old).

### Key Features & Layout

1. Header & Introduction
   - A modern, clean title section.
   - A brief, punchy introduction explaining what "light scattering" means using a simple analogy (e.g., bumper cars or light hitting obstacles).

2. The Main Interactive Simulation (Split Screen/Two-Column Layout)
   - Left Column: Interactive Controls
     - A slider for "Time of Day" (Noon, Afternoon, Sunset).
     - A toggle or slider for "Atmosphere Density" (None/Space, Normal, Heavy Pollution).
   - Right Column: Visual Canvas / Demonstration
     - An interactive HTML5 Canvas or SVG container showing a stylized Earth and its atmospheric layer.
     - When the "Time of Day" changes, show an animated beam of white light (representing sunlight) coming from the sun, traveling through the atmosphere to an observer on Earth.
     - Visually demonstrate that at Noon, the short path allows blue light to scatter everywhere (making the sky look blue). 
     - Visually demonstrate that at Sunset, the long path scatters away all the blue/violet light before it reaches the observer, leaving only the red/orange wavelengths to get through.

3. "Test Your Knowledge" Interactive Quiz Section
   - Include 3 gamified, multiple-choice questions based on the simulation.
   - Provide immediate, encouraging feedback for correct answers and helpful explanations for incorrect ones.
   - Include a score tracker.

### Styling & UI/UX Guidelines
- Use a modern "EdTech" aesthetic with a dark/light mode friendly color palette (deep blues, clean whites, vibrant accent colors for light wavelengths).
- Use a clean sans-serif font (like Arial or system-ui).
- Ensure all interactive elements (sliders, buttons) have smooth CSS transitions and hover states.
- Make sure the UI layout adapts beautifully to both desktop screens and mobile tablets.

Deliver the entire solution as a single, HTML, CSS inside <style> tags, and JS inside <script> tags. Ensure the code is clean, well-commented, and free of placeholder text.
```
