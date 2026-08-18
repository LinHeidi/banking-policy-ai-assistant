
# Banking Policy AI Assistant

A prototype banking policy assistant developed using IBM watsonx.ai and the Granite-4-h-small foundation model.

## Overview

This project explores how a large language model can answer banking policy questions while being constrained to information provided in a defined policy context.

The prototype was developed and evaluated using IBM watsonx.ai Prompt Lab.

## Technologies

- IBM watsonx.ai
- Granite-4-h-small
- Large Language Models (LLMs)
- Prompt Engineering

## System Workflow

The assistant receives a banking policy as context and uses the Granite model to answer user questions.

The prompt instructs the model to:

1. Use only the provided banking policy.
2. Avoid using outside knowledge.
3. Avoid inventing information.
4. State when information cannot be found in the policy.

```text
Banking Policy
      ↓
Prompt + Policy Context
      ↓
Granite-4-h-small
      ↓
Grounded Response
