# AtliQ Hardware Data Analytics Project

## Project Overview

AtliQ Hardware is implementing data analytics using Power BI to enhance decision-making across finance, sales, marketing, and supply chain operations. This project aims to provide actionable insights to stakeholders and improve competitive positioning in the market.

## Live Report Link

[Link to Live Report](https://app.powerbi.com/view?r=eyJrIjoiMzFiYjlhNWItZGQzZC00MTY3LWE4MWYtNzQxYTkwM2NmMzg5IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

## Tech Stacks and Techniques

- **SQL**
- **Power BI Desktop**
- **Excel**
- **DAX Language**
- **DAX Studio** (for optimizing reports)
- **Project Charter File**

## Business Related Terms

- **Gross price**: Total price before deductions.
- **Pre-invoice deductions**: Deductions applied before issuing an invoice.
- **Post-Invoice deductions**: Deductions applied after issuing an invoice.
- **Net Invoice sale**: Final sale amount after deductions.
- **Gross Margin**: Revenue minus COGS, expressed as a percentage.
- **Net sales**: Total sales revenue after deductions.
- **Net profit**: Total revenue minus all expenses.
- **COGC (Cost of Goods Sold)**: Cost incurred in production or acquisition of goods sold.
- **YTD (Year to Date)**: Financial performance from the beginning of the year up to the present date.
- **YTG (Year to Go)**: Forecasted financial performance for the remainder of the year.
- **Direct**: Sales directly to end-users.
- **Retailer**: Sales through retail partners.
- **Distributors**: Sales through distribution channels.
- **Consumer**: End-users who purchase products.

## Company Background

AtliQ Hardware has expanded globally, specializing in the sale of computers and accessories through retailers, direct sales, and distributors. Despite recent challenges, including unexpected losses from a new store opening in America, the company aims to strengthen its analytics capabilities to thrive in a competitive market.

## Project Kick-off

### Questions to Ask Before Starting with Dashboard

1. **Objective**: What is the main goal of building this Power BI dashboard?
2. **Success Metrics**: How will the success of this project be measured?
3. **Timeline**: What is the deadline for completing the project?
4. **Preview Expectations**: Do stakeholders expect a preview before the official release?
5. **Stakeholder Hopes**: What are stakeholders' expectations and desired outcomes from this project?
6. **Stakeholder Concerns**: What are stakeholders' fears or concerns regarding the dashboard's development?
7. **Users**: Who will be using this dashboard and for what purposes?
8. **Expectations**: What do stakeholders expect to achieve once this project is completed?
9. **Potential Challenges**: What are potential risks or challenges that may arise during the project?
10. **Resources**: What resources and data are required to build this dashboard?
11. **Stakeholder Input**: Have stakeholders provided any inputs regarding the design and views of the dashboard?

### Dataset Understanding

Before diving into analysis, it's crucial to understand the available data:

- **Dimension Table**: Contains static data such as customer and product details.
- **Fact Table**: Contains transactional data.
- **gdb041**: Details markets, customers, platforms, and channels.
- **gdb056**: Includes cost details for different markets and fiscal years.
- **Forecast Tables**: Used for predicting customer needs and optimizing warehouse costs.
- **Importing Data**: Data from MySQL databases is imported into Power BI using provided credentials.

## Data Model

Data modeling plays a vital role and is considered as the foundation of our reports. All visualizations are built upon this model, and adhering to good data modeling practices is crucial for performance and accuracy. We follow the Snowflake data modeling method for effective structure and efficiency.

## Dashboard Designing

Our dashboard design process begins with mockups tailored to project requirements. The team iterates on these designs, implementing measures and refining visuals as needed.

### Views Overview

#### Home View

The Home view acts as the central hub, featuring navigation buttons to access specific views:

- **Info**
- **Finance View**
- **Sales View**
- **Marketing View**
- **Supply Chain View**
- **Executive View**
- **Products**

Users can seamlessly navigate between these views to explore detailed insights across different business functions.

