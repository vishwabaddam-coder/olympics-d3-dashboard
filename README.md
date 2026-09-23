# 🏅 TOKYO 2020 — AN INTERACTIVE OLYMPIC DATA STORY

> **A single-page, scroll-driven interactive data visualization project built with HTML, CSS, JavaScript and D3.js v7, transforming Tokyo 2020 Olympic data into an interactive visual story.**

[![D3.js](https://img.shields.io/badge/D3.js-v7-F9A03C?style=flat-square\&logo=d3.js\&logoColor=white)](https://d3js.org/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square\&logo=html5\&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square\&logo=css3\&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=flat-square\&logo=javascript\&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Status](https://img.shields.io/badge/Status-Complete-success?style=flat-square)](#)
[![Visualizations](https://img.shields.io/badge/Visualizations-8+-blue?style=flat-square)](#-visualizations)
[![Academic Project](https://img.shields.io/badge/Academic-Data%20Visualization-purple?style=flat-square)](#-academic-context)

---

## 📌 Project Title

**TOKYO 2020 — An Interactive Olympic Data Story**

### Short Description

A D3.js-powered interactive data visualization website that explores Tokyo 2020 Olympic medal and participation data through multiple coordinated visualizations, animations, filtering, sorting, comparison, zooming, tooltips and drill-down interactions.

---

# 📖 TABLE OF CONTENTS

1. [Project Overview](#-project-overview)
2. [Project Idea](#-project-idea)
3. [Problem Statement](#-problem-statement)
4. [Why This Project](#-why-this-project)
5. [Objectives](#-objectives)
6. [Proposed Solution](#-proposed-solution)
7. [Project Highlights](#-project-highlights)
8. [Interactive Visualizations](#-interactive-visualizations)
9. [How the Visualizations Work](#-how-the-visualizations-work)
10. [D3.js Concepts Demonstrated](#-d3js-concepts-demonstrated)
11. [System Architecture](#-system-architecture)
12. [System Workflow](#-system-workflow)
13. [Application Flow](#-application-flow)
14. [Shared State and Interaction](#-shared-state-and-interaction)
15. [Technology Stack](#-technology-stack)
16. [Project Structure](#-project-structure)
17. [Dataset Documentation](#-dataset-documentation)
18. [Data Limitations](#-data-limitations)
19. [Data Loading and Fallback System](#-data-loading-and-fallback-system)
20. [Design Philosophy](#-design-philosophy)
21. [Responsive Design](#-responsive-design)
22. [Accessibility](#-accessibility)
23. [Performance Optimization](#-performance-optimization)
24. [Original Work vs References](#-original-work-vs-references)
25. [Visualization Reference Links](#-visualization-reference-links)
26. [Official D3.js Documentation](#-official-d3js-documentation)
27. [Olympic Data Sources](#-olympic-data-sources)
28. [Code Architecture](#-code-architecture)
29. [Important Functions](#-important-functions)
30. [How to Run](#-how-to-run)
31. [Troubleshooting](#-troubleshooting)
32. [Academic Context](#-academic-context)
33. [Learning Outcomes](#-learning-outcomes)
34. [Viva / Presentation Explanation](#-viva--presentation-explanation)
35. [Future Enhancements](#-future-enhancements)
36. [Limitations](#-limitations)
37. [Acknowledgements](#-acknowledgements)
38. [License](#-license)
39. [Project Summary](#-project-summary)

---

# 🎯 PROJECT OVERVIEW

**TOKYO 2020 — An Interactive Olympic Data Story** is a front-end data visualization project designed to transform Olympic data from static numbers into an interactive visual narrative.

Instead of presenting medal counts and participation statistics only through tables, the project uses **D3.js** to convert structured CSV data into dynamic SVG-based visualizations.

Users can:

* Explore medal rankings
* Change medal metrics
* Sort countries
* Compare countries
* Inspect medal composition
* Explore athlete participation by sport
* Search sports
* Hover over data points
* Select countries
* Select sports
* Zoom and pan the scatter plot
* Explore a country-to-sport treemap
* Reset interactions
* Discover automatically generated insights

The project is intentionally designed as a **data story rather than a collection of disconnected charts**.

---

# 💡 PROJECT IDEA

The central idea is:

> **How can raw Olympic data be transformed into an interactive visual story that allows users to discover patterns instead of simply reading numbers?**

The project takes structured Tokyo 2020 data and processes it through D3.js.

### Basic concept

```text
Tokyo 2020 Data
       ↓
     CSV Files
       ↓
   JavaScript
       ↓
     D3.js
       ↓
Data Processing
       ↓
Scales / Axes / Layouts
       ↓
SVG Visualizations
       ↓
User Interaction
       ↓
Interactive Data Story
```

The result is a single-page visualization experience where the user moves through the Olympic story section by section.

---

# ❗ PROBLEM STATEMENT

Large sporting events generate enormous quantities of data.

Traditional presentation methods often rely on:

* Static tables
* Long textual explanations
* Separate charts
* Non-interactive reports
* Fixed rankings

These approaches make it difficult for users to:

* Compare multiple countries quickly
* Understand medal composition
* Discover relationships between participation and medals
* Explore country-specific sports
* Identify patterns visually
* Interact directly with the underlying data

The project addresses this problem by creating an **interactive visual exploration environment**.

---

# 🎯 WHY THIS PROJECT?

The project demonstrates that data visualization is not simply about drawing charts.

It demonstrates the complete process:

```text
Data
 ↓
Data Processing
 ↓
Visual Encoding
 ↓
SVG Generation
 ↓
Animation
 ↓
Interaction
 ↓
Exploration
 ↓
Insight
```

D3.js is particularly suitable because it provides direct control over:

* Data binding
* SVG
* Scales
* Axes
* Layouts
* Transitions
* Animation
* Interaction
* Hierarchical visualization

---

# 🎯 OBJECTIVES

## Primary Objective

To develop an interactive Tokyo 2020 Olympic data visualization application using **D3.js v7**.

## Secondary Objectives

1. Load structured Olympic data from CSV files.
2. Transform raw data into meaningful visual representations.
3. Demonstrate multiple D3.js visualization techniques.
4. Provide interactive filtering and sorting.
5. Allow users to compare countries.
6. Visualize participation across sports.
7. Demonstrate relationships between athletes and medals.
8. Provide country-medal intensity visualization.
9. Implement hierarchical country-to-sport exploration.
10. Demonstrate responsive SVG design.
11. Implement reusable interaction components.
12. Provide a transparent reference and attribution system.

---

# 🚀 PROPOSED SOLUTION

The proposed solution is a **single-page interactive Olympic data story**.

The application combines:

* HTML5
* CSS3
* JavaScript ES6
* D3.js v7
* Local CSV datasets
* SVG
* Browser APIs

No backend server or database is required.

---

# ✨ PROJECT HIGHLIGHTS

## 1. Interactive Data Story

The project is organized as a continuous narrative rather than unrelated charts.

## 2. Multiple Visualization Types

The application demonstrates several visualization techniques:

* Bar chart
* Stacked bar chart
* Donut chart
* Grouped bar chart
* Scatter plot
* Heatmap
* Treemap
* KPI visualization
* SVG animation

## 3. Shared Interaction

Selecting a country can affect multiple visualizations.

## 4. Dynamic Data

Charts are generated from CSV data rather than being manually drawn.

## 5. Responsive SVG

Charts adapt to different viewport sizes.

## 6. Lazy Rendering

Charts can be rendered as they enter the viewport.

## 7. Tooltips

Users can inspect detailed information through interactive tooltips.

## 8. Sorting and Filtering

Charts can dynamically change according to user selections.

## 9. Zooming

The scatter plot supports zoom and pan interaction.

## 10. Drill-Down

The treemap provides country-to-sport exploration.

---

# 📊 INTERACTIVE VISUALIZATIONS

The project contains the following major visualization components.

| #  | Visualization                        | Purpose                          |
| -- | ------------------------------------ | -------------------------------- |
| 1  | Olympic Ring Animation               | Interactive project introduction |
| 2  | Animated KPI Counters                | Tokyo 2020 overview              |
| 3  | Medal Ranking Bar Chart              | Country medal comparison         |
| 4  | Medal Donut Chart                    | Gold/Silver/Bronze composition   |
| 5  | Country Comparison Chart             | Compare selected countries       |
| 6  | Sports Participation Chart           | Athlete participation by sport   |
| 7  | Participation vs Medals Scatter Plot | Explore relationships            |
| 8  | Country × Medal Heatmap              | Medal intensity                  |
| 9  | Country → Sport Treemap              | Hierarchical exploration         |
| 10 | Dynamic Insights                     | Automatically generated findings |

> The project documentation describes eight primary interactive visualizations plus the introductory D3 ring animation.

---

# 🎬 1. OLYMPIC RING ANIMATION

The opening section uses SVG circles created through D3.js.

### Main concepts

* SVG `<circle>`
* D3 selection
* D3 transitions
* `attrTween()`
* Easing
* SVG filters
* Animation sequencing

### Custom implementation

The project uses a custom curved-entry animation rather than simply displaying static Olympic rings.

The animation includes:

* Ring positioning
* Sequential movement
* Curved motion
* Pulse effect
* Blur/glow treatment
* Title fade-in
* Subtitle fade-in
* Scroll hint

---

# 🔢 2. ANIMATED KPI COUNTERS

The snapshot section presents important summary metrics.

Example concepts:

```text
0
 ↓
Animation
 ↓
Final value
```

The counters use D3 interpolation and transition techniques.

### Purpose

Instead of immediately displaying numbers, the interface visually introduces them as part of the story.

---

# 📊 3. MEDAL RANKING BAR CHART

This visualization presents country-level medal information.

Users can interact with:

* Total medals
* Gold medals
* Silver medals
* Bronze medals
* Sorting
* Country selection

### D3 concepts

* `scaleBand()`
* `scaleLinear()`
* Axes
* Data joins
* Transitions
* Sorting
* Event handling

---

# 🍩 4. MEDAL DONUT CHART

The donut chart displays medal composition.

It represents:

```text
Gold
Silver
Bronze
```

### D3 concepts

* `d3.pie()`
* `d3.arc()`
* Arc transitions
* Hover interaction
* Percentage calculation
* Dynamic center text

---

# 📊 5. COUNTRY COMPARISON

The comparison section allows selected countries to be examined side by side.

The chart uses grouped bars.

### Example structure

```text
Country A ─ Gold / Silver / Bronze
Country B ─ Gold / Silver / Bronze
Country C ─ Gold / Silver / Bronze
```

The chart updates dynamically when selections change.

### D3 concepts

* Nested band scales
* Data joins
* Enter/update/exit behavior
* Transitions
* Dynamic labels
* Selection state

---

# 🏃 6. SPORTS PARTICIPATION

This visualization explores athlete participation across sports.

Features include:

* Search
* Sorting
* Athlete counts
* Sport selection
* Dynamic rendering

The visualization helps answer questions such as:

* Which sports have large participation?
* How does participation differ across sports?
* How does the selected sport compare with others?

---

# 🔵 7. PARTICIPATION × MEDALS SCATTER PLOT

The scatter plot explores the relationship between:

```text
Athlete Participation
        ×
Medal Count
```

The visualization uses:

* X-axis
* Y-axis
* Circle size
* Continent-based grouping
* Labels
* Zoom
* Pan
* Tooltip interaction

### Important implementation detail

A square-root scale is used for circle radius so that circle **area** represents the underlying value more appropriately.

---

# 🔥 8. COUNTRY × MEDAL HEATMAP

The heatmap represents medal intensity.

Each cell corresponds to a country and medal category.

Example:

```text
             Gold   Silver   Bronze
USA
China
Japan
GBR
...
```

The intensity of the cell represents the corresponding value.

### Interaction

Hovering can highlight:

* Current row
* Current column
* Selected cell

A tooltip provides additional information.

---

# 🧩 9. COUNTRY → SPORT TREEMAP

The treemap provides hierarchical exploration.

Hierarchy:

```text
Tokyo 2020
   │
   ├── Country
   │      ├── Sport
   │      ├── Sport
   │      └── Sport
   │
   ├── Country
   │      ├── Sport
   │      └── Sport
   │
   └── Country
```

Users can drill into a country and examine its sport-level medal distribution.

### D3 concepts

* `d3.hierarchy()`
* `.sum()`
* `.sort()`
* `d3.treemap()`
* Hierarchical positioning
* Zoom/drill-down
* Breadcrumb navigation

---

# 🧠 10. AUTOMATIC INSIGHTS

The project contains an insight-generation layer.

Instead of manually writing every conclusion, the application calculates findings from the loaded data.

This makes the displayed observations dependent on the actual dataset.

---

# 🧠 D3.JS CONCEPTS DEMONSTRATED

## Selection

* `d3.select()`
* `d3.selectAll()`

## Data

* `d3.csv()`
* `.data()`
* `.join()`

## Scales

* `d3.scaleLinear()`
* `d3.scaleBand()`
* `d3.scaleSqrt()`
* `d3.scaleSequential()`
* `d3.scaleOrdinal()`

## Axes

* `d3.axisBottom()`
* `d3.axisLeft()`

## Animation

* `.transition()`
* `.delay()`
* `.duration()`
* `.ease()`
* `.attrTween()`

## Interpolation

* `d3.interpolateNumber()`

## Shapes

* `d3.pie()`
* `d3.arc()`

## Hierarchy

* `d3.hierarchy()`
* `d3.treemap()`

## Interaction

* `.on()`
* Mouse events
* Keyboard events
* `d3.zoom()`

## Data Utilities

* `d3.sum()`
* `d3.max()`
* `d3.mean()`
* `d3.group()`
* `d3.rollup()`
* `d3.format()`

---

# 🏗️ SYSTEM ARCHITECTURE

```text
┌──────────────────────────────────────┐
│             USER / BROWSER           │
└───────────────────┬──────────────────┘
                    │
                    ▼
┌──────────────────────────────────────┐
│              index.html              │
│                                      │
│   HTML + CSS + JavaScript + D3.js    │
└───────────────────┬──────────────────┘
                    │
                    ▼
┌──────────────────────────────────────┐
│           DATA LOADING LAYER         │
│                                      │
│       d3.csv() + fallback data       │
└───────────────────┬──────────────────┘
                    │
                    ▼
┌──────────────────────────────────────┐
│           DATA PROCESSING            │
│                                      │
│   Parsing → Conversion → Grouping    │
│   Sorting → Aggregation → Filtering  │
└───────────────────┬──────────────────┘
                    │
                    ▼
┌──────────────────────────────────────┐
│              D3.JS LAYER             │
│                                      │
│ Scales | Axes | Layouts | SVG        │
│ Transitions | Interaction | Zoom     │
└───────────────────┬──────────────────┘
                    │
                    ▼
┌──────────────────────────────────────┐
│       INTERACTIVE VISUAL STORY       │
│                                      │
│ Charts + Tooltips + Controls         │
│ Animation + Comparison + Drilldown   │
└──────────────────────────────────────┘
```

---

# 🔄 SYSTEM WORKFLOW

```text
USER OPENS APPLICATION
        ↓
index.html loads
        ↓
D3.js library loads
        ↓
CSV datasets requested
        ↓
Data parsed and normalized
        ↓
Application state initialized
        ↓
KPI values prepared
        ↓
Controls initialized
        ↓
Insights generated
        ↓
Charts rendered
        ↓
User interacts
        ↓
Shared state updated
        ↓
Relevant charts re-render
        ↓
User discovers patterns
```

---

# 🔗 SHARED STATE AND INTERACTION

One of the important architectural ideas is a shared application state.

Conceptually:

```javascript
state = {
    selectedCountry,
    selectedSport,
    selectedMetric,
    selectedCountries,
    sortDirection,
    treemapLevel
}
```

The state allows different visualizations to communicate.

For example:

```text
User selects USA
       ↓
state.selectedCountry = "United States"
       ↓
Bar Chart updates
       ↓
Scatter Plot updates
       ↓
Heatmap updates
       ↓
Treemap reflects selection
```

This prevents each chart from behaving like an isolated component.

---

# 🛠️ TECHNOLOGY STACK

| Technology           | Purpose                               |
| -------------------- | ------------------------------------- |
| HTML5                | Page structure                        |
| CSS3                 | Styling and responsive layout         |
| JavaScript ES6       | Application logic                     |
| D3.js v7             | Data visualization                    |
| SVG                  | Chart rendering                       |
| CSV                  | Dataset storage                       |
| Google Fonts / Inter | Typography                            |
| Browser APIs         | IntersectionObserver, Resize handling |

---

# 🚫 TECHNOLOGIES NOT USED

The project intentionally does not depend on:

* React
* Vue
* Angular
* Chart.js
* Plotly
* Highcharts
* Node.js backend
* Flask
* Django
* SQL database
* Authentication
* External application backend

The core visualization is implemented directly using D3.js.

---

# 📁 PROJECT STRUCTURE

```text
tokyo-2020-d3/
│
├── index.html
│
├── README.md
│
└── data/
    ├── medals_total.csv
    ├── medals.csv
    └── athletes.csv
```

### `index.html`

Contains:

* HTML structure
* CSS
* JavaScript
* D3 visualization logic
* Controls
* Animations
* Tooltips
* State management

### `medals_total.csv`

Country-level medal dataset.

### `medals.csv`

Country × sport medal dataset.

### `athletes.csv`

Sport-level athlete participation dataset.

---

# 📚 DATASET DOCUMENTATION

## `medals_total.csv`

### Columns

| Column      | Type    | Description                                   |
| ----------- | ------- | --------------------------------------------- |
| `country`   | String  | Country/NOC name                              |
| `continent` | String  | Continent grouping                            |
| `gold`      | Integer | Gold medal count                              |
| `silver`    | Integer | Silver medal count                            |
| `bronze`    | Integer | Bronze medal count                            |
| `athletes`  | Integer | Athlete/delegation figure used by the project |

### Used by

* KPI section
* Medal ranking
* Donut chart
* Country comparison
* Scatter plot
* Heatmap
* Treemap
* Insights

---

# `athletes.csv`

### Columns

| Column     | Type    | Description                  |
| ---------- | ------- | ---------------------------- |
| `sport`    | String  | Sport                        |
| `athletes` | Integer | Athlete participation figure |
| `events`   | Integer | Events represented           |

### Used by

* Sports participation chart
* Sport filtering
* Insight generation

The project source notes that `Aquatics` is grouped for conciseness.

---

# `medals.csv`

### Columns

| Column    | Type    | Description   |
| --------- | ------- | ------------- |
| `country` | String  | Country       |
| `sport`   | String  | Sport         |
| `gold`    | Integer | Gold medals   |
| `silver`  | Integer | Silver medals |
| `bronze`  | Integer | Bronze medals |

### Used by

* Treemap
* Country → Sport exploration

### Important

This dataset is documented as a **curated subset of country × sport medal relationships**, not a complete replacement for the official full medal-event dataset.

---

# ⚠️ DATA LIMITATIONS

Academic honesty is important for this project.

The current project documentation identifies the following limitations:

1. The country medal table contains the **top 25 NOCs represented in the project**, rather than all participating NOCs.
2. `medals.csv` is a **curated country × sport subset**.
3. Athlete counts are project dataset figures and may differ from other official counting methodologies.
4. The project should therefore be understood as an **interactive visualization demonstration**, not as an official IOC statistical database.

These limitations should not be hidden from evaluators.

---

# 🔄 DATA LOADING AND FALLBACK SYSTEM

The normal workflow is:

```text
d3.csv()
   ↓
CSV file
   ↓
Parse data
   ↓
Application
```

The project also includes embedded fallback data.

Therefore:

```text
CSV available?
     │
   YES ─────→ Load CSV
     │
    NO
     ↓
Use embedded fallback
```

This makes the application more robust during local demonstrations.

---

# 💻 WHY A SINGLE HTML FILE?

The project intentionally uses a compact architecture.

Advantages:

* No build process
* No package installation
* Easy to submit
* Easy to demonstrate
* Easy to move between computers
* Easy for faculty evaluation
* Easy to understand during viva

The external CSV files are still maintained separately to demonstrate actual data loading with `d3.csv()`.

---

# 🎨 DESIGN PHILOSOPHY

The design follows four major principles.

## 1. Visualization First

Charts are the main communication mechanism.

## 2. Interaction Has Meaning

Animations and transitions are used to communicate changes rather than simply decorate the interface.

## 3. Consistent Visual Language

The project uses a controlled Olympic-inspired palette and consistent spacing.

## 4. Academic Presentation

The interface prioritizes:

* readability
* clarity
* interaction
* data interpretation
* technical demonstration

rather than excessive visual effects.

---

# 📱 RESPONSIVE DESIGN

The project is designed to adapt to different screen sizes.

Techniques include:

* SVG `viewBox`
* `preserveAspectRatio`
* CSS Grid
* Responsive containers
* Debounced resize handling
* Flexible typography
* Mobile navigation behavior

The same visualization logic can therefore adapt to desktop and smaller screens.

---

# ♿ ACCESSIBILITY

The project incorporates accessibility-oriented techniques including:

* Semantic headings
* Semantic sections
* Accessible SVG descriptions
* Keyboard-focusable controls
* Tooltip accessibility attributes
* Reduced-motion support
* Text labels alongside color
* Contrast-conscious design

The goal is to avoid making color the only method of communicating information.

---

# ⚡ PERFORMANCE OPTIMIZATION

## Lazy Rendering

`IntersectionObserver` can delay chart creation until the visualization becomes relevant to the viewport.

## Debounced Resize

Resize events are controlled to prevent excessive re-rendering.

## Shared Tooltip

A reusable tooltip avoids creating unnecessary DOM elements.

## SVG ViewBox

Responsive SVG avoids manually calculating every pixel size.

## Embedded Fallback

Fallback data reduces dependency on a successful local CSV request.

---

# 🧬 ORIGINAL WORK VS REFERENCES

This section is intentionally included to maintain academic transparency.

The project uses official documentation and publicly available examples to understand visualization patterns.

That does **not** mean the complete application is copied from those examples.

The distinction is:

```text
Reference / Learning Pattern
          +
Tokyo 2020 Data
          +
Custom Design
          +
Custom Interaction
          +
Custom Architecture
          =
This Project
```

---

# 📌 WHAT WAS REFERENCED?

Examples and documentation were used as references for concepts such as:

* Bar chart construction
* Grouped bar charts
* Stacked bars
* Pie/donut layouts
* Scatter plots
* Heatmaps
* Treemaps
* Zoom behavior
* D3 transitions
* D3 scales
* D3 hierarchy

The project documentation identifies official D3/Observable examples as reference patterns.

---

# ✍️ WHAT WAS CREATED / CUSTOMIZED FOR THIS PROJECT?

The following project-specific elements are documented as custom work:

### Visualization and Interaction

* Tokyo 2020 data integration
* Shared application state
* Country selection system
* Sport selection system
* Cross-chart highlighting
* Custom tooltip implementation
* Dynamic comparison controls
* Search/filter interaction
* Sort controls
* Scatter plot configuration
* Treemap country → sport hierarchy
* Treemap breadcrumb behavior
* Reset behavior

### Animation

* Olympic ring entrance animation
* Curved ring motion
* Ring pulse
* Title/subtitle reveal
* KPI counting animation
* Donut arc animation
* Chart entrance transitions

### Application Architecture

* Single-file application structure
* CSV loading and fallback system
* Lazy visualization rendering
* Responsive redraw mechanism
* Scroll-based navigation
* Section reveal behavior
* Automatic insight generation

### Visual Design

* Overall page composition
* Typography hierarchy
* Card design
* Spacing system
* Navigation
* Section organization
* Color system
* Responsive presentation

---

# 🔗 VISUALIZATION REFERENCE LINKS

The following resources are the documented reference patterns used to understand the respective visualization techniques.

| Visualization              | Reference                                          |
| -------------------------- | -------------------------------------------------- |
| Bar Chart                  | https://observablehq.com/@d3/bar-chart             |
| Horizontal Bar Chart       | https://observablehq.com/@d3/horizontal-bar-chart  |
| Stacked Bar Chart          | https://observablehq.com/@d3/stacked-bar-chart     |
| Grouped Bar Chart          | https://observablehq.com/@d3/grouped-bar-chart     |
| Bar Chart with Transitions | https://observablehq.com/@d3/bar-chart-transitions |
| Pie Chart                  | https://observablehq.com/@d3/pie-chart             |
| Donut Chart                | https://observablehq.com/@d3/donut-chart           |
| Scatterplot                | https://observablehq.com/@d3/scatterplot           |
| Heatmap                    | https://observablehq.com/@d3/heatmap               |
| Treemap                    | https://observablehq.com/@d3/treemap               |
| Zoomable Treemap           | https://observablehq.com/@d3/zoomable-treemap      |
| D3 Zoom                    | https://observablehq.com/@d3/zoom                  |

These links are **learning/reference resources**, not claims that the final implementation was copied from those examples.

---

# 📘 OFFICIAL D3.JS DOCUMENTATION

## Main D3 Website

https://d3js.org/

## D3 API Reference

https://github.com/d3/d3/blob/main/API.md

## Selection

https://github.com/d3/d3-selection

## Scales

https://github.com/d3/d3-scale

## Axes

https://github.com/d3/d3-axis

## Transitions

https://github.com/d3/d3-transition

## Easing

https://github.com/d3/d3-ease

## Shapes

https://github.com/d3/d3-shape

## Hierarchy

https://github.com/d3/d3-hierarchy

## Zoom

https://github.com/d3/d3-zoom

## Arrays

https://github.com/d3/d3-array

## Interpolation

https://github.com/d3/d3-interpolate

## Fetch / CSV

https://github.com/d3/d3-fetch

## Formatting

https://github.com/d3/d3-format

---

# 🏅 OLYMPIC DATA SOURCES

The project documentation identifies the following sources for Olympic-related information and dataset reference.

## International Olympic Committee

https://olympics.com/en/tokyo-2020/

Used as an official reference for Tokyo 2020 information.

## Olympic World Library

https://library.olympics.com/

Used for Olympic documentation and verification/reference material.

## Tokyo 2020 Official Website / Archive

https://tokyo2020.org/

Used as a reference for Tokyo 2020 sports and event information.

## Kaggle — Tokyo 2020 Olympic Summer Games

https://www.kaggle.com/datasets/piterfm/tokyo-2020-olympics

Used as a structured data reference in the project's documented dataset workflow.

> **Important:** Dataset provenance should be described accurately. A dataset being available through Kaggle does not automatically make every row an IOC-published dataset. The project therefore distinguishes official Olympic sources from structured third-party dataset references.

---

# 🌐 GENERAL WEB TECHNOLOGY REFERENCES

## MDN — SVG

https://developer.mozilla.org/en-US/docs/Web/SVG

## MDN — IntersectionObserver

https://developer.mozilla.org/en-US/docs/Web/API/IntersectionObserver

## MDN — CSS Grid

https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout

## MDN — prefers-reduced-motion

https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-reduced-motion

## Can I Use

https://caniuse.com/

---

# 🏗️ CODE ARCHITECTURE

The application can conceptually be divided into the following layers:

```text
┌─────────────────────────────┐
│       PRESENTATION          │
│ HTML + CSS + SVG            │
└──────────────┬──────────────┘
               ↓
┌─────────────────────────────┐
│        INTERACTION          │
│ Click / Hover / Search      │
│ Sort / Select / Zoom        │
└──────────────┬──────────────┘
               ↓
┌─────────────────────────────┐
│       STATE MANAGEMENT      │
│ Selected country / sport    │
│ Metric / sorting / filters  │
└──────────────┬──────────────┘
               ↓
┌─────────────────────────────┐
│       DATA PROCESSING       │
│ Parse / Group / Aggregate   │
│ Filter / Sort / Calculate   │
└──────────────┬──────────────┘
               ↓
┌─────────────────────────────┐
│          D3.JS              │
│ Scales / Axes / Layouts     │
│ Transitions / SVG           │
└─────────────────────────────┘
```

---

# 🔧 IMPORTANT FUNCTIONS

The exact function names can vary with implementation, but the project's documented architecture includes responsibilities such as:

### `loadData()`

Loads and prepares the CSV datasets.

### `buildKPIs()`

Creates the snapshot metrics.

### `buildInsights()`

Calculates project-specific findings from the loaded data.

### `setupNav()`

Configures navigation and scroll behavior.

### `setupControls()`

Initializes interactive controls.

### `setupLazyRendering()`

Controls visualization rendering using viewport visibility.

### `selectCountry()`

Updates country selection and connected visualizations.

### `selectSport()`

Updates sport selection.

### `medalTooltip()`

Generates reusable medal-related tooltip content.

### Chart creation functions

Each major visualization has its own rendering logic.

---

# ▶️ HOW TO RUN

## Method 1 — VS Code Live Server

### Step 1

Open the project folder in VS Code.

### Step 2

Install the **Live Server** extension.

### Step 3

Open:

```text
index.html
```

### Step 4

Right-click:

```text
Open with Live Server
```

### Step 5

The browser will open a local URL similar to:

```text
http://127.0.0.1:5500/
```

---

# 🐍 METHOD 2 — PYTHON HTTP SERVER

Open Command Prompt / PowerShell in the project folder.

```bash
cd tokyo-2020-d3
python -m http.server 5500
```

Then open:

```text
http://localhost:5500
```

---

# 📂 REQUIRED FOLDER STRUCTURE

Before running, verify:

```text
tokyo-2020-d3/
│
├── index.html
├── README.md
│
└── data/
    ├── medals_total.csv
    ├── medals.csv
    └── athletes.csv
```

---

# 🧪 DATA LOADING VERIFICATION

Open browser Developer Tools.

Use:

```text
F12
```

Then:

```text
Network
```

Reload the page.

You should see successful requests for:

```text
data/medals_total.csv
data/medals.csv
data/athletes.csv
```

---

# ⚠️ TROUBLESHOOTING

## Problem: CSV returns 404

Check:

```text
data/medals_total.csv
data/medals.csv
data/athletes.csv
```

Make sure spelling and capitalization match.

---

## Problem: CSV does not load

Do not simply double-click `index.html`.

Use:

```text
Live Server
```

or:

```bash
python -m http.server 5500
```

---

## Problem: Charts are empty

Check:

1. Browser console
2. CSV file names
3. CSV headers
4. Folder structure
5. Network requests

---

## Problem: Application works without CSV

This can happen because the project contains embedded fallback data.

That is expected behavior.

---

# 🎓 ACADEMIC CONTEXT

## Problem Statement

Traditional Olympic information systems often present data through static tables, reports and articles.

The project proposes an interactive approach where users can explore Olympic data visually.

---

# 🎯 ACADEMIC OBJECTIVE

The core academic objective is:

> **To demonstrate how D3.js can transform structured Tokyo 2020 Olympic data into an interactive, responsive and visually connected data story.**

---

# 🧪 TECHNICAL OBJECTIVE

The project demonstrates practical understanding of:

* Data loading
* Data parsing
* Data transformation
* SVG
* D3 selections
* Scales
* Axes
* Layouts
* Animation
* Interaction
* State management
* Responsive design
* Accessibility
* Browser APIs

---

# 📚 LEARNING OUTCOMES

After completing the project, the developer demonstrates understanding of:

### Data Visualization

How raw data can be transformed into visual representations.

### D3.js

How D3 connects data with DOM/SVG elements.

### SVG

How vector graphics can be generated dynamically.

### Interaction

How users can manipulate visualized data.

### Animation

How transitions can communicate state changes.

### Responsive Visualization

How visualizations can adapt to changing screen sizes.

### Data Storytelling

How multiple charts can be organized into a coherent narrative.

---

# 🎤 VIVA / PRESENTATION EXPLANATION

## What is this project?

> This is an interactive Tokyo 2020 Olympic data visualization project developed using HTML, CSS, JavaScript and D3.js v7. It converts structured Olympic data into multiple interactive visualizations such as bar charts, donut charts, scatter plots, heatmaps and treemaps.

---

## Why D3.js?

> D3.js provides direct control over data binding, SVG elements, scales, axes, layouts, transitions and interaction. This makes it suitable for demonstrating how visualizations are constructed rather than simply using a pre-built chart component.

---

## Is this a static website?

> No. The page is dynamically generated from structured CSV data, and users can interact with charts through selection, filtering, sorting, hovering, comparison, zooming and drill-down.

---

## Is there a backend?

> No. The current implementation is a front-end-only visualization application. Data is stored locally in CSV files and processed in the browser.

---

## Why CSV?

> CSV provides a simple structured format for tabular data and allows the project to demonstrate D3's data-loading capabilities.

---

## Why SVG?

> SVG provides scalable vector graphics and allows individual graphical elements such as rectangles, circles, paths and text to be controlled through D3.

---

## What is the most important technical idea?

> The project does not treat each chart as an isolated visualization. A shared state and common interaction logic connect the visualizations into a single exploration experience.

---

# 🔮 FUTURE ENHANCEMENTS

Possible future improvements include:

1. Historical Olympic data from multiple Games.
2. Athlete-level information.
3. Additional geographic visualizations.
4. Sankey diagrams.
5. Brushing and linked filtering.
6. Stronger keyboard navigation.
7. Theme switching.
8. URL-based state persistence.
9. Modular JavaScript architecture.
10. PDF/report export.
11. Additional official datasets.
12. More advanced cross-filtering.
13. Server-side data management for larger datasets.
14. More comprehensive NOC coverage.
15. Full event-level Olympic analysis.

---

# ⚠️ CURRENT LIMITATIONS

The current project intentionally remains lightweight.

### No backend

All processing occurs in the browser.

### Limited dataset scope

The current medal table is not intended to represent every Olympic NOC.

### Curated country-sport dataset

The country × sport dataset is a subset.

### No live Olympic API

The application does not retrieve live Olympic data.

### Static historical event

Tokyo 2020 is the focus.

### Browser dependency

The project requires a modern browser with JavaScript enabled.

---

# 🔐 PRIVACY

The current project:

* Does not require login.
* Does not collect user accounts.
* Does not require a database.
* Does not require personal information.
* Does not require a backend.
* Uses local project datasets.

---

# 🌍 OFFLINE / LOCAL OPERATION

The application is designed to work as a local demonstration project.

With the project files available locally:

```text
index.html
+
data/*.csv
```

the core application does not require a custom backend.

However, using a local HTTP server is recommended when demonstrating CSV loading.

---

# 🧾 DATA AND ATTRIBUTION POLICY

This project follows a transparent attribution approach.

### Official sources

Used for authoritative Olympic context and reference information.

### D3 documentation

Used to understand APIs and visualization techniques.

### Public D3 examples

Used as learning/reference patterns.

### Project implementation

The final composition, integration, interactions, architecture, styling and project-specific behavior are implemented for this project.

### Important distinction

A reference implementation and the final application are not automatically the same thing.

This README intentionally documents the difference.

---

# 🙏 ACKNOWLEDGEMENTS

Special acknowledgement to:

* International Olympic Committee
* Tokyo 2020 Olympic resources
* D3.js contributors
* Mike Bostock
* Observable D3 examples
* MDN Web Docs
* Kaggle data community
* Rasmus Andersson / Inter typeface

These resources provided documentation, data references, technical learning material and visualization patterns used during development.

---

# 📜 LICENSE

This project may be released under the MIT License if a `LICENSE` file containing the MIT License is included in the repository.

If no license file has been added, do **not** claim that the repository is MIT licensed yet.

D3.js itself is distributed under its own open-source license.

This project is an academic/educational visualization project and is **not affiliated with or endorsed by the International Olympic Committee**.

---

# 🏅 PROJECT SUMMARY

## In One Sentence

> **TOKYO 2020 — An Interactive Olympic Data Story is a D3.js-based visual analytics application that transforms structured Olympic data into an interactive, connected and responsive storytelling experience.**

## In One Paragraph

This project transforms Tokyo 2020 Olympic medal and participation data into an interactive visual story using HTML5, CSS3, JavaScript ES6 and D3.js v7. Instead of presenting Olympic statistics through static tables, the application combines animated KPI counters, medal rankings, donut charts, country comparisons, sports participation charts, scatter plots, heatmaps and hierarchical treemaps. Users can hover, click, search, sort, compare, zoom and drill down into the data. The application uses local CSV datasets, a shared state model, reusable interaction components, responsive SVG rendering, lazy visualization loading and fallback data handling. Official Olympic resources and D3 documentation are documented separately from public visualization examples used as technical references. Project-specific architecture, data integration, interaction design, animation, styling and cross-chart behavior are developed as part of this implementation.

---

# ⭐ PROJECT PHILOSOPHY

```text
RAW DATA
   ↓
UNDERSTAND THE DATA
   ↓
CHOOSE THE RIGHT VISUAL FORM
   ↓
BUILD WITH D3.JS
   ↓
ADD INTERACTION
   ↓
CONNECT THE VISUALIZATIONS
   ↓
TELL A DATA STORY
   ↓
HELP THE USER DISCOVER INSIGHTS
```

---

# 🏁 FINAL STATEMENT

**This project is not simply a collection of charts.**

It demonstrates a complete data visualization workflow:

```text
DATA
  ↓
PROCESSING
  ↓
VISUALIZATION
  ↓
INTERACTION
  ↓
ANIMATION
  ↓
EXPLORATION
  ↓
INSIGHT
```

The main technical goal is to demonstrate the capabilities of **D3.js as a data-driven document and visualization framework**, while the main design goal is to make Tokyo 2020 Olympic data easier to explore, compare and understand.

---

<div align="center">

# 🏅 TOKYO 2020

### An Interactive Olympic Data Story

**Explore • Interact • Compare • Discover**

Built with

**HTML • CSS • JavaScript • D3.js**

</div>
