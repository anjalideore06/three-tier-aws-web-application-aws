# Three-Tier Architecture on AWS

Designed a scalable and secure three-tier web application using AWS.

**Technologies:** AWS VPC, EC2, Application Load Balancer, Auto Scaling, Nginx, PHP, PHP-FPM, Amazon RDS MySQL.

**Architecture:**
- **Web Tier:** Nginx servers in private subnets.
- **App Tier:** PHP application servers with PHP-FPM.
- **Database Tier:** Amazon RDS MySQL in private DB subnets.
- **Load Balancing:** Public and internal Application Load Balancers.
- **Networking:** Custom VPC with public and private subnets across two Availability Zones.

**Key Learning:** VPC networking, subnet configuration, load balancing, Auto Scaling, and database connectivity.

**Author:** Anjali Deore
