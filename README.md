# Ansible Role: amz-cloudwatch-agent

Ansible role to download, install and run Amazon CloudWatch Agent.

This role will initialise and start the agent with a simple file based config. You can overwrite this
by simply pointing the `amz_cwagent_agent_template` and/or `amz_cwagent_agent_template` variables
to different templates.

Note: "ssm" configs are not currently supported.

## License

MIT / BSD
