F1 Suzuka Grand Prix 2023 — Race Data Analysis
Project Overview
A comprehensive race data analysis of the 2023 Japanese Grand Prix (Suzuka) using Microsoft Excel.
The analysis covers 5 drivers across 53 laps and replicates the kind of performance engineering analysis conducted by Formula 1 teams on race weekends. The race data captures dynamic track variables, including a Virtual Safety Car (VSC) period on Laps 8–9 and light rain reported on Lap 31.
Dataset
•	265 rows of verified race data
•	14 columns including driver codes, lap times, sector breakdowns (S1, S2, S3), tyre compounds, pit stop durations, and gaps to the leader
•	Drivers analysed: Verstappen (VER), Perez (PER), Alonso (ALO), Sainz (SAI), Norris (NOR)
Analysis Performed
1.	Data cleaning and verification: Verified dataset integrity (265 clean lap records) and separated out pit-stop outlier laps to secure clean baseline metrics.
2.	Lap time analysis: Evaluated average pace, absolute fastest laps, and driver consistency using standard deviation metrics to determine the final pace rankings.
3.	Tyre degradation analysis: Utilized Excel's SLOPE function to calculate compound degradation coefficients (s/lap) for both Medium and Hard compounds.
4.	Pit stop strategy analysis: Documented pit stop durations, mapped total pit time lost, and measured undercut effectiveness by analyzing 3 lap pace deltas before and after stops.
5.	Sector performance breakdown: Extracted the absolute minimum times for Sector 1, Sector 2, and Sector 3 to calculate each driver's theoretical best lap and gap to a perfect lap.
6.	PivotTable race summary: Generated dynamic summaries comparing compound averages, clean lap counts per driver, and race stint performance across three distinct race phases (Laps 1–18, 19–36, and 37–54).
7.	One-page race analysis dashboard: Created an executive summary dashboard consolidating driver statistics, tyre strategies, and sector performance.
Key Findings
•	Fastest Lap: Max Verstappen set the absolute fastest lap of the race with a time of 91.340s on Lap 41 on the Medium tyre compound.
•	Tyre Degradation: The Medium compound showed higher degradation across the field, degrading at 0.078613 s/lap for Alonso and 0.057727 s/lap for Norris. Verstappen displayed superior tyre management with a Medium degradation of only 0.032297 s/lap.
•	Undercut Effectiveness: 8 out of 10 analyzed pit stops showed a clear pace advantage from the undercut. The largest performance jump was observed with Sergio Perez, who achieved a delta of -1.996s following his second stop.
•	Theoretical Perfection: Verstappen was a mere 0.450s away from a theoretical perfect lap, with an ideal sector combination of 90.890s (Best Sectors: S1 = 30.801s, S2 = 38.283s, S3 = 21.806s) versus his actual fastest lap of 91.340s.
•	Strategy Impact: Lando Norris's alternative Hard-Medium strategy backfired in terms of peak performance, yielding the slowest individual fastest lap among the top group (93.136s) and the slowest overall driver average pace (94.424s), demonstrating that starting on the Hard compound compromised late-race pace compared to those on a Medium-first strategy.
Tools Used
•	Microsoft Excel 2021
•	PivotTables, AVERAGEIFS, MINIFS, SLOPE, XLOOKUP, and Conditional Formatting
Author
Muhammed Sufyan Haruna
Automotive Engineering Student — Air Force Institute of Technology, Nigeria
LinkedIn: https://www.linkedin.com/in/muhammed-sufyan-haruna-a190992aa 

