# Libramswap
Adds libram equips to paladin spellcasts

## Commands
All commands support three aliases: `/libramswap`, `/lswap`, or `/ls`

### Basic Commands
- `/ls` - Toggle LibramSwap on/off
- `/ls on` - Enable LibramSwap
- `/ls off` - Disable LibramSwap
- `/ls spam` - Toggle swap confirmation messages
- `/ls status` - Show current settings
- `/ls help` - Show command list

### Libram Selection

Some spells have multiple libram options. You can choose which one to use:

#### Consecration
- `/ls consecration faithful` or `/ls c f` - Use **Libram of the Faithful** (default)
- `/ls consecration farraki` or `/ls c z` - Use **Libram of the Farraki Zealot**

#### Holy Strike
- `/ls holystrike eternal` or `/ls hs e` - Use **Libram of the Eternal Tower** (default)
- `/ls holystrike radiance` or `/ls hs r` - Use **Libram of Radiance**

## Action Bars
Currently LibramSwap won't work with spells on action bars. If you want to cast a spell from your action bar, put it in a macro.

```
#showtooltip
/cast Holy Light
```

LibramSwap will automatically equip Libram of Radiance before the cast goes through.
