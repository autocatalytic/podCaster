# README
## Draft July 13, 2020

Still drinking from the firehose, but if we can figure out how to efficiently utilize and also track IPFS chunk retrieval, building better podcasting architecture that skips from RSS straight to decentralized might be possible. Publisher metrics around user engagement are also antiquated today, limited to coarse numbers like "subscribers", "downloads" and promo-code click-through's. 

Mulling this over still, but some elementary specifications would be:

* File upload tool (adaptive ipfs add parameters, chunk size, etc.)
* RSS-like server API (backward compatibility w/Podcast apps)
* Browser-based player to avoid app-store platform rent-seeking
* Basic tagging functionality to enable discovery
* User/Admin registration and view segmentation (move to v.2?)
* Track subscriptions, downloads, unsubs...traditional RSS metrics
* Views: publisher, show, episode, episode details, search

More interesting specs, possibly exposing my IPFS/IPLD naivite here:

* Link play-clock with IPFS chunks for playback editing
* Using above link to enable interstitial CID's (i.e. ads/promos)
* Swapping interstitials "on the fly"
* For native player, track chunk retrieval to measure user abandonment
* Display abandonment timing/location to publishers
* Is there something about IPFS that will unlock virality/social?

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
