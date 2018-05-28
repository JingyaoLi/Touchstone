# Touchstone
Query-aware synthetic data generation is an essential and highly challenging task, important for database management system (DBMS) testing, database application testing and application-driven benchmarking.
Prior studies on query-aware data generation suffer common problems of limited parallelization, poor scalability, and excessive memory consumption, making these systems unsatisfactory to terabyte scale data generation.
In order to fill the gap between the existing data generation techniques and the emerging demands of enormous query-aware test databases, we design and implement our new data generator, called {\em Touchstone}.
{\em Touchstone} adopts the random sampling algorithm instantiating the query parameters and the new data generation schema generating the test database, to achieve fully parallel data generation, linear scalability and austere memory consumption.
Our experimental results show that {\em Touchstone} consistently outperforms the state-of-the-art solution on TPC-H workload by a 1000$\times$ speedup without sacrificing accuracy.
