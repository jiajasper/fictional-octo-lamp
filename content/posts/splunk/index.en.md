---
title: "myWizard - interactive data visualization tool"
date: 2019-03-01T14:10:27+01:00
weight: 5
description: "Tech Consulting Work Experience @ Accenture"

categories: ["Splunk", "SQL", "Data Visualization", "Front-end", "Agiie", "A/B Testing"]
featuredImage: "/images/splunk/splunk.jpg"
---
myWizard is an interactive, real-time data visualisation tool to automate and monitor supply chain IT operation.
## Intro

The selected work is a collection of 10+ interactive live data visualization dashboards from Accenture's myWizards AIOps package. The interactive dashboards improve the transparency and efficiency of the supply chain IT operations at Coles Supermarket Australia. It is made with Splunk Processing Language and custom frontend codes.

*Please keep in mind that I am not allowed to show this project in greater details, the graphical materials are mostly renders based off the working prototypes.

## Role + Process

![](/images/splunk/splunk-2.jpg )

To synthesize ambiguous business requirements and provide effective solutions through design, my role was to:

• Pinpoint user pain points and create user stories

• Design features and visuals

• Develop working prototypes

• Work with back-end architects for User Acceptance Testing

• Create hand-over document for deployment and maintenance


The team worked in an agile and cross-disciplinary environment; the diagram shows my design and development process for each sprints.

![](/images/splunk/splunk-4.jpg "Ideation and wireframes")

## Challenges

![](/images/splunk/splunk-3.jpg)

A Splunk dashboard usually consists of multiple data visualisation panels and each visualisation requires its unique custom query to achieve. Other than honing my skills writing advanced queries to process and visualise complex machine data sets to help the clients, there are many other technical challenges that I faced, namely:


• Data Structuring:

Raw machine data is not usable - it needs to be properly structured to build a scalable and easily maintainable product.

• Search Speed: 

Raw machine data sets are large which makes the load-up speed slow

• Usability and Readability: 

Can the users find their desired information efficiently? can the user make further investigation as needed?

## Solutions

![](/images/splunk/splunk-1.jpg)

To overcome the technical obstacles mentioned above, the following solutions were adopted.


• Regular Expressions (RegEx): 

To extract fields and give them structured format - this also convert machine data into human-readable terms (eg. epoch time coversion).

• CSV lookup files: 

Instead of using index search (which is includes all real time data), use scheduled saved search to output csv lookup files that include intended fields only.

• Prioritizing counts and trendlines: 

To enable users understand the situation at a quick glance. The dashboards were designed in a top-down structure,to make sure all essential info is displayed on-load without needing to scroll down.

• Tokens: 

To give the users the options to filter, drill-down and direct to their internal IT support page.

![](/images/splunk/splunk-5.jpg "Information Architecture")


## Impacts

{{< youtube F8WXKCA5bhg >}}

We slowly started the deployment of our dashboards for client to use and test at the same time. The reviews from them were positive and we made significant impacts to their daily workflow:

✓ Successfully freed the clients from doing repetitive data consolidating work on a daily basis

✓ Provided a one-stop solution for IT support team for live monitoring,forecasting and in-depth investigation

✓ Improved the transparency between IT and business operation by live feeding information that was not available or was only available to IT team

✓ Since the dashboards were developed with maintainability in mind,the codes were easily modified into a versatile template for future projects

Hard work eventually paid off! The dashboards we developed were included in a bigger application package and the whole project was a huge success!
