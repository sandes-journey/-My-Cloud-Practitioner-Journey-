📦 Storage Summary

Cloud storage comes in different types depending on how data needs to be stored, accessed, and shared. Here's what I've learned about the three main AWS storage services.

🔹 Types of Storage

- **S3 (Simple Storage Service)**: Object storage  
- **EBS (Elastic Block Store)**: Block storage for EC2  
- **EFS (Elastic File System)**: Network file system (NFS)

🔹 Use Cases

- **S3**: Ideal for static website hosting, media files, backups, and data lakes  
- **EBS**: Best for application data, OS volumes, and databases on EC2  
- **EFS**: Used when multiple EC2 instances need shared access to files (e.g., WordPress, CMS)

🔹 Reflection

Understanding the difference between **object**, **block**, and **file storage** helped me figure out when to use each:

- **S3** is great for storing files accessed via URLs or APIs.
- **EBS** feels like a traditional hard drive — attached to one EC2 instance.
- **EFS** allows several EC2 instances to read/write to the same file system, which is useful for collaboration or shared web content.

This knowledge makes it easier to choose the right storage type for different scenarios in the cloud.
