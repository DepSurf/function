# Function: <code>sfp_select_interface</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
phy_interface_t sfp_select_interface(struct sfp_bus *bus, const struct sfp_eeprom_id *id, long unsigned int *link_modes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff8173aec0)
Location: drivers/net/phy/sfp-bus.c:255
Inline: True
```
**Symbols:**

```
ffffffff8173aec0-ffffffff8173af3c: sfp_select_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
phy_interface_t sfp_select_interface(struct sfp_bus *bus, const struct sfp_eeprom_id *id, long unsigned int *link_modes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff8175e830)
Location: drivers/net/phy/sfp-bus.c:255
Inline: True
```
**Symbols:**

```
ffffffff8175e830-ffffffff8175e8ac: sfp_select_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
phy_interface_t sfp_select_interface(struct sfp_bus *bus, const struct sfp_eeprom_id *id, long unsigned int *link_modes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff8179bf34)
Location: drivers/net/phy/sfp-bus.c:255
Inline: True
```
**Symbols:**

```
ffffffff8179bf34-ffffffff8179bf4b: sfp_select_interface.cold (STB_LOCAL)
ffffffff8179be90-ffffffff8179befe: sfp_select_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
phy_interface_t sfp_select_interface(struct sfp_bus *bus, const struct sfp_eeprom_id *id, long unsigned int *link_modes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff817bf9e4)
Location: drivers/net/phy/sfp-bus.c:255
Inline: True
```
**Symbols:**

```
ffffffff817bf9e4-ffffffff817bf9fb: sfp_select_interface.cold (STB_LOCAL)
ffffffff817bf940-ffffffff817bf9ae: sfp_select_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
phy_interface_t sfp_select_interface(struct sfp_bus *bus, long unsigned int *link_modes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:367
Inline: False
```
**Symbols:**

```
ffffffff81888ef4-ffffffff81888f0b: sfp_select_interface.cold (STB_LOCAL)
ffffffff81888350-ffffffff818883d0: sfp_select_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
phy_interface_t sfp_select_interface(struct sfp_bus *bus, long unsigned int *link_modes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:381
Inline: False
```
**Symbols:**

```
ffffffff81c1953a-ffffffff81c19551: sfp_select_interface.cold (STB_LOCAL)
ffffffff818965f0-ffffffff81896670: sfp_select_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
phy_interface_t sfp_select_interface(struct sfp_bus *bus, long unsigned int *link_modes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:392
Inline: False
```
**Symbols:**

```
ffffffff81c0b38e-ffffffff81c0b3a6: sfp_select_interface.cold (STB_LOCAL)
ffffffff81878e60-ffffffff81878efe: sfp_select_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
phy_interface_t sfp_select_interface(struct sfp_bus *bus, long unsigned int *link_modes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81909e16)
Location: drivers/net/phy/sfp-bus.c:392
Inline: True
```
**Symbols:**

```
ffffffff81d10810-ffffffff81d10828: sfp_select_interface.cold (STB_LOCAL)
ffffffff81909de0-ffffffff81909eb7: sfp_select_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
phy_interface_t sfp_select_interface(struct sfp_bus *bus, long unsigned int *link_modes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81a5d525)
Location: drivers/net/phy/sfp-bus.c:398
Inline: True
```
**Symbols:**

```
ffffffff81edb5b7-ffffffff81edb5db: sfp_select_interface.cold (STB_LOCAL)
ffffffff81a5d4f0-ffffffff81a5d5cb: sfp_select_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
phy_interface_t sfp_select_interface(struct sfp_bus *bus, long unsigned int *link_modes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81be7db0)
Location: drivers/net/phy/sfp-bus.c:347
Inline: False
```
**Symbols:**

```
ffffffff81be7db0-ffffffff81be7eb7: sfp_select_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
phy_interface_t sfp_select_interface(struct sfp_bus *bus, long unsigned int *link_modes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81c40150)
Location: drivers/net/phy/sfp-bus.c:357
Inline: False
```
**Symbols:**

```
ffffffff81c40150-ffffffff81c40257: sfp_select_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
phy_interface_t sfp_select_interface(struct sfp_bus *bus, long unsigned int *link_modes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81cf5780)
Location: drivers/net/phy/sfp-bus.c:357
Inline: False
```
**Symbols:**

```
ffffffff81cf5780-ffffffff81cf5887: sfp_select_interface (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
phy_interface_t sfp_select_interface(struct sfp_bus *bus, const struct sfp_eeprom_id *id, long unsigned int *link_modes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffff8000109d9dd0)
Location: drivers/net/phy/sfp-bus.c:255
Inline: True
```
**Symbols:**

```
ffff8000109d9dd0-ffff8000109d9e78: sfp_select_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
phy_interface_t sfp_select_interface(struct sfp_bus *bus, const struct sfp_eeprom_id *id, long unsigned int *link_modes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (c0ac09c0)
Location: drivers/net/phy/sfp-bus.c:255
Inline: True
```
**Symbols:**

```
c0ac09c0-c0ac0a74: sfp_select_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
phy_interface_t sfp_select_interface(struct sfp_bus *bus, const struct sfp_eeprom_id *id, long unsigned int *link_modes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (c000000000a9b860)
Location: drivers/net/phy/sfp-bus.c:255
Inline: True
```
**Symbols:**

```
c000000000a9b860-c000000000a9b928: sfp_select_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
phy_interface_t sfp_select_interface(struct sfp_bus *bus, const struct sfp_eeprom_id *id, long unsigned int *link_modes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffe000624cae)
Location: drivers/net/phy/sfp-bus.c:255
Inline: True
```
**Symbols:**

```
ffffffe000624cae-ffffffe000624d4c: sfp_select_interface (STB_GLOBAL)
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
phy_interface_t sfp_select_interface(struct sfp_bus *bus, const struct sfp_eeprom_id *id, long unsigned int *link_modes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff817844b4)
Location: drivers/net/phy/sfp-bus.c:255
Inline: True
```
**Symbols:**

```
ffffffff817844b4-ffffffff817844cb: sfp_select_interface.cold (STB_LOCAL)
ffffffff81784410-ffffffff8178447e: sfp_select_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
phy_interface_t sfp_select_interface(struct sfp_bus *bus, const struct sfp_eeprom_id *id, long unsigned int *link_modes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81763e04)
Location: drivers/net/phy/sfp-bus.c:255
Inline: True
```
**Symbols:**

```
ffffffff81763e04-ffffffff81763e1b: sfp_select_interface.cold (STB_LOCAL)
ffffffff81763d60-ffffffff81763dce: sfp_select_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
phy_interface_t sfp_select_interface(struct sfp_bus *bus, const struct sfp_eeprom_id *id, long unsigned int *link_modes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff817b4864)
Location: drivers/net/phy/sfp-bus.c:255
Inline: True
```
**Symbols:**

```
ffffffff817b4864-ffffffff817b487b: sfp_select_interface.cold (STB_LOCAL)
ffffffff817b47c0-ffffffff817b482e: sfp_select_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
phy_interface_t sfp_select_interface(struct sfp_bus *bus, const struct sfp_eeprom_id *id, long unsigned int *link_modes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff817ce834)
Location: drivers/net/phy/sfp-bus.c:255
Inline: True
```
**Symbols:**

```
ffffffff817ce834-ffffffff817ce84b: sfp_select_interface.cold (STB_LOCAL)
ffffffff817ce790-ffffffff817ce7fe: sfp_select_interface (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const struct sfp_eeprom_id *id</code>
</li>
<li>
<b>Param reordered. </b>
<code>bus, id, link_modes</code> ➡️ <code>bus, link_modes</code>
</li>
</ul>
</details>
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
