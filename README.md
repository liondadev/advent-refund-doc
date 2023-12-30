# Refunding people with the Advent Calendar

> SteamIDs are Always in SteamID64 form (the long number-y one!)
>
> Refunding someone will also close the box for that user when the complete the refund.
> However, you shouldn't need to refund people (unless their missing a chocolate or something) due to the 25th day being open until January.

## Quick How-To:

1. Open /adventadmin (admin+)
1. Select the player
1. Set the box in the bottom left
1. Hold "Refund Selected Player" in the bottom right

## How To (If the player isn't online):

1. /advent_refund [SteamID64] [Box/Day]

## Refunding Chocolate
> Chocolates serve no purpose atm, and there is no planned purpose for them.

1. /adventadmin
1. 'Extras' button in the bottom right
1. Do Either:
    1. "Spawn Christmas Chocolate"
    1. "Spawn Chocolate" > "Day X"
1. The chocolate should appear magicaly on your head!

![Chocolate Spawning Example Window](https://i.imgur.com/A65WGPV.png)

## Common Errors

### Player not elegible (or a form of this)

This is caused by either the player already having opened the box/day in question, or a refund already being created for that player, and for that box/day.

#### How to fix this:

1. /adventadmin
1. Press the 'Extas' Option
1. Use one of the methods to get the refunds for a player
1. Use the 'Delete Refund by Id' button to delete the reund in question, given the id

IF THAT DOESN'T WORK, THE PLAYER HAS ALRADY OPENED THE BOX (and likely gotten into a screwed up state):

1. Copy the player's SteamID64 to clipboard.
1. Use the 'Un-Open Box for Player' option from the 'Extras' menu, and the player should be able to re-open the box USING THE NORMAL /advent MENU.

Example result from printing refunds (along with how to find the Id):
![Examlple](https://i.imgur.com/clrn1qa.png)

## ConVars
If you're a superadmin, and the system breaks, you can manipulate the following convars to enable / disable certain things:
- cnadvent_enabled (def. 1) - This needs to be set to 0 at the beginning of January, it will disable the advent calendar
- cnadvent_25_open_past_25th_enabled (def. 1) - Should people be alloed to open the 25th day until January
- cnadvent_enable_present_requirement (def. 1) - Should the present requirement be enabled on the 25th day (should be disabled if it is somehow still broken after the patch)
