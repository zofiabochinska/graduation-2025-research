---
{"dg-publish":true,"permalink":"/1-research/tools/turn-counter-twine/","dg-note-properties":{"date created":"Wednesday, March 12th 2025","date modified":"Tuesday, March 24th 2026"}}
---

[Link](https://twinery.org/cookbook/turncounter/chapbook/chapbook_turncounter.html)
### 2025-03-12 15:16

Main Tag: #visual_novel
Secondary Tags: #tools #twine
___ 
![](https://i.imgur.com/6mEzQk7.png)

![](https://i.imgur.com/qHuKzkC.png)

> In Chapbook, the global variable _trail_ stores all of the passages visited as an increasing array. For each passage visited, a new entry is added. 
> 
> Sometimes known as "wrap around," the modulus operator (%) is used to get the remainder of the number of "turns" (number of passages) divided by 24. This creates a clock where its value shows one of a series of strings representing "morning", "mid-morning", "afternoon", or "night."
> 
> By visiting other passages, the turn count is increased and the hour reaches 23 before being reset back to 0 before increasing again.
## References



