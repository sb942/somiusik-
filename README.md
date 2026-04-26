SOMIUSIK!!
An immersive, interactive 3D CD and vinyl record gallery built for the web. Somiusik transforms standard album displays into a fully navigable 3D environment, allowing users to browse and interact with their favorite music covers in a dynamic virtual space.

Features
Interactive 3D Gallery: Navigate through a collection of CDs and vinyl records in a digital 3D space.

Dynamic Texture Loading: Seamlessly renders high-quality album artwork onto 3D objects.

Refined Physics: Smooth interpolation and controlled interactions (featuring stabilized viewing so records don't spin wildly when unmaximized).

Web-Optimized: Built to run directly in the browser with efficient rendering to minimize Z-fighting and visual clipping.

Tech Stack
Core: HTML5, CSS3, JavaScript

3D Rendering: Three.js

Styling & Transforms: CSS 3D Transforms

Getting Started
To run this project locally on your machine:

Clone the repository:

Bash
git clone https://github.com/your-username/somiusik.git
Navigate to the project directory:

Bash
cd somiusik
Start a local server:
Because this project uses Three.js and loads external image textures, it needs to be run on a local web server (opening the HTML file directly in the browser may cause CORS errors). You can use a tool like Live Server in VS Code, or Python via your terminal:

Bash
python -m http.server 8000
Open in Browser:
Visit http://localhost:8000 to view the gallery.

Deployment
Somiusik is structured to be easily hosted on platforms like GitHub Pages.

[Note: You can add your live custom domain link here once your site is published!]
