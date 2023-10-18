# spark-sql-test-suite
Apache Spark SQL Test Suite to validates list of Data Definition and Data Manipulation Statements, as well as Data Retrieval and Auxiliary Statements.

You can store results for each run in Azure Storage container. To synchronize the test run id, you can override `TEST_RUN_ID` in the individual notebook. These notebooks can be useful for:

- Self-learning
- Validating your Spark environment
- and are easy to extend to add your test cases for the Spark runtime session.
