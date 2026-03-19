***REAL-TIME-EQUITY-SCREENER-AND-MARKET-DASHBOARD** 📈🤖

***BRIEF DESCRIPTION / PURPOSE**
This project was engineered to solve the "Noise-to-Signal" problem. In a market with 2000+ volatile scrips, a primary challenge for participants is identifying genuine institutional capital flow versus retail noise.

This project showcases an automated surveillance system that centralizes fragmented market data into a cohesive visual hierarchy. By quantifying market breadth and sector rotation in real-time, the project eliminates the need for manual screening, allowing for the immediate identification of extraordinary activity and structural moves across the NSE.

***TECH STACK**
Data Orchestration: Google Sheets (Engine) & Google Apps Script (Automation).

Database & Real-time Bridge: Firebase Realtime Database for low-latency data syncing between the spreadsheet and the web interface.

Frontend Framework: React.js / Next.js (Functional Components).

Data Visualization: D3.js (Orbital Sector Maps and Sentiment Gauges).

Styling: Tailwind CSS with a custom Cyber-Neon aesthetic.

Analysis Logic: Hybrid distribution between Google Sheet Formulas (backend processing) and Client-side JavaScript (frontend filtering).

***FEATURES / HIGHLIGHTS**
**📊 Market SentiMap (Index Breadth)**
Sentiment Gauge: A dynamic visualizer that translates complex index-wide breadth into a singular, actionable directional reading.

Interactive Treemaps: Provides a weight-adjusted view of the market, allowing users to see exactly which heavyweight stocks are driving index movement.

**🌐 Sector Scope (Orbital Rotation Analysis)**
Orbital UI: Solves the problem of identifying sector leadership through a unique visualization where sector "orbs" expand or contract based on capital flow, providing a 360-degree view of "smart money" movement.

Synchronized Data Grid: Deep-dives into stock-level performance metrics (Price, % Change) the moment a sector is selected via the orbital interface.

**⚡ AI Arena (Momentum Discovery)**
Mighty Move AI: A momentum-tracking module that surfaces stocks exhibiting abnormal activity and price action.

Launchpad: An early-alert system for stocks entering a bullish structural shift, based on predefined technical and financial parameters.

**🎨 Advanced UX Logic**
Implementation of "Shimmer" loading states and skeleton screens to manage data hydration from Firebase, ensuring a professional, high-end terminal feel during data fetches.
