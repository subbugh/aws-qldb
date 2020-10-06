# aws-qldb

An AWS –Amazon Quantum Ledger Database (QLDB) Case Study. 
More details are enclosed in the attached documents, both in the PPT and PDF versions, in the file named AWS_QLDB2.

QLDB Features:
--------------
•Immutable and Transparent: Append-only journal and Easy access to change history.
•Cryptographically Verifiable: Allows to verify the thechanges, through the History called as Digest.
•Serverless: Easy to Scale, Easy setup and Easy Monitoring and metrics.
•Easy to Use: Uses, PartiQLas SQL for querying. Which is a Document-oriented data model with the Transactional Consistency and ACID Semantics.
•Streaming Capability:

Details of the Case Study:
--------------------------
1.An Insurance company.
2.Schema with three tables (Customers, Policies and Claims), indexes and with sample data.
3.Claims table will be having multiple Claims. Chosen Claim904, for our case study. Necessary update statements will be ran on the Claim904 of the samples to create the History.
4.Scripts are available in my GitHubbranch, https://github.com/subbugh/aws-qldb

Steps, Hands-on activity:
-------------------------
1.Create a Ledger.
2.Create Tables.
3.Create Indexes on the tables.
4.Insert Sample data.
5.Query the tables on the ledger.
6.Modify the data on the Ledger.
7.Download a couple of Digest’s after set of Modify transactions.
8.Verify the blockAddress’sof the transactions of a document in the Ledger.
