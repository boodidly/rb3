# Terminal UI

A beautiful, modern terminal interface with customizable buttons and themes.

## Installation on Arch Linux

### Prerequisites

1. Update system packages:
```bash
sudo pacman -Syu
```

2. Install required dependencies:
```bash
sudo pacman -S nodejs npm python
```

### Installation Steps

1. Clone the repository:
```bash
git clone https://github.com/yourusername/terminal-ui
cd terminal-ui
```

2. Install project dependencies:
```bash
npm install
```

3. Create required Python script:
```bash
echo '#!/usr/bin/env python3

def main():
    print("Checking mail...")
    print("No new messages.")

if __name__ == "__main__":
    main()' > .mail_064.py
```

4. Make the Python script executable:
```bash
chmod +x .mail_064.py
```

### Running the Application

1. Start the development server:
```bash
npm run dev
```

2. Open your browser and navigate to:
```
http://localhost:3000
```

## Features

- **Custom Commands**: Add your own command buttons with the '+' button
- **Theme Customization**: Adjust colors and glow effects
- **Built-in Tools**:
  - Mail Checker
  - Node.js REPL
  - NPM Interface
  - JSON Tools
  - Application Importer

## Usage

### Default Buttons
- **Check Mail**: Runs the mail checking script
- **Node.js**: Opens Node.js REPL
- **NPM**: Shows NPM command interface
- **JSON Tools**: Provides access to JQ
- **Import Application**: Import external applications

### Custom Buttons
1. Click the '+' button
2. Enter button name and command
3. Click 'Add Button'

### Removing Buttons
1. Click the trash icon
2. Select buttons to remove
3. Click again to exit delete mode

### Theme Customization
1. Click the settings icon
2. Adjust colors and effects
3. Changes apply immediately

## Keyboard Shortcuts

- **Double-click**: Toggle fullscreen terminal
- **Esc**: Exit fullscreen mode

## System Requirements

- Arch Linux
- Node.js 18+
- NPM 8+
- Python 3.x
- Modern web browser

## License

MIT License - See LICENSE file for details