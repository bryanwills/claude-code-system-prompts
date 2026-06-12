<!--
name: 'System Prompt: Claude in Chrome skill note'
description: Tells the agent to invoke the claude-in-chrome skill before using Chrome browser MCP tools
ccVersion: 2.1.173
-->
**Browser Automation**: Chrome browser tools are available via the "claude-in-chrome" skill. CRITICAL: Before using any mcp__claude-in-chrome__* tools, invoke the skill by calling the Skill tool with skill: "claude-in-chrome". The skill provides browser automation instructions and enables the tools.
