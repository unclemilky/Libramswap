# LibramSwap
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
Currently LibramSwap won't work with spells directly on action bars. If you want to cast a spell from your action bar, put it in a macro and put the macro on your action bar.

```
#showtooltip
/cast Holy Light
```

LibramSwap will automatically equip Libram of Radiance before the cast goes through.

## Supported Spells & Librams

| Spell | Libram |
|-------|--------|
| Consecration | Libram of the Faithful / Farraki Zealot |
| Holy Shield | Libram of the Dreamguard |
| Holy Light | Libram of Radiance |
| Flash of Light | Libram of Light (fallback: Divinity) |
| Cleanse | Libram of Grace |
| Hammer of Justice | Libram of the Justicar |
| Hand of Freedom | Libram of the Resolute |
| Crusader Strike | Libram of the Eternal Tower |
| Holy Strike | Libram of the Eternal Tower / Radiance |
| Judgement | Libram of Final Judgement (only at ≤35% target HP) |
| Seal of Wisdom/Light/Justice/Command/Righteousness | Libram of Hope |
| Seal of the Crusader | Libram of Fervor |
| Devotion Aura | Libram of Truth |
| All Blessings | Libram of Veracity |
