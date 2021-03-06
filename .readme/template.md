# IPTV

Collection of 5000+ publicly available IPTV channels from all over the world. 

Internet Protocol television (IPTV) is the delivery of television content over Internet Protocol (IP) networks. 

## Usage

To watch IPTV you just need to paste this link `https://github.com/KodiTVR-add-on/iptv/index.m3u` to any player with support M3U-playlists.

![VLC Network Panel](preview.png)

Also you can instead use one of these playlists:

- `https://github.com/KodiTVR-add-on/iptv/index.country.m3u` (grouped by country)
- `https://github.com/KodiTVR-add-on/iptv/index.category.m3u` (grouped by category)
- `https://github.com/KodiTVR-add-on/iptv/index.language.m3u` (grouped by language)

Or select one of the playlists from the list below.

## Playlists by category

#include "./.readme/_categories.md"

## Playlists by language

#include "./.readme/_languages.md"

## Playlists by country

#include "./.readme/_countries.md"


## For Developers

In addition to the above methods, you can also get a list of all available channels in JSON format.

To do this, you just have to make a GET request to:

```
https://github.com/KodiTVR-add-on/iptv/channels.json
```

If successful, you should get the following response:

```
[
  ...
  {
    "name": "RTP1",
    "logo": "https://raw.githubusercontent.com/KodiTVR-add-on/IPTV_Logos/master/RTP1.png",
    "url": "http://ott-cdn.ucom.am/s27/index.m3u8",
    "category": "Information",
    "language": [
      {
        "code": "pt",
        "name": "Portuguese"
      }
    ],
    "country": {
      "code": "pt",
      "name": "Portugal"
    },
    "tvg": {
      "id": "rtp1.pt",
      "name": "RTP1",
      "url": "http://epg.streamstv.me/epg/guide-portugal.xml.gz"
    }
  },
  ...
]
```

## Resources

You can find links to various IPTV related resources in this repository [KodiTVR-add-on/iptv](https://github.com/KodiTVR-add-on/iptv).

## Contribution

Please make sure to read the [Contributing Guide](.github/CONTRIBUTING.md) before making a pull request.

If you find an error or have any suggestions on how to organize a playlist, please send an [issue](https://github.com/KodiTVR-add-on/iptv/issues).

## Legal

No video files are stored in this repository. The repository simply contains user-submitted links to publicly available video stream URLs, which to the best of our knowledge have been intentionally made publicly by the copyright holders. If any links in these playlists infringe on your rights as a copyright holder, they may be removed by sending a pull request or opening an issue. 


However, note that we have **no control** over the destination of the link, and just removing the link from the playlist will not remove its contents from the web.  Note that linking does not directly infringe copyright because no copy is made on the site providing the link, and thus this is **not** a valid reason to send a DMCA notice to GitHub. To remove this content from the web, you should contact the web host that's actually hosting the content (**not** GitHub, nor the maintainers of this repository).
