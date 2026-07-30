# EVSetu — EV Charging Station Business Dashboard

## Dashboard Preview/Screenshot
![Dashboard](https://github.com/TechGauri-09/EVSetu/blob/main/EV.pbix)

## Business Problem
India's EV market is growing rapidly, but many charging network operators struggle to identify which cities, vehicle segments, and payment channels drive the most revenue and profit. Without data-backed insights, business expansion decisions are often guesswork-driven. This project simulates **EVSetu**, a fictional EV charging station network, to solve this problem using data analytics.

## Goals
- Analyze total sales and profit performance across charging stations
- Identify the highest-performing states/cities for potential expansion
- Understand customer segments by vehicle type
- Track year-over-year growth to measure business momentum
- Present findings in a business-pitch format, similar to a Shark Tank investment case

## Features
- Interactive dashboard with real-time filtering via slicers (Year, Vehicle Category)
- State-wise geographic visualization using map bubbles
- Year-over-year growth tracking with DAX time-intelligence measures
- Category-wise breakdown of EV sales (2W/3W/4W/Bus)
- Top 10 state ranking for quick performance comparison
- Custom-branded UI with EVSetu theme and dark gradient background
- Multi-page report structure: Overview → Deep Dive → Insights

## What Each Visual Explains

**📊 KPI Cards (Top Row)**
- **Total EV Sales (4M):** Overall market size — total EV units sold across India
- **Count of State (34):** Geographic spread of the EV market across states/UTs
- **YoY Growth % (135.53%):** How fast the market is growing year-over-year, calculated using DAX time-intelligence functions

**🗺️ Map — EV Sales by State**
Visualizes where EV demand is concentrated across India. Bigger bubbles mean higher sales — makes it easy to spot regional hotspots at a glance.

**📈 Line Chart — EV Sales by Year (2014–2024)**
Tracks how EV adoption has grown over the past decade. Highlights a sharp acceleration after 2020, likely driven by government EV incentives and rising fuel costs.

**🏆 Bar Chart — Top 10 States by EV Sales**
Ranks the highest-performing states, with Uttar Pradesh leading. Useful for identifying where to prioritize charging infrastructure investment.

**🍩 Donut Chart — Sales by Vehicle Category**
Breaks down demand across 2-Wheelers, 3-Wheelers, 4-Wheelers, and Buses. Shows that 2-Wheelers dominate — reflecting India's affordability-driven approach to EV adoption.

**🎚️ Slicers — Year & Vehicle Category**
Interactive filters that let users drill down into a specific year or vehicle type, making the dashboard flexible for deeper exploration.

## Impact & Insights
- 2-Wheelers drive the majority of EV demand — any business strategy should prioritize this segment
- Uttar Pradesh is the strongest market, making it a natural candidate for expansion
- The post-2020 growth spike suggests policy incentives significantly boosted adoption
- Together, these insights support a focused go-to-market strategy: 2-wheeler-first charging infrastructure in high-growth states

## Tools Used
- **Power BI Desktop** — dashboard design and interactivity
- **DAX** — Total EV Sales, YoY Growth %, State Rank measures
- **Power Query** — data cleaning and transformation

## Author
**Gauri Thakare**
[LinkedIn](https://linkedin.com/in/gauri-thakare-aba165320) | [GitHub](https://github.com/TechGauri-09)
