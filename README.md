# Amazon F1 instance walk through tutorial

This tutorial uses the hello-world (RTL) design provided by aws-fpga but could be extended to other designs.
Additionally, the FPGA AMI version used is `1.3.4` and the git-tag of `aws-fpga` is `v1.3.6`.

1. [Create an AWS account](create_aws_account.md)
1. [Generate SSH keys](generate_ssh_keys.md)
1. [Create S3 credential](create_s3_credential.md)
1. [Request access to Amazon EC2 F1 instances](request_access_f1.md)
1. [Create an AMI instance](create_ami_instance.md)
1. [Configure S3 bucket](configure_s3.md)
1. [Setup development environment](setup_development_environment.md)
1. [Simulate the design](simulate_design.md)
1. [Build the hardware design](build_hardware.md)
1. [Generate the AFI](generate_afi.md)
1. [Program the FPGA](program_fpga.md)
1. [Compile the runtime of the design](compile_runtime.md)
1. [Bookkeping the AFI](bookkeeping_afi.md)

After you finish this walk through tutorial, you will normally iterate step 8 and step 13
