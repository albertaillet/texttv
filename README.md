# Text TV

Minimal web app that shows SVT Text TV.

Deployed to [GitHub Pages](https://albertaillet.github.io/texttv/).

## References

- [SVT Text TV](https://www.svt.se/text-tv/webb/)
- [Yle Text TV](https://yle.fi/tekstitv/txt/100_0001.htm) ([på svenska](https://yle.fi/tekstitv/txt/700_0001.htm), [API](https://yle.fi/aihe/yle-ttv/json?P=700_0001))
- [Text TV on Wikipedia](https://sv.wikipedia.org/wiki/Text-TV)
- Favicon from [Text TV](https://open.spotify.com/track/3ol2uMEGSbtOZti5EOXV1Q) [image link](https://i.scdn.co/image/ab67616d00001e0232dbb7de30df821d4b64dc83)
Create the favicon with:
```shell
wget https://i.scdn.co/image/ab67616d00001e0232dbb7de30df821d4b64dc83 -O favicon.png
magick favicon.png -resize 256x256 favicon.ico
```

## Development

Serve the app locally with any static file server, for example:

```shell
python3 -m http.server
```