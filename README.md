# OwoFarm

A fully automated farming bot for the popular Owo bot on Discord. This bot is designed to automate various Owo bot commands like hunting, battling, and more, helping you collect resources and improve your gameplay.

## Features

- **Auto Hunting (`owo hunt`)**: Automatically hunts for animals with customizable intervals.
- **Auto Battling (`owo battle`)**: Engage in battles with predefined strategies and commands.
- **Customizable Timing**: Set intervals between commands to avoid detection.
- **Auto Use of Gems**: Automatically uses gems in the game without manual intervention.
- **Auto Quest Checking**: Automatically checks for available quests and updates quest progress.
- **Automatic Zoo View**: Automatically displays the zoo collection and updates it in real-time.
- **Daily Claim Automation**: Automatically claims daily rewards without user input.
- **Calculating Exp from Hunting**: Automatically calculates experience points earned from hunting.
- **Auto Inventory Item Collection**: Automatically collects all items available in the player's inventory.
- **Auto Use of Lootbox/Fabled Lootbox/Crate**: Automatically opens lootboxes, fabled lootboxes, and crates.
- **Owo Pray/Curse Automation (Set Target)**: Automatically performs `owo pray` or `owo curse` commands, with the option to set a target.
- **Owo Cookie Automation (Set Target)**: Automatically sends `owo cookie` with the ability to specify a target.
- **Dynamic Configuration Without App Restart**: Allows configuration updates dynamically without restarting the application.
- **Anti-Detection Measures**: Implements randomization in command timings to reduce the risk of being flagged by Discord or Owo bot's anti-bot systems.
- **Support for Multiple Accounts**: Can be configured to run on multiple Discord accounts.

## Setup & Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/xdgjndudhdnnz-coder/owofarm.git
   cd owofarm
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Configure the bot:
   - Copy `.env.example` to `.env`
   - Update the `.env` file with your Discord token and any required Owo settings
   - Customize the bot's settings in `src/config/config.ts` as needed

4. Build the bot:
   ```bash
   npm run build
   ```

5. Run the bot locally:
   ```bash
   npm start
   ```

## Railway Deployment

This project is compatible with Railway. To deploy:

1. Connect the GitHub repository to Railway.
2. Add the required environment variable:
   ```env
   TOKEN=your_discord_token_here
   ```
3. Use the default Node/Nixpacks build.
4. Set the start command:
   ```bash
   npm start
   ```

You can also use the included `railway.json` file for the deployment configuration.

## Notes

- Use this bot responsibly and at your own risk. Automating Discord bots can potentially violate Discord’s and Owo bot’s terms of service.
- This project is meant for educational purposes only.

---

This description provides a clear overview of the bot's purpose, features, setup instructions, and important disclaimers, ensuring potential users understand its functionality and risks involved.
