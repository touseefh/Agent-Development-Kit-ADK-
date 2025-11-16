# Getting Started with the Agent Development Kit (ADK)

This lesson provides an introduction to the Agent Development Kit (ADK) and guides you through the process of creating and running your first AI agent.

## 1.1 Getting Started

The lesson begins by ensuring the necessary Python packages, specifically `google-adk`, are installed. It also imports a helper module and loads environment variables, which is a common practice for managing configuration and secrets.

## 1.2 Setting Up Your First Agent

This section explains how to create a new agent project using the `adk create` command. This command scaffolds a new project directory with the following essential files:

- `.env`: For storing API credentials and other configuration variables.
- `__init__.py`: Marks the directory as a Python package.
- `agent.py`: The main file where you'll implement your agent's logic.

The lesson also introduces the `--type` and `--model` parameters for the `adk create` command, which allow you to specify the project type (code or config) and the language model to be used.

## 1.3 Writing Your First `agent.py`

Here, you'll write the code for your first agent. The agent is a simple AI News Assistant that uses the `gemini-2.0-flash-live-001` model. The code is written to the `agent.py` file within the `app_01` directory.

## 1.4 Running Your First Agent

This section explains how to run your agent using the ADK Web UI. You'll learn how to start the local server and access the Web UI to interact with your agent.

## 1.5 Adding Tools to Your Agent

This section demonstrates how to extend your agent's capabilities by adding tools. Specifically, it shows how to add the `google_search` tool to your agent, enabling it to search for recent AI news.

## 1.6 Adding a Text Model

This section shows how to create a new agent that uses a different language model, `gemini-2.5-flash`. This demonstrates the flexibility of the ADK in allowing you to easily switch between different models.

## 1.7 Alternative Development Approaches

The ADK also supports a declarative approach to agent development using YAML files. This section shows how to create an agent using a YAML configuration file, which is ideal for rapid prototyping and for those who prefer a declarative style of development.

## 1.8 Fine-tuning Agent Instructions

Finally, the lesson demonstrates how to fine-tune your agent's behavior by providing more specific instructions. This allows you to create more specialized agents that are better suited for specific tasks.
