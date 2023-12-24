There are three types of Criticals - Normal Critical, Super Critical, and Hyper Critical.

The calculation to determine each critical rate is as follows:
```js
Normal Critical Rate = CRIT RATE
Super Critical Rate = Normal Critical Rate * SUPER CRIT RATE
Hyper Critical Rate = Super Critical Rate * HYPER CRIT RATE
```
Each subsequent Critical Rate type depends on the previous. As an analogy - you have three dice rolls. The first die rolls for "Normal Critical", and upon a successful "Normal Critical" roll, a second die rolls for "Super Critical", and upon a successful "Super Critical", a third die rolls for "Hyper Critical". You want to get all three Critical Rates to 100% to guarantee "Hyper Critical" hits.

The calculation for Critical Damage is as follows:
```js
Normal Critical Damage = Final DMG * CRIT DMG
Super Critical Damage = Normal Critical Damage * Super CRIT DMG
Hyper Critical Damage = Super Critical Damage * Hyper CRIT DMG
```
Critical damage modifiers stack on top of one another.
