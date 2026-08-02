# Upstream Production & Compliance Analytics Dashboard 🛢️

## Overview
This project is an automated Power BI analytical framework designed to tackle reporting latency in upstream operations. It transforms static operational data into dynamic tracking for Domestic Crude Oil Supply Obligations (DCOSO), Technical Allowable Rates (TAR), and regulatory gas flaring limits.

## The Operational Challenge
Tracking regulatory thresholds across multiple field assets is often manual, creating compliance risks and masking commercial opportunities. Operators need real-time visibility to optimize delivery logistics and prevent environmental penalties.

## The Solution
I engineered a Power BI star-schema data model incorporating 8 quarters of operational data to deliver:
* **TAR & Efficiency Tracking:** Automatically flags well strings constrained by high Sand Cut or BS&W for proactive workover interventions.
* **DCOSO Delivery Mapping:** Isolates quarters where regulatory crude allocation outpaces physical evacuation capacity.
* **Gas Commercialization Auditing:** Utilizes an automated 10% flaring watch-line to instantly flag spikes, transforming regulatory risks into midstream monetization opportunities (NGFCP).

## Technical Stack & Skills
* **Tool:** Power BI
* **Data Modeling:** Star Schema (Fact and Dimension tables)
* **Languages:** DAX (Custom measures for quarter-over-quarter trends and dynamic aggregations)
* **Domain Knowledge:** Upstream Regulatory Compliance, DCOSO, Reservoir MER, Gas Flaring

## Files in this Repository
* `Upstream_Dashboard.pbix`: The complete Power BI project file containing the data model and DAX measures.
* `Slide_Deck.pdf`: An executive presentation summarizing the core quantitative insights and recommendations.
* `Sample_Dataset.csv`: A sanitized, dummy dataset demonstrating the raw data structure.
