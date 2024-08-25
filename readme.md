# *DESCRIPTION*
This plugin is the advanced version of already published [Dev Zones Anticamp](https://forums.alliedmods.net/showthread.php?t=224839) plugin.
Players are killed if they do not leave an area that their team must leave within a set number of seconds.

> [!CAUTION]
> You need DevZones to use this plugin !
> https://forums.alliedmods.net/showthread.php?t=224839

# *BUGS*
none.

# *USAGE*
Put **anticamp** in front of the zone name so plugin recognizes the zone.
- If you want the zone to affect only the CT team, add **:ct** to the end of the zone name.
- If you want the zone to affect only the T team, add **:t** to the end of the zone name.
- If you want the zone to affect all teams, either add **:all** to the end of the zone name **or leave it blank**.

https://youtu.be/C-bY5ZdGFuk?si=Y3FTzju3Wl_pOgME

# *CHANGELOG*
`v0.2.4 -> "In rare cases, the issue where the countdown would continue outside the
anticamp area and kill the player at the end of the countdown has been fixed.
A convar has been added to allow the prefix to be changed."`

# *CVARS*
// 1->Plugin enabled, 0->Plugin disabled
// -
// Default: "1"
// Minimum: "0.000000"
// Maximum: "1.000000"
sm_vxanticamp_enable "1"

// Time before camp time gets reset after leaving a zone
// -
// Default: "15"
sm_vxanticamp_lefttime "15"

// Prefix
// -
// Default: "{red}[ {olive}VortéX Anti-Camp {red}]"
sm_vxanticamp_prefix "{red}[ {olive}VortéX Anti-Camp {red}]"

// Allowed camp time
// -
// Default: "30"
// Minimum: "10.000000"
sm_vxanticamp_time "30"