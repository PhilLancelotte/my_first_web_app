xkcd api info..

https://xkcd.com/json.html

If you want to fetch comics and metadata automatically,
you can use the JSON interface. The URLs look like this:

https://xkcd.com/info.0.json (current comic)

or:

https://xkcd.com/614/info.0.json (comic #614)

Those files contain, in a plaintext and easily-parsed format: comic titles,
URLs, post dates, transcripts (when available), and other metadata.