# shavit-style-backwards
> ⬅️ Adds a custom backwards style to shavit's bhoptimer.

## Installation
1. Download the latest version from the [releases page](https://github.com/strafe/shavit-style-backwards/releases/latest) and add it to your server.

1. Add a new style to `shavit-styles.cfg` with the `specialstring` key set to `backwards`. Example:
```
"100"
{
	"name"				"Backwards"
	"shortname"			"BW"
	"htmlcolor"			"FFA4D0"
	"command"			"bw; backwards"
	"clantag"			"BW"

	"unranked"			"1"
	"specialstring"			"backwards"
}
```

## Configuration
The plugin can be configured in `cfg/sourcemod/plugin.shavit-style-backwards.cfg`.

ConVar|Default Value|Description
:-:|:-:|:-
`ss_backwards_specialstring`|`backwards`|Special string value to use in shavit-styles.cfg, only change this if the default collides with another plugin.

## Credits
- [Mehis](https://github.com/TotallyMehis)
