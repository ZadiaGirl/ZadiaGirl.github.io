![[jak.png]]

| Str | Dex | Con | Int | Wis | Cha |
| :-: | --- | --- | --- | --- | --- |
| -1  | +3  | +1  | +1  | +0  | +1  |
|  8  | 16  | 12  | 12  |     |     |

```statblock
name: Jak
image: jak.png
hp: 12
ac: 13
speed: 30
size: small
cr: 1
columnWidth: 100%
damage_immunities: poison
stats: [10, 16, 12, 10, 10, 10]

actions:
  - name: Bite
    desc: +3 to hit, 1d4+3
    

bonus_actions:
  - name: Quick Feet
    desc: You can take the Dash or Hide action.

traits:
  - name: Keen Senses
    desc: roll dexterity saving throws with advantage.
senses: tremor sense (15')
```
