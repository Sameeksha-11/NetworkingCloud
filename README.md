# NetworkingCloud

- Developed a social media application using cloud native principles. Technologies used are Java Spring Boot, RDS postgres (private subnets) with replica sets, S3 for file storage, dynamoDB for notification storage. Implemented fault
tolerance by spawning instance in multiple availability zones, auto-scaling, load balancing (load-tested).
- Implemented CICD with Github Actions and AWS Code deploy, containerization using HashiCorp Packer, IAAC setup using CloudFormation, implemented application observability with Springboot AOP logs, metrics using Statsd and
published them to AWS Cloudwatch.
