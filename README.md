<h1 align="center">📊 Meta Advertising &amp; Funnel Analytics</h1>

<p align="center">
  <b>Independent Data Analytics Portfolio Project</b><br>
  Marketing KPIs · Funnel Analysis · Data Quality · Business Insights
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Domain-Marketing%20Analytics-blue" alt="Marketing Analytics">
  <img src="https://img.shields.io/badge/Tools-Excel%20%7C%20Power%20BI-orange" alt="Tools">
  <img src="https://img.shields.io/badge/Focus-KPI%20Analysis%20%7C%20Data%20Storytelling-green" alt="Project Focus">
</p>

<hr>

<h2>📌 Project Overview</h2>

<p>
This independent project analyzes advertising event data modeled around Facebook and Instagram campaigns. It examines impressions, clicks, engagement events, purchases, campaign budgets, and available audience attributes to understand how advertising activity can be measured and reported through consistent KPIs.
</p>

<p>
The analysis uses four related datasets: <code>ad_events</code>, <code>ads</code>, <code>campaigns</code>, and <code>users</code>. Supporting materials include business requirements, domain documentation, dashboard insights, and a project presentation.
</p>

<p><b>Project type:</b> Independent portfolio project; not an official Meta project or commercial deployment.</p>

<hr>

<h2>🎯 Business Problem</h2>

<p>
Impressions and clicks alone do not describe the complete purchase-related journey. This project organizes advertising activity into measurable KPIs to examine reach, engagement, purchase-related event ratios, and campaign-budget allocation.
</p>

<h3>Key Questions</h3>
<ul>
  <li>How many impression, click, engagement, and purchase events are recorded?</li>
  <li>What are the relationships between impressions, clicks, and purchase events?</li>
  <li>How can campaign performance be compared using consistently defined KPIs?</li>
  <li>What data-quality issues could affect reporting accuracy?</li>
</ul>

<hr>

<h2>📈 Key Metrics</h2>

<p>
The following figures were recalculated from the supplied cleaned Excel workbook. Event counts represent recorded events, not unique users.
</p>

<table border="1" cellpadding="8" cellspacing="0" width="100%">
  <tr>
    <th>KPI</th>
    <th>Value</th>
    <th>Calculation</th>
  </tr>
  <tr>
    <td>Impressions</td>
    <td><b>339,812</b></td>
    <td>Count of impression events</td>
  </tr>
  <tr>
    <td>Clicks</td>
    <td><b>40,079</b></td>
    <td>Count of click events</td>
  </tr>
  <tr>
    <td>Purchases</td>
    <td><b>2,031</b></td>
    <td>Count of purchase events</td>
  </tr>
  <tr>
    <td>Click-Through Rate (CTR)</td>
    <td><b>11.79%</b></td>
    <td>Clicks ÷ impressions × 100</td>
  </tr>
  <tr>
    <td>Purchase-to-Click Event Ratio</td>
    <td><b>5.07%</b></td>
    <td>Purchases ÷ clicks × 100</td>
  </tr>
  <tr>
    <td>Purchase-to-Impression Event Ratio</td>
    <td><b>0.60%</b></td>
    <td>Purchases ÷ impressions × 100</td>
  </tr>
  <tr>
    <td>Total Campaign Budget</td>
    <td><b>$2,535,923.78</b></td>
    <td>Sum of campaign budget values</td>
  </tr>
  <tr>
    <td>Campaign Records</td>
    <td><b>50</b></td>
    <td>Count of campaign records in the cleaned workbook</td>
  </tr>
</table>

<p>
<b>Metric interpretation:</b> These are ratios of event counts. They should not be interpreted as verified unique-user conversion rates or proof that purchases were caused by specific advertising interactions.
</p>

<p>
<b>Engagement definition:</b> The inclusive engagement calculation (58,157 events; 17.11% of impressions) includes clicks, likes, shares, and comments. The original business requirements document defines engagement without likes. Therefore, this metric requires a consistent definition before being treated as a final standardized KPI.
</p>

<hr>

<h2>🔍 Analysis &amp; Findings</h2>

<ul>
  <li><b>Reach and click activity:</b> Recalculated impression and click counts to establish an event-count CTR of 11.79%.</li>
  <li><b>Purchase-related analysis:</b> Compared purchase events with click and impression counts to describe the observed funnel ratios.</li>
  <li><b>Campaign-budget analysis:</b> Summarized budget allocation across 50 campaign records.</li>
  <li><b>Data-quality review:</b> Identified inconsistencies in event labels, missing values, unmatched user identifiers, and differences between raw and cleaned ad-record counts.</li>
</ul>

<hr>

<h2>📊 Dashboard Reference</h2>

<p align="center">
  <img width="100%" alt="Reference screenshot of the Meta Advertising and Funnel Analytics dashboard" src="https://github.com/user-attachments/assets/a0c4a0b7-6980-428e-b9bd-296763e415e7">
</p>

<p>
The reference image illustrates a dashboard layout with KPI cards, audience charts, geographic analysis, time-based visuals, an ad-format comparison, and filter controls.
</p>

<p>
<b>Reproducibility note:</b> The original editable Power BI file was not available in the materials reviewed. The screenshot demonstrates the intended reporting layout, but interactive behavior, underlying DAX measures, and model relationships have not been independently verified. Its displayed totals also differ from the recalculated workbook figures.
</p>

<hr>

<h2>🧹 Data Quality &amp; Limitations</h2>

<ul>
  <li>The cleaned workbook contains 400,000 event rows.</li>
  <li>Raw event labels contain capitalization and whitespace inconsistencies that require standardized classification.</li>
  <li>Missing event fields and unmatched user identifiers may affect time-based and audience analyses.</li>
  <li>The raw ads file contains 230 records, compared with 200 ad records in the cleaned workbook; the reason for this difference has not been established.</li>
  <li>Engagement definitions differ between the original requirements document and the inclusive recalculation shown above.</li>
  <li>Dashboard screenshot totals have not been reconciled with the cleaned workbook.</li>
</ul>

<hr>

<h2>🛠️ Tools &amp; Analytical Concepts</h2>

<ul>
  <li><b>Excel:</b> Tabular data inspection and KPI recalculation.</li>
  <li><b>Power BI:</b> Dashboard visualization and reporting concepts represented by the supplied screenshot.</li>
  <li><b>Business Analysis:</b> Problem definition, analytical questions, and requirements documentation.</li>
  <li><b>KPI Analysis:</b> Formula definition, denominator selection, and metric interpretation.</li>
  <li><b>Data Quality:</b> Identification of missing values, inconsistent labels, and record-count discrepancies.</li>
</ul>

<hr>

<h2>💡 Business Recommendations</h2>

<ul>
  <li>Standardize KPI definitions and maintain a documented metric dictionary.</li>
  <li>Reconcile source records and validate event-to-user relationships before drawing audience conclusions.</li>
  <li>Compare advertising formats only when reporting periods, filters, and denominators are consistent.</li>
  <li>Validate purchase attribution before making claims about conversion effectiveness or return on advertising spend.</li>
</ul>

<hr>

<h2>👨‍💻 Author</h2>

<p>
  <b>Pranay Shrivastava</b><br>
  B.Tech — Artificial Intelligence &amp; Data Science
</p>

<p>
  <a href="mailto:shrivastavapranay.35@gmail.com">Email</a> |
  <a href="https://www.linkedin.com/in/pranayshrivastavaofficial/">LinkedIn</a> |
  <a href="https://github.com/pranay-125">GitHub</a>
</p>

<p align="center">
  <i>Independent analytics portfolio project. Figures are based on the supplied cleaned workbook and are subject to the limitations documented above.</i>
</p>
