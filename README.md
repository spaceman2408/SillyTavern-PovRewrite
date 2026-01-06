# POV Rewrite Extension for SillyTavern

Convert character cards to first-person perspective using AI.

## Installation

1. Install: Extensions → Install extension → `https://github.com/spaceman2408/pov-rewrite`
2. Open any character and find the "💬" button

## Usage

1. Open a character in edit mode
2. Click the comments icon (💬) in the character panel
3. Review the prompt preview
4. Click "Start Rewrite"
5. Wait for the AI to process
6. Preview and apply changes

## Settings

- **Enable Extension**: Show/hide the rewrite button
- **Max Response Tokens**: Increase for longer character cards (default: 4000)
- **Show Preview Before Applying**: Review changes before applying
- **Prompt Template**: Customize the conversion prompt
- **Fields to Rewrite**: Select which character fields to convert:
  - Description
  - Personality
  - First Message
  - Example Messages
  - Alternate Greetings

## How It Works

1. Extracts selected text fields from the character card
2. Sends data to your configured AI model
3. Receives rewritten fields in JSON format
4. Updates only the selected fields to first-person perspective
5. Preserves character name, tags, and other metadata

## Requirements

- SillyTavern with AI backend configured
- AI model that supports JSON output (OpenAI, Claude, etc.)

## Troubleshooting

**Button not visible**: Enable "Show Rewrite Button" in extension settings.

**AI errors**: Ensure your AI backend is properly configured.

**Poor quality output**: Adjust the prompt template or increase max tokens.

## License

MIT License

## Author

spaceman2408