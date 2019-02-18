# Quine
## How t0
brew install python3
python3 scraper.py

## Algorithm
<pre>
QUINE <- Feed it a link
   |
   ▼
1.Scan for more `<a>` links
  |     |
  |     |
  |     ▼
  |   1.2.Remember the links   
  |                        |
  ▼                        | 
2.Scan the link for Emails |
     |                     |
     ▼                     ▼
3.Take new links and scan them for more emails & links 
  |
  ▼
4.Repeate til no new links or emailes are found
</pre>
