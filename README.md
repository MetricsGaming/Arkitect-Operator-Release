![Arkitect Operator](.github/ArkitectOperator_hero.png)

# Arkitect Operator

Arkitect Operator watches your ARK: Survival Ascended tribe log and sends alerts to Discord. It can also run in-game tasks for you, such as feeding dinos, farming resources, and rejoining a full server.

## Download

Download `ArkitectOperator.exe` from the [latest release](https://github.com/MetricsGaming/Arkitect-Operator-Release/releases/latest).

Windows may warn that the app is from an unknown publisher. To run it, click **More info**, then **Run anyway**.

## Requirements

- Windows
- ARK: Survival Ascended, running at 1920x1080
- An Arkitect Operator activation key
- A Discord server, if you want alerts

## What it does

Arkitect Operator has a page for each feature. Pick one from the sidebar.

| Page | What it does |
| --- | --- |
| **LogBot** | Reads the in-game tribe log and posts the events you choose to Discord. You set the trigger words, the words that skip a ping, and the cooldown. |
| **AutoSim** | Keeps trying to join the server you enter until a slot opens, then sends you a Discord message. |
| **AutoFeed** | Feeds the dino you're looking at when you press **F**. |
| **AutoFarm** | Farms resources, such as metal or stone, with the teleporters you set up. |
| **AutoAchatina**, **AutoBeer**, **AutoARB**, **AutoLevel**, **AutoClaim** | More in-game automations. Each page lists its own steps. |
| **AutoClick**, **AutoRun**, **AutoKey** | Utilities for clicking, running, and pressing a single key. |

Most automations start with **F2** or the **Run** button and stop with **F3**.

## Get started

1. Start ARK: Survival Ascended and set the game to 1920x1080.
2. Run `ArkitectOperator.exe`.
3. Enter your Discord username and your activation key when the app asks.
4. Open the **Settings** page and enter the channel IDs for your alerts. To post through your own Discord bot instead of Arkitect's, enter its token too.
5. Click **Save**.
6. Open a page, such as **LogBot**, and follow the steps on the page.

## Updates

Arkitect Operator checks for a new version each time it starts. When there is one, it downloads the update, checks that the download is intact, and restarts on its own after a short countdown. You don't need to do anything.

You can also check at any time with the refresh button (↻) in the app window.

If the app stays open for days, it doesn't restart by itself. Instead, it posts a message in your Discord alerts channel when a new version is out. Restart Arkitect Operator to update.

## Your settings

Arkitect Operator saves your settings as you use the app. They live in the `.arkitect_operator_config` folder in your Windows user folder. The `logbot_config.json` file in it holds your Discord settings, so don't share it.

## Help

For questions or problems, message **Arkitect.dev** on Discord.
