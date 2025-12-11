FROM mcr.microsoft.com/devcontainers/universal:2-linux

# Install Python, pip, Node.js, and npm
RUN apt-get update && apt-get install -y \
    python3 \
    python3-pip \
    nodejs \
    npm \
    && rm -rf /var/lib/apt/lists/*

# Install Vue CLI globally
RUN npm install -g @vue/cli

# Install Flask
RUN pip3 install flask