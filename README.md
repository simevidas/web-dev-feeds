# Over 1000 feeds for web developers

Download feeds.opml and import it into your feed reader. I update this file once per month. Watch this repo to get notified.

## Recommended feed reader

I recommend the [Feedbro browser extension](https://nodetics.com/feedbro/), which I’m using myself. The extension continuously fetches new feed items in the background, and the UI is blazing fast. After importing the feed collection into Feedbro, you may have to wait one or a few days for all 1000+ feeds to load, but after this initialization is complete, new feed items will be shown without any noticeable delay. Below, I’m including a usage demonstration where I go through 77 new feed items and open 14 blog posts in background tabs in less than 4 minutes.

[usage.webm](https://user-images.githubusercontent.com/716405/215263231-d1089951-fb0a-4539-90b2-b54f8bbe06e8.webm)

## Problems with websites and feeds

Problem with feed | 📥 | 💬 | ❓
-|-|-|-
[knutmelvaer.no](https://www.knutmelvaer.no/) | [/rss.xml](https://www.knutmelvaer.no/rss.xml) | [30.4.2023](https://twitter.com/simevidas/status/1652752225029042177) | URLs are broken
[stuffandnonsense.co.uk/blog/](https://stuffandnonsense.co.uk/blog/) | [/blog/feed](https://stuffandnonsense.co.uk/blog/feed) | [11.1.2023](https://mastodon.social/@simevidas/109669185308080021) | server error
[aetherpoint.com/writing/](https://www.aetherpoint.com/writing/) | [/feed.xml](https://www.aetherpoint.com/feed.xml) | [4.12.2022](https://mastodon.social/@simevidas/109457465962904832) | feed is empty
[robdodson.me](https://robdodson.me/) | [/feed.xml](https://robdodson.me/feed.xml) | [25.11.2022](https://mastodon.social/@simevidas/109402350486107411) | invalid XML

<details>
<summary>Problem with feed in Feedbro specifically</summary>

<p>The following feeds do not work in Feedbro, but may work in other feed readers.</p>

Problem in Feedbro | 📥 | 💬 | ❓
-|-|-|-
[developer.chrome.com](https://developer.chrome.com/) | [/feeds/all.xml](https://developer.chrome.com/feeds/all.xml) | [30.12.2022](https://github.com/GoogleChrome/developer.chrome.com/issues/4472) | issue with caching headers
[voorhoede.nl/en/blog/](https://www.voorhoede.nl/en/blog/) | [/blog/feed.json](https://www.voorhoede.nl/blog/feed.json) | n/a | JSON feed not supported
[guybedford.com](https://guybedford.com/) | [/feed.json](https://guybedford.com/feed.json) | n/a | JSON feed not supported
[addons.mozilla.org/blog/](https://addons.mozilla.org/blog/) | [/blog/feed.xml](https://addons.mozilla.org/blog/feed.xml) | [26.11.2022](https://www.reddit.com/r/firefox/comments/z4u4kb/feedbro_addon_cant_access_feed_of_firefox_addons/) | CORS error

</details>

Website is not HTTPS | 📥 | 💬
-|-|-
[farmdev.com](http://farmdev.com/) | [/feeds/thoughts/](http://farmdev.com/feeds/thoughts/) | [4.12.2022](https://mastodon.social/@simevidas/109456873257419744)
[erahm.org](http://www.erahm.org/) | [/feed/](http://www.erahm.org/feed/) | [4.12.2022](https://twitter.com/simevidas/status/1599202160524562432)
[didoo.net](http://www.didoo.net/) | [/feed/](http://www.didoo.net/feed/) | [3.12.2022](https://twitter.com/simevidas/status/1598828194924089346)

Problem with website | 💬 | ❓
-|-|-
[snook.ca](https://snook.ca/) | n/a | disconnected
[p42.ai](https://p42.ai/) | n/a | connection timed out
[medinathoughts.com](https://medinathoughts.com/) | n/a | secure connection failed
[carmalou.com](https://carmalou.com/) | n/a | 404

Feed disappeared | 📥 | 💬
-|-|-
[wattenberger.com](https://wattenberger.com/) | [/rss](https://wattenberger.com/rss) | [1.5.2023](https://twitter.com/simevidas/status/1653025445607092225)
[speedcurve.com/blog/](https://www.speedcurve.com/blog/) | [/blog/rss/](https://www.speedcurve.com/blog/rss/) | [1.5.2023](https://twitter.com/simevidas/status/1653023285355991043)
[user-interface.io](https://user-interface.io/) | [/rss/](https://user-interface.io/rss/) | [29.1.2023](https://twitter.com/simevidas/status/1619661726198435840)
[mrd0x.com](https://mrd0x.com/) | [/rss.xml](https://mrd0x.com/rss.xml) | [28.12.2022](https://twitter.com/simevidas/status/1608228297221046272)
[filamentgroup.com/lab/](https://www.filamentgroup.com/lab/) | [/lab/atom.xml](https://www.filamentgroup.com/lab/atom.xml) | [28.12.2022](https://twitter.com/simevidas/status/1607876034216579073)
[wesbos.com/blog/](https://wesbos.com/blog/) | [/feed/](http://wesbos.com/feed/) | [7.12.2022](https://github.com/wesbos/wesbos/issues/70#issuecomment-1341369901)
[ben.robertson.is/writing/](https://ben.robertson.is/writing/) | [/feed.xml](https://ben.robertson.is/feed.xml) | [7.12.2022](https://github.com/benrobertsonio/benrobertson.io/issues/65)
[pcwalton.github.io](https://pcwalton.github.io/) | [/feed.xml](https://pcwalton.github.io/feed.xml) | [29.11.2022](https://github.com/pcwalton/pcwalton.github.com/issues/6)
[giovannibenussi.com](https://www.giovannibenussi.com/) | [/rss.xml](https://www.giovannibenussi.com/rss.xml) | [29.10.2021](https://twitter.com/simevidas/status/1454144581684039689)

Feed requested | 💬
-|-
[nray.dev/blog/](https://www.nray.dev/blog/) | [23.5.2023](https://github.com/nicholasray/nray.dev/issues/3)
[h3manth.com/posts/](https://h3manth.com/posts/) | [15.2.2023](https://twitter.com/simevidas/status/1625759385690509312)
[blog.dwac.dev](https://blog.dwac.dev/) | [25.1.2023](https://mastodon.social/@simevidas/109749224237131369)
[nemzes.net/posts/](https://nemzes.net/posts/) | [7.1.2023](https://mastodon.social/@simevidas/109649862770330876)
[imkev.dev](https://imkev.dev/) | [5.1.2023](https://mastodon.social/@simevidas/109638313938258067)
[frontend.horse/articles/](https://frontend.horse/articles/) | [12.12.2022](https://twitter.com/simevidas/status/1602156649938124800)
[react-spectrum.adobe.com/blog/](https://react-spectrum.adobe.com/blog/) | [12.12.2022](https://twitter.com/simevidas/status/1602155142643695618)
[bholmes.dev/blog/](https://bholmes.dev/blog/) | [12.12.2022](https://twitter.com/simevidas/status/1602149251575947265)
[leininger.tech/words/](https://leininger.tech/words/) | [11.12.2022](https://twitter.com/simevidas/status/1601747628165042176)
[tomvanantwerp.com/writing/#technical-writing](https://tomvanantwerp.com/writing/#technical-writing) | [11.12.2022](https://github.com/tvanantwerp/tomvanantwerp.com/issues/88)
[strictmode.io](https://www.strictmode.io/) | [11.12.2022](https://twitter.com/simevidas/status/1601745034164174848)
[tpiros.dev/blog/](https://tpiros.dev/blog/) | [11.12.2022](https://twitter.com/simevidas/status/1601740434858213376)
[trost.codes/posts/](https://trost.codes/posts/) | [8.12.2022](https://twitter.com/simevidas/status/1600981003388219392)
[leerob.io/blog](https://leerob.io/blog) | [8.12.2022](https://twitter.com/simevidas/status/1600700426420391937)
[davidmacd.com/blog/?C=M;O=D](https://www.davidmacd.com/blog/?C=M;O=D) | [8.12.2022](https://twitter.com/simevidas/status/1600697135367786497)
[themosaad.com/blog](https://www.themosaad.com/blog) | [29.11.2022](https://news.ycombinator.com/item?id=33789426)
[svgees.us/blog/](https://svgees.us/blog/) | [29.6.2022](https://github.com/svgeesus/svgeesus.github.io/issues/12)
[gregives.co.uk/blog/](https://gregives.co.uk/blog/) | [4.5.2022](https://gregives.co.uk/guestbook/)
[tobireif.com/posts/](https://tobireif.com/posts/) | [7.2.2021](https://twitter.com/simevidas/status/1358289331291643908)

| No feed |
|-|
[react.dev/blog](https://react.dev/blog)
[jgw96.github.io/blog](https://jgw96.github.io/blog/)
[accessuse.eu/en/blog-en.html](https://accessuse.eu/en/blog-en.html)
[team-usability.de/en/Blog.html](https://team-usability.de/en/Blog.html)
[aibolik.github.io](https://aibolik.github.io/)
[polymer-project.org/blog/](https://www.polymer-project.org/blog/)
[moiety.me/thinks/](https://moiety.me/thinks/)
[nicolaschevobbe.com](https://nicolaschevobbe.com/)
[simonsmith.io](https://simonsmith.io/)
[daliborgogic.com](https://daliborgogic.com/)
[simontaggart.com/posts](https://www.simontaggart.com/posts)
[blog.twitter.com/engineering/en_us](https://blog.twitter.com/engineering/en_us)
[samsaccone.com](https://samsaccone.com/)
[hjorthhansen.dev](https://www.hjorthhansen.dev/)
[leucosite.com](https://leucosite.com/)
[webcloud.se](https://webcloud.se/)
[ninjarockstar.dev](https://ninjarockstar.dev/)
[sarahchima.com/blog/](https://sarahchima.com/blog/)
[gwhitworth.com/posts/](https://www.gwhitworth.com/posts/)
[/marektoth.com/blog/](https://marektoth.com/blog/)
[uselessdivs.com/blog/](https://uselessdivs.com/blog/)

