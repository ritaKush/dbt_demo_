# dbt_demo_

Tips

1. Create a staging layer 
- embraces modularity
- gate keeper

2. CTEs Common Table Expression
- custom logic
- final CTE
- final select

3. Use Directories
- dbt run -m directory.*

4. Create a Style Guide
- development, review, onboarding
- naming convention
- README

5. Don't optimize for fewer lines

## DBT SOURCES
https://docs.getdbt.com/docs/building-a-dbt-project/using-sources

## DBT Macros
https://docs.getdbt.com/docs/building-a-dbt-project/building-models/using-custom-schemas

For generating schema with custom schema name. Under macro code remove {{ default_schema }}_ inside else code.

## DBT Tests
https://docs.getdbt.com/docs/build/tests

## DBT Materialization
https://docs.getdbt.com/docs/build/materializations
