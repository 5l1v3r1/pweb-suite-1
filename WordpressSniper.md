# Wordpress Sniper #

**wp\_sniper** is an automation tool

**scrape** is an automation tool for generating a list of known exploits from exploit-db.com


<a href='http://weaknetlabs.com/images/wp_sniper.png'>Full sized screenshot of wp_sniper - post vulnerability testing.</a>

## Dependencies (2 Perl modules) ##
<a href='http://search.cpan.org/~gaas/libwww-perl-6.04/lib/LWP.pm'>LWP;</a>
<a href='http://search.cpan.org/~rra/Term-ANSIColor-3.02/ANSIColor.pm'>Term::ANSIColor;</a>

## Manual ##
Usage: ./wp-sniper URL OPTIONS

### Options ###
**-r** random wait time between GET requests - to seem more human

**-d** check default installation files

## TODO ##