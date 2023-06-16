# HttpStatusExtention
This is a fork of [HttpStatusExtension](https://github.com/denpadokei/HttpStatusExtention) with support for BeatLeader Star Ranking

## Dependencies  
SiraUtil  
SongCore  
[HttpSiraStatus](https://github.com/denpadokei/beatsaber-http-status)  
SongDetailsCache >= 1.2.2 
  
# Note  
BeatSaberHTTPStatus from denpadokei is needed.
  
### Status object

```js
StatusObject = {
　"performance": null | {
		"current_pp": Double, // スコアに応じた取得可能PP
  },
  "beatmap": null | {
    "customLabel": 譜面の難易度につけられたカスタムラベルです。
    "pp": ランク譜面の時PPが入ります。
    "star": スコアセイバーの星
    "starBL": Beatleader Star Ranking
    "downloadCount": ダウンロード回数
    "upVotes": アップボーテ数
    "downVotes": ダウンボーテ数
    "rating": アップボーテとダウンボーテの比率みたいなもの
  }
},
OtherObject = {
    "srm_queue_status": Boolean // キューが開いてたらtrue.閉じてたらfalse.
}
```
