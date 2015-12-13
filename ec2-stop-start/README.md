## Usage

aws.hosts should contain the host where the aws-cli is installed.

- To stop AWS EC2 instances from your group_vars list:

    ansible-playbook stop.yaml -i aws.hosts

- To start AWS EC2 instances from your group_vars list:

    ansible-playbook start.yaml -i aws.hosts --extra-vars "ec2_tag=YOUR_TAG"
