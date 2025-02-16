# DC-Bot

DC-Bot is a Discord bot designed to help manage your server with various features and commands.

## Setup Instructions

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/DC-Bot.git
    ```

2. Navigate to the project directory:
    ```bash
    cd DC-Bot
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Add your Discord Bot Token in `config.json`:
    ```json
    {
      "bot_token": "YOUR_BOT_TOKEN_HERE",
      "prefix": "!",
      "scripts": [
        {
          "name": "willkommen",
          "enabled": true
        },
        {
          "name": "command.command",
          "enabled": true
        }
      ],
      "commands": {
        "reload": {
          "enabled": true
        }
      }
    }
    ```

5. Run the bot:
    ```bash
    python main.py
    ```

## Adding New Strips

To add new strips, simply update the `config.json` file with new command-response pairs under the `strips` section.

## Running the Web Panel

To run the web panel for editing JSON files and controlling the bot:

1. Navigate to the `web-panel` directory:
    ```bash
    cd web-panel
    ```

2. Install the required dependencies:
    ```bash
    pip install flask
    ```

3. Run the Flask application:
    ```bash
    python app.py
    ```

4. Open your web browser and go to `http://127.0.0.1:5000` to access the web panel.

5. Use the web panel to start and stop the bot, and to edit the JSON configuration files.

6. deuland
