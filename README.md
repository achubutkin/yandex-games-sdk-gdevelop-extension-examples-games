# Examples of games for the extension for Yandex.Games SDK
Examples of games for the [GDevelop extension for Yandex.Games SDK](https://github.com/achubutkin/yandex-games-sdk-gdevelop-extension) that allows you to easily integrate games created by [GDevelop](https://gdevelop-app.com/) into the [Yandex.Games](https://yandex.com/games/) platform.

Before setting up and running the sample games, download the entire repository to your computer. Each game is placed in a separate directory along with assets.

> To download the repository, click the green "Code" (top right) button and then "Download ZIP". [Or just click on this link](https://github.com/achubutkin/yandex-games-sdk-gdevelop-extension-examples-games/archive/refs/heads/main.zip).

# Games

### Falling box
A hyper-casual game where you have to toss a box and not let it fall. This game uses user authorization and competition tables to save the player's current achievement and restore it the next time they log in. When you lose, ads are displayed.

#### Instructions 
This game displays ads, so make sure you have monetization enabled. Follow [this instruction in the official documentation](https://yandex.ru/dev/games/doc/dg/console/enable-monetization.html) to enable monetization and display ads.

This game uses competitive tables, so you need configuring that tables in Yandex Games Developer Console. For to do this: 
1. Go to the developer dashboard.
2. Select the game.
3. Go to the Leaderboards tab.
4. Add leaderboard with the following parameters. **Leaderboard string identificator** = leaderboard2021, **Main leaderboard** = yes, **Leaderboard type** = numeric. Leave the rest of the parameters as default.

Configure and run game: 
1. Open the game from **falling-box** in GDevelop.
2. Run game.

## License

MIT