# Rajagiri-Business-School-Cost-Management-Analysis-Dashboard_PowerBI
This project is an interactive Power BI dashboard that applies cost management accounting principles to the audited financial statements of Rajagiri Business School. The dashboard provides a clear, interactive view of the institution's financial health, with a specific focus on calculating and visualizing income and expenditure per student.


**The Business Challenge**

The core challenge was to analyze raw, static financial statements to derive meaningful insights. Traditional financial documents like balance sheets and income statements are often difficult to navigate and don't readily provide per-unit metrics, such as income or expense per student. The goal was to transform this static data into a dynamic tool that could:

Provide a clear overview of the college's financial position.

Break down income and expenses by category.

Calculate and visualize the key metric of income and expenditure on a per-student basis.

Enable easy exploration of financial data to understand key cost drivers and revenue streams.

**Project Goal & Methodology**

This project was developed as a class assignment for a cost management accounting course. The primary objective was to apply theoretical knowledge to a real-world scenario by creating a practical financial analysis tool. The methodology involved an end-to-end data pipeline:

Data Sourcing: Audited Financial Statements (FS) of Rajagiri Business School were downloaded from their official website.

Data Extraction & Cleaning: Large Language Model (LLM) tools were used to parse the raw Balance Sheet (BS) and Income Statement from the financial documents. The extracted data was then converted into a structured Excel file. This data was subsequently cleaned and formatted to ensure accuracy and consistency for analysis.

Analysis & Visualization: The cleaned data was loaded into Power BI. A detailed data model was created to connect the Balance Sheet and Income Statement. The dashboard was then built to visualize key financial metrics and, most importantly, calculate and display the income and expenditure per student, broken down by individual line items.

**Dashboard Walkthrough**

<img width="1109" height="616" alt="image" src="https://github.com/user-attachments/assets/d785f48b-ecf3-491b-8482-423e18cf6dc9" />

The dashboard is structured into two main pages, each designed to provide a different level of financial insight. The first page is the Balance Sheet page, which shows categories and items, along with their corresponding amounts. This page includes slicers for Assets, Liabilities, and Year, allowing for interactive exploration of the college's financial position.

<img width="1108" height="634" alt="image" src="https://github.com/user-attachments/assets/7745f2b3-4a2a-4b6d-8a9a-47fec4d01455" />

The second page focuses on cost management, specifically detailing income per student and expenditure per student. It provides an interactive feature where a user can select a specific line item to find its per-student amount. This page also includes slicers for Year, which enables a dynamic analysis of how these key metrics change with student enrollment and over different financial periods.
