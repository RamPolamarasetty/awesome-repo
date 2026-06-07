# Awesome Repo

This repository was created by the Pi coding agent.

## Purpose

This repo contains the initial setup for a coding session. Clone it on your MacBook and follow the instructions to get started.

## Getting Started on macOS

```bash
# Clone the repository
git clone https://github.com/<YOUR_USERNAME>/awesome-repo.git
cd awesome-repo

# Install any dependencies (if applicable)
# e.g., npm install

# Run the initial script or start coding
# e.g., ./setup.sh
```

Replace `<YOUR_USERNAME>` with your GitHub username.

## Importing Configuration on macOS (AI)

The following steps allow the Pi AI agent to import the same configuration on your MacBook:

1. **Clone the repository** (as shown above).
2. **Copy the configuration files** to the Pi directory on macOS. For example, if you have a `pi-config/` folder in this repo:
   ```bash
   cp -r pi-config/* "$HOME/.pi/"
   ```
   Adjust the target path if your Pi installation uses a different location.
3. **Restart the Pi agent** (or run the setup script) so it picks up the new configuration:
   ```bash
   pi restart   # or the appropriate command for your setup
   ```
4. **Verify the import** by checking that the expected extensions, themes, or skills are loaded:
   ```bash
   pi list   # should show the imported items
   ```

These commands can be executed directly on your MacBook, and the AI will use the imported configuration for subsequent sessions.

