# Molecular dynamics is calculus

A one-page, self-contained web demo for calculus students: atoms are balls, the energy is a landscape,
the force is minus the slope, Newton's law is a differential equation, and two Taylor series give the
step that almost every molecular dynamics code uses.

Live page: https://mironovb.github.io/mdcalculus/

- `index.html`: the simple version. Forty Lennard-Jones atoms bouncing in a box, a pointer-driven
  energy landscape, the Verlet step derived and shown live, and the femtosecond clock.
- `advanced/index.html`: the full tool. One atom on a one-dimensional energy curve with tangent, force,
  Verlet ghost points, Taylor parabola, Euler versus Verlet, a Langevin thermostat and a second screen
  with metadynamics. Live at https://mironovb.github.io/mdcalculus/advanced/

Both pages are single HTML files with inline CSS and vanilla JavaScript: no build step, no libraries,
no network requests. Open either file in a browser and it works offline.
