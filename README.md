# TabSorting

![Image](https://i.imgur.com/WAEzk68.png)

Sort your stuff!
  
This mod can sort furniture/structures into appropriate tabs.
It started as an improved version of the LigtsTab (by betaALPHAs) but since that version relied on patches it was very complex and hard to maintain.

Instead this mod uses C#-code to sort things after they have loaded, removing the need for specific patch-files for each mod/item. The downside is that it requires a rescan of the changed tabs at startup but this should add no more than at most a few seconds depending on how many tabs has been changed.

Currently the mod supports the following sorting:

- All lights to a separate Lights-tab
- All walls and doors to the Structure-tab
- All floors to the Floors-tab
- All beds and linkable furniture to a separate Bedroom-tab
- All hospitalbeds and linkable medical furniture to a separate Hospital-tab
- All tables and sittable furniture to a separate Tables/Chairs-tab
- All decorative items to a separate Decorations-tab

Options dependant of other mods:
- All storage-containers to the Storage-tab of the Extended Storage-mod
  https://steamcommunity.com/sharedfiles/filedetails/?id=731732064
- All garden-tools to the Garden Tools-tab of the VGP Garden Tools-mod
  https://steamcommunity.com/sharedfiles/filedetails/?id=2007063961
- All fences the Fences-tab of the Fences and Floors-mod
  https://steamcommunity.com/sharedfiles/filedetails/?id=2012420113
  
Other options:
- If a tab is empty after the sorting the mod can remove it
- You can sort all tabs alphabetically, the Zones and Orders-tab can be skipped


If you find any item that dont get sorted or gets sorted in the wrong tab, please leave a report of what item and from what mod it comes from. Either here in the comments or at the support-channel via the Discord-link below.
Also, if you have any ideas on more stuff that can be categorised, just let me know and Ill look into it.

The preview-images look horrible I know.
If anyone can make me some nice ones Id appreciate it. Im a coder, not an artist. :)

