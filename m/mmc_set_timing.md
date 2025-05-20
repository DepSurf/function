# Function: <code>mmc_set_timing</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mmc_set_timing(struct mmc_host *host, unsigned int timing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff816c04b0)
Location: drivers/mmc/core/core.c:1651
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff816c04b0-ffffffff816c0557: mmc_set_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mmc_set_timing(struct mmc_host *host, unsigned int timing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817231f0)
Location: drivers/mmc/core/core.c:1667
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff817231f0-ffffffff8172329a: mmc_set_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mmc_set_timing(struct mmc_host *host, unsigned int timing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81756060)
Location: drivers/mmc/core/core.c:1737
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81756060-ffffffff8175610a: mmc_set_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mmc_set_timing(struct mmc_host *host, unsigned int timing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817740a0)
Location: drivers/mmc/core/core.c:1562
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff817740a0-ffffffff8177413f: mmc_set_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mmc_set_timing(struct mmc_host *host, unsigned int timing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817ea430)
Location: drivers/mmc/core/core.c:1776
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff817ea430-ffffffff817ea4d5: mmc_set_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mmc_set_timing(struct mmc_host *host, unsigned int timing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81833390)
Location: drivers/mmc/core/core.c:1586
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81833390-ffffffff81833433: mmc_set_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mmc_set_timing(struct mmc_host *host, unsigned int timing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8185f320)
Location: drivers/mmc/core/core.c:1589
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff8185f320-ffffffff8185f3c3: mmc_set_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mmc_set_timing(struct mmc_host *host, unsigned int timing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818a2ec0)
Location: drivers/mmc/core/core.c:1271
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff818a2ec0-ffffffff818a2f76: mmc_set_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mmc_set_timing(struct mmc_host *host, unsigned int timing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818d51b0)
Location: drivers/mmc/core/core.c:1271
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff818d51b0-ffffffff818d5266: mmc_set_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mmc_set_timing(struct mmc_host *host, unsigned int timing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a7990)
Location: drivers/mmc/core/core.c:1254
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
```
**Symbols:**

```
ffffffff819a7990-ffffffff819a7a46: mmc_set_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mmc_set_timing(struct mmc_host *host, unsigned int timing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819aabf0)
Location: drivers/mmc/core/core.c:1254
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
```
**Symbols:**

```
ffffffff819aabf0-ffffffff819aaca6: mmc_set_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mmc_set_timing(struct mmc_host *host, unsigned int timing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8198f490)
Location: drivers/mmc/core/core.c:1260
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
```
**Symbols:**

```
ffffffff8198f490-ffffffff8198f546: mmc_set_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void mmc_set_timing(struct mmc_host *host, unsigned int timing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1261
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
```
**Symbols:**

```
ffffffff81d2d1aa-ffffffff81d2d1ca: mmc_set_timing.cold (STB_LOCAL)
ffffffff81a3abb0-ffffffff81a3ac71: mmc_set_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void mmc_set_timing(struct mmc_host *host, unsigned int timing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1261
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
```
**Symbols:**

```
ffffffff81ef9564-ffffffff81ef9584: mmc_set_timing.cold (STB_LOCAL)
ffffffff81ba7a20-ffffffff81ba7aed: mmc_set_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void mmc_set_timing(struct mmc_host *host, unsigned int timing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1268
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
```
**Symbols:**

```
ffffffff820a96b7-ffffffff820a96d7: mmc_set_timing.cold (STB_LOCAL)
ffffffff81d4a0c0-ffffffff81d4a18c: mmc_set_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mmc_set_timing(struct mmc_host *host, unsigned int timing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1268
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
```
**Symbols:**

```
ffffffff8212aab6-ffffffff8212aad6: mmc_set_timing.cold (STB_LOCAL)
ffffffff81db4920-ffffffff81db49e9: mmc_set_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void mmc_set_timing(struct mmc_host *host, unsigned int timing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1273
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
```
**Symbols:**

```
ffffffff8220c830-ffffffff8220c850: mmc_set_timing.cold (STB_LOCAL)
ffffffff81e6c9c0-ffffffff81e6ca89: mmc_set_timing (STB_GLOBAL)
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
void mmc_set_timing(struct mmc_host *host, unsigned int timing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffff800010b2e978)
Location: drivers/mmc/core/core.c:1271
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffff800010b2e978-ffff800010b2ea28: mmc_set_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mmc_set_timing(struct mmc_host *host, unsigned int timing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c0c09ea4)
Location: drivers/mmc/core/core.c:1271
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
c0c09ea4-c0c09f58: mmc_set_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mmc_set_timing(struct mmc_host *host, unsigned int timing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c000000000c282b0)
Location: drivers/mmc/core/core.c:1271
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
c000000000c282b0-c000000000c283b8: mmc_set_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mmc_set_timing(struct mmc_host *host, unsigned int timing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffe00070818c)
Location: drivers/mmc/core/core.c:1271
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffe00070818c-ffffffe000708220: mmc_set_timing (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void mmc_set_timing(struct mmc_host *host, unsigned int timing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81878b70)
Location: drivers/mmc/core/core.c:1271
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81878b70-ffffffff81878c26: mmc_set_timing (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mmc_set_timing(struct mmc_host *host, unsigned int timing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818ca010)
Location: drivers/mmc/core/core.c:1271
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff818ca010-ffffffff818ca0c6: mmc_set_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mmc_set_timing(struct mmc_host *host, unsigned int timing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818e6b30)
Location: drivers/mmc/core/core.c:1271
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff818e6b30-ffffffff818e6be6: mmc_set_timing (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
