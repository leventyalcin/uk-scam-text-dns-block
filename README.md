# Block list

## What is this?

Presumably, my mobile number ended up in a breached data. So, I started to get scam texts regularly.

I regularly report those messages to [7726](https://www.ofcom.org.uk/phones-telecoms-and-internet/advice-for-consumers/problems/tackling-nuisance-calls-and-messages/spam-texts). However, I thought it could be good to block these domains at DNS level as well.

**TL;DR** This is the list of domain names that I see in scam texts.

## What can I do with this list?

* Add under your hosts file `/etc/hosts`
* Import it to [Pi-hole](https://docs.pi-hole.net/database/gravity/example/#example-2-blocklist-management)
  * Group Management -> Adlists -> Add a new list
  * Address: `https://raw.githubusercontent.com/leventyalcin/uk-scam-text-dns-block/master/hosts`
  * Add
* Use in NextDNS.io if they approve the repo

## Can I contribute?

Yes. Please!

* Fork it.
* Follow the pattern in the file
* Change it. (I hope you sign your commits!)
* Raise a PR.
