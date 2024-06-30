# High Availability PHP Website with MySQL Database on AWS

## Description:

This project focuses on deploying a highly available and scalable web application on AWS, utilizing Amazon EC2 for compute capacity, Amazon RDS for database management, and Auto Scaling to ensure high availability. The project involves setting up a PHP website with a MySQL database, leveraging AWS services to automate infrastructure management and handle traffic fluctuations.

## Key Services Used:

1. **Amazon EC2 (Elastic Compute Cloud):** Scalable virtual server instances for hosting the PHP website.
2. **Amazon RDS (Relational Database Service):** Managed MySQL database, providing scalability and reliability.
3. **Auto Scaling:** Automatically adjusts the number of EC2 instances to maintain performance and availability.
4. **Amazon VPC (Virtual Private Cloud):** Isolated network environment for enhanced security and control.
5. **Security Groups:** Configures firewall rules to control inbound and outbound traffic to EC2 and RDS instances.
6. **Amazon CloudWatch:** Monitors the performance and operational health of the EC2 instances and RDS database.
7. **Elastic Load Balancing (ELB):** Distributes incoming application traffic across multiple EC2 instances to ensure fault tolerance and high availability.
   
## Steps Performed

- Created an EC2 instance to host the PHP website, ensuring a scalable and flexible compute environment.

- Configured Auto Scaling to maintain a minimum of 2 instances, providing automatic scaling based on traffic and load. This ensures high availability and fault tolerance.

- Set up an RDS instance to manage the MySQL database. This offers automated backups, software patching, and seamless scaling.

- Created a database named intel and a table named data within the RDS instance. The database password was set to intel123, ensuring secure access.

- Modified the PHP website configuration to use the new RDS instance as the database host, ensuring seamless database connectivity.

- Configured security groups to allow traffic from the EC2 instances to the RDS instance. This ensures the web application can communicate with the database securely.

- Updated security groups to allow necessary traffic to the EC2 instances, enabling full functionality of the web application.
  
