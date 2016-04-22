# Ansible AWS Inspector Agent Role

Installs the [AWS Inspector Agent](http://docs.aws.amazon.com/inspector/latest/userguide/inspector_introduction.html).

### Example Playbook

No dependencies or variables, so simply adding the role to a playbook should be sufficient.

    - hosts: servers
      roles:
         - { role: benjamin-smith.ansible-aws-inspector-agent }

###License

MIT
