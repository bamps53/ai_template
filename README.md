# claude code

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash
source ~/.bashrc
nvm install --lts
npm install -g @anthropic-ai/claude-code

# uv
curl -LsSf https://astral.sh/uv/install.sh | sh
source $HOME/.local/bin/env 
