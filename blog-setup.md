# Blog serving plan

* Website should be a single HTML file (per page) and a common CSS file.

* HTML pages can be cacheable for 5 minutes, so that e.g. Cloudflare can be put in front easily if scaling is necessary.

* CSS file can be cacheable for longer - 31 days, for instance. At least once it is pinned down.

* HTML should be written so that basic readability holds.

* Main goal (above are implementation details): site should load really fast on bad connection and bad hardware. Should look good for reading. (Compare to e.g. motherfuckingwebsite.com which has text going all the way across the screen.)
