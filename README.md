# yt-search
Youtube Crawler with no API that returns 3 first videos.

## Usage
```sh
const yt = require('yt_search');
let query = "search term";
yt.search(query)
.then(function(result) {
//Do something with result
});
```

## Returns
```sh
[
  {
    id: 'pRpeEdMmmQ0',
    title: 'Shakira - Waka Waka (This Time for Africa) (The Official 2010 FIFA World Cup™ Song)',
    time: '3:31',
    link: 'https://www.youtube.com/watch?v=pRpeEdMmmQ0',
    thumbnail: 'https://i.ytimg.com/vi/pRpeEdMmmQ0/hqdefault.jpg'
  },
  {
    id: '1zacYmrdexA',
    title: 'Waka Waka (This Time for Africa) - Shakira (Lyrics) 🎵',
    time: '4:02',
    link: 'https://www.youtube.com/watch?v=1zacYmrdexA',
    thumbnail: 'https://i.ytimg.com/vi/1zacYmrdexA/hqdefault.jpg'
  },
  {
    id: 'gVfgTw_W_JY',
    title: 'Just Dance 2018 • Waka Waka (Football Version)',
    time: '3:59',
    link: 'https://www.youtube.com/watch?v=gVfgTw_W_JY',
    thumbnail: 'https://i.ytimg.com/vi/gVfgTw_W_JY/hqdefault.jpg'
  }
]
```

