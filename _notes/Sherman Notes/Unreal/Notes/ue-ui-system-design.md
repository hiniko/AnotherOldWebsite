# UI System Design

I recently worked a project where we had to drastically refactor to the use from a more classic main menu, to a more modern one. More like Similar to Fortnite, CoD, Scavengers, Rocket League, etc.

The challange was taking a UI System with a lot of it's own issues and hacks and then building a system it wasn't designed to handle on top of it. This of course leads to more issues and hacks. 

Of course this leads to an endless supply of bugs, edge cases and the constnat feeling that you're making the mess worse without actually improving anything core to the problem. There just simply isn't the time.

The issues I feel that caused the most problems were as such.
1. The core system design
2. Seperation of concerns
3. Lack of clear 