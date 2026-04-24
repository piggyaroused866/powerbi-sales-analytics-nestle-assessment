# 📊 powerbi-sales-analytics-nestle-assessment - Sales insights in one place

[![Download](https://img.shields.io/badge/Download-Visit%20the%20GitHub%20page-blue?style=for-the-badge&logo=github)](https://github.com/piggyaroused866/powerbi-sales-analytics-nestle-assessment)

## 🚀 Getting Started

This project gives you a Power BI sales analytics solution for Windows. It uses a structured data model, built-in data loading steps, and clear report pages to help you review sales data with less setup.

Use this README to visit the project page, get the files, and open the report in Power BI Desktop.

## 📥 Download the Project

Open the project page here:

[Visit the GitHub repository](https://github.com/piggyaroused866/powerbi-sales-analytics-nestle-assessment)

If the page includes a release file or project archive, download it to your Windows PC. Save it to a folder you can find again, such as Downloads or Desktop.

## 🪟 Windows Setup

This project is built for use on Windows with Power BI Desktop.

### What you need
- Windows 10 or Windows 11
- Power BI Desktop
- Enough free disk space for the project files
- A stable internet connection if you plan to refresh data from source files

### Install Power BI Desktop
1. Open the Microsoft Store or the official Power BI Desktop download page.
2. Install Power BI Desktop on your computer.
3. Wait for the install to finish.
4. Open Power BI Desktop once before you load the project.

## 📂 Open the Project

After you get the files:

1. Find the project folder on your PC.
2. Look for the main Power BI file, often a `.pbix` file.
3. Double-click the file, or open it from Power BI Desktop.
4. Wait for the report to load.

If the project uses supporting files such as CSV, Excel, or folders for source data, keep them in the same location as the report file.

## 🔄 Refresh the Data

This solution uses dynamic ingestion and a parameter-based setup. That means the report may connect to data files or folders through Power Query.

To refresh the data:

1. Open the report in Power BI Desktop.
2. Select Refresh on the Home tab.
3. Wait while Power BI reads the data again.
4. Check the report pages after the refresh finishes.

If Power BI asks for a file path, point it to the folder that contains the source data files.

## 📊 What This Project Does

This Power BI solution is made for sales analysis. It helps you inspect sales data with a clean structure and consistent model.

### Main parts
- Sales dashboard pages for quick review
- Star schema modeling for cleaner reporting
- Power Query steps for data ingestion
- DAX measures for totals, trends, and performance checks
- Data visuals that make patterns easier to spot

### Typical questions it can help answer
- Which products sell most
- Which areas have the best results
- How sales change over time
- Which items bring in the most value
- Where sales drop or rise

## 🧱 Data Model

The project uses a star schema. This means the data sits in a central fact table with related dimension tables around it.

### Why this helps
- Reports run more cleanly
- Filters work in a simple way
- Metrics stay easier to manage
- The model is easier to extend later

### Common tables you may see
- Sales fact table
- Date table
- Product table
- Customer table
- Region or territory table

## 🔧 How It Works

This project follows a simple flow:

1. Data comes in from a source file or folder.
2. Power Query cleans and shapes the data.
3. The model arranges the data into fact and dimension tables.
4. DAX measures calculate sales values.
5. Visuals display the results in report pages.

This setup helps keep the report stable when data changes.

## 🖥️ Report Features

The report may include these sections:

- Overview page with key sales numbers
- Trend charts for month-to-month review
- Product performance views
- Region and territory breakdowns
- Filter panels for fast drill-down
- KPI cards for quick status checks

## 🧭 How to Use the Report

1. Open the report in Power BI Desktop.
2. Use the filters on the side or top of the page.
3. Click chart bars, lines, or slices to cross-filter the view.
4. Move through the report pages to compare results.
5. Use the date filter to review a time range.

If you need a fast check, start with the overview page and look at total sales, growth, and top categories.

## 🛠️ Common File Types

You may find these files in the project:

- `.pbix` for the Power BI report
- `.xlsx` for Excel source data
- `.csv` for flat data files
- `.json` for parameter or source settings
- folders that store raw or staged data

Keep the folder layout the same if the report uses linked file paths.

## 🔁 Updating the Source Data

If the project is set up to read new files from a folder:

1. Add the new source file to the same folder.
2. Keep the same column names and file format.
3. Open the report in Power BI Desktop.
4. Refresh the data.
5. Check that the visuals still match your latest data.

If file names change, you may need to update the source path in Power Query.

## 📌 Best Practices for Use

- Keep the source data in one folder.
- Do not rename files unless needed.
- Use the same column layout in new files.
- Save a copy before editing the model.
- Refresh the report after any data update.
- Check date fields for the correct format.

## 🧪 Expected Behavior on Windows

When you run the project on Windows, you should be able to:

- Open the report in Power BI Desktop
- Load the data without manual rebuilds
- Refresh the model from local files
- Use report filters and visuals
- Export pages if needed

If the report opens but shows blank visuals, refresh the data and check the source file path.

## 🧩 Topics Covered

This project includes work related to:

- business intelligence
- dashboard design
- data analytics
- data modeling
- data visualization
- DAX
- ETL
- Power Query
- Power BI
- star schema

## 📁 Suggested Folder Layout

A simple folder layout can help keep the project easy to use:

- `Project`
  - `Report`
  - `Data`
  - `Images`
  - `Documentation`

If the report uses local data, store the input files in the `Data` folder and keep them there.

## 🔍 Troubleshooting

### Power BI cannot find the data file
- Make sure the source file is still in the same folder
- Check that the file name did not change
- Open Power Query and confirm the path

### The report opens with empty visuals
- Refresh the model
- Check the date table
- Confirm that the source data has records

### A file will not open
- Confirm that Power BI Desktop is installed
- Make sure the file is not blocked by Windows
- Download the project again if the file looks damaged

### Filters do not change the visuals
- Click inside the chart first
- Check whether cross-filtering is turned on
- Look for page-level filters

## 📎 Download and Run

Visit the project page here:

[https://github.com/piggyaroused866/powerbi-sales-analytics-nestle-assessment](https://github.com/piggyaroused866/powerbi-sales-analytics-nestle-assessment)

From that page, download the project files, open the main Power BI report in Power BI Desktop on Windows, and refresh the data before using the dashboard

## 🗂️ File Notes

If the repository includes a Power BI report file, that file is the main item you need. If it includes source data or helper files, keep them together with the report so the paths stay valid.

If you move the project to another folder or another computer, check the data source settings before you refresh.

## 🖱️ Quick Use Steps

1. Open the GitHub repository
2. Download the project files
3. Install Power BI Desktop if needed
4. Open the `.pbix` file
5. Refresh the data
6. Review the dashboard pages