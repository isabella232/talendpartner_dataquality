<h1 style="padding-bottom:0px;color:#76678b;font-weight:500">Talend Data Quality Block</h1>
<p style="font-weight: 300">
</p>
<h2 style="padding-bottom:0px;color:#76678b;font-weight:500">Why Use This Block?</h2>
<p style="font-weight: 300">
This block will accelerate your efforts to create a Business Data Quality dashboard using the Talend DQ Data Mart.
</p>
<h2 style="padding-bottom:0px;color:#76678b;font-weight:500">Logical Architecture</h2>
<p style="font-weight: 300">
The below Logical Architecture highlights how data is sent to Talend Data Quality, which executes business rules, and the DQ metrics from these executions are stored in Snowflake DQ Mart, and finally Looker is used to produce DQ Dashboards.
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)
</p>
<h2 style="padding-bottom:0px;color:#76678b;font-weight:500">Business Dashboard</h2>
<p style="font-weight: 300">
The business dashboard will provide a view across the 6 DQ dimensions: <br>
a.      Completeness<br>
b.      Timeliness<br>
c.      Validity<br>
d.      Accuracy <br>
e.      Consistency<br>
f.       Uniqueness 
</p>
<h2 style="padding-bottom:0px;color:#76678b;font-weight:500">Talend Concepts</h2>
<p style="font-weight: 300">
In Talend Studio, within the Profiling perspective, use **Analysis** to create a Data quality rule, and then use **Report** to group all rules that should by logically together – i.e. by Department, Function or Regulation.<br><br>
When the Report is executed it populates the DQ Mart.
</p>

<p style="font-weight: 300">
<strong><a href = "/dashboards/thelook/business_pulse" style="text-decoration:underline">The Business Pulse Dashboard</a></strong> provides a highly manicured executive summary of the current status of the business. Interactive filtering and drilling within the dashbaord provide a curated, interactive experience for users with limited data skills to ask and answer questions based on patterns and trends in the data in real time.
 </p>
 <p style="font-weight: 300">
 <strong><a href = "/explore/thelook/order_items" style="text-decoration:underline">Looker's explore section</a></strong> provides an easy-to-use, flexible interface for self-service exploration to answer any question from your data without having to involve IT. Regardless of their level of SQL knowledge, analysts and business users alike have the power and depth of the entire database at their fingertips to easily answer ad-hoc questions and quickly build visualizations, dashbaords, and automated reports. Looker's 100% browser based workflow enables fast and easy collaboration and sharing.
</p>
<p style="font-weight: 300">
<strong><a href = "/projects/welcome_to_looker/files/thelook.model.lkml" style="text-decoration:underline">The LookML data model</a></strong> is the backbone of Looker, providing a platform to define key metrics once, in one place, so people from across the organization combine them in any number of ways, anytime.
</p>

<h1 style="padding-bottom:0px;color:#76678b;font-weight:500">Connecting to your own data set</h1>

<p style="font-weight: 300">
Looker can connect to any SQL-compliant database for you to build out a demo environment of your own, or build proof-of-concept analyses for your customers.
</p>

<p style="font-weight: 300">
<strong>1.</strong> Connect to your database follow the instructions <a href = "http://www.looker.com/docs/admin/looker-hosted" style="text-decoration:underline">here</a> to establish a connection between Looker and your database
</p>

<p style="font-weight: 300">
<strong>2.</strong> Create a new LookML project using the LookML generator. Instructions <a href = "http://www.looker.com/docs/data-modeling/getting-started/connect-to-db-and-generate-model" style="text-decoration:underline">here</a>
</p>


<h1 style="padding-bottom:0px;color:#76678b;font-weight:500"><strong>Next: </h1>
<h1 style="padding-bottom:0px;color:#76678b;font-weight:500"><a href = "/stories/welcome_to_looker/2_lookml_101.md" style="text-decoration:underline">Looker 101 - Developing with LookML</strong><a></h1>
<h1 style="padding-bottom:0px;color:#76678b;font-weight:500"><a href = "/stories/welcome_to_looker/3_business_analyst_101.md" style="text-decoration:underline">Exploration, Visualizations, and Dashboards</strong><a></h1>
