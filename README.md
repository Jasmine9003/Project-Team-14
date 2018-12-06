# Project-Team-14
PROJECT IDEA

## Team Name : Tech Titans

## Presented By: 
--------------
1. Akhilesh Anand 
2. Jasmine Dhunna 
3. Sanjay Nag Bangalore Ravishankar
4. Vishwanath Manvi
                                                      
## 1. Decentralized Digital Identity Management System - APPROVED
--------------------------------
Implement a decentralized digital identify management system using Hyperledger to demonstrate below use case.

### Project Abstract:

International students applying to a US university go through a long and painful process of getting the required credentials from various issuing authorities/intermediaries like below to apply.

1. School to obtain transcripts,
2. ETS (for GRE/TOEFL tests), 
3. WES (for evaluating transcripts), 
4. Recommendation letters, etc 

This process takes months and students have to produce their personal identifiable information (PII) data every time to each of authorities. Also, these authorities additionally request students to provide proof of identity to provide the service. The student's identity is replicated across the intermediaries centralized systems. This data is now not only vulnerable to potential information threats, but also potential misuse by the agencies themselves to further their own business interests. With a decentralized blockchain solution, there's no need for any of the authorities to collect and store personal and identity data. Students will own their data and will only provide access to minimum required data that each of the intermediary requires to provide their service. Once approved, the credential is then added to the students wallet. Since adding credentials would be transactions on the blockchain, they are verified and therefore can be trusted by all authorities. It also makes data more secured and transparent to all parties involved. The student can then present the verified credentials along with application form to the university thereby enabling them to make a faster decision.

### Proposed methodology/ resources, etc:
1. Implement a permissioned blockchain using Hyperledger Indy open source project. 
2. Implement REST APIs for various business entities involved.
3. Implement a web application to demonstrate the students application journey highlighted above.

### Usage Instructions:
Docker and docker compose are used to build and run the demo.

- Install docker and docker compose on the system.
- To check the version of docker and docker compose on the system, use the commands:

$ docker --version  
$ docker-compose –version

To run Edublocks, follow the below steps:

- First, go to the nodejs folder of the project from the terminal.
- Use the commands,
   ./manage build 
   then ./manage up or ./manage start
   
  If server needs to be started again,
  ./manage down 
  and then ./manage up
