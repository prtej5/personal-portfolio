# Pranav Rohan Tejomurtula — Aerospace Engineering Portfolio

A sleek, dark-themed, interactive personal portfolio for an aerospace engineering student at UT Austin.

## Features
- 🌌 Animated starfield + orbit ring background
- 🛸 Interactive Kepler Orbit Simulator (real orbital mechanics)
- 📊 SVG project diagrams for each engineering project
- 🔍 Project filtering by category (Structures, Aero, Propulsion, etc.)
- 💬 Project detail modals
- 📈 Animated skill bars (scroll-triggered)
- 📅 Timeline-style experience section
- 📱 Fully responsive

## Deployment on Vercel

### Option 1: Drag & Drop
1. Go to [vercel.com](https://vercel.com)
2. Click "Add New → Project"
3. Drag the entire `portfolio/` folder into Vercel
4. Click Deploy

### Option 2: GitHub + Vercel
1. Push this folder to a GitHub repo
2. Import the repo in Vercel
3. Vercel auto-detects the static site — no build config needed
4. Deploy

### Option 3: Vercel CLI
```bash
npm i -g vercel
cd portfolio
vercel --prod
```

## Adding Your Resume Files
Place these files in the same folder as `index.html`:
- `PranavRohanTejomurtulaResume.docx`
- `Pranav_Rohan_Tejomurtula_-_Engineering_Portfolio.pdf`

## Customization
Edit `index.html`:
- **Name / Contact**: Search for "Pranav" to find all instances
- **Projects**: Edit the `projects` array in the `<script>` section
- **Skills**: Edit the `skillBlocks` array
- **Experience**: Edit the `experiences` array
- **LinkedIn URL**: Update the LinkedIn href in the contact section
"# personal-portfolio" 
