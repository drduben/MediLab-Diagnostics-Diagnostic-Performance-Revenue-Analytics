MediLab Diagnostics - Diagnostic Performance & Revenue Analytics

End-to-end Power BI healthcare analytics case study demonstrating data preparation, analytical modelling, KPI development, DAX, dashboard design, insight generation and evidence-based business recommendations.
## Dashboard Preview

### Executive & Diagnostic Overview

![MediLab Diagnostics - Executive & Diagnostic Overview](Dashboard/Page_1.png)

### Patient Analysis

![MediLab Diagnostics - Patient Analysis](Dashboard/Page_2.png)

### Service & Financial Analysis

![MediLab Diagnostics - Service & Financial Analysis](Dashboard/Page_3.png)

Project at a glance

Business domain: Healthcare / Diagnostic Laboratory Analytics
Tool: Microsoft Power BI
Analysis focus: Diagnostic Operations & Financial Performance
Dashboard: 3 analytical pages - Overview, Patient, Service
Primary audience: Operations, finance and management stakeholders

1. Business Context

MediLab Diagnostics is presented in the case study as a growing laboratory network providing diagnostic testing services to individuals, hospitals, clinics, HMOs and corporate healthcare partners across Nigeria.

The business collects information about patients, diagnostic tests, branches, referring clinicians, test outcomes and financial transactions. The case study explains that this information was held in a flat-file structure, creating challenges around organisation, consistency, maintenance, reliable calculations and reporting.

The management requirement was therefore to turn the available data into a reporting solution that could provide a clearer view of:

diagnostic demand;

patient activity;

branch and regional performance;

turnaround time;

test status and outcomes;

service performance;

customer contribution;

revenue, cost and profit; and

management priorities for improvement and growth.

The case-study brief required an analyst to examine and prepare the raw data, define relevant metrics, build an interactive dashboard, identify meaningful trends and translate the analysis into practical recommendations.

2. My Objective

I approached the project as a business intelligence problem rather than a visualisation exercise.

The objective was to build a reporting solution that could move management through the following sequence:

Business question -> data -> KPI -> visual evidence -> insight -> recommendation

The finished dashboard was designed to answer the business questions in the case-study brief while giving users enough context to interpret activity, operational performance and financial outcomes together.

3. Analytical Approach

The project followed an end-to-end workflow:

Step 1 - Understand the business requirement

I started by translating the case-study brief into specific analytical questions covering diagnostic activity, service performance, customers, clinicians, branches, results, turnaround time and financial outcomes.

Step 2 - Prepare and structure the data

The source data contained repeated information across business entities in a flat-file structure. The analytical solution therefore required a more structured approach for reliable reporting.

The final Power BI model is organised around transaction data with supporting analytical dimensions for areas such as calendar, patients, branches, tests and clinicians.

Step 3 - Develop business measures

I built measures to support the management questions, including:

Total Tests

Total Patients

Total Revenue

COGS

Total Profit

Profit Margin

Average Turnaround Time

Revenue per Patient

Tests per Patient

Completion Rate

Cancellation Rate

Pending Rate

Revenue per Clinician

Step 4 - Build the dashboard

The final report contains three analytical pages:

Overview - executive and diagnostic performance
Patient - patient, customer and service analysis
Service - service outcomes, branch performance and regional financial analysis

The case study permits a dashboard of two pages or more, provided the required business questions are addressed.

Step 5 - Analyse and recommend

I moved beyond describing chart values and looked for patterns, concentration, operational gaps and relationships between volume and financial performance.

4. Executive KPI Snapshot

The final dashboard reports:

KPI

Dashboard result

Total Tests

12K

Total Patients

3.79K

Total Revenue

91.16M

COGS

38.08M

Total Profit

53.08M

Profit Margin

58.22%

Average Turnaround Time

1.04 days

Revenue per Patient

24.06K

Tests per Patient

3.17

Completion Rate

90.13%

These KPIs provide the executive baseline for the rest of the analysis.

5. Key Business Insights

5.1 Diagnostic activity is substantial

MediLab processed approximately 12K tests across 3.79K patients, generating 91.16M in revenue and 53.08M in profit.

The dashboard also reports 3.17 tests per patient, showing that patient count on its own would understate the operational workload.

Why this matters

Management needs both patient-level and test-level measures. A growing patient base is not the only indicator of activity; the number of diagnostic requests generated per patient also affects capacity, workload and revenue.

Recommendation

Use patients, tests, tests per patient, revenue and profit as a core management KPI set and monitor them together by month, region and customer type.

5.2 Diagnostic volume changes materially over the period

The monthly activity view shows stronger testing activity through the earlier months, with:

1,304 tests in January

1,257 in February

1,403 in March - the peak

1,303 in April

1,344 in May

1,372 in June

Activity then drops sharply:

657 in July

665 in August

623 in September

670 in October

683 in November

719 in December

The profit trend broadly follows diagnostic volume.

Why this matters

The size of the change is large enough to warrant investigation. The dashboard does not establish whether the decline is seasonal, operational or demand-driven, so it would be inappropriate to assume a single cause.

Recommendation

Investigate the July break and later-period decline using referral, customer type, branch and test-category trends. Add previous-period and year-on-year comparisons in the next reporting iteration.

5.3 Demand is concentrated in three regions

Test volume by region is:

Region

Tests

South West

3.1K

Lagos

3.0K

South

2.9K

South East

1.6K

North

1.5K

Insight

South West, Lagos and South are the largest diagnostic activity centres, while North and South East operate at materially lower volumes.

Why this matters

The concentration identifies where capacity and service continuity are most important, while the lower-volume regions may contain underutilised capacity or growth opportunities.

Recommendation

Protect capacity in the three leading regions and investigate lower volumes in North and South East through referral reach, accessibility, branch capability and demand-generation opportunities.

5.4 Clinical Chemistry, Molecular Diagnostics and Hormonal Assay dominate revenue

The leading revenue categories are:

Test Category

Revenue

Clinical Chemistry

24M

Molecular Diagnostics

22M

Hormonal Assay

21M

Microbiology

9M

Serology

7M

Haematology

5M

Histopathology

4M

The top three categories generate approximately 67M, around 73% of total revenue.

Why this matters

These services form the core revenue engine. Capacity constraints, equipment downtime, cost inflation or quality issues in these categories could disproportionately affect the overall business.

Recommendation

Protect capacity, quality and equipment uptime in the top three categories while assessing lower-revenue categories for targeted growth and strategic positioning.

5.5 The overall completion rate is strong, but there is still an improvement opportunity

The dashboard reports:

90.13% completion

with the remaining requests represented by:

6.46% inconclusive

3.42% cancelled

Why this matters

A 90.13% completion rate indicates that most requests reach completion, but 9.87% do not.

The largest non-completed segment is inconclusive requests.

Recommendation

Investigate inconclusive and cancelled cases by branch, service category, customer type and clinician. Capture the operational or clinical reason for each non-completed request so management can move from monitoring the rate to addressing the cause.

5.6 Turnaround time reveals a major operational disparity between services

The overall average turnaround time is 1.04 days, but service-level performance varies:

Test Category

Average TAT

Histopathology

3.0 days

Molecular Diagnostics

2.0 days

Hormonal Assay

1.5 days

Microbiology

1.2 days

Serology

0.7 days

Clinical Chemistry

0.5 days

Haematology

0.4 days

Insight

The network average masks a much more significant service-level gap.

Histopathology is the clearest turnaround-time bottleneck, followed by Molecular Diagnostics.

Recommendation

Prioritise workflow analysis for Histopathology and Molecular Diagnostics. Break turnaround into stages such as collection, preparation, analysis and reporting to identify where delays actually occur.

5.7 Walk-in customers are the largest displayed revenue channel

Customer-type revenue is:

Customer Type

Revenue

Walk-in

33.0M

HMO

17.9M

Corporate

17.3M

Hospital Referral

13.9M

Clinic Referral

9.1M

Insight

Walk-in customers are the largest displayed revenue segment. HMO and Corporate customers also make substantial contributions.

Recommendation

Protect the direct walk-in channel while strengthening HMO and Corporate relationships.

For deeper commercial analysis, monitor patients, tests, revenue and revenue per patient by customer type so that demand and value are not inferred from revenue alone.

5.8 The leading services contribute strongly to profit as well as revenue

The revenue/profit analysis shows approximately:

Category

Revenue

Profit

Clinical Chemistry

24M

14M

Molecular Diagnostics

22M

12M

Hormonal Assay

21M

12M

Microbiology

9M

5M

Serology

7M

4M

Haematology

5M

3M

Histopathology

4M

2M

Why this matters

The strongest revenue categories are also major contributors to absolute profit.

This means management should not view service mix purely through percentage margin. Absolute profit contribution matters.

Recommendation

Evaluate service investment decisions using revenue, profit, margin and turnaround time together.

5.9 Branch activity should be assessed alongside value

The branch performance scatter shows test volumes in a relatively narrow range of approximately 1.45K-1.58K tests, while revenue varies across branches.

Insight

Branches with similar activity levels are not automatically creating the same financial value.

Recommendation

Build a branch performance matrix using:

Tests + Revenue + Profit + Margin + Completion Rate + Average TAT

This would help identify high-volume/high-value branches, high-volume/low-value branches and locations where operational or commercial improvement may be needed.

5.10 Patient demographics are broadly balanced by gender

The age/gender distribution shows a broadly even female/male split across the displayed age groups.

Why this matters

The dashboard does not show a major gender imbalance in the patient population.

However, demographic neutrality should not be interpreted as the absence of useful segmentation opportunities.

Recommendation

Use demographics as a baseline and cross-analyse age group and gender with service category, customer type, branch and test volume to identify more actionable patterns.

5.11 Referring clinician revenue is relatively concentrated within a narrow range

The leading displayed clinician revenues range from approximately:

7.3K to 7.9K

among the top clinicians shown.

Insight

There is a relatively tight spread among the highest displayed clinician contributions rather than one overwhelmingly dominant referrer.

Recommendation

Protect the existing high-value clinician relationships while developing the next tier of referral partnerships. Add patient count and test volume alongside clinician revenue to distinguish referral activity from monetary value.

5.12 Diagnostic result patterns provide a quality-monitoring opportunity

The result-by-category analysis shows the Normal result group as the largest component across the displayed service categories, with smaller portions represented by other outcome groups such as abnormal, inconclusive, negative and positive.

Why this matters

Result composition is useful for identifying categories where abnormal or inconclusive outcomes may warrant closer clinical or operational review.

Recommendation

Monitor result patterns alongside:

turnaround time;

inconclusive rate;

cancellation rate; and

test category.

This would create a more complete service-quality monitoring framework.

6. Management Priorities

Based on the combined operational, diagnostic and financial evidence, the highest-priority actions are:

Priority 1 - Protect the core revenue engine

Clinical Chemistry, Molecular Diagnostics and Hormonal Assay generate roughly 73% of revenue.

Protect capacity, quality, equipment uptime and cost control in these services.

Priority 2 - Reduce turnaround-time bottlenecks

Histopathology averages 3.0 days, substantially above the network average of 1.04 days.

Conduct process-level root-cause analysis rather than relying solely on the overall average.

Priority 3 - Improve completion performance

The 9.87% non-completed share should be actively managed, especially the 6.46% inconclusive segment.

Priority 4 - Investigate the mid-year volume decline

The fall from 1,372 tests in June to 657 in July is large enough to justify investigation.

Priority 5 - Develop regional opportunity

South West, Lagos and South are the main activity centres. North and South East should be examined for underlying demand and capacity factors.

Priority 6 - Improve branch-level decision making

Use volume and value together, rather than treating test count as a complete measure of branch performance.

Priority 7 - Continue strengthening analytical governance

Validate measures, relationships, formatting and aggregation logic before important management decisions are based on the dashboard.

7. Technical Skills Demonstrated

Power BI

Interactive dashboard development

KPI cards

Slicers and filtering

Time-series analysis

Comparative analysis

Scatter-plot analysis

100% stacked visualisation

Executive dashboard design

Multi-page report navigation

DAX / Analytical Calculations

Total tests

Unique patient analysis

Revenue

COGS

Profit

Profit margin

Completion rate

Cancellation/pending rates

Average turnaround time

Revenue per patient

Tests per patient

Revenue per clinician

Data Modelling

Fact/dimension analytical structure

Calendar dimension

Analytical relationships

Reusable business measures

Time-based reporting dimensions

Data Analysis

Trend analysis

Segmentation

Service-mix analysis

Regional analysis

Customer analysis

Branch performance analysis

Clinician analysis

Operational performance analysis

Financial analysis

Data-quality validation

Business Communication

Translating business questions into analytical questions

Explaining why a finding matters

Converting findings into recommendations

Communicating analytical limitations

Presenting insights for management decision-making

8. What Changed in the Rebuilt Dashboard

This final rebuild was not simply a redesign.

It was an analytical improvement exercise focused on correcting previous measure/visual issues and creating stronger alignment between the business questions and the visuals used to answer them.

The final report now separates the analytical story into:

Overview -> Patient -> Service

and includes stronger measures for customer, branch, service and profitability analysis.

The rebuild also reinforces an important principle:

A dashboard should be designed around the decision the user needs to make, not around the chart types available in the software.

9. Analytical Judgement and Data Quality

One of the most important professional lessons from this project is that dashboard development requires validation as well as visual design.

During the rebuild, the focus was placed on correcting analytical issues rather than simply making the dashboard look polished.

That mindset is important because a visually attractive dashboard can still produce misleading conclusions if:

a measure is calculated at the wrong grain;

a relationship is incorrect;

a value is formatted incorrectly;

an aggregation does not match the business question; or

a visual is interpreted without understanding its denominator.

This project therefore demonstrates not only Power BI capability, but also the ability to question the reliability of an analytical output.

10. Final Portfolio Statement

This project represents my approach to data analytics:

Start with the business problem.
Understand and structure the data.
Build the right measures.
Create a dashboard around the business questions.
Find the patterns.
Explain why they matter.
Recommend action.
Validate the numbers.

The goal is not to create more charts.

The goal is to turn data into evidence that supports better decisions.
Add case study write-up
