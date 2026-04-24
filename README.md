# AutoSubs — AI-Powered Subtitles for After Effects

![GitHub Release](https://img.shields.io/github/v/release/ventriquo/AutoSubs-ae-extension?include_prereleases&label=Version)
![GitHub Downloads](https://img.shields.io/github/downloads/ventriquo/AutoSubs-ae-extension/total)
![Price](https://img.shields.io/badge/Price-%2415%2Fmonth-brightgreen)
![After Effects](https://img.shields.io/badge/After%20Effects-CC%202014%2B-blue)

## Automatically generate professional subtitles in After Effects using AI transcription

AutoSubs brings the power of AI-driven transcription directly into your After Effects workflow. No more exporting audio, using external tools, or importing SRT files — everything happens inside AE with a seamless 4-screen workflow: **Transcribe → Review & Edit → Style → Apply**.

### Why creators choose AutoSubs

🎯 **Accurate AI Transcription**  
Powered by Groq Whisper API (cloud-based), so you don't need a powerful GPU or complex local setup. Just install the plugin and transcribe directly from your AE layers.

📝 **Built-in Transcript Editor**  
Review, edit, split, and merge subtitle chunks with real-time preview in After Effects. Word-level timestamp precision ensures perfect synchronization.

🎨 **Professional Style System**  
Choose from 3 designer presets (MrBeast, Minimal, Cinematic) or customize fully in Advanced mode with editable text layers. Simple mode uses expression-driven single layers for optimal performance.

🔐 **Secure & Flexible Licensing**  
Your subscription provides one license usable on up to 2 active devices. Easily manage devices from your dashboard — deactivate an old one to add a new one when switching workstations.

⚡ **Seamless AE Integration**  
Bundled FFmpeg extracts audio directly from selected layers. Session management keeps you logged in, and automatic version checks ensure you always have the latest features.

### How it works

1. **Get your license**  
   Purchase a subscription ($15/month) via our secure Mayar payment system

2. **Install the extension**  
   Download the latest `.zxp` file from [GitHub Releases](https://github.com/ventriquo/AutoSubs/releases)  
   Install manually:  
   - Copy `dist/` contents to `%APPDATA%\Adobe\CEP\extensions\com.autosubs.plugin`  
   - Or run `install-manual.ps1` from the repository  
   - Enable debug mode in AE (required for unsigned extensions)

3. **Start creating subtitles**  
   Open AutoSubs from Window > Extensions  
   Select an audio layer in After Effects  
   Follow the workflow: Transcribe → Review & Edit → Style → Apply  
   Enjoy professional subtitles in minutes!

### What you get

- ✅ Cloud-based AI transcription (no local AI setup)
- ✅ Complete subtitle workflow inside After Effects
- ✅ Three professional preset styles + full customization
- ✅ Device flexibility (2 active devices per license)
- ✅ Automatic updates and version checks
- ✅ Priority support and continuous improvements
- ✅ Admin key system for teams and studios (available upon request)

### System Requirements

- **After Effects**: CC 2014 or later (Windows/Mac)
- **Internet Connection**: Required for transcription and license validation
- **Note**: Node.js 18+ only needed for development (not for end users)

### Support & Resources

- **Email Support**: support@autosubs.xyz
- **Documentation**: See the [WORKFLOW.md](https://github.com/ventriquo/AutoSubs/blob/main/WORKFLOW.md) for technical details
- **Release Notes**: Available in each GitHub Release
- **Version Check**: Plugin automatically checks for updates on startup
- **API Status**: Backend at `https://api.autosubs.xyz` (FastAPI + Neon PostgreSQL on Railway)

---

*AutoSubs is developed and maintained by @ventriquo. Join hundreds of creators who are already saving hours on subtitle work every week.*  
*For business inquiries or team licensing, contact support@autosubs.xyz*

[Download Latest Release →](https://github.com/ventriquo/AutoSubs/releases)
