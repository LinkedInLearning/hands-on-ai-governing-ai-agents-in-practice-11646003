# Governing AI Agents: Visibility and Control
This is the repository for the LinkedIn Learning course `Governing AI Agents: Visibility and Control`. The full course is available from [LinkedIn Learning][lil-course-url].

![lil-thumbnail-url]

## Course Description

_See the readme file in the main branch for updated instructions and information._

You’ll learn how to:
- Identify and document AI agents operating in a system using a structured agent inventory.
- Assess agent capabilities, permissions, and risk levels to establish visibility and accountability.
- Implement runtime guardrails that restrict agent actions and data access.
- Enforce governance controls directly in code rather than relying on documentation or policy alone.
- Apply agent governance patterns that translate across different agent frameworks and platforms.

## Requirements
- Python 3.9+
- An [OpenAI API key](https://platform.openai.com/account/api-keys)

## Setup

1. **Clone this repo** (or download the files).
2. **Create and activate a virtual environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate   # macOS/Linux
    venv\Scripts\activate      # Windows
    ```
3. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
4. **Set your OpenAI API key or place in .env file**:
    ```bash
    export OPENAI_API_KEY="your_api_key"      # macOS/Linux
    setx OPENAI_API_KEY "your_api_key"        # Windows PowerShell
    ```