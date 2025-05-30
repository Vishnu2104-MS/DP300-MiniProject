Monitor & Tune Query Performance in Azure SQL Database with sample data
# Azure SQL Database Query Performance Monitoring & Tuning

## Overview
This mini-project demonstrates how to:
1. Set up an Azure SQL Database with sample data.
2. Monitor query performance using Query Store and Query Performance Insight.
3. Tune slow queries with indexing and query rewrites.

## Steps
- Load sample data or use built-in AdventureWorksLT.
- Run inefficient queries to simulate workload.
- Monitor slow queries and identify bottlenecks.
- Apply optimizations and measure improvements.

## Tools
- Azure SQL Database
- Azure Data Studio or SSMS
- Query Store & Query Performance Insight

## Run
1. Load sample data: `scripts/load_sample_data.sql`
2. Run inefficient queries: `scripts/inefficient_queries.sql`
3. Monitor performance: `monitoring_queries.sql`
4. Apply tuning: `scripts/optimized_queries.sql`
