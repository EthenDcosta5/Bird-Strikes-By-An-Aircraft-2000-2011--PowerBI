# Bird Strike Analysis (2000-2011)

## Problem Statement

Bird strikes are collisions between birds and aircraft during flight or on takeoff/landing. These incidents pose significant safety risks, especially during low-altitude phases like takeoff and landing, and can cause severe damage to aircraft, including engine failures. This repository analyzes data collected by the FAA from 2000 to 2011 to identify trends, risks, and recommendations for mitigating bird strikes.

---

## Key Questions

1. **General Overview**

   - How many bird strikes were recorded between 2000 and 2011?
   - What is the yearly trend in bird strike incidents?
   - What are the total costs incurred due to bird strikes?

2. **Pilot Awareness**

   - How effective are warnings in reducing bird strike impacts?
   - What percentage of incidents occurred without prior warnings?

3. **Altitudes and Locations**

   - What percentage of bird strikes occur below 1000 feet?
   - Which states and airports report the highest bird strike incidents?

4. **Airlines and Aircraft**

   - Which airlines are most affected by bird strikes?
   - During which phases of flight (e.g., takeoff, landing) do most bird strikes occur?

5. **Environmental Factors**

   - How do weather conditions (e.g., clear skies, overcast) affect bird strike frequency?
   - What are the most common sky conditions during bird strikes?

---
## Dashboard Overview
![Bird Strike Dashboard 1](https://github.com/EthenDcosta5/Bird-Strikes-By-An-Aircraft-2000-2011--PowerBI/blob/main/dashboard-images/D1.jpg)
![Bird Strike Dashboard 2](https://github.com/EthenDcosta5/Bird-Strikes-By-An-Aircraft-2000-2011--PowerBI/blob/main/dashboard-images/D2.jpg)

---

## Detailed Report

### Dashboard 1: Bird Strikes by an Aircraft (2000-2011)
Key Insights
Total Overview Metrics:

Total Bird Strikes Cases: 25.43K
Total Cost in Repairments: $142M
Total Birds Struck: 69K
Number of Birds Struck & Impact to Flight:

A majority of bird strikes caused no significant impact on flights (56K cases).
Minor impacts include:
Precautionary Landing: ~7K cases
Aborted Take-off, Engine Shut Down, and Other impacts were minimal.
Insight: Most bird strikes do not critically affect flight safety but contribute to repair costs.

Yearly Cost Incurred Due to Bird Strikes:

Yearly costs are variable but show a rising trend:
2002 and 2010 incurred the highest costs (~$6.2K and $7.7K respectively).
2004 had the lowest yearly cost ($4.3K).
Yearly Actual Bird Strikes:

Bird strikes generally increased over the years:
2000: 4.6K
2010: 7.1K
Peaks observed in 2008 (7.2K) and 2009 (7.7K).
Insight: Bird strike cases have been on a rising trend, possibly due to increased air traffic.

Cases Where Pilot Was Warned (Y/N):

Pilots Not Warned: 10.86K (42.7%)
Pilots Warned: 14.57K (57.3%)
Insight: Pilots were warned in more than half the cases, indicating room for improving warning systems.

Altitude of Bird Strike Cases:

Majority of strikes (87.11%) occurred below 1000 ft, while only 12.89% happened above 1000 ft.
Insight: Bird strikes primarily occur during take-off and landing phases when aircraft operate at lower altitudes.

### Dashboard 2: Bird Strikes by an Aircraft (2000-2011)
Key Insights
Average Altitude of Aircraft in Different Phases of Strikes:

798.90 ft is the average altitude for bird strikes, reinforcing the finding that strikes occur at low altitudes.
Number of Bird Strikes in Each State:

The heatmap shows bird strikes distribution across the United States. Specific states are not labeled but likely represent states with higher air traffic.
When Do Most Bird Strikes Occur (Sky Conditions)?

Strikes are most frequent under:
No Cloud conditions: 12.57K cases
Some Cloud: 8.66K cases
Overcast: 4.20K cases
Insight: Clear skies tend to have the highest frequency of bird strikes, possibly due to birds being more active.

Top 5 Airline Operators in Bird Strikes:

Southwest Airlines: 4.6K cases
Business Jets: 3.1K cases
American Airlines: 2.1K cases
Delta Air Lines: 1.3K cases
American Eagle Airlines: 0.9K cases
Insight: Larger airlines like Southwest Airlines and American Airlines experience the highest bird strikes, correlating with their extensive flight operations.

When Do Most Bird Strikes Occur (Phase of Light)?

Strikes predominantly occur during:
Approach Phase: ~10K cases
Landing Roll: ~5K cases
Take-off Run: ~4.7K cases
Climb: ~4.4K cases
Insight: Bird strikes are most common during approach and landing phases when aircraft descend to low altitudes.

---

## Insights and Recommendations

### Insights

- **Altitude and Flight Phases:** 87% of bird strikes occur below 1000 feet, primarily during takeoff and landing phases.
- **Cost Impact:** Bird strikes have incurred $142 million in repair costs between 2000 and 2011.
- **Airline Vulnerability:** Southwest Airlines, American Airlines, and Delta Air Lines are the most affected operators.
- **Environmental Conditions:** Clear skies account for the majority of bird strikes, followed by incidents during cloudy or overcast weather.

### Recommendations

1. **Improved Detection Systems:** Deploy advanced bird detection systems around airports to warn pilots.
2. **Wildlife Management:** Implement measures to reduce bird activity near runways and low-altitude flight paths.
3. **Phase-Specific Protocols:** Enhance safety protocols during critical flight phases like takeoff and landing.
4. **Collaboration with Airlines:** Partner with high-risk airlines to address operational vulnerabilities and refine bird strike response measures.

---

## Repository Contents

- **Full Analysis Report:** Detailed insights and trends extracted from the bird strike data.
- **Raw Data Files:** Original data from the FAA for the years 2000-2011.
- **Dashboard File:** Power BI (.pbix) file for interactive exploration of the dataset.
- **Dashboard PDF:** [Bird Strikes Dashboard](./Dashboard.pdf)

---

## How to Use This Repository

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/bird-strike-analysis.git
   ```
2. Explore the detailed report in `Full Analysis Report.pdf`.
3. Open `Dashboard.pdf` for a visual overview.
4. Use `Dashboard.pbix` to interact with the data using Power BI.

---

## Links and Socials

- **LinkedIn:** [Ethen D'Costa](https://www.linkedin.com/in/ethendcosta/)
- **Email:** [ethendcosta5@gmail.com](mailto:ethendcosta5@gmail.com)

