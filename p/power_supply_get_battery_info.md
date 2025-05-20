# Function: <code>power_supply_get_battery_info</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int power_supply_get_battery_info(struct power_supply *psy, struct power_supply_battery_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff817288e0)
Location: drivers/power/supply/power_supply_core.c:523
Inline: True
```
**Symbols:**

```
ffffffff817288e0-ffffffff8172892e: power_supply_get_battery_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int power_supply_get_battery_info(struct power_supply *psy, struct power_supply_battery_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff8179a070)
Location: drivers/power/supply/power_supply_core.c:561
Inline: True
```
**Symbols:**

```
ffffffff8179a070-ffffffff8179a0be: power_supply_get_battery_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int power_supply_get_battery_info(struct power_supply *psy, struct power_supply_battery_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff817e14a0)
Location: drivers/power/supply/power_supply_core.c:568
Inline: True
```
**Symbols:**

```
ffffffff817e14a0-ffffffff817e14ee: power_supply_get_battery_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int power_supply_get_battery_info(struct power_supply *psy, struct power_supply_battery_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff8180cb90)
Location: drivers/power/supply/power_supply_core.c:568
Inline: True
```
**Symbols:**

```
ffffffff8180cb90-ffffffff8180cc05: power_supply_get_battery_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int power_supply_get_battery_info(struct power_supply *psy, struct power_supply_battery_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff8184eeed)
Location: drivers/power/supply/power_supply_core.c:565
Inline: True
```
**Symbols:**

```
ffffffff8184eeed-ffffffff8184ef0e: power_supply_get_battery_info.cold (STB_LOCAL)
ffffffff8184e840-ffffffff8184e8a3: power_supply_get_battery_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int power_supply_get_battery_info(struct power_supply *psy, struct power_supply_battery_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff818808f7)
Location: drivers/power/supply/power_supply_core.c:565
Inline: True
```
**Symbols:**

```
ffffffff818808f7-ffffffff81880918: power_supply_get_battery_info.cold (STB_LOCAL)
ffffffff81880270-ffffffff818802d3: power_supply_get_battery_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int power_supply_get_battery_info(struct power_supply *psy, struct power_supply_battery_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff8194f074)
Location: drivers/power/supply/power_supply_core.c:565
Inline: True
```
**Symbols:**

```
ffffffff8194f074-ffffffff8194f095: power_supply_get_battery_info.cold (STB_LOCAL)
ffffffff8194e6b0-ffffffff8194e75a: power_supply_get_battery_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int power_supply_get_battery_info(struct power_supply *psy, struct power_supply_battery_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (0)
Location: drivers/power/supply/power_supply_core.c:565
Inline: False
```
**Symbols:**

```
ffffffff81c25334-ffffffff81c25355: power_supply_get_battery_info.cold (STB_LOCAL)
ffffffff81953dd0-ffffffff81953e99: power_supply_get_battery_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int power_supply_get_battery_info(struct power_supply *psy, struct power_supply_battery_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (0)
Location: drivers/power/supply/power_supply_core.c:565
Inline: False
```
**Symbols:**

```
ffffffff81c173d7-ffffffff81c173f9: power_supply_get_battery_info.cold (STB_LOCAL)
ffffffff81937c60-ffffffff81937d24: power_supply_get_battery_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int power_supply_get_battery_info(struct power_supply *psy, struct power_supply_battery_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (0)
Location: drivers/power/supply/power_supply_core.c:565
Inline: False
```
**Symbols:**

```
ffffffff81d262d8-ffffffff81d262f9: power_supply_get_battery_info.cold (STB_LOCAL)
ffffffff819dbf30-ffffffff819dc039: power_supply_get_battery_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int power_supply_get_battery_info(struct power_supply *psy, struct power_supply_battery_info **info_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (0)
Location: drivers/power/supply/power_supply_core.c:569
Inline: False
```
**Symbols:**

```
ffffffff81ef212b-ffffffff81ef2142: power_supply_get_battery_info.cold (STB_LOCAL)
ffffffff81b3faa0-ffffffff81b400a6: power_supply_get_battery_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int power_supply_get_battery_info(struct power_supply *psy, struct power_supply_battery_info **info_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81cd6030)
Location: drivers/power/supply/power_supply_core.c:569
Inline: False
```
**Symbols:**

```
ffffffff81cd6030-ffffffff81cd664d: power_supply_get_battery_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int power_supply_get_battery_info(struct power_supply *psy, struct power_supply_battery_info **info_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81d3e030)
Location: drivers/power/supply/power_supply_core.c:573
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff81d3e030-ffffffff81d3e65f: power_supply_get_battery_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int power_supply_get_battery_info(struct power_supply *psy, struct power_supply_battery_info **info_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81df4980)
Location: drivers/power/supply/power_supply_core.c:572
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff81df4980-ffffffff81df4faf: power_supply_get_battery_info (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int power_supply_get_battery_info(struct power_supply *psy, struct power_supply_battery_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffff800010acb178)
Location: drivers/power/supply/power_supply_core.c:565
Inline: False
```
**Symbols:**

```
ffff800010acb178-ffff800010acb57c: power_supply_get_battery_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int power_supply_get_battery_info(struct power_supply *psy, struct power_supply_battery_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (c0babff0)
Location: drivers/power/supply/power_supply_core.c:565
Inline: False
```
**Symbols:**

```
c0babff0-c0bac41c: power_supply_get_battery_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int power_supply_get_battery_info(struct power_supply *psy, struct power_supply_battery_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (c000000000bad160)
Location: drivers/power/supply/power_supply_core.c:565
Inline: False
```
**Symbols:**

```
c000000000bad160-c000000000bad7b4: power_supply_get_battery_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int power_supply_get_battery_info(struct power_supply *psy, struct power_supply_battery_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffe0006c8a1c)
Location: drivers/power/supply/power_supply_core.c:565
Inline: False
```
**Symbols:**

```
ffffffe0006c8a1c-ffffffe0006c8e14: power_supply_get_battery_info (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int power_supply_get_battery_info(struct power_supply *psy, struct power_supply_battery_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81828e67)
Location: drivers/power/supply/power_supply_core.c:565
Inline: True
```
**Symbols:**

```
ffffffff81828e67-ffffffff81828e88: power_supply_get_battery_info.cold (STB_LOCAL)
ffffffff818287e0-ffffffff81828843: power_supply_get_battery_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int power_supply_get_battery_info(struct power_supply *psy, struct power_supply_battery_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff817f04f7)
Location: drivers/power/supply/power_supply_core.c:565
Inline: True
```
**Symbols:**

```
ffffffff817f04f7-ffffffff817f0518: power_supply_get_battery_info.cold (STB_LOCAL)
ffffffff817efe70-ffffffff817efed3: power_supply_get_battery_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int power_supply_get_battery_info(struct power_supply *psy, struct power_supply_battery_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81875da7)
Location: drivers/power/supply/power_supply_core.c:565
Inline: True
```
**Symbols:**

```
ffffffff81875da7-ffffffff81875dc8: power_supply_get_battery_info.cold (STB_LOCAL)
ffffffff81875720-ffffffff81875783: power_supply_get_battery_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int power_supply_get_battery_info(struct power_supply *psy, struct power_supply_battery_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81891747)
Location: drivers/power/supply/power_supply_core.c:565
Inline: True
```
**Symbols:**

```
ffffffff81891747-ffffffff81891768: power_supply_get_battery_info.cold (STB_LOCAL)
ffffffff818910c0-ffffffff81891123: power_supply_get_battery_info (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct power_supply_battery_info **info_out</code>
</li>
<li>
<b>Param removed. </b>
<code>struct power_supply_battery_info *info</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
