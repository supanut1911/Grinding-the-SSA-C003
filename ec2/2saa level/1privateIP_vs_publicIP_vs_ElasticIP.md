### Public IP

- mean the machine can be identified on public internet (WWW)
- unique and easy to geo-location

### Private IP

- mean the machine can be identified on private network only
- unique in private network
- machine connect to WWW with NAT + internet gateway

### Elastic IP

- fix public IP for AWS EC2 instance
- qouta 5 EIP per account

### \*Try avoid using Elastic IP

- instead use a random public IP and register a DNS Name
- Much more scale, can also use LoadBalancer and not using Elastic IP
