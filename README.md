# TabSorting

Sort your stuff!
  
This mod can sort furniture/structures into appropriate tabs.
It started as an improved version of the LigtsTab (by betaALPHAs) but since that version relied on pathes it was very complex and hard to maintain.

Instead this mod uses C#-code to sort things after they have loaded, removing the need for specific patch-files for each mod/item. The downside is that it requires a rescan of the changed tabs at startup but this should add no more than 10 seconds depending on how many tabs has been changed.

Currently the mod supports the following sorting:

- All lights to a separate Lights-tab
- All walls and doors to the Structure-tab
- All floors to the Floors-tab
- All beds and linkable furniture to a separate Bedroom-tab
- All tables and sittable furniture to a separate Tables/Chairs-tab

Options dependant of other mods:
- All storage-containers to the Storage-tab of the Extended Storage-mod
  https://steamcommunity.com/sharedfiles/filedetails/?id=731732064
  
Other options:
- If a tab is empty after the sorting the mod can remove it

If you find any item that dont get sorted or gets sorted in the wrong tab, please leave a report of what item and from what mod it comes from. Either here in the comments or at the support-channel via the Discord-link below.

Support-chat:
https://invite.gg/mlie

Non-steam version:
https://github.com/emipa606/TabSorting

