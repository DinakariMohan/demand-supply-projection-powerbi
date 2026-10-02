<div align="center">

# Demand Supply Projection Report

</div>

How do you know whether a factory will deliver what customers ordered, and where it will fail, before it's too late to act?

I'm building a Demand & Supply Projection report in Power BI. It compares demand with planned supply, classifies each line as Met on time, Met late or Not met, and points to the bottlenecks behind the gaps.

**Project goal:**
Show the business where demand is not being met by supply, find the bottlenecks behind it, and alert planners when late or unmet demand gets high, so they can act before customers are affected.

**Objectives:**
- Measures demand against supply
- Measure overall demand against the supply available to meet it.
- Classify every demand line as Met on time, Met late or Not met.
- Identify bottlenecks: the products, periods, factories, resources or supply sources where late and unmet demand is concentrated.
- Raise an alert when Not met % or Met late % goes above an agreed threshold, so the business can act early.
- Identify the highest-demand products.
- Use that view to set product priorities when factory or resource capacity is limited, which reduces delays and improves efficiency.

**Assumptions**
- Demand comes from customer orders and forecast, and supply from planned and committed supply schedules.
- "On time" means supplied on or before the requested date. This is agreed before building anything.
- Supply is matched to demand at product and date level.
- A bottleneck is defined as a product, period or resource with a Not Met % or Met Late % above the agreed threshold.
- Alert thresholds are set by the business and reviewed regularly.
- Data from the source systems is reconciled before it reaches the report.
- This project uses synthetic data, so the results show the method, not real company performance.

**Built with** Power BI, SQL and Python, using synthetic data. 
**Status:** in progress.

What alert would you want to see first in a report like this?

#PowerBI #DataAnalytics #SupplyChain #BusinessAnalyst #DemandPlanning
