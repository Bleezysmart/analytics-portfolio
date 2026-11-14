# Bolz Grillz Analytics

**Business Intelligence & Commercial Analytics Case Study | 2026**

## Project overview
Bolz Grillz Analytics is a business intelligence project built around a multi-unit food and grill business. The objective is to create a connected view of sales, customer behaviour, product performance, workforce activity, inventory and operating expenses to support better commercial and operational decisions.

## Data model
The analytical dataset includes:
- 12,000 orders
- 27,000 order-line records
- 720 inventory snapshots
- 189 expense records
- 250 customers
- 16 employees
- 32 products
- 3 business units

The project uses a PostgreSQL database named bolz_grillz_analytics, with an analytics schema, alongside Power BI for reporting and exploration.

## Analytical workstreams
The dashboard design covers five business views:
1. **Executive Overview** — headline sales and business performance.
2. **Sales & Product Performance** — order activity, product mix and sales contribution.
3. **Customer Intelligence** — customer activity and purchasing behaviour.
4. **Team & Staff Performance** — workforce activity and operational contribution.
5. **Branch & Operational Performance** — business-unit performance, inventory and expenses.

## Example business-unit analysis
A Redflames unit-level reconciliation recorded:
- 2,000 orders
- ₦53.05m gross sales
- ₦1.59m discounts
- ₦51.46m net revenue
- ₦23.73m cost of goods sold
- ₦27.73m gross profit

The Redflames revenue reconciliation difference was ₦0. The figures above are specific to that unit-level analysis and should not be interpreted as totals for the entire business.

## How the analysis supports management questions
The five reporting workstreams organise the dataset around practical operating questions:

| Management question | Analytical view |
|---|---|
| How is the business performing overall? | Executive Overview |
| Which products and sales channels contribute to results? | Sales & Product Performance |
| What does customer activity and repeat purchasing look like? | Customer Intelligence |
| How does workforce activity relate to operations? | Team & Staff Performance |
| How do business units, inventory and expenses compare? | Branch & Operational Performance |

The Redflames example provides a unit-level illustration of reconciliation: gross sales less discounts equals net revenue, and the stated net revenue less cost of goods sold equals gross profit. The reconciliation difference was ₦0. These figures apply to Redflames only and are not presented as consolidated business totals.

## Analytical controls and interpretation
- Keep business-unit figures separate from company-wide totals.
- Reconcile gross sales, discounts, net revenue and cost of goods sold before interpreting gross profit.
- Treat customer, product, inventory, employee and expense records as distinct analytical entities connected through the data model.
- Use the reporting views to identify where further investigation may be required; do not infer causation from descriptive patterns alone.

The project describes the structure of the analysis and selected reconciled outputs. It does not claim quantified improvements in sales, margin or operating efficiency.

## Tools and methods
**PostgreSQL · SQL · Power BI · Data Modelling · Data Reconciliation · Commercial Analytics**

## Business questions
- Which products and business units contribute most to sales and gross profit?
- How do discounts affect realised revenue?
- What patterns appear in customer activity and repeat purchasing?
- How do inventory and expenses relate to operational performance?
- Where should management investigate opportunities to improve performance?

> This case study describes analytical work on a project dataset. Unit-level figures are identified explicitly; they should not be generalised beyond their stated scope.
