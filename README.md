# brave-debloat

A lightweight Preferences file to quickly debloat your Brave Browser user profile by applying privacy-focused, minimal settings.

---

## Compatibility

- Only compatible with [Brave Browser](https://brave.com)
- Tested on version 1.78.102

---

## Installation

> ⚠️ **Warning:** This process will delete all browser data in the selected profile (bookmarks, passwords, history, etc.). Only use on a fresh Brave installation or if you are certain you want to reset your profile.

1. Open Brave.
2. Visit any website (this updates your user profile folder).
3. Completely close Brave.
4. Download the latest Preferences file from the latest [releases page](https://github.com/RedCrafter07/brave-debloat/releases/latest).
5. Navigate to your Brave user data folder:  
   - Windows: `%LOCALAPPDATA%\BraveSoftware\Brave-Browser\User Data\`
6. Identify your profile folder (usually "Default" for new installs, or the folder with the most recent modification date).
7. *optional* Delete all contents inside that profile folder. This is not required but recommended.
8. Paste the Preferences file you've downloaded to your Brave profile (it **has to be named Preferences**)
9. Start Brave. If you see a popup warning about changed settings, confirm to keep the new settings.
10. Done! Your Brave profile is now debloated.

---

## FAQ

**Why use brave-debloat?**

Brave ships with many default features and settings enabled. This tool provides a clean, privacy-respecting starting point by disabling unnecessary features and telemetry, based on a fresh Brave installation configured for minimalism and privacy.

**Who should use this?**

- Users setting up Brave for the first time who want a clean, debloated profile.
- Not recommended for existing users with important browsing data, unless you have backed up your profile and are comfortable with a full reset.

**Is it free?**

Yes, this tool is completely free to use.

**What if it doesn’t work?**

Please open an issue on the GitHub repository, including your Brave version and operating system.

---

## Notes & Tips

- This tool is not officially affiliated with Brave Software Inc.
- For maximum privacy and performance, always keep Brave updated to the latest version.
- If you want to preserve bookmarks or passwords, export them before using brave-debloat and re-import after setup.
- For more about Brave’s privacy features and philosophy, see [Brave’s official site](https://brave.com).

---

**Disclaimer:**
Use at your own risk. This tool is provided as-is, without warranty. Always back up important data before making changes to your browser profile.
