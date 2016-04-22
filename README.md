# Ansible AWS Inspector Agent Role

Installs the [AWS Inspector Agent](http://docs.aws.amazon.com/inspector/latest/userguide/inspector_introduction.html).

### Requirements

This role does not depend on any other Ansible roles. This will only install on AWS EC2 instances. Ensure your instance has proper autorization to call AWS APIs, either through an [instance IAM role](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/iam-roles-for-amazon-ec2.html) or via a dedicated `awscli` user authentication.

Also make sure your instance has a default region defined via `aws configure`.

### Example Playbook

No dependencies or variables, so simply adding the role to a playbook should be sufficient.

    - hosts: servers
      roles:
         - { role: benjamin-smith.ansible-aws-inspector-agent }

###License

MIT
