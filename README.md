# Auto-Insurance-MySQL-Database-Project

This report outlines the culmination of our project aimed at enhancing customer retention for an insurance company through an advanced database application. The project's core objective was to utilize database-driven insights to optimize liability car insurance, thereby improving customer retention.

The database and SQL queries were designed to dynamically tailor car insurance liability plans to client needs as they change over time in order to:
1.)	Save clients money through discounts and
2.)	Increase feelings of security.

Objectives:
1.	Safe Driving Discount Plan Enrollment: Leverage low accident frequency data to alert agents to propose enrollment, enhancing customer savings.
2.	Registration Lapse Savings: Identify vehicles with lapsed registrations and vehicle safety features eligible for discounts.
3.	Plan Customization Based on Client Data: Utilize data on past accident frequency and income brackets to customize plans:
a.	High Frequency, High Income (>$100k): Opt for higher liability limits and higher premiums.
b.	High Frequency, Medium Income ($60k-$100k): Recommend lower deductibles with medium premiums.
c.	Low Frequency: Suggest low deductibles and low premiums.
4.	Plan Adjustments Over Time: Monitor for car registration lapses, under-coverage, and over-coverage to adjust plans appropriately:
a.	Car Registration Status: If inactive, refer to objective #2 to identify potential discount and call client to discuss registration
b.	Under-coverage: If accident damages exceed the plan’s liability limit, discuss the need for higher liability.
c.	Overcoverage: If damages fall below the deductible, consider recommending a lower deductible at the cost of a higher premium.
d.	Payment Issues: Engage with clients who miss multiple premium payments to discuss potential premium reductions.

