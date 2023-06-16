# HttpStatusExtention
This is a fork of [HttpStatusExtension](https://github.com/denpadokei/HttpStatusExtention) with support for BeatLeader Star Ranking

## Dependencies  
SiraUtil  
SongCore  
[HttpSiraStatus](https://github.com/denpadokei/beatsaber-http-status)  
SongDetailsCache >= 1.2.2 
  
# Note  
BeatSaberHTTPStatus from denpadokei is needed.
  
### Status object (translated)

```js
StatusObject = {
　"performance": null | {
		"current_pp": Double, // gained PP score 
  },
  "beatmap": null | {
    "customLabel": custom difficulty name
    "pp": total PP score
    "star": ScoreSaber star ranking
    "starBL": Beatleader star ranking
    "downloadCount": number of downloads
    "upVotes": number of upvotes
    "downVotes": number of downvotes
    "rating": up- and downvotes ratio
  }
},
OtherObject = {
    "srm_queue_status": Boolean // true on open queue, false on closed queue.
}
```
