# Function: <code>mmc_power_cycle</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mmc_power_cycle(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff816c06c0)
Location: drivers/mmc/core/core.c:1772
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/core.c:mmc_set_signal_voltage
  - drivers/mmc/core/sd.c:mmc_sd_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_reset
```
**Symbols:**

```
ffffffff816c06c0-ffffffff816c070a: mmc_power_cycle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mmc_power_cycle(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81723400)
Location: drivers/mmc/core/core.c:1788
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_signal_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/mmc.c:mmc_reset
  - drivers/mmc/core/sd.c:mmc_sd_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_reset
```
**Symbols:**

```
ffffffff81723400-ffffffff8172344a: mmc_power_cycle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mmc_power_cycle(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81756270)
Location: drivers/mmc/core/core.c:1858
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_signal_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/mmc.c:mmc_reset
  - drivers/mmc/core/sd.c:mmc_sd_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_reset
```
**Symbols:**

```
ffffffff81756270-ffffffff817562ba: mmc_power_cycle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mmc_power_cycle(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817742a0)
Location: drivers/mmc/core/core.c:1683
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/mmc.c:mmc_reset
  - drivers/mmc/core/sd.c:mmc_sd_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_reset
```
**Symbols:**

```
ffffffff817742a0-ffffffff817742ea: mmc_power_cycle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mmc_power_cycle(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817ea640)
Location: drivers/mmc/core/core.c:1897
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/mmc.c:mmc_reset
  - drivers/mmc/core/sd.c:mmc_sd_reset
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_reset
```
**Symbols:**

```
ffffffff817ea640-ffffffff817ea68a: mmc_power_cycle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mmc_power_cycle(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818335a0)
Location: drivers/mmc/core/core.c:1701
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
```
**Symbols:**

```
ffffffff818335a0-ffffffff818335e8: mmc_power_cycle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mmc_power_cycle(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8185f530)
Location: drivers/mmc/core/core.c:1704
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
```
**Symbols:**

```
ffffffff8185f530-ffffffff8185f578: mmc_power_cycle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mmc_power_cycle(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818a30f0)
Location: drivers/mmc/core/core.c:1386
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
```
**Symbols:**

```
ffffffff818a30f0-ffffffff818a313c: mmc_power_cycle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mmc_power_cycle(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818d53e0)
Location: drivers/mmc/core/core.c:1386
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
```
**Symbols:**

```
ffffffff818d53e0-ffffffff818d542c: mmc_power_cycle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mmc_power_cycle(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a7bf0)
Location: drivers/mmc/core/core.c:1369
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
```
**Symbols:**

```
ffffffff819a7bf0-ffffffff819a7c65: mmc_power_cycle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mmc_power_cycle(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819aae50)
Location: drivers/mmc/core/core.c:1369
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
```
**Symbols:**

```
ffffffff819aae50-ffffffff819aaec5: mmc_power_cycle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mmc_power_cycle(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8198f6f0)
Location: drivers/mmc/core/core.c:1375
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
```
**Symbols:**

```
ffffffff8198f6f0-ffffffff8198f765: mmc_power_cycle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mmc_power_cycle(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81a3ae30)
Location: drivers/mmc/core/core.c:1376
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
```
**Symbols:**

```
ffffffff81a3ae30-ffffffff81a3aeaf: mmc_power_cycle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mmc_power_cycle(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81ba7cf0)
Location: drivers/mmc/core/core.c:1376
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
```
**Symbols:**

```
ffffffff81ba7cf0-ffffffff81ba7d77: mmc_power_cycle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mmc_power_cycle(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81d4a3e0)
Location: drivers/mmc/core/core.c:1383
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
```
**Symbols:**

```
ffffffff81d4a3e0-ffffffff81d4a467: mmc_power_cycle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mmc_power_cycle(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81db4c40)
Location: drivers/mmc/core/core.c:1383
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
```
**Symbols:**

```
ffffffff81db4c40-ffffffff81db4cc7: mmc_power_cycle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mmc_power_cycle(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81e6d074)
Location: drivers/mmc/core/core.c:1388
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
```
**Symbols:**

```
ffffffff81e6d390-ffffffff81e6d40e: mmc_power_cycle (STB_GLOBAL)
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
void mmc_power_cycle(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffff800010b2ebf0)
Location: drivers/mmc/core/core.c:1386
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
```
**Symbols:**

```
ffff800010b2ebf0-ffff800010b2ec4c: mmc_power_cycle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mmc_power_cycle(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c0c0a0d0)
Location: drivers/mmc/core/core.c:1386
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
```
**Symbols:**

```
c0c0a0d0-c0c0a124: mmc_power_cycle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mmc_power_cycle(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c000000000c285c0)
Location: drivers/mmc/core/core.c:1386
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
```
**Symbols:**

```
c000000000c285c0-c000000000c28658: mmc_power_cycle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mmc_power_cycle(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffe0007083a6)
Location: drivers/mmc/core/core.c:1386
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
```
**Symbols:**

```
ffffffe0007083a6-ffffffe000708402: mmc_power_cycle (STB_GLOBAL)
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
void mmc_power_cycle(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81878da0)
Location: drivers/mmc/core/core.c:1386
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
```
**Symbols:**

```
ffffffff81878da0-ffffffff81878dec: mmc_power_cycle (STB_GLOBAL)
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
void mmc_power_cycle(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818ca240)
Location: drivers/mmc/core/core.c:1386
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
```
**Symbols:**

```
ffffffff818ca240-ffffffff818ca28c: mmc_power_cycle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mmc_power_cycle(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818e6d60)
Location: drivers/mmc/core/core.c:1386
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
```
**Symbols:**

```
ffffffff818e6d60-ffffffff818e6dac: mmc_power_cycle (STB_GLOBAL)
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
