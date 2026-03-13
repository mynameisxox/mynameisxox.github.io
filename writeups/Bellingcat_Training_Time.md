![[20260310153431.png]]

```
Image credit: ARIJ Network

Following the creation of Bellingcat in 2014, the first few years were focused on publishing investigations, and running training sessions.

In December 2017, Christiaan Triebert hosted a workshop as a representative of Bellingcat. The image above shows Christiaan at that event.

**Your task is to identify the name of the room seen in the photo (answer format: The Name Of The Room).**

Puzzle by [Sofia Santos](https://gralhix.com/list-of-osint-exercises/)
```

---

Several details in the prompt stand out: we're given the month and year the photo was taken, the context of the event, and its organizer.

We therefore search for a workshop hosted by **Christiaan Triebert** in **December 2017**.

Searching these keywords quickly leads us to [this page](https://arij10thannualforum2017.sched.com/event/Cf6S/investigating-war-and-conflict-with-digital-information-hosted-by-bellingcat-br-hosted-by-bellingcat-tqswy-wqy-hrwb-wmntq-nz-blmlwmt-lrqmy), which appears to list events, including one that looks very relevant:

![[20260310153915.png]]

Clicking on the event reveals the venue:

![[20260310154025.png]]

A Google Maps link is even provided, but the coordinates point to Australia, which seems inconsistent.

![[20260313135940.png]]

Digging further into the ARIJ 10th Annual Forum, I land back on the same site, this time on a page with a **Venue Map**:

![[20260310155155.png]]

Some sessions list the following address: `Dead Sea Road, Swemeh 11180, Jordan` — so the forum appears to have taken place in Jordan.

Searching for "Al Diwan 1 @ Floor G Jordan", I find [this page](https://movenpick.accor.com/en/middle-east/jordan/dead-sea/resort-dead-sea/meeting-rooms/al-diwan.html) on the Mövenpick hotel website. Al Diwan turns out to be the name of one of the hotel's meeting rooms, but that answer isn't accepted. Continuing to browse, I come across [another meeting room](https://movenpick.accor.com/en/middle-east/jordan/dead-sea/resort-dead-sea/meeting-rooms/the-grand-ball-room.html) and everything matches: the wall color, the carpet pattern:

![[20260310163332.png]]

#### FLAG: `The Grand Ball Room`