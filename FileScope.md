FileScope - Web server reconnaissance tool.

_**About**_

FileScope uses a wordlist to brute force directories and files for web servers where indexing has been disabled. This will recursively scan directories found and make a log of all successful HTTP requests.

_**Depends**_

use Term::ANSIColor (Perl)<br />use LWP::UserAgent (Perl)

_**Manual**_

Usage: ./FileScope < ARGS >
Arguments:
> -f < wordlist >
> -u < URL >
> -s < Seconds to sleep between requests >
> -t < File types, comma separated, e.g.: js,pdf,txt,psd >
> -r (make search recursive)

_**Demo**_

<a href='http://weaknetlabs.com/linux/pcrackdemo/pcrackdemo.html'>pCrack Demo showing FileScope in action</a> on the WeakNet Labs website

_**Author(s)**_

Trevelyn - weaknetlabs[-at-]gmail