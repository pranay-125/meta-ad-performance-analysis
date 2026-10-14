<h1 align="center">📊 Meta Advertising & Funnel Analytics</h1>

<p align="center">
  <b>End-to-End Marketing Analytics Project</b><br>
  Advertising Performance, Audience Engagement & Conversion Funnel Analysis
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Domain-Marketing%20Analytics-blue" alt="Marketing Analytics">
  <img src="https://img.shields.io/badge/Tools-Power%20BI%20%7C%20DAX%20%7C%20Excel-orange" alt="Tools">
  <img src="https://img.shields.io/badge/Focus-KPI%20Analysis%20%7C%20Funnel%20Analytics-green" alt="Project Focus">
  <img src="https://img.shields.io/badge/Project-Independent%20Analytics-lightgrey" alt="Independent Project">
</p>

<hr>

<h2>📌 Project Overview</h2>

<p>
This independent marketing analytics project examines advertising event data
modelled around Facebook and Instagram campaigns. It focuses on measuring
advertising reach, clicks, engagement activity, purchases, audience segments,
ad-format performance, and campaign budget allocation.
</p>

<p>
The project combines event-level data with advertising, campaign, and user
attributes to define performance KPIs and explore the relationship between
advertising exposure, engagement, and recorded purchases.
</p>

<p>
The analysis uses four related datasets:
</p>

<ul>
  <li><b>Ad Events:</b> Event records such as impressions, clicks, shares,
      comments, likes, and purchases.</li>
  <li><b>Ads:</b> Advertising platform, format, campaign association,
      and targeting attributes.</li>
  <li><b>Campaigns:</b> Campaign dates, names, and allocated budgets.</li>
  <li><b>Users:</b> Available demographic and geographic attributes.</li>
</ul>

<p>
<b>Project type:</b> Independent portfolio project using a dataset modelled
on social advertising activity. This is not an official Meta dataset or a
commercial deployment.
</p>

<hr>

<h2>🎯 Business Problem</h2>

<p>
Marketing performance involves more than counting impressions and clicks.
Analysts need consistent KPI definitions to understand how recorded
advertising activity varies across campaigns, audiences, time periods,
and creative formats.
</p>

<p><b>Key analytical questions:</b></p>

<ul>
  <li>How many impressions, clicks, engagements, and purchases are recorded?</li>
  <li>What proportion of impressions results in clicks or purchases?</li>
  <li>How does recorded engagement vary across audience segments?</li>
  <li>How do advertising formats compare on impressions, clicks, and
      conversion-related metrics?</li>
  <li>How does engagement vary by date and hour?</li>
  <li>How are campaign budgets distributed across the available campaigns?</li>
</ul>

<p><b>Core Question:</b></p>

<blockquote>
How can advertising event data be organized into consistent KPIs and
interpretable reporting to support campaign-performance analysis?
</blockquote>

<hr>

<h2>📊 Dashboard Preview</h2>

<p align="center">
  <img
    src="dashboard/dashboard_screenshot.png"
    alt="Meta Advertising Performance Dashboard preview"
    width="100%">
</p>

<p>
The dashboard preview follows the intended Power BI report layout and
includes KPI cards, audience breakdowns, a geographic visual, time-based
trends, a calendar heat map, an ad-type comparison table, and campaign
filter controls.
</p>

<p>
<b>Dashboard availability:</b> The original editable Power BI (.pbix) file
is not available in the current project materials. The image is a visual
preview and should not be interpreted as proof that the original interactive
report file is included in this repository.
</p>

<h3>Dashboard Components</h3>

<table border="1" cellpadding="8" cellspacing="0" width="100%">
  <tr>
    <th>Component</th>
    <th>Purpose</th>
  </tr>
  <tr>
    <td>KPI Cards</td>
    <td>Summarize impressions, clicks, shares, comments, purchases,
        engagement, performance rates, and campaign budgets.</td>
  </tr>
  <tr>
    <td>Audience Analysis</td>
    <td>Explore engagement across the available gender and age
        categories.</td>
  </tr>
  <tr>
    <td>Geographic Analysis</td>
    <td>Explore event activity by the available user-country attributes.</td>
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
    <td>Display activity by date to help identify potential peaks and
        low-activity periods.</td>
  </tr>
  <tr>
    <td>Ad-Type Comparison</td>
    <td>Compare advertising formats using consistently defined KPIs.</td>
  </tr>
  <tr>
    <td>Filter Controls</td>
    <td>Provide the intended report layout for platform, campaign,
        and targeting selections.</td>
  </tr>
</table>

<hr>

<h2>📈 Key KPIs & Metrics</h2>

<p>
The following headline counts and rates were recalculated from the supplied
cleaned workbook. Rates use the event counts shown in this table. Values are
rounded for readability.
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
    <td>Total Campaign Budget</td>
    <td><b>$2,535,923.78</b></td>
    <td>Sum of the campaign budget field in the cleaned workbook.</td>
  </tr>
  <tr>
    <td>Average Budget per Campaign</td>
    <td><b>$50,718.48</b></td>
    <td>Total campaign budget divided by 50 campaign records.</td>
  </tr>
</table>

<p>
<b>Metric interpretation:</b> CTR measures clicks relative to impressions.
Click-to-purchase rate measures recorded purchases relative to recorded
clicks. Purchase rate per impression measures recorded purchases relative
to impressions. These are event-count ratios and should not automatically
be interpreted as unique-user conversion rates.
</p>

<p>
<b>Engagement definition:</b> This project uses clicks, likes, shares, and
comments in the recalculated engagement total. This definition must be
applied consistently in the data dictionary, dashboard calculations,
and supporting documents.
</p>

<p>
<b>Data-version note:</b> The recalculated event totals differ from those
displayed in the earlier dashboard screenshot. The figures above describe
the supplied cleaned workbook, not a verified reproduction of the original
dashboard's measures.
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
These figures describe the volume of recorded advertising activity in the
cleaned dataset. They do not, by themselves, establish campaign
profitability or performance relative to an industry benchmark.
</p>

<h3>2. Recorded Engagement</h3>

<ul>
  <li>The dataset contains <b>58,157 engagement events</b> under the
      documented definition that includes clicks, likes, shares, and
      comments.</li>
  <li>The resulting engagement-to-impression ratio is <b>17.11%</b>.</li>
</ul>

<p>
Engagement is measured as an aggregate of events. It should not be described
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
These ratios provide a descriptive comparison of event counts. A purchase
event does not establish that a purchase was uniquely attributable to a
specific click or impression. The available materials do not establish a
validated user-level attribution model.
</p>

<h3>4. Audience and Geographic Analysis</h3>

<p>
The project includes user attributes and ad-targeting fields that can be
used to explore audience segments. However, unmatched user identifiers and
missing attributes require validation before demographic or geographic
results are treated as complete.
</p>

<p>
No claim that a particular gender, age group, or country is the best
performing segment should be treated as a verified finding until the
underlying records, grouping logic, and visual calculations have been
reconciled.
</p>

<h3>5. Ad-Format Comparison</h3>

<p>
The dashboard design includes a comparison of Carousel, Image, Stories,
and Video formats. A reliable comparison requires consistent filters,
event definitions, denominators, and reporting periods across all formats.
</p>

<p>
The current documentation does not establish a validated ranking of
ad formats by profitability, return on ad spend, or incremental conversion
impact. Those outcomes should not be inferred from CTR or engagement alone.
</p>

<h3>6. Time-Based Analysis</h3>

<p>
The project includes weekly, hourly, and calendar-based views. Missing
timestamps and inconsistent date context can affect these visuals, so
time-based conclusions require validation against the available timestamp
field and the selected reporting period.
</p>

<hr>

<h2>💡 Business Recommendations</h2>

<p>
The following are analytical recommendations to investigate, rather than
claims of proven business improvements:
</p>

<ul>
  <li><b>Investigate conversion measurement:</b> Confirm the relationship
      between impression, click, and purchase events before attributing
      purchases to individual campaign interactions.</li>
  <li><b>Compare ad formats consistently:</b> Evaluate CTR and
      click-to-purchase rates using the same filters and clearly defined
      denominators.</li>
  <li><b>Review audience segmentation:</b> Validate user-to-event joins and
      distinguish actual user attributes from ad-targeting attributes.</li>
  <li><b>Examine time-based patterns:</b> Confirm timestamp completeness and
      reporting-period consistency before recommending campaign schedules.</li>
  <li><b>Improve measurement documentation:</b> Maintain a clear KPI
      dictionary and record any data exclusions, transformations, or
      assumptions.</li>
  <li><b>Assess cost efficiency:</b> Use budget data for allocation analysis,
      but do not claim ROI, ROAS, CPC, or CPM without the appropriate spend
      and attribution definitions.</li>
</ul>

<hr>

<h2>⚙️ Technical Implementation</h2>

<h3>Data Sources</h3>

<ul>
  <li><code>ad_events.csv</code> — event-level activity.</li>
  <li><code>ads.csv</code> — advertising metadata and targeting fields.</li>
  <li><code>campaigns.csv</code> — campaign information and budget fields.</li>
  <li><code>users.csv</code> — user attributes for segmentation.</li>
  <li><code>clean_data.xlsx</code> — supplied cleaned workbook used for the
      recalculated headline KPIs.</li>
</ul>

<h3>Tools and Concepts</h3>

<ul>
  <li><b>Excel:</b> Inspecting and reviewing tabular data.</li>
  <li><b>Power BI:</b> Dashboard design and performance reporting concepts,
      as represented by the supplied dashboard screenshot.</li>
  <li><b>DAX:</b> Relevant to the intended Power BI KPI calculations;
      the original editable report and its measures are not available for
      independent inspection.</li>
  <li><b>Data Modeling:</b> Relating event data to advertising, campaign,
      and user attributes.</li>
  <li><b>KPI Definition:</b> Documenting formulas, units, denominators,
      and business interpretation.</li>
</ul>

<p>
The original Power BI file and the complete transformation scripts were not
available in the supplied project materials. Consequently, the exact
Power Query steps, original DAX measures, model relationships, and interactive
filter behavior have not been independently verified.
</p>

<hr>

<h2>🧹 Data Quality & Limitations</h2>

<p>
The cleaned workbook preserves 400,000 event rows, but data cleaning and
record preservation do not by themselves establish that every field or
relationship is correct.
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
      while the cleaned workbook contains 200. The reasons for the difference
      should be established before claiming that all ad records were retained.</li>
  <li><b>Event-count versus user-count metrics:</b> Event totals can include
      repeated actions by the same user and should not be described as unique
      customers.</li>
  <li><b>Attribution limitations:</b> The available event data does not, by
      itself, prove causal relationships between advertising activity and
      purchases.</li>
  <li><b>Dashboard reproducibility:</b> The original editable Power BI
      report is unavailable, so screenshot values cannot be assumed to
      reproduce the recalculated workbook metrics.</li>
</ul>

<p>
These limitations are part of the current audit status. They should be
updated only after the relevant data checks and model validation are
completed.
</p>

<hr>

<h2>📁 Repository Contents</h2>

<p>
The repository contains the available source data and project documentation.
Use the folders below to locate the corresponding artifacts.
</p>

<ul>
  <li><b><code>data_files/</code></b> — available raw datasets and cleaned
      workbook.</li>
  <li><b><code>dashboard/</code></b> — dashboard-related assets and the
      preview image, if included.</li>
  <li><b><code>required_documents/</code></b> — BRD, KPI documentation,
      domain notes, and dashboard insights, where included.</li>
  <li><b><code>notebook/</code></b> — notebook-related project materials,
      where included.</li>
  <li><b><code>sql queries/</code></b> — SQL-related materials, where
      included.</li>
</ul>

<p>
Folder names above describe the intended organization of the existing
repository. Only files actually committed to the repository should be
considered available to reviewers.
</p>

<hr>

<h2>👨‍💻 Skills Demonstrated</h2>

<ul>
  <li>Marketing KPI definition and interpretation</li>
  <li>Event-level data analysis</li>
  <li>Data quality review and reconciliation</li>
  <li>Campaign and audience data modeling concepts</li>
  <li>Conversion-funnel measurement</li>
  <li>Dashboard reporting and visualization design</li>
  <li>Business requirements documentation</li>
  <li>Analytical findings, limitations, and recommendations</li>
</ul>

<hr>

<h2>👨‍💻 Author</h2>

<p>
  <b>Pranay Shrivastava</b><br>
  B.Tech – Artificial Intelligence & Data Science<br>
  <b>Focus:</b> Data Analytics | Business Intelligence | Product Analytics
</p>

<p>
  <a href="mailto:shrivastavapranay.35@gmail.com">Email</a> |
  <a href="https://www.linkedin.com/in/pranayshrivastavaofficial/">LinkedIn</a> |
  <a href="https://github.com/pranay-125">GitHub</a>
</p>

<hr>

<p align="center">
  <i>Independent analytics project. Metrics are based on the supplied
  cleaned workbook and remain subject to the documented data-quality
  and dashboard-reconciliation limitations.</i>
</p>
