# <p align="center"><img src="assets/unspeed.png" width="256" alt="Unspeed logo"></p>
A "proxy" that lets you bypass website blocks from Lightspeed Filter.

> [!IMPORTANT]
> This "proxy" is **NOT OUT** yet. It'll release mid-late August of 2026. This proxy **ONLY** works for **Lightspeed Filter Agent**. Support for other filters is **not planned**.

## How does Unspeed work exactly?
I have to be vague in order for the patch to take longer, but while decompiling Lightspeed Filter's worker code, I've noticed Lightspeed Filter has a flaw where if a request's URL contains a specific string, the request will not be intercepted any further. I've tested the bug with a bookmark and I could access a blocked website for around half a second!

A few days later, I had the thought of embedding an iframe with this bug and it allowed me to visit a stripped down version of a blocked website.

> [!NOTE]
> The rest of this is to be determined as this is the current story as of now.

## Where can I download the full quality Unspeed logo? What is the meaning behind it?
Click [this link](assets/unspeed.pclx) to download the PCLX file. You will need [Pencil2D](https://www.pencil2d.org) in order to open the file.

The lightning represents Filter's webRequest listeners. Requests come in from the bottom end and travel to the top end. The Filter logo on top of the lightning represents a guard. Filter sees these requests traveling through the lightning and makes decisions: should they be blocked from passing by or not?

The slightly dark cover at the bottom essentially blocks the requests from traveling through the lightning. Filter doesn't see the cover, but it's going to be there for an unknown amount of time. 

After the cover was suddenly just placed there, the requests find an alternate pathway that very little have heard of and successfully bypass the Filter.