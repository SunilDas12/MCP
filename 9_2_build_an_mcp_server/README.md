# Use uv in project in VS code

step-1: pip install uv
step-2: uv init 'your projrct name'
step-3: cd 'your project name'
step-4: uv venv
step-5: uv add "mcp[cli]" httpx python-dotenv requests  / uv add -r requirements.txt
step-6: uv run main.py
step-7: uv lock    (opt: lock your dependancies)

step-8: uv run mcp dev weather.py  (Run in developer mode console(Inspector))