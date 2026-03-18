# Gauss's Law Interactive Simulator

An interactive educational tool designed to visualize electric flux through a closed Gaussian surface.

## Features
- **Dynamic Flux Calculation:** Automatically calculates net flux ($\Phi = \sum Q / \varepsilon_0$) based on the charges inside the surface.
- **Multiple Charges:** Add and drag any number of positive and negative charges.
- **Visual Indicators:** Real-time marking of field lines entering (red) and exiting (green) the surface.
- **Touch Support:** Fully compatible with mobile devices and tablets for classroom demonstrations.

## Technical Note on Physics Model
To ensure maximum educational clarity, this simulator uses **individual field mapping** for each charge rather than vector field superposition. 

**Why?** In a complex superposition field, the "in-and-out" cancellation of flux from external charges becomes visually obscured. By rendering lines individually, it provides a direct visual proof of Gauss's Law: every line from an external charge that enters the volume must also exit it, resulting in a net flux of zero.

## How to Use
1. Use **Add +Q** or **Add -Q** to place charges on the canvas.
2. Drag charges inside or outside the dashed circle (Gaussian Surface).
3. Observe the change in the net flux formula and the intersection points.