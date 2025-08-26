Welcome to your new dbt project!

# Netflix Snowflake dbt Project

End-to-end data pipeline for analyzing Netflix datasets using **Amazon S3**, **Snowflake**, and **dbt**.  
Raw data is stored in S3, loaded into Snowflake, and transformed with dbt into clean, analytics-ready models.

---  

## 🔑 Highlights (My Work in dbt)
- Designed **staging models** to clean and standardize raw Netflix data.  
- Built **fact and dimension tables** for analytics-ready schemas.  
- Implemented **dbt tests** (unique, not null, referential integrity) to ensure data quality.  
- Created **modular, reusable SQL models** using Jinja + macros.  
- Documented models and enabled **data lineage tracking** with `dbt docs`.  
- Configured **incremental models** for efficient transformations on large datasets. 
---

## ⚙️ Tools & Tech
- Amazon S3 | Snowflake | dbt | SQL | Git  

---

## 🚀 Run Locally
```bash
git clone https://github.com/ishshah1101/netflix-snowflake-dbt.git
cd netflix-snowflake-dbt
dbt run
dbt test

### Resources:
- Learn more about dbt [in the docs](https://docs.getdbt.com/docs/introduction)
- Check out [Discourse](https://discourse.getdbt.com/) for commonly asked questions and answers
- Join the [chat](https://community.getdbt.com/) on Slack for live discussions and support
- Find [dbt events](https://events.getdbt.com) near you
- Check out [the blog](https://blog.getdbt.com/) for the latest news on dbt's development and best practices
