# Multi-Agent AI Collaboration System

[![LangChain](https://img.shields.io/badge/LangChain-0.2.0-green)]()
[![Gemini](https://img.shields.io/badge/Google%20Gemini-1.5%20Flash-blueviolet)]()

An autonomous multi-agent system where specialized AI agents collaborate to solve complex coding tasks. Features a Planner agent that decomposes problems, an Executor agent that writes and tests code, and a Reviewer agent that ensures quality.

![Agent Collaboration Diagram](https://via.placeholder.com/800x400?text=Agent+Collaboration+Diagram)

## Key Features

- **Role-based agents** with specialized capabilities
- **Autonomous collaboration** between Planner, Executor, and Reviewer
- **Real code execution** with sandboxed testing
- **Structured output generation** for reliable task decomposition
- **Quality assurance** with automated code reviews
- **End-to-end project execution** from task to solution

## How It Works

![image](https://github.com/user-attachments/assets/b059a466-0a59-4351-89ce-eb98d7c5bd86)


Planner Agent: Breaks down complex problems into executable subtasks

Executor Agent: Generates and tests Python code for each subtask

Reviewer Agent: Analyzes code quality and identifies critical issues

Orchestrator: Coordinates the workflow and compiles the final output


##Prerequisites
Python 3.9+
Google Gemini API key
Basic Python development environment

Configuration:
Obtain a Google Gemini API key
Set the key variable in the code.

##Usage:
Run the system with a project request:

from orchestrator import Orchestrator
system = Orchestrator()
response = system.execute_project("Build a REST API for user management")
print(response)

