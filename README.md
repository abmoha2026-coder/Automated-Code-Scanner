
# ai_detect_interactive.py 

is a lightweight Python utility that:

Prompts the user for a public GitHub repository (owner/name).
Retrieves the repository’s file tree via the GitHub API (default main branch).
Downloads source‑code files (.py, .js, .ts, .ipynb, .json, .yaml, .yml).
Scans each file with a small set of regular expressions to spot imports, require statements, or environment‑variable names that indicate usage of one of the five major AI agents: OpenAI, Anthropic, Google Gemini, Cohere, or LLaMA.
Prints a concise report showing the filenames and the detected agents, or a single line stating that no supported AI agents were found.
