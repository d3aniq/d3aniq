### Hi, I'm Jasmin 👋

Data engineer and BI developer in Gothenburg, Sweden. My work often starts where two systems describe the same thing in different ways, and ends with numbers people can make decisions on.

**Different sources. One answer.**

---

#### 📊 [sweden-bi-job-market](https://github.com/d3aniq/sweden-bi-job-market)

What do BI jobs in western Sweden ask for? All 7.7 million job ads in the Swedish Public Employment Service's Platsbanken from 2016 to 2026, in a medallion pipeline with dbt and DuckDB, answered in a Power BI report with the semantic model written as code (TMDL/PBIR). Open data, rebuildable from source.

`dbt` `DuckDB` `Python` `Power BI` `DAX`

#### ⚡ [sweden-power-lakehouse](https://github.com/d3aniq/sweden-power-lakehouse)

Reconciles Svenska kraftnät's hourly electricity production with Statistics Sweden's monthly figures across bronze, silver and gold on Databricks, with dbt models and 29 automated tests. Three production types agree within a tenth of a percent; solar and thermal deviate systematically, because the monthly statistics count production that never reaches the grid.

`Databricks` `PySpark` `Delta Lake` `dbt` `Unity Catalog`

#### 🟣 [RefStat](https://refstat.se/) · live

Referee statistics for football, futsal, floorball and handball in Sweden and Norway. Fetches and parses match data from six federations' public match pages, one parser per source, and combines them into one view. API on Deno Deploy behind Cloudflare, 57 automated tests, used by active referees. Code available on request.

#### 🟢 [FogiZi](https://fogizi.se/) · live

Shows which open referee assignments in FOGIS and iBIS can be applied for without a clash, with match length per competition and travel time between venues, and applies for several at once. An application only counts as done once the federation's system confirms it, and passwords are never stored. Deno, 125 automated tests. Code available on request.

---

#### Work

- **Copa Solar**, Fullstack Developer, 2026: serverless AWS backend defined as code with CDK, six external data sources in one data model, CI/CD with around 100 tests. [copa-solar.github.io](https://copa-solar.github.io)
- **Captario**, BI Analyst, 2024: automated manual Python ETL runs, built star schemas and Power BI dashboards used as a decision basis. [captario.com](https://captario.com/)
- **Securitas**, Team Leader with data responsibility, 2019–2023: Power BI analysis of passenger flows in Västtrafik's public transport network, used as a basis for ticket inspections and resource allocation.

#### Team project

- [manufacturing-optimization-engine](https://github.com/LTU-2025-Team6/manufacturing-optimization-engine): a distributed system in C# and .NET with RabbitMQ, Docker and Google OR-Tools (Luleå University of Technology)

#### Tools

**Data and BI:** SQL, T-SQL, Python (Pandas, NumPy), Power BI, DAX, Power Query, dimensional modelling, Databricks, PySpark, Delta Lake, dbt, DuckDB  
**Cloud:** AWS (CDK, Lambda, DynamoDB, S3, API Gateway, Cognito), Azure, Deno Deploy, Cloudflare, Docker, GitHub Actions  
**Development:** C#, .NET, ASP.NET Core, Entity Framework Core, TypeScript, React, Node.js, xUnit, Vitest  
**Languages:** Swedish and English (fluent), Bosnian (native), German (professional), Italian (basic)

---

[dzanic.se](https://dzanic.se/) · [d3aniq.com](https://d3aniq.com/) · [LinkedIn](https://www.linkedin.com/in/d3aniq/) · jasmin@dzanic.se
