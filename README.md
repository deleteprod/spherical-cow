# spherical-cow
Example of an agent built in Python using the Claude Agent SDK. Amend the agent.py script to suit your own requirements in an agent.
# Usage
Requires that you build a suitable Python Virtual Environment (venv) to execute:
`python3 -m venv .venv` 

Activate the venv:
`source .venv/bin/activate`

Install Claude Agent SDK:
`pip install claude-agent-sdk`

Execute agent: 
`python3 agent.py` 
# agent file options
Main settings you’ll adjust:

Tools. `Read/Glob/Grep` give read-only analysis. Adding `Edit` lets the agent modify files. Adding `Bash` gives full automation. `WebSearch` adds web access.
`permission_mode` sets how much human approval the agent needs.
`system_prompt` sets the agent’s role and rules.
`mcp_servers` connects the agent to databases, APIs and other external systems. This is how you’d point it at your own data sources.

[Agent SDK Quickstart](https://code.claude.com/docs/en/agent-sdk/quickstart)
