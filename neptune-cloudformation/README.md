# GraphCMDB - Setting up Amazon Neptune + ALB

Installing Amazon Neptune database :
0. (check VPC Imports from the templates and modify to match your VPC stack)
1. Deploy neptune.yaml
2. Deploy neptune-alb.yaml
3. Add neptune ip-address to a newly created ALB Target Group
4. Change ALB Security Group to allow :8182 only from your own IP-address

