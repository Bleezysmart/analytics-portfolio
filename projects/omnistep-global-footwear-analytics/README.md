# OmniStep Global Footwear Analytics

**Power BI Business Intelligence Case Study · July 2026**

OmniStep Footwear operates across six international markets, five footwear categories, multiple customer segments and both online and retail channels. The project turns 30,000 transaction records into a consolidated analytical view of sales performance, discount exposure, customer behaviour, product demand and regional performance.

## Business question

Management needed to understand:

- How revenue changes over time and across markets
- Which countries and product categories generate the most value
- How much potential revenue is surrendered through discounts
- Whether higher discounts are associated with stronger sales volume
- How customer income levels relate to purchasing behaviour
- Which shoe sizes and product categories show the strongest demand
- How payment methods and sales channels contribute to activity

## Approach

The project followed a business-first BI workflow:

1. **Business understanding** — defined the decisions the dashboard needed to support.
2. **Data preparation** — cleaned and structured the transaction data.
3. **Data modelling** — built a structured Power BI model around the business questions.
4. **Measure development** — created consistent KPIs for sales, revenue, discounts, orders, units and customer behaviour.
5. **Dashboard development** — built multiple analytical pages for executive performance, product/customer insights, pricing/discount analysis and key business insights.
6. **Validation** — tested the findings against the available data and documented limitations.
7. **Recommendations** — translated the evidence into measurable actions.

## Key results

| Metric | Result |
|---|---:|
| Gross Sales | **$10.48M** |
| Net Revenue | **$9.08M** |
| Discount Value | **$1.40M** |
| Total Orders | **30,000** |
| Units Sold | **75,006** |
| Average Order Value | **$302.71** |
| Revenue Retention Rate | **86.64%** |
| Discounted Orders | **25,029 (83.43%)** |
| Customer Rating | **4.00 / 5** |

## What the analysis found

### 1. Discount exposure was the main management issue

Discounts were applied to **83.43% of orders**, reducing Gross Sales by approximately **$1.40M**.

Training generated **$1.84M** in Net Revenue with the lowest average discount rate of **13.21%**, while Gym had the highest average discount rate at **13.46%** but generated the lowest category revenue at **$1.77M**.

This is an association in the observed data, not proof that discounts caused Gym's lower revenue. The recommended next step is controlled discount testing rather than an immediate company-wide change.

### 2. Lifestyle led the product categories, but only narrowly

Lifestyle generated **$1.84M** in Net Revenue, **6,059 orders** and **15,129 units**. Training followed closely at **$1.84M**, with a difference of only about **$8.3K**.

The implication is to prioritise Lifestyle where market-level demand supports it while continuing to monitor Training rather than treating the global category ranking as sufficient evidence for every market.

### 3. Size 7 was the strongest demand signal

Size 7 generated **12,667 units**, **5,068 orders** and **$1.53M** in Net Revenue.

The analysis recommends using this as a starting point for market- and category-level inventory planning, while recognising that the dataset measures demand rather than actual stock availability.

### 4. Country performance was relatively balanced

The UAE generated the highest Net Revenue at approximately **$1.55M**, while Pakistan generated the lowest at approximately **$1.47M**. The gap was about **$80.3K**.

Rather than responding with heavier discounts automatically, the project recommends decomposing the gap into orders, average order value, units per order, category mix, customer segment, channel and discount rate.

### 5. Low- and high-income customers were commercially similar

The Low-income segment generated approximately **$3.04M** in Net Revenue and the High-income segment approximately **$3.04M**, with only about **$2.8K** separating them.

This supports testing differentiated offers rather than assuming one segment is inherently more valuable.

## Recommendations

- Test targeted discounts before applying broad promotions.
- Investigate the drivers of Pakistan's revenue gap before increasing promotional intensity.
- Prioritise Lifestyle products using market-level demand evidence while monitoring Training closely.
- Use Size 7 as a starting point for more granular inventory planning.
- Test differentiated offers for Low- and High-income customers.
- Continue supporting all four payment methods while collecting operational cost and failure data.
- Use the dashboard to investigate annual revenue changes by country, category, customer segment, channel and discount level.

## Limitations

The dataset supports analysis of revenue, discounts, orders, units, products, customers, countries, channels and payment methods. It does **not** contain enough information to directly measure:

- Product profitability or gross margin
- Actual inventory levels, stock-outs or inventory turnover
- Individual customer behaviour
- Individual product profitability
- Promotion incrementality using test/control groups

Future versions could add product cost, inventory, returns, customer-level and campaign/control-group data, as well as automated refresh and performance alerts.

## Tools

**Power BI · DAX · Power Query · Data Modelling · Business Intelligence · Excel**

## Project files

The original project package includes:

- Power BI dashboard workbook
- Dashboard PDF
- Project report
- Project documentation
- Presentation

