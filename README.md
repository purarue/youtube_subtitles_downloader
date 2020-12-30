# Youtube Subtitles Downloader

Forked from [here](https://github.com/vvigilante/youtube-subtitles-downlaoder) to use as a submodule for [`url_metadata`](https://github.com/seanbreckenridge/url_metadata)

I prefer this to `youtube-dl` since this also downloads automatically generated subtitles, which gives me access to much more info.

Used as a git submodule 'python package' instead of a CLI tool

```python
from youtube_subtitles_downloader import download_subs
download_subs("YoMUQXgcH94", "en")
```

# Acknowledgements
- Original js implementation: https://github.com/syzer/youtube-captions-scraper/blob/master/src/index.js
- SRT conversion: http://code.activestate.com/recipes/577459-convert-a-youtube-transcript-in-srt-subtitle/
