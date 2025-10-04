# Snekbooru

A feature-rich desktop application for browsing and managing content from various image boards.

## Disclaimers
  - **THIS IS NOT A WRAPPER FOR THE PyPi PROJECT [Snakebooru](https://pypi.org/project/snakebooru)**
  - **THIS PROJECT IS SOURCE CLOSED, FOR MORE INFORMATION AND INQUIERIES PLEASE CONTACT THE CREATOR AND DEVELOPER atroubledsnake**

## Features

### Content & Sources
- **Multi-Source Support**: Browse content from multiple built-in sources:
  - Gelbooru, Danbooru, Konachan, Yandere, Rule34, Hypnohub, Waifu.pics
- **Combined Search**: Search across all sources simultaneously for a massive content pool.
- **Custom Sources**: Add your own favorite booru sites to the application.

### Media & Viewing
- **Rich Media Handling**: View both images and videos seamlessly.
- **Full-Screen Viewer**: An immersive, multi-process media viewer with zoom and video controls that won't freeze the app.
- **Efficient GIF Handling**: GIFs are converted to WebP on the fly for smoother playback.
- **Automatic Video Support**: Plays most video formats automatically (requires VLC Media Player).

### Search & Organization
- **Tag-Based Searching**: Powerful tag search with auto-completion to find exactly what you're looking for.
- **Reverse Image Search**: Find the source of an image using SauceNAO, IQDB, or Google Lens.
- **Favorites System**: Save your favorite posts for easy access.
- **Personalized Recommendations**: Get content suggestions based on your favorites and search history.
- **Bulk Downloading**: Download multiple posts at once with a progress tracker.
- **Blacklist System**: Filter out unwanted content using a personal tag blacklist.
- **Search History**: Quickly access your previous searches.

### AI & Personalization
- **AI Chat Assistant**: Chat with a built-in AI assistant that is knowledgeable about art and imageboards.
- **AI Personalization**: Customize your AI's name, personality, and behavior with a system prompt and personality sliders.
- **Customizable Theming**: Style the entire application using a simple but powerful sCSS (Snekbooru CSS) system.
- **Incognito Mode**: Browse privately without affecting your history or recommendations.
- **Multilingual Support**: The application is available in multiple languages.

### Fun & Games
- **Random Post/Tag**: Discover new content and tags with the click of a button.
- **Tag Suggestion System**: Get ideas for new tags to explore.
- **Multiple Minigames**: Test your knowledge and have fun with several built-in games:
  - Tag Guesser, Score Showdown, Missing Tag, Guess the Score

## Download
Windows only for now
- Link: [WIN_Snekbooru_Installer_x64](https://github.com/atroubledsnake/Snekbooru/releases/download/v5.0.2/WIN_Snekbooru_Installer_x64.exe)

## Installation

1. Run the Snekbooru installer (WIN_Snekbooru_Installer_x64.exe)
2. Follow the installation wizard
3. Launch Snekbooru from your Start Menu or desktop shortcut

### System Requirements

- Windows 7 or later (64-bit)
- 4GB RAM recommended
- VLC Media Player 64-bit (required for video playback)
- Internet connection

## First-Time Setup

1. On first launch, you'll be prompted to configure your settings.
2. **(Optional but Recommended)** Enter API keys for enhanced access:
   - Gelbooru: User ID and API Key
   - Danbooru: Login and API Key
   - Rule34: User ID and API Key
   - AI Chat: OpenRouter.ai API Key (free)

### Getting API Keys

- **Gelbooru**: Available with a [Gelbooru account](https://gelbooru.com/index.php?page=account&s=reg).
- **Danbooru**: Available with a [Danbooru account](https://danbooru.donmai.us/users/new).
- **Rule34**: Available with a [Rule34 account](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwiBnqiH1KuPAxUrEhAIHQ4mIeoQFnoECAoQAQ&url=https%3A%2F%2Frule34.xxx%2Findex.php%3Fpage%3Daccount%26s%3Dreg&usg=AOvVaw3TBT0l81tteZ1h8o6JIaHA&opi=89978449).
- **AI Chat (OpenRouter)**: Get a free key from [OpenRouter.ai](https://openrouter.ai/), a gateway for various AI models.

The application works without API keys but may have reduced functionality or be subject to stricter rate limits.

## Basic Usage

### Searching
1. Select your preferred source from the dropdown menu in Settings.
2. Enter tags in the search box (e.g., "cat_ears rating:safe").
3. Click "Search" or press Enter.

### Downloading
- **Single File**: Click a thumbnail, then use the "Quick Download" button in the Post Inspector.
- **Bulk Download**: Ctrl/Shift+Click thumbnails to select them, then use the "Download Selected" button.

### Favorites
- Add/remove favorites via the star button in the Post Inspector or by right-clicking a thumbnail.
- View all your favorites in the "Favorites" tab.
- Recommendations in the "Browser" tab improve based on your favorites and history.

### Reverse Image Search
1. Go to the "Browser" tab, then the "Reverse Search" sub-tab.
2. Drag and drop an image, paste an image from your clipboard, or upload a file. You can also paste an image URL.
3. Select a search engine (SauceNAO, IQDB, Google Lens).
4. Click "Search".

## Advanced Usage

### AI Chat
The AI tab provides a chat interface with a customizable assistant.
- **Setup**: Go to `Settings -> AI API` and enter your free API key from OpenRouter.ai.
- **Personalization**: In the AI tab, go to "Personalisation" to change the AI's name, system prompt (its personality and rules), and adjust sliders for tone and creativity.

### Customizing Appearance
Snekbooru uses a custom styling language called **sCSS** to give you full control over the application's look and feel.
1. Go to `Settings -> Appearance`.
2. Click "New" to create a new theme file. It will open in the built-in sCSS editor, pre-filled with an example.
3. Click "Styling Help" for a detailed guide on all available selectors and properties.
4. Save your changes, then select your new theme from the "Active Theme" dropdown.

### Adding Custom Sources
You can add other booru-style websites to the application.
1. Go to `Settings -> Custom Sources`.
2. Click "New" to open the Booru Editor.
3. Use the "Simple" mode for common booru types (Gelbooru, Danbooru, Rule34) by just providing a name and URL.
4. Use the "Advanced" mode for full control over API endpoints for unsupported site types.
5. Test your configuration before saving. Your new source will appear in the source dropdown in Settings.

## Troubleshooting

### Video Playback Issues
- Ensure VLC Media Player (64-bit) is installed
- Try reinstalling VLC if videos won't play

### Performance Tips
- Reduce the number of grid columns for slower connections
- Lower the thumbnail size if loading is slow
- Clear search history periodically for better performance

### Common Issues

1. **"Failed to load" on thumbnails**
   - Check your internet connection
   - The post might have been deleted from the source.
   - Try refreshing the page

2. **API Errors**
   - Verify your API keys in Settings.
   - You might be rate-limited; wait a few minutes and try again.
   - Check if the source website is online

3. **Download Issues**
   - Ensure you have write permissions to the download folder
   - Check available disk space
   - Try changing the download location in Settings

## Support

For bug reports, feature requests, and community discussion, please join our Discord server or contact the developers.
- **Discord**: https://discord.gg/BqNxn7ftqn
- Creator: atroubledsnake
- Contributors: pathetic.dev (Discord) - [Portfolio](https://pathetic.dev), 69st (Discord), 572.labman (nikolai.lol) (Discord)

## Changelog
### Release Version 5.0.2
- Introduced a better way to choose sources (via checkboxes) - this now allows mixing different sources instead of all or just one.
- Refactored the downloads tab:
    - Added tag saving
    - introduced thumbnail viewing.
- Refactored favorites tab:
    - Added categories/catalogues.
    - Changed the positioning and size of the post inspector.
- Minor stability improvements.
### Release Version 5.0.0
  - Overhauled the **AI Chat Assistant**:
    - Implemented response streaming for faster, more interactive conversations.
    - Added support for multiple, renameable chat tabs to organize conversations.
    - Introduced customizable AI Presets to easily switch between different AI models, names, and personalities.
  - Added a **Hotkeys** tab in Settings, allowing for full customization of application keyboard shortcuts.
  - Added a "Go to Page" input field for direct page navigation in the browser.
  - Changed settings layout for a more user-friendly experience.
    - Added special toggles to quickly blacklist harmful content.
    - Grouped all API keys into one singular tab for ease of use.
    - Fixed bugs involved with styling the settings tab.
  - General stability improvements and major bug fixes.
### Release Version 4.9.4
  - Added AI Chat Assistant with advanced personalization options.
  - Added Reverse Image Search tab with support for SauceNAO, IQDB, and Google Lens.
  - Added a link to the official Discord server on the home page.
  - Completely overhauled the README with detailed documentation for all features.
  - Minor bug fixes and performance improvements.
### Release version 4.8.7
  - Added custom styling using sCSS (documentation provided in settings)
  - Added support for multiple languages
  - New logo and improved scraping
  - Added incognito mode
  - Added a section for adding your own api
  - Improved the recommendations bot even further
  - Fixed multiple visual bugs
### Release Version 4.8
  - Fixed major bug causing frequent crashes in the video player.
  - Added more and improved video and sound controls.
  - Upgraded the recommendations robot.
### Release Version 4.7.4
  - Multiprocessing implemented in order to stop app from crashing if a media causes VLC to crash.
### Release Version 4.6.1
  - Fixed major bug causing crashes after searching for a second time.
## Credits

- Creator & Developer: atroubledsnake
- Developer: pathetic.dev
- Testers & Idea Contributors: 69st and nikolailol

Special thanks to all users who provided feedback and suggestions!
