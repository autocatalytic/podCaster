## README

Podcasting is due for a rewrite, and may benefit from IPFS primitives such as trickle-DAG retrieval, and IPLD/storage efficiency when editing episodes. Migrating from RSS could be a 10x improvement for publisher flexibility and metrics as well.

This project seeks to upgrade podcasting architecture, skipping from RSS straight to decentralized. Modernizing the software stack does not require IPFS or decentralization, but if you believe that audio has the potential expand significantly (extending beyond entertainment and news, to secondary school, adult education, etc.) podcasting will benefit from its resilience and localization properties. 

Publisher metrics around user engagement are also antiquated today, limited to coarse numbers like "subscribers", "downloads" and promo-code click-through's. Using IPLD to intelligently segment audio files may offer a solution that's far better than simply moving away from RSS using the typical software stack.

Necessary research, possibly exposing IPFS/IPLD naivite here:

* Link play-clock with IPFS chunks for playback editing
* Use above feature to add or substitute new content "in the middle" of an episode
* For native player, track chunk retrieval to measure user abandonment
* Display abandonment timing/location to publishers

Sprint A (may modify based on above research):

* File upload tool (adaptive ipfs add parameters, chunk size, etc.)
* RSS-like server API (backward compatibility w/Podcast apps)
* Browser-based player to avoid app-store platform rent-seeking
* Basic tagging functionality to enable discovery and search
* User views: publisher, show, episode, episode details, search

Sprint B:

* User/Admin registration and view segmentation (move to v.2?)
* Track subscriptions, downloads, unsubs...traditional RSS metrics

## Version 2
* Discovery based on tags above and publishers and guests
* Publisher and guest linking
* Server "push" publication 
* Selective content pinning based on utilization
* Rating system for shows, episodes, guests, etc.
* Ad market if interstitial injection works
* Pay with crypto
* Automated filecoin storage
* App store version, enabling nice things like "don't interrupt me"
* Explore offline classroom opportunities (not necessarily the tool?)

## Rambling Thoughts
* Is there something native to IPFS that will unlock virality/social?

