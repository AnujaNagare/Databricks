Sensitive data sets can be encrypted directly by new Apache Spark™ versions (3.2 and higher). Setting several configuration parameters and DataFrame options will trigger the Apache Parquet modular encryption mechanism that protects select columns with column-specific keys. The upcoming Spark 3.4 version will also support uniform encryption, where all DataFrame columns are encrypted with the same key.

 

Spark data encryption is already leveraged by a number of companies to protect personal or business confidential data in their production environments. The main integration effort is focused on key access control and on building a Spark/Parquet plug-in code that can interact with company’s key management service (KMS).

 

In this session, we will briefly cover the basics of Spark/Parquet encryption usage, and dive into the details of encryption key management that will help in integrating this Spark data protection mechanism in your deployment. You will learn how to run a HelloWorld encryption sample, and how to extend it into a real world production code integrated with your organization’s KMS and access control policies. We will talk about the standard envelope encryption approach to big data protection, the performance-vs-security trade-offs between single and double envelope wrapping, internal and external key metadata storage. We will see a demo, and discuss the new features such as uniform encryption and two-tier management of encryption keys.

Experience: In Person
Track: Data Governance
Type: Breakout
Level: Intermediate
Industry: Enterprise Technology, Financial Services, Healthcare and Life Sciences, Public Sector
Technologies: Data Governance


---
Lead Systems Architect, Apple
