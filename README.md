# Student Career Discovery Platform — Project Dashboard

**Founder Deliverable | Executive Presentation Dashboard**  
*Prepared by:* **Nishtha Khanna** | October 2026  
*Status:* Draft for Founder Review (Presentation Ready)  
*Source Documents:*  
1. `RFP_Student_Career_Discovery.pdf` (Issued by Founder)  
2. `Career Guidance Platform Research Report and Product Roadmap (1).docx` (Survey Findings across 35 respondents)  
3. `PRD_Student_Career_Discovery_Platform.pdf` (PRD v1.0)

---

## 🎯 Executive Overview & Purpose

This single-page responsive web dashboard consolidates all phases of the **Student Career Discovery Platform** into an executive-ready, polished interface built for review with the founder (an educator and venture lead).

### Key Architectural Tenet:
> **“Build the mirror first, the map second, and earn trust at every step.”**

---

## 🚀 How to View the Dashboard

The dashboard is built as a self-contained, high-performance static web application that requires zero compilation or complex setup.

### Option 1: Direct File Open
Simply double-click `index.html` or drag it into any modern web browser (Google Chrome, Microsoft Edge, Safari, Firefox).

### Option 2: Local Web Server (Node.js)
```bash
npm start
# Or:
npx serve .
```
Then visit `http://localhost:3000` (or the port indicated in your terminal).

### Option 3: Python Built-in Server
```bash
python -m http.server 8080
```
Then open `http://localhost:8080` in your browser.

---

## 🧭 Dashboard Sections Breakdown

| # | Section | Key Highlights |
|---|---------|----------------|
| **1** | **PRD Summary (Hero)** | Product vision banner, Problem Statement, Target Stakeholders (Grades 9–11 primary; Teachers & Parents secondary), 7 Product Goals, and 6 Guiding Principles. |
| **2** | **Project Phases** | Horizontal Stepper with 5 phases: Problem Framing (Done), Research Design (Done), Data Collection (35 responses), Analysis (Thematic synthesis), and Product Definition (**Ready for Review**). |
| **3** | **Research Findings** | **KPI row** (35 total responses: 17 Students, 13 Teachers, 5 Parents).<br>• **3 Interactive Chart.js Horizontal Bar Charts** (Biggest Challenge, Value Ranking, Desired Features).<br>• **Direct Quotes & Inline Metrics** for Students, Teachers, and Parents.<br>• **4E Comparative Triangulation Matrix** (Blue, Teal, and Amber color coding). |
| **4** | **Key Strategic Insights** | 7 synthesis cards with bold takeaways and supporting stat badges (e.g., *0% tested*, *59% self-influenced*, *80% cite trust barrier*). |
| **5** | **Product Decisions** | Numbered decision table (**D1 to D8**) directly connecting empirical survey evidence to product capabilities. |
| **6** | **Feature Priority Matrix** | Filterable matrix (P0 Must Have, P1 Should Have, P2 Nice to Have) with real-time text search and release stage tags. |
| **7** | **Product Roadmap** | Visual horizontal **Gantt Cascade** across Q4 2026 to Q4 2027+ with 5 stage cards (Discover, Plan, Support, Involve Family, Scale). |
| **8** | **Success Metrics** | Accountability table mapping stages, KPI targets (e.g., 80% assessment completion, 70% usefulness, 4/5 parent trust), and research baselines. |
| **9** | **Core Experience Flow** | 6-step end-to-end journey from onboarding self-discovery to family involvement. |
| **10** | **Limitations & Risks** | Risk mitigation matrix addressing small parent sample size, lack of interview transcripts, and survey spread. |
| **11** | **Dependencies** | Enablers including counsellor networks, school pilot cohorts, and student consent mechanisms. |

---

## 🎨 Design & Technical Features

- **Color Palette:**
  - Deep Navy (`#1B3A5C`) — Primary brand tone
  - Warm Amber (`#F5A623`) — High-visibility accent
  - Light Grey (`#F4F6F8`) — Clean, airy light mode background
  - Deep Slate/Navy (`#0B1320` / `#152238`) — High-contrast dark mode
- **Interactive Dark Mode Toggle:** Seamless toggle between light and dark modes with state saved in `localStorage` and dynamic Chart.js canvas re-theming.
- **ScrollSpy Sticky Navbar:** Sticky header highlighting active sections as you scroll, with one-touch mobile drawer.
- **Reading Progress Bar:** Live scroll progress indicator along the top edge.
- **Print / PDF Presentation Mode:** Built-in `@media print` stylesheet that removes navbars, unwraps tables, formats canvas charts, and creates an executive PDF deliverable with a single click on **"Print / PDF"**.
- **Interactive Search & Filters:**
  - Real-time priority switcher and text search on the Feature Matrix.
  - Stakeholder tabs for granular data exploration or side-by-side view.

---

## 📄 File Manifest

- [`index.html`](file:///c:/Users/nishtha%20khanna/OneDrive/Desktop/Jira%20project/index.html) — Primary standalone dashboard application.
- [`package.json`](file:///c:/Users/nishtha%20khanna/OneDrive/Desktop/Jira%20project/package.json) — Node configuration and convenience serve script.
- [`README.md`](file:///c:/Users/nishtha%20khanna/OneDrive/Desktop/Jira%20project/README.md) — Documentation and founder presentation guide.
- `RFP_Student_Career_Discovery.pdf` — Original Founder RFP.
- `Career Guidance Platform Research Report and Product Roadmap (1).docx` — Source Research Report.
- `PRD_Student_Career_Discovery_Platform.pdf` — Source PRD v1.0.
