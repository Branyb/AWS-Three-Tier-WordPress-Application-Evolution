# AWS-Three-Tier-WordPress-Application-Evolution

This demo takes you through the step by step requirements of building a Wordpress application, starting from a signle EC2 server, to gradually evolving it to a 3 tier architecture, following the well-architectured guildlines from AWS. 

This demo is my own interpritation from Adrian Cantrill's AWS training guides, link: [here](https://github.com/acantril/learn-cantrill-io-labs/tree/master/aws-elastic-wordpress-evolution), I'll also highlight the mistakes I made in this build and how I recover from issues along te way.

The demo consists of 6 stages, each implementing additional components of the architecture:

Stage 1 - Setup the environment and manually build wordpress

Stage 2 - Automate the build using a Launch Template

Stage 3 - Split out the DB into RDS and Update the LT

Stage 4 - Split out the WP filesystem into EFS and Update the LT

Stage 5 - Enable elasticity via a ASG & ALB and fix wordpress (hardcoded WPHOME)

Stage 6 - Cleanup

Each stage instructions

[Stage1](https://github.com/Branyb/AWS-Three-Tier-WordPress-Application-Evolution/edit/main/Building%20Stages/%20STAGE1%20-%20Setup%20and%20Manual%20wordpress%20build.md)

[Stage2](https://github.com/Branyb/AWS-Three-Tier-WordPress-Application-Evolution/blob/main/Building%20Stages/STAGE2%20-%20Automate%20the%20build%20using%20a%20Launch%20Template.md)

[Stage3](https://github.com/Branyb/AWS-Three-Tier-WordPress-Application-Evolution/blob/main/Building%20Stages/STAGE3%20-%20Add%20RDS%20and%20Update%20the%20LT.md)

[Stage4](https://github.com/Branyb/AWS-Three-Tier-WordPress-Application-Evolution/blob/main/Building%20Stages/STAGE4%20-%20Add%20EFS%20and%20Update%20the%20LT.md)

[Stage5](https://github.com/Branyb/AWS-Three-Tier-WordPress-Application-Evolution/blob/main/Building%20Stages/STAGE5%20-%20Add%20an%20ELB%20and%20ASG.md)

[Stage6](https://github.com/Branyb/AWS-Three-Tier-WordPress-Application-Evolution/blob/main/Building%20Stages/STAGE6%20-%20CLEANUP.md)

1-Click Installs
Make sure you are logged into AWS and in us-east-1
VPC


Video Guides
HERE


Architecture Diagrams
Stage1 - PNG
Stage1 - PDF
Stage2 - PNG
Stage2 - PDF
Stage3 - PNG
Stage3 - PDF
Stage4 - PNG
Stage4 - PDF
Stage5 - PNG
Stage5 - PDF
