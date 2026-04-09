TireBuddy is a minimalist, Progressive Web App (PWA) designed to bridge the gap between automotive engineering constraints and everyday drivers. It translates complex tire sizing and safety standards into a simple, user-friendly interface.

 Features

1. Calculates safe alternative tire sizes (Width & Aspect Ratio) for an existing rim. The logic strictly filters out any combinations that deviate more than ±3% from the original total diameter, ensuring the vehicle's speedometer, ABS, and clearance remain uncompromised.
2. Features a dynamically updating, CSS-rendered tire to help non-technical users visually understand where the Section Width, Aspect Ratio, and Rim Diameter are measured on the sidewall.
3. Instantly decodes the 4-digit DOT manufacturing code to determine the tire's age and outputs a color-coded safety verdict (Safe, Caution, or Danger) based on rubber degradation standards.

 Tech Stack

Frontend: HTML5, CSS3 (Automotive Dark Mode UI), Vanilla JavaScript.
Architecture: Single-file application structure optimized as a Progressive Web App (PWA).
Hosting: GitHub Pages.

The Engineering Behind It

As a tool built with mechanical engineering principles in mind, the core upsize calculation relies on the standard total diameter formula:
`Total Diameter = (2 * (Width * (Aspect Ratio / 100))) + (Rim Diameter * 25.4)`

This project demonstrates how strict physical and mechanical constraints can be smoothly integrated into a consumer-facing digital tool. 

📱 Installation
TireBuddy is a PWA. To install it on your device:
open this link https://kirupan2023-prog.github.io/TireBuddy/
Tap the browser menu and select "Install App" or "Add to Home Screen".
