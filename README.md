# ask

A lightweight Bash command-line tool that sends prompts to an OpenAI-compatible LLM API.

## Requirements
This script uses only the following dependencies:
- `curl`
- `jq`

## Configuration
Before using the tool, you must set the following environment variables exactly as named:
```bash
export ASK_API_URL="[https://api.groq.com/openai/v1/chat/completions](https://api.groq.com/openai/v1/chat/completions)"
export ASK_MODEL="llama-3.3-70b-versatile"
export ASK_API_KEY="your_api_key_here"

## Usage Examples

./ask "Establishment dates of" "Turkey" "Azerbaijan" "Japan"

./ask "explain this shell command output:" "$(uname -a)"

cat ask | ./ask "Explain what this Bash script does in simple terms:"