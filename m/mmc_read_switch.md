# Function: <code>mmc_read_switch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff816c7318)
Location: drivers/mmc/core/sd.c:280
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_setup_card
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff8172a2ff)
Location: drivers/mmc/core/sd.c:278
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_setup_card
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff8175d405)
Location: drivers/mmc/core/sd.c:278
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_setup_card
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff8177bb98)
Location: drivers/mmc/core/sd.c:280
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int mmc_read_switch(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff817f1750)
Location: drivers/mmc/core/sd.c:280
Inline: True
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff817f1750-ffffffff817f1878: mmc_read_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_read_switch(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:280
Inline: True
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff8183aaf0-ffffffff8183abc5: mmc_read_switch (STB_LOCAL)
ffffffff8183bef7-ffffffff8183bf43: mmc_read_switch.cold.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_read_switch(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81866a8a)
Location: drivers/mmc/core/sd.c:280
Inline: True
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff81866a60-ffffffff81866b35: mmc_read_switch (STB_LOCAL)
ffffffff81867e87-ffffffff81867ed3: mmc_read_switch.cold.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff818ab88d)
Location: drivers/mmc/core/sd.c:300
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff818aa8b0-ffffffff818aa97d: mmc_read_switch.part.0 (STB_LOCAL)
ffffffff818abd6e-ffffffff818abdba: mmc_read_switch.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff818ddcdd)
Location: drivers/mmc/core/sd.c:300
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff818dcd00-ffffffff818dcdcd: mmc_read_switch.part.0 (STB_LOCAL)
ffffffff818de1d5-ffffffff818de221: mmc_read_switch.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff819b0ab7)
Location: drivers/mmc/core/sd.c:300
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_setup_card
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_setup_card
```
**Symbols:**

```
ffffffff819afea0-ffffffff819aff6d: mmc_read_switch.part.0 (STB_LOCAL)
ffffffff819b1087-ffffffff819b10d3: mmc_read_switch.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff819b3027)
Location: drivers/mmc/core/sd.c:300
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_setup_card
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_setup_card
```
**Symbols:**

```
ffffffff819b2410-ffffffff819b24dd: mmc_read_switch.part.0 (STB_LOCAL)
ffffffff81c2aed7-ffffffff81c2af23: mmc_read_switch.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81997807)
Location: drivers/mmc/core/sd.c:306
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_setup_card
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_setup_card
```
**Symbols:**

```
ffffffff81996b70-ffffffff81996c3d: mmc_read_switch.part.0 (STB_LOCAL)
ffffffff81c1d22d-ffffffff81c1d279: mmc_read_switch.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81a43ec3)
Location: drivers/mmc/core/sd.c:316
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_setup_card
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_setup_card
```
**Symbols:**

```
ffffffff81a42a80-ffffffff81a42b4d: mmc_read_switch.part.0 (STB_LOCAL)
ffffffff81d2e100-ffffffff81d2e14c: mmc_read_switch.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_read_switch(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81bb03ab)
Location: drivers/mmc/core/sd.c:325
Inline: True
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_setup_card
```
**Symbols:**

```
ffffffff81bb0380-ffffffff81bb046a: mmc_read_switch (STB_LOCAL)
ffffffff81efa532-ffffffff81efa57b: mmc_read_switch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81d55625)
Location: drivers/mmc/core/sd.c:325
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_setup_card
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81dbff65)
Location: drivers/mmc/core/sd.c:325
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_setup_card
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81e78725)
Location: drivers/mmc/core/sd.c:325
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_setup_card
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (ffff800010b3804c)
Location: drivers/mmc/core/sd.c:300
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffff800010b36f60-ffff800010b37080: mmc_read_switch.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (c0c12968)
Location: drivers/mmc/core/sd.c:300
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
c0c118cc-c0c119f0: mmc_read_switch.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (c000000000c33b88)
Location: drivers/mmc/core/sd.c:300
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
c000000000c324d0-c000000000c32644: mmc_read_switch.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffe00070ff10)
Location: drivers/mmc/core/sd.c:300
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffe00070efa4-ffffffe00070f0b2: mmc_read_switch.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff8188169d)
Location: drivers/mmc/core/sd.c:300
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff818806c0-ffffffff8188078d: mmc_read_switch.part.0 (STB_LOCAL)
ffffffff81881b95-ffffffff81881be1: mmc_read_switch.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff818d2b3d)
Location: drivers/mmc/core/sd.c:300
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff818d1b60-ffffffff818d1c2d: mmc_read_switch.part.0 (STB_LOCAL)
ffffffff818d3035-ffffffff818d3081: mmc_read_switch.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff818ef65d)
Location: drivers/mmc/core/sd.c:300
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff818ee680-ffffffff818ee74d: mmc_read_switch.part.0 (STB_LOCAL)
ffffffff818efb55-ffffffff818efba1: mmc_read_switch.part.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
