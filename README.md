Use Anthropic's [computer use API](https://github.com/anthropics/anthropic-quickstarts/tree/main/computer-use-demo) and PyAutoGUI

## Installation and Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/zaarheed/anthropic-computer-use-starter.git
   cd anthropic-computer-use-starter
   ```

2. **Create a virtual environment + install dependencies:**

   ```bash
   python -m venv venv
   source venv/bin/activate
   python install -r requirements.txt
   ```

3. **Set your Anthropic API key as an environment variable:**

   ```bash
   export ANTHROPIC_API_KEY="CLAUDE_API_KEY"
   ```

4. **Grant Accessibility Permissions:**

   - Go to **System Preferences** > **Security & Privacy** > **Privacy** tab.
   - Select **Accessibility** from the list on the left.
   - Add your terminal application or Python interpreter to the list of allowed apps.

## Usage

Replace the prompt on Line 26 with your own.
