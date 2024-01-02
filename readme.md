# Wick Studio's AI BOT

Wick Studio's AI Discord bot is a powerful and versatile bot designed to enhance your Discord experience. It features image text extraction, intelligent conversation, and more, all powered by the latest in AI technology.

## Features

- **Image Text Extraction**: Automatically extract and respond with the text from images sent in designated channels.
- **AI Conversation**: Engage in intelligent conversations powered by the Hercai AI model.
- **Customizable**: Works with a `config.json` file for easy customization of allowed channels and other settings.

## Prerequisites

Before you install and run the bot, make sure you have:

- Node.js installed on your machine.
- A Discord Bot Token. You can obtain one by creating a bot application in the [Discord Developer Portal](https://discord.com/developers/applications).

## Installation

1. Clone the repository or download the source code.
2. Navigate to the bot's directory.
3. Run `install.bat` to install all the required packages.

## Configuration

Create a `config.json` file in the root directory of your bot with the following structure:

```json
{
  "token": "YOUR_BOT_TOKEN",
  "allowed_channel_ids": ["ID1", "ID2"],
  "image2textChannels": ["ID3", "ID4"]
}
```

Replace `YOUR_BOT_TOKEN` with your Discord Bot Token and add the channel IDs where you want the bot to operate.

## Running the Bot

After installation and configuration, you can start the bot by running `start.bat`. This will initiate the bot and you should see it coming online in your Discord server.

## Commands

- **Image Text Extraction**: Simply upload an image to one of the designated channels, and the bot will automatically extract and reply with the text it finds.
- **AI Conversation**: Engage with the bot in any of the allowed channels for intelligent responses.

## Support

For support, questions, or to report issues, please visit [Wick Studio Discord](https://discord.gg/wicks).

## Contributing

Contributions are welcome! If you have a feature request, bug report, or pull request, please feel free to get in touch.

## License

[MIT](LICENSE)

## Acknowledgments

- Thanks to the Hercai and Tesseract.js teams for libraries.
- This bot is brought to you by Wick Studio - visit us at `discord.gg/wicks`.