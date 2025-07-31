## Project 1: AWS Static Website Hosting

**Goal**: Deploy a static website using AWS Amplify for simplified hosting

**Implementation**: 
- Upload static website files (HTML, CSS, JS) directly to S3 bucket
- Deploy website using AWS Amplify console
- Amplify automatically generates DNS name for public access
- Built-in CDN and SSL certificate provisioning

**Outcome**: Live static website accessible via Amplify-generated URL with automatic HTTPS

![Static Website](https://github.com/user-attachments/assets/b8f5903e-525e-4b3e-ba1a-3082600a7ea3)

---

## Project 2: Designing Secure AWS Infrastructure for Internet-Exposed Backend Services

**Goal**: Host Grafana application in a secure private subnet with internet access

**Implementation**:
- Custom VPC with public and private subnets
- NAT Gateway in public subnet for outbound internet access
- Grafana deployed on EC2 instance in private subnet (app-tier)
- Security groups configured for secure access
- Internet access via NAT Gateway for downloading applications and updates

**Outcome**: Secure Grafana deployment accessible from private subnet with controlled internet connectivity

![Manual Deployment](https://github.com/user-attachments/assets/dd9bef27-0db5-4852-a40f-92103664182c)
