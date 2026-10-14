
<h1 align="center">📊 Meta Advertising &amp; Funnel Analytics</h1>

<p align="center">
  <b>Independent Marketing Analytics Project</b><br>
  Advertising Performance, Audience Engagement &amp; Conversion Funnel Analysis
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Domain-Marketing%20Analytics-blue" alt="Marketing Analytics">
  <img src="https://img.shields.io/badge/Tools-Power%20BI%20%7C%20Excel-orange" alt="Tools">
  <img src="https://img.shields.io/badge/Focus-KPI%20Analysis%20%7C%20Funnel%20Analytics-green" alt="Project Focus">
  <img src="https://img.shields.io/badge/Project-Independent%20Portfolio-lightgrey" alt="Independent Project">
</p>

<hr>

<h2>📌 Project Overview</h2>

<p>
This independent analytics project examines advertising event data modelled
around Facebook and Instagram campaigns. It focuses on measuring advertising
impressions, clicks, engagement activity, recorded purchases, audience
segments, advertising formats, and campaign budget allocation.
</p>

<p>
The project brings together event-level records with advertising metadata,
campaign information, and user attributes to define performance KPIs and
explore recorded activity across different dimensions.
</p>

<p><b>The project uses four related datasets:</b></p>

<ul>
  <li><b>Ad Events:</b> Event records including impressions, clicks, shares,
      comments, likes, and purchases.</li>
  <li><b>Ads:</b> Advertising platform, format, campaign association,
      and targeting attributes.</li>
  <li><b>Campaigns:</b> Campaign names, dates, and allocated budgets.</li>
  <li><b>Users:</b> Available demographic and geographic attributes.</li>
</ul>

<p>
<b>Project type:</b> Independent portfolio project using a dataset modelled
on social advertising activity. This is not an official Meta dataset,
a Meta-sponsored project, or a commercial deployment.
</p>

<hr>

<h2>🎯 Business Problem</h2>

<p>
Advertising performance cannot be evaluated through impressions or clicks
alone. A structured reporting approach is needed to compare event volumes,
engagement, purchase-related activity, audience segments, advertising formats,
and time-based patterns using consistent KPI definitions.
</p>

<p><b>Key analytical questions:</b></p>

<ul>
  <li>How many impressions, clicks, engagements, and purchases are recorded?</li>
  <li>What proportion of recorded impressions results in clicks or purchases?</li>
  <li>How does recorded engagement vary across available audience segments?</li>
  <li>How do advertising formats compare using consistently defined metrics?</li>
  <li>How does recorded event activity vary by date and hour?</li>
  <li>How are allocated campaign budgets distributed across campaigns?</li>
  <li>What data-quality limitations could affect the reliability of reporting?</li>
</ul>

<p><b>Core analytical question:</b></p>

<blockquote>
How can advertising event data be organized into consistent KPIs and
interpretable reporting to support campaign-performance analysis?
</blockquote>

<hr>

<h2>📊 Dashboard Preview</h2>

<p align="center">
  <img width="1920" height="1080" alt="Screenshot 2026-10-14 184008" src="https://github.com/user-attachments/assets/867600c8-3f97-4ec3-a512-9f2637a41aa3" />
</p>

<p>
The dashboard reference image shows KPI cards, gender and age breakdowns,
a geographic visual, weekly and hourly trends, a calendar heat map,
an ad-type comparison table, and campaign filter controls.
</p>

<p>
<b>Dashboard availability:</b> The original editable Power BI (.pbix) file
is not available in the current project materials. The image is a visual
reference and does not establish that the original interactive report can
be opened or reproduced from this repository.
</p>

<h3>Dashboard Components</h3>

<table border="1" cellpadding="8" cellspacing="0" width="100%">
  <tr>
    <th>Component</th>
    <th>Purpose</th>
  </tr>
  <tr>
    <td>KPI Cards</td>
    <td>Summarize event volumes, performance rates, and campaign budget metrics.</td>
  </tr>
  <tr>
    <td>Audience Analysis</td>
    <td>Explore recorded activity across available gender and age categories.</td>
  </tr>
  <tr>
    <td>Geographic Analysis</td>
    <td>Explore event activity using available user-country attributes.</td>
  </tr>
  <tr>
    <td>Weekly Trend</td>
    <td>Compare event activity over time and across event categories.</td>
  </tr>
  <tr>
    <td>Hourly Trend</td>
    <td>Explore activity patterns by hour where timestamps are available.</td>
  </tr>
  <tr>
    <td>Calendar Heat Map</td>
    <td>Visualize activity by date and explore potential high- and low-activity periods.</td>
  </tr>
  <tr>
    <td>Ad-Type Comparison</td>
    <td>Compare advertising formats using defined metrics and consistent filters.</td>
  </tr>
  <tr>
    <td>Filter Controls</td>
    <td>Show the intended report layout for platform, campaign, and targeting selections.</td>
  </tr>
</table>

<hr>

<h2>📈 Key KPIs &amp; Metrics</h2>

<p>
The following figures were recalculated from the supplied cleaned Excel
workbook. Event counts refer to standardized event labels in that workbook.
Values are rounded for readability except for the campaign budget figures.
</p>

<table border="1" cellpadding="8" cellspacing="0" width="100%">
  <tr>
    <th>KPI</th>
    <th>Recalculated Value</th>
    <th>Definition</th>
  </tr>
  <tr>
    <td>Impressions</td>
    <td><b>339,812</b></td>
    <td>Count of standardized Impression events.</td>
  </tr>
  <tr>
    <td>Clicks</td>
    <td><b>40,079</b></td>
    <td>Count of standardized Click events.</td>
  </tr>
  <tr>
    <td>Shares</td>
    <td><b>1,957</b></td>
    <td>Count of standardized Share events.</td>
  </tr>
  <tr>
    <td>Comments</td>
    <td><b>4,108</b></td>
    <td>Count of standardized Comment events.</td>
  </tr>
  <tr>
    <td>Likes</td>
    <td><b>12,013</b></td>
    <td>Count of standardized Like events.</td>
  </tr>
  <tr>
    <td>Purchases</td>
    <td><b>2,031</b></td>
    <td>Count of standardized Purchase events.</td>
  </tr>
  <tr>
    <td>Engagements</td>
    <td><b>58,157</b></td>
    <td>Clicks + Likes + Shares + Comments.</td>
  </tr>
  <tr>
    <td>Click-Through Rate (CTR)</td>
    <td><b>11.79%</b></td>
    <td>Clicks ÷ Impressions × 100.</td>
  </tr>
  <tr>
    <td>Engagement Rate</td>
    <td><b>17.11%</b></td>
    <td>Engagements, including likes, ÷ Impressions × 100.</td>
  </tr>
  <tr>
    <td>Click-to-Purchase Rate</td>
    <td><b>5.07%</b></td>
    <td>Purchases ÷ Clicks × 100.</td>
  </tr>
  <tr>
    <td>Purchase Rate per Impression</td>
    <td><b>0.60%</b></td>
    <td>Purchases ÷ Impressions × 100.</td>
  </tr>
  <tr>
    <td>Total Allocated Campaign Budget</td>
    <td><b>$2,535,923.78</b></td>
    <td>Sum of the campaign budget field in the cleaned workbook.</td>
  </tr>
  <tr>
    <td>Average Budget per Campaign Record</td>
    <td><b>$50,718.48</b></td>
    <td>Total allocated budget ÷ 50 campaign records.</td>
  </tr>
</table>

<p>
<b>Important metric definitions:</b> CTR measures clicks relative to
impressions. Click-to-purchase rate measures recorded purchases relative
to recorded clicks. Purchase rate per impression measures recorded purchases
relative to impressions.
</p>

<p>
These are ratios of event counts, not necessarily unique-user conversion
rates. The available project materials do not establish a validated
user-level purchase attribution model.
</p>

<p>
<b>Engagement definition:</b> The recalculated engagement total includes
clicks, likes, shares, and comments. This differs from the original BRD
definition, which lists clicks, shares, and comments. The definition must
be made consistent across the final KPI dictionary and any rebuilt dashboard.
</p>

<p>
<b>Data-version note:</b> These recalculated event totals differ from those
shown in the earlier dashboard screenshot. The figures above describe the
supplied cleaned workbook and are not presented as a verified reproduction
of the original dashboard's measures.
</p>

<hr>

<h2>🔍 Analytical Findings</h2>

<h3>1. Advertising Reach and Click Activity</h3>

<ul>
  <li>The cleaned workbook contains <b>339,812 impression events</b>.</li>
  <li>It contains <b>40,079 click events</b>.</li>
  <li>The resulting event-count CTR is <b>11.79%</b>.</li>
</ul>

<p>
These values describe the volume of recorded activity in the cleaned dataset.
They do not, by themselves, establish campaign profitability or performance
relative to an industry benchmark.
</p>

<h3>2. Recorded Engagement</h3>

<ul>
  <li>The dataset contains <b>58,157 engagement events</b> using the documented
      definition of clicks, likes, shares, and comments.</li>
  <li>The resulting engagement-to-impression ratio is <b>17.11%</b>.</li>
</ul>

<p>
Engagement is measured as an aggregate of events. It should not be interpreted
as the percentage of unique users who engaged unless the analysis explicitly
deduplicates users and defines the eligible population.
</p>

<h3>3. Purchase-Related Metrics</h3>

<ul>
  <li>The cleaned workbook contains <b>2,031 purchase events</b>.</li>
  <li>The purchase-to-click event ratio is <b>5.07%</b>.</li>
  <li>The purchase-to-impression event ratio is <b>0.60%</b>.</li>
</ul>

<p>
These ratios describe the relationship between recorded event counts.
They do not prove that every purchase was caused by, or attributable to,
a particular click or impression.
</p>

<h3>4. Audience and Geographic Analysis</h3>

<p>
The project includes user attributes and ad-targeting fields for audience
analysis. However, unmatched user identifiers and missing attributes require
validation before demographic or geographic results can be considered complete.
</p>

<p>
Actual user demographics and ad-targeting categories are different concepts.
Any audience chart should clearly identify which field is being analyzed.
Claims about a leading gender, age group, or country should be made only
after the underlying records, grouping logic, and visual calculations
have been reconciled.
</p>

<h3>5. Ad-Format Comparison</h3>

<p>
The dashboard design includes a comparison of Carousel, Image, Stories,
and Video formats. Reliable comparisons require consistent filters,
event definitions, denominators, and reporting periods across formats.
</p>

<p>
The available materials do not establish a verified ranking of advertising
formats by profitability, return on ad spend, or incremental conversion
impact. Such outcomes should not be inferred from CTR or engagement alone.
</p>

<h3>6. Time-Based Analysis</h3>

<p>
The project includes weekly, hourly, and calendar-based views. Missing
timestamps and differences in reporting-date context can affect these
visuals. Time-based conclusions require validation against the available
timestamp field and the selected reporting period.
</p>

<hr>

<h2>💡 Business Recommendations</h2>

<p>
The following are recommendations for further investigation, not claims
of proven business improvements:
</p>

<ul>
  <li><b>Validate conversion measurement:</b> Confirm the relationship between
      impression, click, and purchase events before attributing purchases
      to specific campaign interactions.</li>
  <li><b>Compare advertising formats consistently:</b> Evaluate CTR and
      click-to-purchase rates using consistent filters and denominators.</li>
  <li><b>Review audience segmentation:</b> Validate event-to-user relationships
      and distinguish actual user attributes from targeting attributes.</li>
  <li><b>Investigate time-based patterns:</b> Check timestamp completeness
      and reporting-period consistency before recommending campaign schedules.</li>
  <li><b>Improve KPI documentation:</b> Maintain a clear KPI dictionary
      and document data exclusions, transformations, and assumptions.</li>
  <li><b>Assess cost efficiency carefully:</b> Use campaign budget data for
      allocation analysis, but do not claim ROI, ROAS, CPC, or CPM without
      the required spend, delivery, and attribution definitions.</li>
</ul>

<hr>

<h2>⚙️ Technical Implementation</h2>

<h3>Data Sources</h3>

<ul>
  <li><code>ad_events.csv</code> — event-level advertising activity.</li>
  <li><code>ads.csv</code> — advertising metadata and targeting attributes.</li>
  <li><code>campaigns.csv</code> — campaign information and budget fields.</li>
  <li><code>users.csv</code> — user attributes for segmentation.</li>
  <li><code>clean_data.xlsx</code> — supplied cleaned workbook used for
      recalculating headline KPIs.</li>
</ul>

<h3>Tools and Concepts</h3>

<ul>
  <li><b>Excel:</b> Inspection and review of tabular data.</li>
  <li><b>Power BI:</b> Dashboard design and reporting concepts represented
      by the supplied dashboard screenshot.</li>
  <li><b>DAX:</b> Relevant to the intended Power BI KPI calculations;
      the original editable report and its measures are not available
      for independent inspection.</li>
  <li><b>Data Modeling:</b> Relating event records to advertising,
      campaign, and user attributes.</li>
  <li><b>KPI Definition:</b> Documenting formulas, units, denominators,
      and business interpretation.</li>
</ul>

<p>
The original Power BI file and complete transformation scripts were not
available in the supplied project materials. Therefore, the exact original
Power Query steps, DAX measures, model relationships, and interactive filter
behavior have not been independently verified.
</p>

<hr>

<h2>🧹 Data Quality &amp; Limitations</h2>

<p>
The cleaned workbook contains 400,000 event rows. Preserving the row count
does not by itself establish that all fields, classifications, and
relationships are correct.
</p>

<ul>
  <li><b>Event standardization:</b> The raw event file contains inconsistent
      capitalization, whitespace, and event labels. KPI calculations depend
      on consistent event classification.</li>
  <li><b>Missing values:</b> The raw files contain missing timestamps,
      event types, and user attributes. Their treatment should be documented
      and validated.</li>
  <li><b>Unmatched user identifiers:</b> Some event records do not match a
      record in the cleaned users table. Demographic and geographic analyses
      may therefore be incomplete.</li>
  <li><b>Ad-record reconciliation:</b> The raw ads file contains 230 records,
      while the cleaned workbook contains 200. The reason for the difference
      should be established before claiming all ad records were retained.</li>
  <li><b>Event counts versus unique users:</b> Event totals may include
      repeated actions by the same user and should not be described as
      unique customers.</li>
  <li><b>Attribution limitations:</b> The available event data does not
      establish a causal relationship between advertising activity and
      purchases.</li>
  <li><b>Dashboard reproducibility:</b> The original editable Power BI
      report is unavailable, so screenshot values cannot be assumed to
      reproduce the recalculated workbook metrics.</li>
</ul>

<p>
These limitations are documented to make the analysis transparent.
They should be updated only after the relevant data checks and model
validation are completed.
</p>

<hr>

<h2>📁 Repository Contents</h2>

<p>
The repository contains the available source data and supporting project
documentation. Review the committed folders for the corresponding artifacts.
</p>

<ul>
  <li><b><code>data_files/</code></b> — available raw datasets and cleaned workbook.</li>
  <li><b><code>dashboard/</code></b> — dashboard-related assets and preview image,
      where included.</li>
  <li><b><code>required_documents/</code></b> — BRD, domain knowledge,
      and dashboard insights documents, where included.</li>
  <li><b><code>sql queries/</code></b> — SQL-related materials, where included.</li>
  <li><b><code>README.md</code></b> — project overview, KPI definitions,
      findings, and limitations.</li>
</ul>

<p>
The original editable Power BI file is not available in the current project
materials. Only files actually committed to the repository should be
considered available to reviewers.
</p>

<hr>

<h2>👨‍💻 Skills Demonstrated</h2>

<ul>
  <li>Marketing KPI definition and interpretation</li>
  <li>Event-level data analysis</li>
  <li>Data-quality review and reconciliation</li>
  <li>Campaign and audience data-modeling concepts</li>
  <li>Conversion-funnel measurement</li>
  <li>Dashboard reporting and visualization design</li>
  <li>Business requirements documentation</li>
  <li>Analytical findings, limitations, and recommendations</li>
</ul>

<hr>

<h2>👨‍💻 Author</h2>

<p>
  <b>Pranay Shrivastava</b><br>
  B.Tech — Artificial Intelligence &amp; Data Science<br>
  <b>Focus:</b> Data Analytics | Business Intelligence | Product Analytics
</p>

<p>
  <a href="mailto:shrivastavapranay.35@gmail.com">Email</a> |
  <a href="https://www.linkedin.com/in/pranayshrivastavaofficial/">LinkedIn</a> |
  <a href="https://github.com/pranay-125">GitHub</a>
</p>

<hr>

<p align="center">
  <i>
    Independent analytics portfolio project. Reported metrics are based on
    the supplied cleaned workbook and remain subject to the documented
    data-quality and dashboard-reconciliation limitations.
  </i>
</p>
