song-downloader
============
search youtube and download audio files from a csv list

relies on [youtube-dl](https://github.com/rg3/youtube-dl) python package behind the scenes

Usage
-------
get a youtube data API key and place inside of `~/.config/youtube-csv-dl/config.json`:

```json
{  "YOUTUBE_API_KEY": "xxxxx" }
```

run the downloader with:

```shell
node song-downloader.js [songlist.csv]
```

csv file input format:

```
song name; artist name (optional); album name (optional);
```


License
--------
MIT License

Copyright (c) 2017 Alex Ehrnschwender (http://ehrns.com/)
 
Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:
 
The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.
 
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

