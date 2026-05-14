# gomiq

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A fast-paced quiz game to test your knowledge of trash sorting. Based on the burnable/non-burnable classifications for Sabae City, Japan, your goal is to correctly identify and "burn" the right items in each round.

## Demo

Play the game live: **https://github.com/code4fukui/gomiq

## How to Play

1.  The game presents 5 different trash items.
2.  A challenge appears at the top, like "Burn 3 items!".
3.  Click on the items you believe are burnable.
    -   **Correctly** chosen items turn red.
    -   Clicking an **incorrect** (non-burnable) item reveals its proper classification and resets the round.
4.  Successfully select all the required burnable items to win the round. Your score is tracked at the bottom.

## Features

- Simple, quiz-style gameplay based on real-world trash sorting rules.
- Dynamically loads trash item data for endless variety.
- Tracks correct rounds vs. total rounds and displays a real-time success percentage.
- Reset button to start your score over at any time.

## Data & Attribution

This game uses real-world trash classification data for Sabae City, Fukui, Japan.

-   **Application:** Based on the original "ごみ燃やしゲーム" by Taisuke Fukuno ([福野泰介の一日一創](http://fukuno.jig.jp/1514)). (APP: CC BY)
-   **Data:** Fetched live from the [odp SPARQL Endpoint](http://sparql.odp.jig.jp/). (DATA: CC BY)

## License

[MIT](LICENSE)