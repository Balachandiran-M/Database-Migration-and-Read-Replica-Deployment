# Database-Migration-and-Read-Replica-Deployment
Creating a Database in EC2 and  replicated into RDS and with Read Replica Deployment.

1)  create a EC2 instance for creating database and create a security group which has to allow port values like 22 and 3306.
   
![Screenshot (154)](https://github.com/Balachandiran-M/Database-Migration-and-Read-Replica-Deployment/assets/152047725/c2e7a60f-0a27-419f-8401-5cdc8a2c2509)
![Screenshot (155)](https://github.com/Balachandiran-M/Database-Migration-and-Read-Replica-Deployment/assets/152047725/08dc6a23-3824-4db3-9efc-b6c3ed51d4cc)
![Screenshot (156)](https://github.com/Balachandiran-M/Database-Migration-and-Read-Replica-Deployment/assets/152047725/06b92968-698b-4a74-b2cc-abc2dc3258f9)

2) And then ssh into instance and download mariadb
3) And create a user , database and then replicated into existing rds ( commands available in repo)
   
![Screenshot (157)](https://github.com/Balachandiran-M/Database-Migration-and-Read-Replica-Deployment/assets/152047725/4c4d0fff-4660-47f9-971f-b5f45826f47f)
![Screenshot (158)](https://github.com/Balachandiran-M/Database-Migration-and-Read-Replica-Deployment/assets/152047725/ae6af461-9b66-40f1-a3b4-c42b879b767d)
![Screenshot (159)](https://github.com/Balachandiran-M/Database-Migration-and-Read-Replica-Deployment/assets/152047725/b687b787-02c7-41f9-88af-bc1f67ff3c56)


4) AND create a read replica for the rds database for high availability. I created a read replicas in different availabilty zone in same region.
![Screenshot (162)](https://github.com/Balachandiran-M/Database-Migration-and-Read-Replica-Deployment/assets/152047725/8e2cd432-c898-4de5-977e-cc9ec1aa937a)
![Screenshot (163)](https://github.com/Balachandiran-M/Database-Migration-and-Read-Replica-Deployment/assets/152047725/cf2702d0-8528-4a4c-bf33-2cabf2d2a9b3)
![Screenshot (164)](https://github.com/Balachandiran-M/Database-Migration-and-Read-Replica-Deployment/assets/152047725/d8c56b5c-8eb9-4257-bb02-3cab59531cd4)
![Screenshot (165)](https://github.com/Balachandiran-M/Database-Migration-and-Read-Replica-Deployment/assets/152047725/ed28df94-91eb-4df9-a0c4-3850b89ab96e)
