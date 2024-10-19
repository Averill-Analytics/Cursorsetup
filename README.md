![image](https://github.com/user-attachments/assets/0060e10c-bfc8-4f7c-afe7-059f3f3fbfe7)
# Cursor AI Setup Guide

Cursor AI is a modern code editor powered by AI that helps developers write, understand, and transform code more efficiently. This guide will help you get started with Cursor AI and configure it for your development workflow.

## Installation

1. Download Cursor AI from the official website: [https://cursor.sh/](https://cursor.sh/)
2. Follow the installation instructions for your operating system:
   - **Windows**: Run the downloaded installer
   - **macOS**: Drag the app to your Applications folder
   - **Linux**: Extract and run the AppImage

## Authentication

1. Launch Cursor AI
2. Sign in with your preferred method (GitHub or email)
3. If using your own OpenAI API key:
   - Go to Settings > AI
   - Enter your OpenAI API key
   - (Optional) Configure model preferences

## Key Features

- **AI Chat**: Press `Cmd/Ctrl + K` to open the AI chat
- **Code Generation**: Press `Cmd/Ctrl + L` for inline code suggestions
- **Code Explanation**: Highlight code and press `Cmd/Ctrl + I`
- **Terminal Integration**: Built-in terminal with AI assistance
- **Git Integration**: Native Git support with AI-powered commit messages

## Project Configuration
To make the most of Cursor setting up specific rules and documentation references can make all the difference between spinning your wheels and saving hours or days of work. 

### Basic Configuration
Create a `.cursorrules` file in your project root to customize Cursor's behavior.  This will act similar to a pre-prompt for a regular chat ai model, Cursor will use this as a guide for how to respond to questions and what style and methods to generate code for you in. 

1. Create the file: `.cursorrules` in the root folder of your project
      Here's  an example of one: 
2. Fill out with the details that best fit your project.  For commonly used frameworks you can start with [cursor.directory](https://cursor.directory)
4. Restart Cursor to apply changes

### Documentation References
To increase response accuracy, especially if you need to be using a specific version of tool or one that is newer and not widely used, you can tell Cursor specifically where to look when developing a response for you.  
1. Go to **Settings>Features** and scroll down to **Docs**
2. From here you can set what to reference, it works best when you specify the docs url not just the base domain
   Example:
   For Next.js use the url https://nextjs.org/docs

## Extensions
To install extensions go to [Visual Studio Marketplace](https://marketplace.visualstudio.com/vscode) 
1. Download the desired extension \
   <img src="https://github.com/user-attachments/assets/b1e36073-5349-4671-b56c-0652980c251c" width="200"> 
2. Navigate to the extension pane within cursor \
   <img src="https://github.com/user-attachments/assets/bbb4ae68-cb43-4975-b662-f98139b03646" width="200"> 
3. Drag and drop the downloaded file into the extension pane \
   <img src="https://github.com/user-attachments/assets/8b3eb188-5656-4ae9-9b60-e1d82b860d89" width="200"> 

### Helpful Extensions
- [**Prettier**](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode): Code formatting
- [**ESLint**](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint): Code linting
- [**GitLens**](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens): Enhanced Git functionality
- [**Path Intellisense**](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense): Autocomplete file paths



## Support and Resources

- Documentation: [https://cursor.sh/docs](https://cursor.sh/docs)
- GitHub Issues: [https://github.com/getcursor/cursor/issues](https://github.com/getcursor/cursor/issues)
- Discord Community: [https://discord.gg/cursor](https://discord.gg/cursor)

