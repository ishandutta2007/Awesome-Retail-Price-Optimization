# Awesome-Retail-Price-Optimization

## Top Retail Price Optimization Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Dynamic Pricing, Competitive Price Intelligence, Margin Optimization, Markdown & Promotion Pricing, and Omnichannel Price Management*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Retail Price Optimization**. These systems help retailers set optimal regular, promotional, and markdown prices using demand models, competitor data, elasticity insights, and business rules to improve margin, sell-through, and revenue.



**Examples** include Revionics, Competera, Intelligence Node, Pricefx, Zilliant, Blue Yonder Pricing, Omnia Retail, Quicklizard, Prisync, and PROS Smart Price (the category leaders).



**Open-source emphasis**: Enterprise retail price optimization platforms with governed workflows, large-scale elasticity modeling, and deep merchandising integrations are commercial. Open-source activity is concentrated in machine-learning prototypes, real-time pricing engines, causal inference pipelines, and academic dynamic-pricing research. This section lists every significant relevant project found.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Revionics](https://www.revionics.com/)**  

  AI-powered retail price optimization and promotional/markdown management platform focused on governed recommendations, margin impact, and large-scale retail execution.



- **[Competera](https://competera.ai/)**  

  Retail pricing platform combining competitive intelligence, AI recommendations, and price optimization for omnichannel retailers.



- **[Blue Yonder Pricing](https://blueyonder.com/)**  

  Enterprise pricing solution within the Blue Yonder suite for regular price, promotion, and markdown optimization with strong supply-chain context.



- **[Pricefx](https://www.pricefx.com/)**  

  Configurable price optimization and management platform used across retail and other industries for rule-based and AI-assisted pricing.



- **[Zilliant](https://www.zilliant.com/)**  

  Pricing and revenue intelligence platform strong in B2B and complex pricing scenarios, also applied in retail contexts.



- **[Intelligence Node, Omnia Retail](https://www.intelligencenode.com/)**  

  Competitive price intelligence and retail pricing platforms that feed optimization and monitoring use cases.



- **[Quicklizard, Prisync](https://www.quicklizard.com/)**  

  Dynamic pricing and competitor-price monitoring tools popular with e-commerce and mid-market retailers.



- **[PROS Smart Price and related solutions](https://pros.com/)**  

  Pricing optimization capabilities from PROS used in various industries including retail and distribution.



- **[Other retail pricing & intelligence platforms](https://www.revionics.com/)**  

  Additional commercial tools covering price scraping, elasticity modeling, and automated price execution.



## Open-Source GitHub Projects



- **[Retail Price Optimization ML projects](https://github.com/search?q=retail+price+optimization+OR+dynamic+pricing+retail)**  

  End-to-end machine-learning systems that predict demand, estimate elasticity, and recommend prices to maximize revenue or margin.



- **[Real-Time Dynamic Pricing Engines](https://github.com/search?q=dynamic+pricing+engine+OR+real-time+pricing)**  

  Event-driven pricing services (often using Kafka, Redis, and APIs) that update prices based on demand signals, views, carts, and purchases.



- **[Causal ML & elasticity pipelines](https://github.com/search?q=price+elasticity+OR+Double+Machine+Learning+pricing)**  

  Projects applying causal inference (e.g., Double Machine Learning) to obtain unbiased price elasticity estimates for optimization.



- **[Bayesian Optimization for Dynamic Pricing](https://github.com/search?q=Bayesian+Optimization+dynamic+pricing)**  

  Research implementations that use Gaussian Processes and Bayesian Optimization for adaptive, revenue-maximizing pricing and demand learning.



- **[Perishable goods & inventory-aware pricing](https://github.com/normanrz/dynamic-prices)**  

  Open-source tools for dynamic pricing of perishable or time-sensitive inventory with demand estimation and strategy simulation.



- **[E-commerce pricing optimization notebooks](https://github.com/search?q=ecom+dynamic+pricing+OR+pricing+optimizer)**  

  Practical pipelines that combine demand forecasting, constraint-based optimization (margin floors, max change), and serving APIs.



- **[Competitor price monitoring helpers](https://github.com/search?q=price+scraping+OR+competitor+price+tracker)**  

  Scripts and tools for collecting competitive price data that can feed custom optimization models (use responsibly and legally).



- **[Other pricing research & simulators](https://github.com/search?q=dynamic+pricing+OR+revenue+management+pricing)**  

  Academic and experimental codebases exploring pricing strategies, simulation, and reinforcement learning approaches.



### Additional Strong Open-Source Options



- **Demand forecasting libraries**: Prophet, statsmodels, LightGBM, or neural models used as inputs to pricing engines.

- **Optimization solvers**: OR-Tools, PuLP, or commercial solver wrappers for constrained price optimization.

- **Data pipelines**: Airbyte + dbt patterns to unify sales, inventory, and competitor data.

- **Dashboards**: Metabase or Superset for visualizing price performance, elasticity, and recommendation impact.

- **Rule engines**: Open-source business-rule tools for simple cost-plus or competitive-matching logic.

- Spreadsheet + Python hybrids still common for smaller assortments or pilot pricing projects.



**Frameworks for building custom systems**:  

Combine demand forecasting and elasticity models (open ML libraries) with a constraint optimizer and a serving layer (FastAPI or similar).  

Real-time engines can be built with event streaming (Kafka) and fast state stores (Redis).  

Commercial platforms (Revionics, Competera, Blue Yonder, Pricefx, Zilliant, Omnia, etc.) provide enterprise-scale modeling, governance workflows, promotion/markdown integration, and production reliability that research prototypes rarely match.  

Many retailers prototype pricing science with open-source tools and then operationalize through a commercial price optimization platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Price optimization directly affects revenue, margin, customer perception, and regulatory compliance (including pricing transparency and competition rules). Models must be carefully validated and governed.

- Open-source pricing engines and research code offer transparency and experimentation value but require significant data science, engineering, and business oversight before production use. They are not substitutes for mature commercial retail pricing platforms in most large-scale environments.



---



**Made for pricing analysts, retail merchandisers, revenue teams, data scientists, and e-commerce operators.**  

Let's advance open research and practical tools in retail pricing while recognizing the critical role of enterprise-grade commercial platforms.
