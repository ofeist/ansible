# Based on "Introduction To Ansible" (A Cloud Guru Course)

Creates and configures a load balancer and two web servers.\

Prerequisites:\
- python\
- ansible\

Recipe:\
---
1 create the AWS resources - use the "setup-env.yml" CloudFormation template in setup folder\
2 update servers, install and update services - use the "all-playbooks.yml" in playbooks folder\
