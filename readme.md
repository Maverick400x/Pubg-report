# Match Performance Report - Power BI Dashboard

## Overview

This Power BI dashboard provides an interactive analysis of match performance using various metrics such as kills, win distribution, damage dealt, and distance covered. It enables users to filter data based on match mode and team ID for deeper insights.

## Features

* **Kill Performance Analysis** (Bar Chart)
  * X-axis:** **`<span>player_id</span>`
  * Y-axis:** **`<span>kills</span>`
  * Sorted in descending order
* **Win Place Distribution** (Pie Chart)
  * Displays percentage of wins in** **`<span>solo</span>`,** **`<span>duo</span>`, and** **`<span>squad</span>` modes
* **Weapons Acquired vs Match Mode** (Clustered Column Chart)
  * X-axis:** **`<span>match_mode</span>`
  * Y-axis: Sum of** **`<span>weapons_acquired</span>`
  * Categorized by** **`<span>player_id</span>`
* **Damage vs Distance Covered** (Scatter Plot)
  * X-axis:** **`<span>damage_dealt</span>`
  * Y-axis:** **`<span>walk_distance</span>`
  * Bubble Size:** **`<span>kills</span>`
* **Team ID & Match Mode Filters**
  * **Slicers** for filtering by** **`<span>match_mode</span>` and** **`<span>team_id</span>`
  * **Cross-filtering enabled** between visuals

## How to Use

1. **Select Filters**: Use the slicers on the left to filter by** **`<span>match_mode</span>` or** **`<span>team_id</span>`.
2. **View Performance Metrics**: Analyze player performance based on kills, weapons acquired, damage dealt, and win distribution.
3. **Interactivity**: Clicking on one visual updates other visuals dynamically.
4. **Switch to Mobile Layout**: Go to the** **`<span>View</span>` tab and select** **`<span>Mobile Layout</span>` to optimize the report for mobile devices.

## Customization

* Modify or add new visuals based on additional performance metrics.
* Adjust filters for more refined insights.
* Customize themes and formatting as needed.

## Author

Created by B.Srinivasa Ranganath using Power BI.

---

### Notes

* Ensure data is updated regularly for accurate analysis.
* Use Power BI Mobile for an optimized experience on mobile devices.
