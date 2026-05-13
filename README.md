# AWS-Three-Tier-WordPress-Application-Evolution

This demo takes you through the step by step requirements of building a Wordpress application, starting from a signle EC2 server, to gradually evolving it to a 3 tier architecture, following the well-architectured guildlines from AWS. 

This demo has taken inspiration from Adrian Cantrill's AWS training guides, link: https://github.com/acantril/learn-cantrill-io-labs/tree/master/aws-elastic-wordpress-evolution, I'll also highlight the mistakes I made in this build and how I recover from issues along te way.

The demo consists of 6 stages, each implementing additional components of the architecture:

Stage 1 - Setup the environment and manually build wordpress
Stage 2 - Automate the build using a Launch Template
Stage 3 - Split out the DB into RDS and Update the LT
Stage 4 - Split out the WP filesystem into EFS and Update the LT
Stage 5 - Enable elasticity via a ASG & ALB and fix wordpress (hardcoded WPHOME)
Stage 6 - Cleanup

Each stage instructions
Stage1
Stage2
Stage3
Stage4
Stage5
Stage6

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
