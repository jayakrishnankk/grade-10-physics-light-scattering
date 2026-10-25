# Grade 10 Physics: Atmospheric Light Scattering 🌤️

An interactive, self-contained HTML5 learning simulation demonstrating **Rayleigh Scattering**, explaining why the daytime sky is blue and why sunsets and sunrises turn brilliant shades of orange and red.

---

## 🎯 Educational Overview

- **Subject**: High School Physics (Grade 10 / Sophomore)
- **Unit**: Light, Waves, and Optics
- **Core Topics**:
  - **Rayleigh Scattering Law**: $\text{Scattering Intensity} \propto \frac{1}{\lambda^4}$
  - **Wavelength Disparity**: Short blue wavelengths ($\sim 400\text{ nm}$) scatter $\sim 9.4\times$ more vigorously off air molecules ($N_2, O_2$) than long red wavelengths ($\sim 700\text{ nm}$).
  - **Optical Path Length**: At noon, light traverses a short perpendicular column of air ($\approx 12\text{ km}$); at sunset, light cuts tangentially through $10\times$ to $30\times$ more atmosphere, filtering out all blue light.
  - **Zero Atmosphere (Moon/Space)**: Without air molecules, the daytime sky is pitch black.
  - **Mie Scattering (Clouds & Smog)**: Particles larger than light wavelengths scatter all colors equally.

---

## 📁 Files in This Directory

- [`index.html`](./index.html): Self-contained, single-file interactive simulation (Canvas visuals, controls, ROYGBIV explorer, interactive quiz).
- [`PROMPT.md`](./PROMPT.md): The full initial prompt specifying all pedagogical, architectural, and design requirements.
- [`README.md`](./README.md): This documentation file.

---

## 🚀 How to Run Locally

Open [`index.html`](./index.html) directly in any modern browser:
```bash
open index.html
```
Or serve via a local HTTP server:
```bash
python3 -m http.server 8000
```
Then navigate to `http://localhost:8000`.
