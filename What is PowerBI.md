# Power BI concepts
The major building blocks of Power BI are: datasets, reports, and dashboards. They are all organized into workspaces, and they are created on capacities.

##### 1. Microsoft Power BI is a collection of software services, apps, and connectors that work together to turn your unrelated sources of data into coherent, visually immersive, and interactive insights.

##### 2. Leveraging Power BI and other Microsoft technologies can lead to significant returns in terms of not only revenue, but your business users' ability to make beneficial decisions.

##### 3. Power BI is built on Azure, Microsoft's cloud computing infrastructure and platform, ensuring your data is secure and only accessible by authenticated users.

## Datasets
A dataset is a collection of data that you import or connect to. Power BI lets you connect to and import all sorts of datasets and bring all of it together in one place. Datasets can also source data from dataflows.

## Shared Datasets
Business intelligence is a collaborative activity. It's important to establish standardized datasets that can be the 'one source of truth.' Discovering and reusing those standardized datasets is key. When expert data modelers in your organization create and share optimized datasets, report creators can start with those datasets to build accurate reports. Your organization can have consistent data for making decisions, and a healthy data culture. To consume these shared datasets just choose Power BI datasets when creating your Power BI report.

## Reports
A Power BI report is one or more pages of visualizations such as line charts, maps, and treemaps. Visualizations are also called visuals. You can create reports from scratch within Power BI, import them with dashboards that colleagues share with you, or Power BI can create them when you connect to datasets from Excel, Power BI Desktop, databases, and SaaS applications. For example, when you connect to an Excel workbook that contains Power View sheets, Power BI creates a report based on those sheets. And when you connect to a SaaS application, Power BI imports a pre-built report.

## Data modeling and visualizations
Power BI Desktop is a free application you install on your local computer that lets you connect to, transform, and visualize your data. With Power BI Desktop, you can connect to multiple different sources of data, and combine them (often called modeling) into a data model. This data model lets you build visuals, and collections of visuals you can share as reports, with other people inside your organization. Most users who work on business intelligence projects use Power BI Desktop to create reports, and then use the Power BI service to share their reports with others. When you launch Power BI Desktop, the Getting Started dialog box will appear, which provides useful links to forums, blogs, and introductory videos.

In Power BI Desktop, you will begin to build reports in the Report view. You will be working in five main areas:
![image](https://user-images.githubusercontent.com/52828894/190334173-bfe3c2a2-afba-45ab-98ed-653abc49c016.png)

1. Ribbon - Displays common tasks that are associated with reports and visualizations.

2. Report view, or canvas - Where visualizations are created and arranged.

  a) The Data view allows you to view all of your data available in your report. This is an easy way to quickly check data types and validate data.

  b) The Model view allows you to visually set the relationship between tables or elements. A relationship is where two or more tables are linked together because they contain related data. This enables users to run queries for related data across multiple tables.

3. Pages tab - Located along the bottom of the page, this area is where you would select or add a report page.

4. Visualizations pane - Where you can change visualizations, customize colors or axes, apply filters, drag fields, and more.

5. Fields pane - Where query elements and filters can be dragged onto the Report view or dragged to the Filters area of the Visualizations pane.

# Bar and column charts
Bar charts are the standard for looking at a specific value across different categories.
![image](https://user-images.githubusercontent.com/52828894/190335024-df2b3b74-a720-4a5c-bfe0-6413b30b3a84.png)
![image](https://user-images.githubusercontent.com/52828894/190335109-0428a76d-ecf0-4af9-b155-c4b2bbca00ca.png)

## Cards: Single or Multi row
![image](https://user-images.githubusercontent.com/52828894/190335467-2d839dfd-ca4d-47ce-8b70-2ef7841bea9c.png)

## KPIs
Displays progress toward a measurable goal.

![image](https://user-images.githubusercontent.com/52828894/190335524-2a8bac02-b74a-483d-922b-7e73458c62ca.png)

## Maps: Basic maps
Used to associate both categorical and quantitative information with spatial locations.

![image](https://user-images.githubusercontent.com/52828894/190335611-d3ae5696-15f4-4c13-bd2a-ab7205c48028.png)

## Pie charts
Pie charts show the relationship of parts to a whole.

![image](https://user-images.githubusercontent.com/52828894/190335678-a39be4ce-5784-4a2d-9ff1-0ff2f3628c1a.png)


## Q&A visual
The Q&A visual lets you ask questions about your data using natural language.

![image](https://user-images.githubusercontent.com/52828894/190335733-37999dd6-932b-4378-8555-58227cdc96a3.png)

## Tables
Work well with quantitative comparisons among items where there are many categories. These are some of the out-of-the-box Power BI visuals available from the visualization pane in Power BI Desktop and Power BI Service. However, sometimes you need a more custom visual and these can be found in AppSource for Power BI.

![image](https://user-images.githubusercontent.com/52828894/190336024-bc4c59c9-4f2d-4b6c-817f-1ca3de42f588.png)

## Filter data with Power BI
Data is the core of Power BI. As you explore reports, each visual draws its underlying data from sources that often contain far more data than you need. Power BI offers several ways to filter and highlight reports. Knowing how to filter data is the key to finding the right information.

## Slicers
A simple type of filtering that you can use directly on the report page is called a slicer. Slicers provide cues to ways you can filter the results in the visuals on a report page. There are several different types of slicers: numeric, categorical, and date. Slicers make it easy to filter all the visuals on the page at once.

![image](https://user-images.githubusercontent.com/52828894/190336731-b1a862bb-54a9-4901-89f8-f0409b6a6271.png)

## Explore the Filters pane
Another way to filter data is by opening and modifying filters in the Filters pane. The Filters pane contains filters that were added to the report by the report designer. As a consumer, you can interact with the filters and save your changes but cannot add new filters.

The four types of filters are:

1. Report – Applies to all pages in the report.
2. Page – Applies to all the visuals on the current report page.
3. Visual – Applies to a single visual on a report page. You only see visual level filters if you have selected a visual on the report canvas.
4. Drillthrough – Allows you to explore successively more detailed views within a single visual.

## Use buttons in Power BI
Using buttons in Power BI lets you create reports that behave like apps, and thereby, create an engaging environment so users can hover, click, and further interact with Power BI content. You can add buttons to reports in Power BI Desktop and in the Power BI service. When you share your reports in the Power BI service, they provide an app-like experience for your users.

To create a button in Power BI Desktop, on the Insert ribbon, select Buttons and a drop-down menu appears, where you can select the button you want from a collection of options, as shown in the following image.

![image](https://user-images.githubusercontent.com/52828894/190337116-21e469e7-ac5f-4ca9-af34-e0353fcdfdf6.png)

## Transform data
Sometimes, your data might contain extra data or have data in the wrong format. Power BI Desktop includes the Power Query Editor tool, which can help you shape and transform data so that it's ready for your models and visualizations.
![image](https://user-images.githubusercontent.com/52828894/190337434-ae7b3d0a-d330-4fb7-9266-61555058dd6d.png)


https://sankalptaru.org/tree/TcLUfL/
