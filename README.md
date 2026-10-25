# Grade 10 Physics: Atmospheric Light Scattering 🌤️

An interactive, self-contained HTML5 physics simulation designed for Grade 10 students to explore **Rayleigh Scattering**, why the daytime sky appears blue, and why sunsets blaze in brilliant shades of orange and red.

🔗 **Live Interactive App**: [https://jayakrishnankk.github.io/grade-10-physics-light-scattering/](https://jayakrishnankk.github.io/grade-10-physics-light-scattering/)

---

## 🎯 Educational Goals

1. **Rayleigh Scattering Law**: Understand that scattering intensity is inversely proportional to the fourth power of wavelength:
   $$\text{Scattering Intensity} \propto \frac{1}{\lambda^4}$$
   Because blue light ($\sim 400\text{ nm}$) has roughly half the wavelength of red light ($\sim 700\text{ nm}$), blue light scatters nearly **$10\times$ more intensely** off atmospheric gas molecules ($N_2$ and $O_2$).
2. **Daytime Sky vs. Sunset**:
   - **Noon**: Sunlight traverses a short atmospheric path ($\sim 12\text{ km}$ air mass). Blue light scatters in all directions across the sky dome, bathing the ground in diffuse blue light while the Sun appears bright yellow-white.
   - **Sunset**: Sunlight strikes Earth's curvature tangentially, traversing $10\times$ to $30\times$ more atmosphere. Virtually all blue and violet photons scatter out of line-of-sight, leaving only long red and orange wavelengths to reach the observer's eyes.
3. **Atmospheric Density Differences**:
   - **Moon / Space Vacuum**: Zero air molecules $\rightarrow$ zero scattering. The sky remains pitch black even with the blazing Sun directly overhead.
   - **Heavy Smog / Volcanic Ash**: Larger aerosol particles cause Mie scattering and heavy extinction, resulting in murky brown/orange skies and blood-red sun discs.

---

## 🚀 Features

- **Interactive Orbital & Planetary Canvas**: Visualizes Earth's curvature, the atmospheric shell, the Sun's orbital position, and real-time probabilistic photon scattering.
- **Ground Observer POV Window**: A synchronized real-time view of what human eyes see on the horizon as the Sun moves from midday noon to sunset.
- **Interactive ROYGBIV Wavelength Explorer**: Drag across 380 nm to 750 nm to inspect wavelength, frequency, and live Rayleigh scattering multipliers relative to red light.
- **Gamified Quiz**: 3 sophomore-level conceptual questions with instant feedback, explanations, score tracking, and retry functionality.
- **Physics Mythbusters**: Clarifies why the sky isn't violet (solar spectrum emission + human eye cone sensitivities), why clouds are white (Mie scattering), and why brake lights and stop signs are red.

---

## 💻 Tech Stack

- **Pure HTML5, CSS3, and JavaScript**
- **Zero external libraries or CDN dependencies** (No React, No Tailwind, No external fonts, No external images).
- Fully responsive across desktop, tablet, and mobile screens.
- Canvas rendering with device pixel ratio scaling for crisp retina display graphics.

---

## 📄 License

MIT License. Created for high school physics education.
