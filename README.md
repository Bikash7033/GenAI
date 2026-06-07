# GenAI

# Create Python Virtual Environment
python -m venv .venv

# Activate on Non-Windows
source .venv/bin/activate

# Activate on Windows
.venv\Scripts\Activate.ps1
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser

# Install Package manager
python -m pip install --upgrade pip

# Install openai and python-dotenv modules
python -m pip install openai python-dotenv


(.venv) (base) hemant@Hemants-Mac-mini gen_ai % pip install -U openai langchain langchain-openai langchain-community langchain-text-splitters faiss-cpu pypdf python-dotenv pydantic