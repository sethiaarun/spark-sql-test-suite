# spark-sql-test-suite
Apache Spark SQL Test Suite to validates list of Data Definition and Data Manipulation Statements, as well as Data Retrieval and Auxiliary Statements.

You can store results for each run in Azure Storage container. To synchronize the test run id, you can override `TEST_RUN_ID` in the individual notebook. These notebooks can be useful for:

- Self-learning
- Validating your Spark environment
- Easy to extend to add your test cases for the Spark runtime session and various configurations
- Compare results across multiple runs
- Add performance test cases
- Add intergarted scenarios

## [Apache SQL 3.3 Reference](https://spark.apache.org/docs/3.3.0/sql-ref-syntax.html)
- [DDL Statements](./DDLTestCases.ipynb)
- [DML Statements](./DMLTestCases.ipynb)
- [Auxiliary Statements](./AuxStatementsTestCases.ipynb)
- [Data Retrieval Statements](./DataRetrievalStatements.ipynb)
