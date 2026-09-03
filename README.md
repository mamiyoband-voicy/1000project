# Voicy 1000回・777再生チャレンジ

マミヨと村上のVoicy 1000回記念LPです。

## 公開後の数値更新

`index.html` の末尾にある `campaign` の値を更新します。

```js
const campaign = {
  currentEpisode: 985, // 直近に公開した放送回数
  currentPlays: 10,    // 今日の対象放送の再生回数
  targetEpisode: 1000,
  targetPlays: 777
};
```

- `currentEpisode` を更新すると、1000回目までの残り回数が変わります。
- `currentPlays` を更新すると、今回の放送の再生数・進捗バーが変わります。

## 企画の前提

- 1000回目は10月14日のライブ放送予定
- 1000回目の1放送777回再生を目指す
- 達成特典はコメントをもとに検討中
