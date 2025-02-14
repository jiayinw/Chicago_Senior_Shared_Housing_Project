# Chicago_Senior_Shared_Housing_Project
An exploration on Chicago South housing supply and senior shared housing needs

**I.	Executive Summary**

Our project provides elderly South Siders with roommates in safe neighborhoods. After careful analysis, our work suggests (1) relocation to a safe neighborhood per the AARP Livability Index and (2) finding a roommate both save money; and that age, income, and health are key factors impacting housing needs for the elderly. We also share professionals’ recommendations.

We recommend accessible senior-focused housing communities or a matching platform for elderly individuals to meet. We conclude with suggestions for further research: (1) identification of stakeholders and funding sources, (2) a limited-scale shared housing initiative pilot, (3) establishing legal frameworks for roommate matching, (4) expansion of geographic scope, and (5) conducting a longitudinal study on the effect(s) of shared housing. See appendices for further detail.


**II.	Background and Motivation**

Evidence shows the national elderly homeless population would triple between 2020 and 2030.  (Santos 2020) Between 1990 and 2010, divorce rates among Americans over the age of fifty doubled. Elders who live alone are generally lonelier than those who do not.  (Shoichet 2023) Older Americans struggle to downsize: today, only 7 percent of new homes are 1,400 square feet or less. Historically Black neighborhoods, such as those on Chicago’s South Side, see the largest numbers of seniors unable to downsize. (Review of As Gen X and Baby Boomers Age, They Confront Living Alone 2022)

Housing construction for elderly Chicagoans since the ruling Gautreaux v. Chicago Housing Authority has focused on building affordable housing in majority-white neighborhoods. (Choldin 2019) In this ruling, the plaintiffs alleged that the Chicago Housing Authority contributed to segregation by only building public housing in segregated Black communities. Historically, Chicago real estate companies engaged in redlining, in which those from Black neighborhoods “were usually denied bank loans and insurance, limiting their housing prospects and mobility.” (Serrato et al. 2022) Chicago remains segregated, and 80.45% of those at least 65 years old on the South Side are Black. (Review of Population 60 Years and Older in the United States n.d.)

We aim to reduce living costs and combat social isolation among Chicago’s older adults. To avoid engaging in systemic bigotry, we include accommodations based off of the roommates’ identity and incorporate a targeting system to locate marginalized minorities who would most benefit from our project’s priorities. 


**III.	Data Sources and Methodology** 

The AARP Livability Index evaluates general community livability for residents regardless of age across seven categories: Housing, Neighborhood, Transportation, Environment, Health, Engagement, and Opportunity, assigning scores from 0 to 100. Metrics include housing availability and costs, healthcare access, transit options, pollution levels, broadband access, and income inequality. A community's livability score averages these categories, offering a comprehensive measure of neighborhood quality.

Figure 1 illustrates overall livability scores for the Chicago area. 

https://github.com/jiayinw/Chicago_Senior_Shared_Housing_Project/blob/main/Map/chicago_neighborhood_map.html

<img width="468" alt="image" src="https://github.com/user-attachments/assets/507446a5-ffae-45b8-99a1-199ef24e6491" />

In general, communities in South Chicago score within the medium range, indicating that their livability is comparable to most other Chicago communities. Pullman Park stands out with a low score (40-49), suggesting the need for targeted efforts to improve infrastructure and make it more resident-friendly. Alternatively, relocating elderly residents to higher-scoring communities remains an option.
 
Figure 2:Score for healthcare accessibility for whole Chicago area

<img width="294" alt="image" src="https://github.com/user-attachments/assets/92b6a96b-be8c-4a40-af96-75962f991112" />

Figure 2 highlights Chicago’s healthcare accessibility scores. Kenwood and Hyde Park demonstrate slightly higher scores compared to other South Side communities. Most South Side communities have lower healthcare accessibility scores than other areas in Chicago, indicating that the South Side faces healthcare accessibility challenges.

Quantitative Analysis:
●	Logistic Regression: Our model identified factors influencing the need for housing support, incorporating variables such as age, income, health conditions, and mental health status.

●	Linear Regression: This model explored the relationship between household size and variables like age, income, and the number of people in residence.

●	ANOVA: We compared rent savings between transitioning to shared two-bedroom and three-bedroom apartments to assess the cost-effectiveness of shared living arrangements.

Qualitative Analysis:

●	Conducted four stakeholder interviews with young potential roommates, one housing professional and one attorney (Appendix B). Three of them are semi-structured individual interviews and one is a focus group interview. 

●	Conducted thematic analysis to assess shared living feasibility, identifying challenges and incentives, supported by professional advice on inclusive designs and legal soundness.

Mapping and Visualization:

●	Rent and livability data were visualized using curated tables and charts, highlighting cost disparities and potential savings through shared living arrangements.

**IV.	Quantitative Analysis and Insights**

a)  Cost Savings through Housing Choices

South Side rent is generally lower than the Chicago average . Analyzing rent as a percentage of median household income reveals disparities in rent burden across neighborhoods. Greater Grand Crossing residents face the highest rent burden, spending over half their income on a studio apartment and up to 92.9% for three-bedroom units. Hyde Park and Kenwood demonstrate lower rent burdens, with studio apartments requiring 26.4% and 23.1% of income, respectively. Larger apartments in these neighborhoods remain relatively more affordable compared to others.

Shared living arrangements offer clear economic advantages. Transitioning from a one-bedroom to a two-bedroom shared apartment reduces rental costs by 17% on average, while moving to a shared three-bedroom cuts costs by 22%. In Bridgeport, the percentage of income spent on rent drops from 37% for a one-bedroom to 13% for a shared two-bedroom and 17% for a shared three-bedroom. Similar trends are evident elsewhere: in Greater Grand Crossing, rent burden decreases from 68% for a one-bedroom to 31% and 21% for shared two-bedroom and three-bedroom units, respectively. Other neighborhoods also show considerable reductions in rent burden through shared living arrangements.

Moving further enhances cost savings. Relocating from a one-bedroom apartment in Hyde Park to a two-bedroom in South Shore reduces rent by $622, a 40.6% decrease. Similarly, moving from Greater Grand Crossing to Washington Park saves $594, (i.e., a 40.49% reduction). Transitions from one-bedroom to three-bedroom apartments save $453 when moving from Hyde Park to South Shore and $395 from Greater Grand Crossing to Washington Park. Thus, the project team believes shared living and neighborhood transitions can save rent without sacrificing space.

b) Insights from Quantitative Analysis
Part 1. Logistic Regression: Predictors of Housing Support Needs
To evaluate housing support needs, we employed the following logistic regression model:
logit(P(Y=1))=β0+β1Age+β2 Income+β3 Health Conditions
Where Y=1 represents individuals requiring housing support.

Findings:

●	Age (β1=−0.0349, p<0.001): Older individuals are less likely to require housing support, indicating that they may already have stable living arrangements.

●	Income (β2=−1.324e−05, p<0.001): Lower-income individuals are more likely to need housing support, emphasizing the importance of targeting economically vulnerable populations.  

●	Health Conditions:

○	Diabetes (β=0.3183, p=0.01): A positive correlation indicates increased housing support needs for individuals with diabetes.
○	Mental Health (β=−0.6865, p<0.001): Poor mental health reduces housing stability, increasing support needs.
Policies should prioritize low-income and health-vulnerable populations, particularly those with chronic illnesses or mental health challenges, to maximize the impact of shared housing programs.

Part 2. Linear Regression: Understanding Household Size Dynamics
To analyze patterns in household size, the following linear regression model was developed:
Y=β0+β1Age+β2 Income
Where Y represents household size.

Findings:

●	Age (β1=−0.0073, p<0.001): Older adults are more likely to live alone, reinforcing the relevance of shared living arrangements for this demographic.

●	Income (β2): Not significant (p>0.05): Household size does not appear to vary with income in this dataset.
Older adults living alone are a key demographic for shared housing initiatives, as these arrangements can address loneliness and financial challenges.


Part 3. ANOVA: Rent Savings Across Neighborhoods
We used an ANOVA Model to evaluate rent savings from transitioning between different apartment types. The analysis compares savings for moves from 1BR to 2BR and 1BR to 3BR apartments across 10 neighborhoods in Chicago.

Key Findings

1.	Savings Across Groups:
○	Hyde Park to South Shore transitions (1BR → 2BR) show the highest savings at $622.
○	Greater Grand Crossing to Washington Park transitions (1BR → 2BR) yield $594.
2.	Statistical Analysis:
○	ANOVA results indicate no significant difference between savings groups (p = 0.769).
○	The model explains only 3.3% of the variability in savings (R-squared = 0.033), suggesting that room type alone does not adequately explain savings.
3.	Neighborhood-Specific Patterns:
○	Savings vary by neighborhood but follow no statistically significant trend. Observed savings should be interpreted with caution.

While shared living arrangements offer measurable cost reductions in certain neighborhoods, statistical tests reveal that these patterns are not consistent enough to generalize across all neighborhoods or room types. Future studies should explore additional factors influencing rent savings, such as building amenities and lease terms.

**V.  Qualitative Analysis: Findings from Stakeholder Interviews**
a)  Feasibility of Young Potential Roommates' Involvement in Shared Living

To assess the feasibility of shared living arrangements between young roommates and elderly individuals, our team conducted one individual interview and one focus group interview with participants from Harris School of Public Policy (Appendix B.1 & B.2). Thematic analysis highlighted two main challenges and one potential driver of interest:

●	Compatibility and Lifestyle Differences: Interviewees expressed concerns about mismatched routines, habits, and limited shared interests with elderly roommates, which could hinder harmonious cohabitation. 

●	Practical Concerns: Cost, safety, proximity to essential services, and potential caregiving responsibilities, further influenced their hesitations.

●	Incentives: Structured arrangements, including financial subsidies to offset costs, opportunities for pre-match interactions to assess compatibility, and flexible configurations like mixed roommate arrangements (e.g., two young roommates and one elderly roommate), were identified as ways to bridge generational and cultural gaps and enhance comfort.

b)  Professional advice for Roommates Project

Also, our team gathered professional insights from Professor Emily Talen (Appendix B.3) and an attorney (Appendix B.4), offering complementary guidance to shape the Roommates Project into a legally sound, inclusive, and community-focused initiative.

From an urban design perspective, Professor Talen underscored the importance of creating shared accessible and inclusive living spaces. She emphasized addressing intersectionality—particularly the overlapping impacts of age, gender, and disability—to ensure equitable housing solutions. Additionally, her focus on intergenerational and community-driven spaces, such as integrating libraries and preschools, highlights their potential to reduce loneliness and enhance mental well-being among seniors.

From a legal perspective, the attorney confirmed the Roommates Project is feasible with proper safeguards in place. Compliance with the Fair Housing Act is essential, ensuring non-discriminatory practices and reasonable accommodations. Zoning laws may require careful navigation, including variances for shared living arrangements, while Illinois tenant protections necessitate clear agreements for deposits, cost-sharing, and exit plans. Liability risks can be minimized through participant screening and defining the organization’s facilitator role. While impacts on social welfare benefits should be carefully considered, these challenges are manageable, making the project a legally viable initiative to support affordable housing for seniors.

**VI.  Recommendations**
Our primary objective is to reduce social isolation among older adults, with the added benefit of lowering housing expenses. This program differs from traditional affordable housing or full-time nursing care solutions. For instance, individuals with extremely low incomes may require fully government-funded affordable housing, while those with significant health challenges would benefit more from full-time nursing care facilities. Based on our analysis, the most promising beneficiaries of this program are older adults who are mostly independent in their daily living, have some savings or retirement income to cover rent, and seek emotional companionship.
Based on case studies, we propose two potential rental models that fall between fully subsidized affordable housing and private housing options:

1.	Senior-Focused Housing Communities

These communities would be managed by the government or social organizations and could involve partnerships with housing companies. For example, buildings where over 40% of the residents are older adults, as seen in Naturally Occurring Retirement Communities in New York (See appendix for details), could be developed. These communities provide low-cost rental options and could provide systematic basic healthcare and management services without offering full-time nursing care. 

2.	Matching Platform for Shared Housing

This model would connect older adults with potential housemates. Housing options could include private residences owned by seniors or market-rate apartments. Outreach efforts would target locations frequently visited by older adults, such as churches or community centers. Additionally, a user-friendly, interactive online portal is essential to be developed, with features like compatibility matching based on lifestyle preferences, health needs, and rental affordability. 

For senior-focused housing communities, targeted subsidies could provide critical support for low-income seniors. Expanding the Housing Choice Voucher Program (Section 8) specifically for older adults or implementing rent control measures could help address affordability challenges. Additionally, it’s highly recommended to select program location based on variations in livability scores across neighborhoods in Chicago's South Side. This may involve relocating elderly residents to areas which offer higher livability scores and lower average rents.

For the shared housing model, local governments could incentivize private developers with tax benefits or zoning changes to promote the construction or retrofitting of senior-friendly housing units. Furthermore, planning for the development of an online shared housing platform is essential, including an evaluation of the required investment, operating model, and outreach strategies.

While the proposed measures offer promise, there are still significant challenges to bring them to fruition. Key hurdles include funding constraints, legal and policy complexities, operational issues, and more. To address these challenges, we propose the following steps for future exploration:

1.	Stakeholders and Funding

Identify specific stakeholders, funding sources, and operational strategies by investigating:

●	Municipal funding options and support from local organizations.
●	Opportunities in the private housing market.
●	Collaboration with social workers and public medical teams. Additionally, consider engaging potential partners such as:
●	Universities to attract young participants and volunteers.
●	Research institutions, like law school housing clinics, to support policy research and operational planning.

2. Pilot a Limited-Scale Shared Housing Initiative
Develop a pilot program targeting seniors in areas with the greatest housing affordability challenges and social isolation.

●	Leverage data from Chicago Comprehensive Care Program (CCP) and other social services to identify eligible participants.
●	Test the roommate matching model to assess feasibility and gather insights that can inform a larger-scale rollout.

3. Establish Legal Frameworks for Roommate Matching

Create standardized roommate agreements to:
●	Define roles and responsibilities.
●	Address privacy concerns and conflict resolution.
●	Provide legal protections for seniors to prevent exploitation and ensure safe living conditions.

4. Conduct a Longitudinal Study on Shared Housing Impact

Initiate a longitudinal study to evaluate the long-term effects of shared housing on seniors. Key metrics to assess include:
●	Health outcomes and changes in well-being.
●	Rental cost reductions due to improved living conditions.
●	Social engagement levels among participants.

These findings can serve as a foundation for future policy recommendations and program expansions.
Through these efforts, the Chicago South Side Elderly Shared Housing Program can become a scalable and sustainable solution to social isolation and housing affordability among elders.










