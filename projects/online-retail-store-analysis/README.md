![Online Retail dashboard](../../images/Retail%20Dashboard%20Edit.png)

# Online Retail Store Analysis

**Revenue Leakage & Retail Performance**

This project analyses online retail transactions from **December 2010 to December 2011**, with a focus on sales performance and revenue leakage caused by returns and cancellations.

## Business question

The analysis goes beyond headline revenue to ask:

- How much revenue did the business generate?
- How much revenue was lost through returns and cancellations?
- Which products generated the most revenue?
- Which products were returned most?
- Which countries contributed the most revenue?
- Which months and quarters performed best?

## Data preparation

The dataset contains invoice number, product description, quantity, invoice date, unit price, customer ID and country.

The cleaning process:

- Preserved transactions with missing Customer IDs because they remained useful for sales analysis.
- Separated negative quantities into a dedicated return/cancellation analysis.
- Reviewed unusual product descriptions.
- Investigated zero-price transactions.
- Created Month, Quarter and Year fields for time analysis.

## Key results

- Approximately **£13.2M revenue** from more than **540,000 transactions**.
- Approximately **£896.8K** lost through returns and cancellations.
- Revenue loss rate of **6.78%**.
- The United Kingdom accounted for approximately **88% of total revenue**.
- November generated the highest revenue.
- December recorded the highest revenue loss.
- Q4 generated the highest revenue and the highest losses.

## Recommendations

The analysis recommends investigating the causes of returns during peak periods, strengthening quality control for high-performing products, monitoring Q4 operations more closely, and diversifying beyond the UK market.

## Deliverables

- Cleaned analytical workbook
- Retail dashboard
- Analysis document

## Tools

**Excel · Data Cleaning · Pivot Tables · Exploratory Analysis · Dashboarding**
