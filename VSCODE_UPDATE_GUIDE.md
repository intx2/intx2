# VS Code Update Guide

## Important: VS Code is Free!

**Visual Studio Code (VS Code) is completely free and open-source.** You do not need to pay any subscription fees to use or update VS Code.

## Common Misconceptions

### VS Code vs Visual Studio
- **VS Code** (Visual Studio Code): Free, lightweight, open-source code editor
- **Visual Studio**: Different product with both free (Community) and paid (Professional/Enterprise) versions

### What Might Require Subscriptions?
While VS Code itself is free, some services and extensions may require subscriptions:
- **GitHub Copilot**: AI pair programmer (requires subscription)
- **Azure DevOps**: Cloud services (may require subscription)
- **Various marketplace extensions**: Some premium extensions may have costs

## How to Update VS Code

### Automatic Updates (Recommended)
1. VS Code automatically checks for updates
2. When an update is available, you'll see a notification
3. Click the notification and follow the prompts to update

### Manual Update Methods

#### Windows
1. Download the latest version from https://code.visualstudio.com/
2. Run the installer
3. The installer will update your existing installation

#### macOS
1. Download the latest version from https://code.visualstudio.com/
2. Open the downloaded .zip file
3. Drag the Visual Studio Code app to your Applications folder (replace existing)

#### Linux (Ubuntu/Debian)
```bash
# If installed via .deb package
sudo apt update
sudo apt upgrade code

# If installed via Snap
sudo snap refresh code
```

#### Linux (Fedora/RHEL)
```bash
sudo dnf check-update
sudo dnf upgrade code
```

### Check Your Current Version
1. Open VS Code
2. Go to **Help** > **About** (or **Code** > **About Visual Studio Code** on macOS)
3. You'll see your current version number

### Enable/Disable Automatic Updates
1. Open VS Code settings (File > Preferences > Settings or Code > Preferences > Settings on macOS)
2. Search for "update mode"
3. Set `Update: Mode` to:
   - `default`: Check for updates automatically
   - `manual`: Never check for updates automatically
   - `start`: Check for updates on startup

## Troubleshooting Update Issues

### Issue: "No updates available" but you know there's a newer version

**Solution 1: Check Update Mode**
- Ensure automatic updates are enabled (see above)
- Restart VS Code

**Solution 2: Manual Download**
- Visit https://code.visualstudio.com/
- Download and install the latest version manually

**Solution 3: Check Installation Method**
- If installed via package manager (apt, snap, brew), update through that
- If installed manually, download the new version from the website

### Issue: Update fails or VS Code won't start after update

**Solution 1: Clean Reinstall**
1. Uninstall VS Code completely
2. Download fresh installer from https://code.visualstudio.com/
3. Install the new version
4. Your settings and extensions are stored separately and will be preserved

**Solution 2: Check Permissions**
- On Linux/macOS, ensure you have write permissions to the installation directory
- On Windows, try running the installer as Administrator

### Issue: Extensions not working after update

**Solution:**
1. Go to Extensions view (Ctrl+Shift+X or Cmd+Shift+X)
2. Check for extension updates
3. Update all extensions
4. Reload VS Code

## Still Having Issues?

If you're still experiencing problems:

1. **Check the VS Code documentation**: https://code.visualstudio.com/docs
2. **VS Code GitHub Issues**: https://github.com/microsoft/vscode/issues
3. **Stack Overflow**: Search for your specific issue
4. **VS Code Community**: https://github.com/microsoft/vscode/discussions

## Summary

Remember:
- ✅ VS Code is completely free
- ✅ No subscription is required for updates
- ✅ Updates are usually automatic
- ✅ You can always download the latest version from the official website
- ⚠️ Some extensions or services (like Copilot) may require subscriptions, but not VS Code itself

If you paid for something thinking it was required for VS Code updates, you may want to:
1. Check what you actually subscribed to
2. Determine if it's a service you actually need (like GitHub Copilot)
3. Cancel if it was purchased in error
