FROM node:22-bookworm

RUN apt update && apt install -y \
    git \
    curl \
    jq \
    ripgrep \
    python3 \
    build-essential

RUN npm install -g opencode-ai

WORKDIR /workspace/apps

CMD ["bash"]