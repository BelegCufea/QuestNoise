# QuestNoise

## **Original**

Original addon by cybermind.

Forked from [curseforge](https://www.curseforge.com/wow/addons/questnoise) on 27<sup>th</sup> of March 2023

## What is QuestNoise?

This addon plays sounds whenever you make progress on a quest. It plays a different sound for completing the quest, completing only a single objective of the quest, or making progress on an objective. Unlike the other addons I've found that provide the sound feature of GuestGuru, this addon does not require or use LibQuixote (which does many quest-related things that we don't use or need).

## What does it look like?

It's invisible! The only thing this addon does is play the noise and, upon quest completion, display a yellow message (just like the objective progress messages) saying which quest you just completed.

## What are the default sounds?

Upon making progress on a quest, it will play the ding that you hear when you open the Auction House window:

`/run PlaySound(SOUNDKIT.AUCTION_WINDOW_OPEN)`

Upon completing an objective, it will play the ding that you hear when you close the Auction House window:

`/run PlaySound(SOUNDKIT.AUCTION_WINDOW_CLOSE)`

Upon completing the quest, it will play the orc peon's "Work Complete" sound:

`/run PlaySoundFile("558132")`¨

## How do I change the sounds?

Go to the Interface options, and then choose the Addons tab. On the left, look for "QuestNoise." In here, you can change the sounds for each event. Options are currently limited, more will be added soon.