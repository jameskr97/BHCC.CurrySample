FROM node:21

# Install curl and any other dependencies
RUN apt-get update && apt-get install -y \
    curl \
    && rm -rf /var/lib/apt/lists/*

# Run the installation script
RUN curl -fsSL https://bun.sh/install | bash

