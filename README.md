# NeoISE's Miscellaneous Filters (NeoISE's Filters)

## Background
Located ![Here](https://github.com/NeoISE/adblist).
The filter list "adblock-list.txt" contains rules that I, NeoISE, use personally in ![uBO](https://github.com/gorhill/uBlock);
as such, there are many rules/filters that are **uBO** specific and there are no guarantees that the rules will work *correctly* outside of **uBO**.
(Maybe *equivalent, compatible* rules can be substituted.)

## Requirements
- ![uBlock Origin](https://github.com/gorhill/uBlock) (Of Course!) or any other ad-block.
- This filters list is a companion to (supplements) the following lists:
  * uBlock filters (including **Annoyances**, **Badware risks**, **Privacy**, **Resource abuse**, **Unbreak**)
  * Adblock Warning Removal List
  * Adguard Filters (inc. **Base**, **Spyware**, **Annoyance List**)
  * EasyList _and_ EasyPrivacy
  * Fanboy's Lists (inc. **Enhanced Tracking**, **Annoyance**)
  * Spam404, Malware Domain List
  * ![AakList](https://github.com/reek/anti-adblock-killer/)
  * ![Adware filters](https://easylist-downloads.adblockplus.org/adwarefilters.txt)
  * ![Privacy filters](https://github.com/metaphoricgirrafe/tracking-filters)
  * ![uBlock Filters +](https://github.com/IDKwhattoputhere/uBlock-Filters-Plus)
  * ![Nano Defender List](https://jspenguin2017.github.io/uBlockProtector)
  * ![Overlay Blocker](https://github.com/LordBadmintonofYorkshire/Overlay-Blocker)

## Summary
Contains rules/filters that targets:
1. ads (by blocking or corrected cosmetically),
2. anti-adblock behaviors and,
3. _small annoyances_ (like overlays and popups)
along with protection from some potentially _bad_ domains (those that deliver ads, tracks you, or is just "phishy").

The list *adblock-list.txt* is intended for use in uBO (or any other ad-blocker that may or may not support all of the uBO static filter syntax).

The list *hosts-blacklist.txt* is intended for use as an extension to one's *Hosts* file to contain *potentially dangerous* domains (or in ![uMatrix](https://github.com/gorhill/uMatrix)).
