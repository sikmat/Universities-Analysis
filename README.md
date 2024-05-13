# Power BI

## Describe the Capabilities of MS Power BI

### Explore the different Power BI Elements

**Capacities**
Capacities are a core Power BI concept representing a set of resources used to host and deliver your Power BI content. Capacities are either shared or dedicated. A shared capacity is shared with other Microsoft customers, while a dedicated capacity is fully committed to a single customer. Dedicated capacities require a subscription. By default, workspaces are created on a shared capacity.

**Workspaces**
Workspaces are containers for dashboards, reports, datasets, and dataflows in Power BI. There are two types of workspaces: My workspace and workspaces. Semantic models are associated with workspaces and a single semantic model can be part of multiple workspaces

**Semantic models**
A semantic model is a collection of data that you import or connect to. Consists of all connected data, transformations, relationships, and calculations.

**Shared semantic models**
Business intelligence is a collaborative activity. It's important to establish standardized semantic models that can be the 'one source of truth.' Discovering and reusing those standardized semantic models is key

**Reports**
A Power BI report is one or more pages of visualizations such as line charts, maps, and other elements. You can create reports in Power BI from scratch, import them from shared dashboards, or have Power BI generate them when connecting to datasets. 

**Dashboards**
A dashboard is a single canvas that contains zero or more tiles and widgets. Each tile pinned from a report or from Q&A displays a single visualization that was created from a dataset and pinned to the dashboard.

Why do people create dashboards? Here are just some of the reasons:
- To see all information needed to make decisions in one glance.
- To monitor the most important information about your business.
- To ensure all colleagues are on the same page, viewing and using the same information.
- To monitor the health of a business, product, business unit, or marketing campaign, etc.
- To create a personalized view of a larger dashboard and show all the metrics that matter to them.

**Template Apps**
Power BI template apps enable Power BI partners to build Power BI apps with little or no coding and deploy them to any Power BI customer. As a Power BI partner, you create a set of out-of-the-box content for your customers and publish it yourself.


## Describe cleaning and transforming data in Power BI Desktop
To begin transforming and cleaning data, you use the Power BI Desktop application.

Power BI Desktop has three views:
- Report view: You can create queries to build compelling visualizations that you can share with others. You can arrange them as you want them to appear.
- Data view: See the data in your report in data model format, where you can add measures, create new columns, and manage relationships.
- Model view: Get a graphical representation of the relationships that are established in your data model and manage or modify them as needed.

_Power BI Desktop includes the Power Query Editor tool, which can help you shape and transform data so that it's ready for your models and visualizations._

**Transforming data**
Transforming data is the process of putting data into a format that is useable in your reports. 

**Clean data**
While Power BI can import your data from almost any source, its visualization and modeling tools work best with columnar data. Sometimes, your data isn't formatted in simple columns, which is often the case with Excel spreadsheets.

### Describe using AI Insights to spot trends and anomalies
Power BI’s insights feature helps organizations easily identify insights such as anomalies and trends in your data as you interact and consume elements such as reports, dashboards, and visualizations. It notifies you if there are interesting insights and provides explanations for them. It works out-of-the-box on any report, so you can automatically start getting insights from your reports without any setup.

**Power BI has multiple insights features that use artificial intelligence (AI):**
- Insights for reports: Analyzes data and finds anomalies and trends in your data as you interact with reports.
- Insights for individual visuals: Analyzes and explains the fluctuations of data points in visuals.
- Insights for dashboard tiles: Looks at the data being used to render that tile and presents them in interactive visuals.
- Quick Insights for datasets: Automatically generate data insights on a dataset in the Power BI service.
- AI Insights for data models in Power Query: Provide access to pretrained machine learning models from Azure Cognitive Services.

**Notifications**
Notifications are an important part of the Insights capabilities in Power BI. As you're working on Power BI elements such as reports, Power BI automatically runs insights analysis. When Power BI identifies insights, you're presented with a notification

**Insights**
The Insights pane currently shows three types of insights:
**Anomalies**: Represents something that is out of the ordinary from what is expected. For example, a smart thermostat that suddenly reads the temperature as 100 F when it's typically 72 F would be considered an anomaly.
- Significant
- Recent
- Anomaly summary

**Trends**: Represents a pattern that is found in time-series datasets. For example, if a company’s sales are steadily increasing through the month of April that would represent a trend.
- Long
- Steep
- Recent
- Trend reversal

**Key Performance Indicator (KPI) analysis**: Helps you evaluate the current value against a defined target. For example, a company might set a sales goal at 1.2 million, but currently they are at 1 million.
KPI analysis with a target looks at the variance of the current value to its target. It's considered significant if the variance is high or low compared to other segments. KPI analysis without a target looks at the value itself and flags ones that are high or low compared to other segments. Power BI looks for and identifies the categories that have higher or lower than anticipated values.

### Build a basic dashboard
- **Prepare your data**: Preparing the data ensures that it's in a format that Power BI can easily consume.
-** Build a report**: The report contains the visuals that you want to include in your dashboard. Depending on the scenario, reports can be built in either Power BI Desktop or using the Power BI Service.
- **Pin the report visuals to a dashboard**: Dashboards are the primary element that users use for viewing data. They can include data from multiple reports as needed.
- **Share a link to the dashboard**: Any users with the link and the necessary permissions are easily able to view and interact with the data.

**Prepare the data**
The first thing you need to do is ensure that your data is ready to be consumed. Depending on the data source and the volume of data you're working with, you may need to do some data cleansing and transforming using Power Query

**Upload your data to the Power BI service**
**Build your report**
**Pin to dashboard**
**Share a link to dashboard**

### Consider the business value of Power BI
It's now common knowledge that data can improve business processes and increase revenue
- By analyzing their data in Power BI, the Miami Heat operations team has been able to increase revenue, but also improve the allocation of resources by predicting customer behavior. “Using Power BI and the entire Azure data platform, we can predict attendance for all 44 games of the season within hours of the schedule being released,”













# PowerBI
Building blocks of PowerBI
- **Semantic** - consists of all connected data, transformations, relationships, and calculations.
- **Vizualizations** - when you create a visualization (also called visual), you add it to the canvas for a report page

### Create a dashboard
Dashboards consist of a single page made up of tiles. Add tiles to a dashboard by pinning a visual in a report to the dashboard. Tiles aren't interactive like visuals, so when a user interacts with the tile, they go to the underlying report for more information.

_To recap, the building blocks of Power BI are semantic models and visuals. Using Power BI Desktop, you create the semantic model and use visuals to create reports.

In the Power BI service, you can distribute content to your consumers and use reports to create dashboards._

### Organize items with workspaces
Workspaces are the foundation of the Power BI service. When publishing any report, you must choose a workspace. By default, every user has access to My workspace, which is ideal only for testing. When you want to share content with others, always create and use a shared workspace.
