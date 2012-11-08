### Check URL List ###

This script takes a file that has a list of urls
1 url per line, and checks to see if any of them
reply with an error. If they do, it'll display in
red.

This script was intended to be used to check Google
Crawl Errors after an attempt at fixing them has been
made.

In Google Webmaster Tools, export URLS as CSV, open in
excel/numbers/google docs, highlight url column and paste into a text file.
Then run this script on it.

If the script doesn't run, you may need to:

```bash
chmod +x check-url-list
```

## Example Text File Contents ##

```
http://www.somedomain.com/page1
http://www.somedomain.com/page2
http://www.somedomain.com/page3
```


Graham Mickle