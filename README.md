# Voicy 1000回・777再生チャレンジ

マミヨと村上のVoicy 1000回記念LPです。

## 日々の更新データ

LP本体を編集せず、ルートの `status.json` を更新すると表示が変わります。

```json
{
  "currentEpisode": 986,
  "currentPlays": 52,
  "latestVoicyUrl": "https://r.voicy.jp/YQm4by41MV2",
  "updatedAt": "2026-09-04T00:00:00+09:00"
}
```

|項目|意味|
|---|---|
|`currentEpisode`|直近に公開した放送回数。LPは「あと◯回で1000回」を自動計算する。|
|`currentPlays`|最新回の再生数。LPの進捗バーと表示に使う。|
|`latestVoicyUrl`|「最新のVoicyを聴きにいく」ボタンのリンク先。|
|`updatedAt`|データ確認日時の記録用。|

`status.json` が一時的に取得できない場合は、LP内に保存された直前の安全な値を表示します。値を0にしたり、リンクを空にしたりしません。

## 今後の自動更新

GitHub Appを `mamiyoband-voicy/1000project` のみに導入し、`status.json` だけを書き換える権限に限定する想定です。これにより、Discordで受け取った更新値を反映する際に毎回のGitHub端末認証を不要にできます。

## 企画の前提

- 1000回目は10月14日のライブ放送予定
- 1000回目の1放送777回再生を目指す
- 達成特典はコメントをもとに検討中
