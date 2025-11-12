#SFWealthApp
===========

The SFWealth demo shows how details of your personal spending habits can be made available through dashboards, drilldown and interactive statements. This demo could be shown to prospects that require great looking customer-facing content that can be made interactive. Heavy use of our BIRT Data Object hierarchy is used in drilldown scenarios within various dashboards. The interactive capabilities of the beautifully crafted billing statement is a big differentiator. This demo helps our prospects see how interactive our dashboards and report content can be.

Personal Finance Management, Wealth Management, Portfolio Statements. 

To install the demo if it is not on your system:

   The subfolder "Composition" contains the files necessary to build out the localized version of the SF Wealth Credit Card Statement.
   The run the report, you will need to make sure mySQL is running.
   Import all the .sql statements into mySQL under the sql subfolder.
   Install the fonts located in the Fonts subfolder. (These support the barcodes)  (To install fonts, open a windows explorer, peruse to the directory containing the fonts and double click.  The font installer will then prompt you to ask if you want to install the fonts.
   Install the rotated tex.jar file into the bdpro\eclipse\plugin folder and ihub\eclipse\plugin folders
   Upload the new alertHTML.rptdesign and alertHTML.rptdocument into the Report Design folder
   Upload the My Personal Wealth.DASHBOARD file to the dashboard folder.

Dan Morris is the first user that appears in the drop down if you run the report.
If you want to generate a new .pdf file, be sure mySQL is running.

## Core Intelligence Aviator in SF Wealth Demo  
A Portfolio Performance aviator was added to the demo (11/13/2025) on the dashboard's Portfolio Performance tab alongside the report. 

**Aviator Resource Deployment**  
In Core Intelligence's Information Console:  
- deploy Portfolio Performance.aviator and Portfolio Performance.datadesign into Resources | UserData | tm-demouser@opentext.com folder  
- deploy PortfolioPerformance.csv, PortfolioPerformanceDetail.csv and PortfolioPerformanceRatReturn.csv into Resources | data folder (CSV files can be found in the data folder of this version control repository)  
