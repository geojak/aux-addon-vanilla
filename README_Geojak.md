1. Added auto bid feature, doubled the existing auto buy code and slighly editted
2. Added auto pricing heuristic, these are activate when posting an item with bid price 0, the buyout price works as a minimum
3. Added a keybind for the post button, this significantly speeds up mass posting of items when you dont need to change saved prices
4. New option to change the default post stack size to rand(1,max) instead of always max stacks, use /aux post stack to toggle
5. FIXED TWILLIGHT CULTIST SET NOT DISENCHATABLE
6. use SHagu tweaks vendor values if aux values not avaialbe (might need fixing if you dont actually have shaguweaks)
7. dont auto bid on own items
8. new filter disenchant-percent and bid-disencahnt-percent
9. enchanting created wands are not encahntabke, same with twillight stuff at 5. reworked implementation for easier addition
10. disenchant values are calcualted from min(value,value_today), this protects users from low enchanting mat prices
11. advanced trade skill menu compabillity to display aux crafting cost
12. changed default post duration from 8 to 24, since turtle wow got no fees anyway
13. new filter "isgear" which can be used to generic filter out all white and green armor and weapons that have incosinstent market value
14. made ah data crossfaction on the server "Turtle WoW" (all chars are considered horde)
15. fixed a bug with the auto bid, bidding yoursefl up
16. adjusted the auto pricing to not post items and instead pprint a warning if it things its not profitable
17. percentage pricing, do 1g 10s 50% or 100% 50s which will calc a price as max( % * market_value, gold silver copper), the calc vlaue is then saved
18. if you use the aux post bid mode, then clicking a buyout to undercut will not adjust the starting bid price aswell
19. added profit next to % at search results. profit  = 0.95 (marketvalue - price) - 0.6 * 10 * vendorprice
the profit is supposed to tell you, how much profit you make if you bough the item at its current price and put it back into the ah at 100% market value for 10 times until it sells
20. made the #auctions column wider so you can see better how many items you have listed in brackets
21. made the #auctions counter display total items instead of the number of auctions ingoring, that means a stack of 20 runecloth gets counteed as 20 and not 1 and 20 single stacks of runecloth get also counted as 20.