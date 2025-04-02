# DEVOPS SESSION

## Setup Instructions

### SSH Configuration
If you encounter SSH connectivity issues with GitHub:

1. Check your internet connection
2. Verify SSH key setup:
   ```bash
   ssh -T git@github.com
   ```
3. Ensure your SSH config is correct:
   ```bash
   cat ~/.ssh/config
   ```
4. Check GitHub's status: https://www.githubstatus.com/

## Common Issues

### Cannot resolve github.com
If you see "Could not resolve hostname github.com", try:
- Check your DNS settings
- Try using the IP directly: `ssh -T git@140.82.121.4`
- Flush your DNS cache