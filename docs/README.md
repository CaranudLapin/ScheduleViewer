# ScheduleViewer

Adds two new menus that show the schedules for NPCs. The main menu shows the previous, current, and next schedule entries for each NPC. It will also show an "!" icon next to a character's name if they have an active quest associated with them. If you hover over a schedule entry it shows which specific tile the NPC is on in that location, which direction they are facing, and which sprite animation will be playing. On click, a second menu opens showing the full schedule for that NPC as well as their current location and if they can receive a gift today.

## Install

Install the latest version of SMAPI.
Download this mod and unzip it into Stardew Valley/Mods.
Run the game using SMAPI.

## Config Options

| setting                           | default                | what it does                                                                                           |
| --------------------------------- | ---------------------- | ------------------------------------------------------------------------------------------------------ |
| `ShowSchedulesKey`                | `V`                    | the key to open the Schedule Viewer                                                                    |
| `UseAddress`                      | `true`                 | use Pelican Town address instead of "Home of ..." for schedule entries i.e. "2 Willow Lane" instead of "Home of Emily & Haley". (Changes may not take effect until the next day.) |
| `DisableHover`                    | `false`                | don't show tile, facing direction, and animation info on hover                                         |
| `UseLargerFontForScheduleDetails` | `false`                | use a larger font size on the Schedule Details page (longer location names may get cut off if enabled) |
| `NPCSortOrder`                    | Alphabetical Ascending | the order the NPCs are sorted in the Schedule Viewer (Alphabetical/Heart Level & Ascending/Descending) |
| **Filters**                       |
| `OnlyShowMetNPCs`                 | `false`                | hides NPCs the farmer hasn't met yet                                                                   |
| `OnlyShowSocializableNPCs`        | `true`                 | hides NPCs you can't socialize with i.e. Gunther or Sandy before the bus is repaired                   |

## Compatibility

Works with Stardew Valley 1.6+ on Windows/Linux/Mac

Works in single-player and multiplayer (mods need to match for it to be accurate).

Works with mods that change NPC schedules

Custom NPCs (like those from SVE and RSV) are fully supported

Custom Locations are fully supported.

No known mod conflicts

## Specific Mod Integrations

- [Generic Mod Config Menu](https://www.nexusmods.com/stardewvalley/mods/5098) - UI for editing config options
- [Lookup Anything](https://www.nexusmods.com/stardewvalley/mods/541) - able to lookup NPC information from the Schedule Viewer and details pages
- [Mobile Phone Continued](https://www.nexusmods.com/stardewvalley/mods/21017) - able to open the Schedule Viewer from the Mobile Phone
- [Stardew Valley Expanded](https://www.nexusmods.com/stardewvalley/mods/3753) - see [SVETileAreas](..\SVETileAreas) for optional download that enhances schedule details for custom SVE locations
- [Toolbar Icons](https://www.nexusmods.com/stardewvalley/mods/21017) - able to open the Schedule Viewer from a toolbar icon

To integrate your mod see the [author guide](author-guide.md) for more info.

## Translations

<!--

    This section is auto-generated using a script, there's no need to edit it manually.
    https://github.com/Pathoschild/StardewScripts/tree/main/create-translation-summary

-->

Mods can be translated into any language supported by the game, and SMAPI will automatically
use the right translations.

Contributions are welcome! See [Modding:Translations](https://stardewvalleywiki.com/Modding:Translations)
on the wiki for help contributing translations.

(❑ = untranslated, ↻ = partly translated, ✓ = fully translated)

| Language   | Status                           | Contributors                                            |
| ---------- | -------------------------------- | ------------------------------------------------------- |
| Chinese    | [↻](ScheduleViewer/i18n/zh.json) | [RegenLicht](https://www.nexusmods.com/users/102031818) |
| French     | [✓](ScheduleViewer/i18n/fr.json) | YoshY                                                   |
| German     | [❑](ScheduleViewer/i18n)         | &nbsp;                                                  |
| Hungarian  | [❑](ScheduleViewer/i18n)         | &nbsp;                                                  |
| Italian    | [❑](ScheduleViewer/i18n)         | &nbsp;                                                  |
| Japanese   | [❑](ScheduleViewer/i18n)         | &nbsp;                                                  |
| Korean     | [✓](ScheduleViewer/i18n/ko.json) | [cheesecats](https://www.nexusmods.com/users/88438538)  |
| Portuguese | [✓](ScheduleViewer/i18n/pt.json) | [Sxdic](https://www.nexusmods.com/users/34556965)       |
| Russian    | [❑](ScheduleViewer/i18n)         | &nbsp;                                                  |
| Spanish    | [✓](ScheduleViewer/i18n/es.json) | [36095](https://github.com/36095)                       |
| Turkish    | [✓](ScheduleViewer/i18n/tr.json) | [KzyNothh](https://www.nexusmods.com/users/94536368)    |

## See also

- [Nexus Mods](https://www.nexusmods.com/stardewvalley/mods/19305)
- [CurseForge](https://www.curseforge.com/stardewvalley/mods/schedule-viewer)
