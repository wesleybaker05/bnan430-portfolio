 # bnan430-portfolio
 Portfolio of projects from my Data Visualization course in the the fall of 2026. This will include the completion of projects in Excel, Tableau, BowerBi through Datacamp, Adobe Express, and various AI tools.

Initial E-Commerce Profitability Analysis. Develop a profitability set of dashboards and explain your decisions. 
https://public.tableau.com/views/SouthwestOfficeSolutions-ProfitabilityAnalysis-WesleyBaker/ExploratoryDash?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
If I were doing this again, I would have focused on more color aligned color scheming and more dynamic dashboards.

For the second analysis of a business, I was tasked with analyzing the service tiers of a business. Within this task, I was required to build a predetermined dashboard, and then create my own. 
https://public.tableau.com/app/profile/wes.baker/viz/AnalysisofServiceTiers/AccountPortfolioDashboard
If I were to repeat this task, I would likely experiment with different types of visuals in order to see if there is a better way to portray the data.

BNAN 430, 9/28/2026, https://public.tableau.com/app/profile/wes.baker/vizzes
Using Tableau, while I have to maunally map data and it may feel like an extra step, this step gets rid of the opportunity to have data mapped poorly automatically. By adding the extra step, Tableau makes it so that there is no chance my data mapping fails, which makes me feel like I have more control. Because I am more fluent in Tableau, I would likely do this task in Tableau in the future.

BNAN 430, 10/5/2026, https://public.tableau.com/app/profile/wes.baker/viz/PowerBITrainingCertifications_17906601650340/PowerBITrainingCertificates
I built a profit margin calculated field, SUM([Profit])/SUM([Revenue]), which divides total profit by total revenue. In Power BI I'd make it a measure rather than a calculated column, because it has to add up profit and revenue for by region, or by  another category, A margin stored on each row would give an incorrect result. Within the model, Anita and Marcus can slice it themselves in a meeting and always see a current number opposed to waiting on a new verison of the same sheet.

BNAN 430, 10/12/2026, https://public.tableau.com/app/profile/wes.baker/viz/PowerBITrainingCertifications_17906601650340/PowerBITrainingCertificates
I’m ready for BI work at Southwest because I’ve already built the views that found its two biggest profit leaks. In my Flex 3 Explanatory Dashboard, a Tableau lollipop chart of profit margin by subcategory shows Tables losing more than $0.08 per dollar: −$16,937 on $200,237 in revenue at a 26% average discount. The discount sits in one callout. In Power BI I would rebuild it as a scatter plot of average discount against profit margin, sized by revenue, so Anita can see where margin turns negative across every subcategory and set a discount cap. In Flex 2, my “Inside Sales Is an Issue” view needed a custom Bar Color calculation to turn the ($16,822) bar red, and the Account List on my Account Portfolio Dashboard is a plain grid. Power BI’s rule-based conditional formatting would flag negative Net Contribution and high Avg. Discount cells directly, so Marcus could spot an Inside Sales account losing $654 at a 35.5% discount without reading every row.
Excel stays right for one-off questions and anything Marcus edits himself. Tableau fits exploring a new question or publishing a public story, where speed matters more than control. Power BI fits when a report pulls from Southwest’s Microsoft systems, refreshes on a schedule, and many people rely on the same numbers.
My gap: I have never published to the Power BI Service or maintained a report others depend on. I would publish my course report to a trial workspace, schedule a refresh, and have a classmate use it for two weeks and report what breaks.

Card Portfolio Review - BNAN 430
Which non-contactless cards should Bear Down Bank replace early this quarter, and what will it cost?
https://public.tableau.com/views/CardPortfolioReview_17924593962870/DesignJustification?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
If I did it again, I would build the explanatory chart first and design the exploratory dashboard around it, so the colors and labels matched from the start.
