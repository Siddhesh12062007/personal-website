# Siddhesh Barabde | Personal Portfolio Website

A responsive, interactive portfolio that presents my projects, skills, achievements and contact details. Instead of only listing work, it lets visitors use it: a live Excel-style dashboard and two working demos run right in the browser.

**Live website:** https://siddhesh-portfolio-theta.vercel.app
**GitHub repository:** https://github.com/Siddhesh12062007/siddhesh-portfolio

## Features
- Sections: Home, About, Skills, Projects, Excel Dashboard, Live Demos, Education, Achievements, Experience and Contact
- **NASA Space Apps Challenge 2025 (Team Leader)** featured under Achievements
- **Live Movie & OTT dashboard:** 650 titles with Type, Platform and Language filters, KPI cards and charts, rebuilt from my Excel workbook
- **Smart Parking simulator:** click slots to see red/green LED status and the nearest vacant slot
- **Simulated Annealing scheduler:** watch the makespan fall as the optimiser cools
- Project filtering by category (AI, Data, Embedded & IoT, Web)
- Downloadable project reports and the Excel workbook
- Dark and light themes that remember your choice
- Animated skill bars, starfield hero and typing headline
- Responsive on mobile, tablet and desktop, with keyboard focus styles and reduced-motion support

## Projects showcased
| Project | Summary |
|---|---|
| Rule-Based Course Recommendation | Expert system with 15 IF–THEN rules, 25 courses and 10 career paths; 0 of 1,000 test profiles violated a rule |
| Movie & OTT Platform Analysis | Excel analysis of 650 titles with pivot tables, dashboard and 7 insights |
| Smart Parking Slot Indicator | IoT and embedded design using sensors, LEDs and a Wi-Fi dashboard |
| Simulated Annealing Job Scheduling | AI heuristic that minimises makespan across machines |

## Technologies used
- HTML5, CSS3 and vanilla JavaScript
- Google Fonts (Bricolage Grotesque, IBM Plex Sans)
- Git and GitHub for version control
- Vercel for deployment
- Microsoft Excel for the original data analysis

## Installation and running locally
1. Clone the repository:
   ```bash
   git clone https://github.com/Siddhesh12062007/siddhesh-portfolio.git
   cd siddhesh-portfolio
   ```
2. Open `index.html` in any browser, or run a local server:
   ```bash
   npx serve .
   ```
No build step or dependencies are required.

## Project structure
```
siddhesh-portfolio/
├── index.html      # complete site (HTML, CSS, JavaScript and OTT dataset in one file)
├── assets/
│   └── Movie_OTT_Analysis.xlsx
├── docs/
│   ├── Rule_Based_Course_Recommendation_Report.docx
│   ├── Smart_Parking_Slot_Indicator.docx
│   └── Simulated_Annealing_Job_Scheduling_System.docx
└── README.md
```

## Deployment
The site is deployed on Vercel and connected to this GitHub repository.
1. Push the code to GitHub.
2. In Vercel choose **Add New → Project** and import the repository.
3. Keep the defaults (Framework: Other, no build command) and click **Deploy**.
4. Every push to `main` redeploys the site automatically.

## Screenshots
Add screenshots to an `assets/screenshots/` folder and link them here:

| Home | Excel Dashboard |
|---|---|
| ![Home](assets/screenshots/home.png) | ![Dashboard](assets/screenshots/dashboard.png) |

## Author
**Siddhesh Barabde**
B.Tech Computer Science & Engineering (AI & ML), Sandip University, Nashik

- Email: siddheshbarabde2007@gmail.com
- LinkedIn: https://www.linkedin.com/in/siddhesh-barabde-6739ab430
- GitHub: https://github.com/Siddhesh12062007
- Portfolio: https://siddhesh-portfolio-theta.vercel.app
