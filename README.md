# Agric_Investment_Data_Analysis
## Yield Gap and Climate Stress Analysis for Strategic Agricultural Investment in Nigeria (2000 -2010)
### Client: Farmex Investment Limited
1. **Project Description**  
This project analyze maize yield data across 12 rain-fed climate zones in Nigeria between 2000 and 2010. The objective is to evaluate production performance, identify key constraints to productivity, and provide data-driven recommendations for targeted investment and intervention.
The analysis focuses on understanding whether low agricultural productivity is driven by climatic factors, management inefficiencies, or a combination of both. By integrating yield gap and stress index metrics, the study provides a structured approach to identifying high-potential regions and prioritizing interventions.

2. **Objectives**  
Specifically, the project addresses the following questions:
- To what extent are farmers achieving the potential yield across climate zones?
- Is low productivity driven by climate stress or management inefficiencies?
- What regions represent the highest need for investment?
- What type of intervention is required for each climate zones
  
3. **Data Description**
The dataset contains:
- Actual Yield (YA)
- Potential Yield (YP)
- Stress Index (SI)
- Climate Zone Classification
- Data Spans from 2000 to 2010 across 12 regions

4. **Data Metrics Used**
The following core indicators were used in this analysis
4.1 **Yield Trend** 
Yield trend from Actual Yield shows whether yield is increasing, decreasing or stagnant over time across climate zones, and identify top high and low performing regions.

4.2 **Yield Gap** 
Yield Gap measures the difference between achievable and actual production, indicating inefficiencies in farm management. Categorized into High, Medium and Low.  
          *Yield Gap = Potential Yield (YP) - Actual Yield (YA)*

4.3 **Stress Index**  
Stress Index evaluates the effect of climate on yield  
  SI > 1 → Favourable conditions or good management  
SI = 1 → Yield aligns with expected condition  
SI < 1 → Climate stress limits production  

4.4 **Combined insights between Yield Gap and Stress Index**  
By integrating Yield Gap and Stress Index, each climate zone is classified into production constraint categories:  
Condition	Interpretation
High YG + SI >1	Strong  Mangement Constrant
High YG + SI <1	Climate + Mangement Constrant
Medium YG + SI >1	Management Improvement Needed
Medium YG + SI < 1	Moderate Climate Constraint
Low YG + SI >1	Mainly Climate Constraints
Low YG + SI < 1	Minor Management Issue

5. **Results**  
5.1 Top 2 Highest and Lower Actual Yield Across Year   
*Image should be here*

5.2 **Stress Index: Stress Pattern Across Climate Zones**  
   *Graph*  
**Note:** The heatmap shows that most regions maintain stress index values close to 1, indicating stable production conditions. A smaller number of regions exhibit higher values, suggesting favorable climate conditions during those periods. Region 9301 lacks data for 2010, preventing conclusive interpretation for that year.

5.3 **Yield Gap Comparison Across Climate Zones**
*Graph*

Using percentile thresholds, yield gap was classified into three categories: **Low (≤ 11.9), Medium (~12.7), and High (≥ 13.5)**.
Regions with **low yield gaps (≤ 11.9)** are performing close to their potential yield, indicating that farmers in these areas are operating efficiently with minimal production losses.
Regions within the **medium yield gap range (~12.7)** exhibit moderate deviations from potential yield. This suggests that while current practices are somewhat effective, there is still room for improvement through targeted interventions.

In contrast, regions with **high yield gaps  (≥ 13.5)** are significantly below their potential yield, indicating substantial production inefficiencies. These regions represent priority areas for intervention, as they offer the greatest opportunity for yield improvement.
To better understand the underlying causes of these yield gaps, subsequent analysis integrates the **Stress Index (SI)** to distinguish whether productivity constraints are primarily driven by climate factors, management practices, or a combination of both. This enables the identification of appropriate and targeted intervention strategies for each region.  

5.4 **Relationship between Yield Gap and Stress Index**  
*graph*  
**Note:** The scatter plot highlights the relationship between yield performance and limiting factors. Regions are distributed across categories that indicate whether climate stress, management inefficiencies, or both are responsible for production gaps.  

6.0 **Interpretation of Production Constraints**  
*Table*  

7.0 **Investment Insight**  
The analysis identify regions with highest potential for agricultural investment by combining yield gap and stress index metrics.  

Regions (9501, 10401) with **high yield gap** and **stress index greater than 1 (SI>1)** represent the highest investment opportunity. These regions exhibit significant under-performance despite favourable climate conditions, indicating that productivity can be improved though better management practices, such as improved seed varieties, fertilizer application, and farm management techniques.  

Region (9301, 9701) with **medium yield gaps and SI > 1** also represent good investment opportunities, as moderate improvement can lead to improved yield  

In contract, regions (10301) with **high yield gap** and **SI < 1** represent higher risk investment, as climate stress significantly limit production. In such areas, improvement may require substantial investment in climate adaptation strategies, making returns less predictable.
Regions with **low yield gap** show limited opportunity for further yield improvement, as farmers are already performing close to their potential yield.

7.1 **Summary**  
*Table*  

8.0 **Conclusion**
The study demonstrate that agricultural productivity is influenced by both climate condition and management practices. By combining yield gap analysis with climate stress index, the analysis identify not only where productivity is low but also the underlying constraint affecting production.

The result shows that while both factors contribute to yield limitations, **management-related constraints present the most immediate and cost-effective opportunities for productivity improvement**. Regions with **high yield gaps and low climate stress** offers particularly **strong investment opportunities**, as improvements in agronomic practices, input access, and farm management can rapidly increase productivity. 

In contrast, regions experiencing both **climate and management constraints require more capital-intensive interventions such as irrigation systems and climate-resilient crop technologies**, but they present substantial long-term agricultural development potential.

Therefore, agricultural investment strategies should prioritize **management-driven regions for short-term productivity gains**, while targeting **climate-constrained regions for long-term strategic development**.














