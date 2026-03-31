# EV.ENGINEER™ – Electric 2-Wheeler Repair & Service Center

This is a premium, dark-green themed static website for **EV.ENGINEER™**, a specialized electric 2-wheeler (e-bike and e-scooter) repair center based in Shakthinagar, Mangalore.

## Features
- **Modern Design**: Dark theme with green accent (Telematics branding), glassmorphism and smooth animations.
- **Dynamic Gallery**: Automatically loads and sorts images from the `/public/gallery` folder using the GitHub API.
- **Mobile Optimized**: Fully responsive with a sticky bottom CTA bar on mobile devices.
- **SEO Ready**: Optimized with meta tags, Open Graph, JSON-LD Schema, sitemap, and robots.txt.
- **Fast Performance**: Lightweight vanilla HTML/CSS/JS with no dependencies.
- **EV-Specific Services**: Comprehensive service listings for battery diagnosis, repair, charging issues, motor repair, firmware updates, and emergency breakdown support.

## Services Offered
- 🔋 EV Battery Diagnosis & Repair
- 🔋 EV Battery Replacement
- ⚡ Charging Issues
- 🔌 Charger Repair & Replacement
- 🧠 Controller & BMS Repair
- ⚙️ Motor & Drive System Repair
- 🔧 Wiring & Electrical Issues
- 💧 Water Damage Inspection
- 🔄 Software & Firmware Update
- 🛠 General EV Service
- 🚨 Emergency Breakdown Support

## Project Structure
- `index.html`: Main structure and SEO tags.
- `styles.css`: Styling, animations, and responsive design.
- `script.js`: Gallery logic, scroll reveal, and UI interactions.
- `public/gallery/`: Store your shop images here (e.g., `0.jpg`, `1.png`, `11.png`).
- `public/images/`: Brand assets (EV.ENGINEER - BIKE.png, EV.ENGINEER - CAR.png, etc.)

## How to Deploy to GitHub Pages
1. **Initialize Git**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   ```
2. **Create a GitHub Repository**:
   - Create a new repository named `REPAIR.EV.ENGINEER` on GitHub.
   - Follow the instructions to push your local code to GitHub.
3. **Configure Script.js**:
   - Open `script.js` and update `REPO_OWNER` and `REPO_NAME` with your actual GitHub username and repository name. This is required for the Dynamic Gallery to work.
4. **Enable GitHub Pages**:
   - Go to your repository settings on GitHub.
   - Click on **Pages** in the left sidebar.
   - Under **Build and deployment > Source**, select "Deploy from a branch".
   - Select the `main` branch and `/ (root)` folder.
   - Click **Save**.
5. **Add Gallery Images**:
   - Simply upload your images to the `public/gallery` folder in your GitHub repo.
   - The website will automatically detect and display them in the "Gallery" section.

## Domain & Branding
- **Website**: https://repair.ev.engineer
- **EV Battery Division**: https://battery.ev.engineer
- **Brand Color**: Lime Green (#00FF00) with gradient accents (white, yellow, orange, red)

## Contact Information
**Owner**: Sudarshana Karkala
**Location**: Opposite Classic Sapphire Apartment, Gopalakrishna Temple Road, Shakthinagar, Mangalore, KA 575016
**Phone**: +91 9108206147
**WhatsApp**: +91 9108206147
**Hours**: Mon - Sun: 10:00 AM - 10:00 PM
**Developer**: iTelematics Software Private Limited (https://itelematics.com)
