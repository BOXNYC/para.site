# para.site
para.site is a automatic website builder that uses social media API to generate. If you have a public Facebook page, Instagram account, Google Place, or Bandcamp account, you already have a para.site website.

Currently para.site latches on to Facebook, Instagram, Google Places, and Bandcamp APIs, but in the future, we may add Pinterest and LinkedIn. Currently we don't have plans to connect to Google Plus, mainly because we think Google Places has more usage because of Google Maps.

## Free Usage
Free usage of the para.site system is access to sub-domain websites and requires manual refreshing of the cached site otherwise cache TTL is one month. The sub-domain naming convention goes like so:

`SN_UID`.`SN`.para.site/`PG`/`PA`

For example, Pepsi's Facebook para.site URL would look like this:

http://339150749455906.fb.para.site

Kinda ugly, but no sweat, just point a domain CNAME to it because it wont change.

Don't want to use a domain name? Well if the para.site uses Facebook and has a Facebook username set, then use the username instead of the account ID:

http://pepsi.fb.para.site

Note: If you plan in pointing a CNAME domain to it, use the ID URL not tge username, as the ID never chamges.

Even better, you can <a href="http://para.site/alias">reserve aliases</a> for free, first come first serve. For example, if Pepsi reserves the alias 'pepsi' and wants to point it to there Facebook para.site, then the URL will look like this:

http://pepsi.para.site



Keys  
====
`SN_UID` : Social Network User ID  
`SN` : Social Network (Default 'fb')  
`PG` : Page  
`PA` : Page Argument

