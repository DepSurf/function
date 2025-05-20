# Function: <code>mmc_power_up</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_up(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff816c0010)
Location: drivers/mmc/core/core.c:1710
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_power_restore_host
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_start_host
Direct callers:
  - drivers/mmc/core/core.c:mmc_power_restore_host
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/sd.c:_mmc_sd_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff816c0010-ffffffff816c01f5: mmc_power_up.part.21 (STB_LOCAL)
ffffffff816c0680-ffffffff816c069a: mmc_power_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_up(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81722f89)
Location: drivers/mmc/core/core.c:1726
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_power_restore_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_power_restore_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81722d60-ffffffff81722f39: mmc_power_up.part.28 (STB_LOCAL)
ffffffff817233c0-ffffffff817233da: mmc_power_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_up(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81755d63)
Location: drivers/mmc/core/core.c:1796
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_power_restore_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_power_restore_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81755b30-ffffffff81755d09: mmc_power_up.part.34 (STB_LOCAL)
ffffffff81756230-ffffffff8175624a: mmc_power_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_up(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81773e3b)
Location: drivers/mmc/core/core.c:1621
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_power_restore_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_power_restore_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81773c10-ffffffff81773de4: mmc_power_up.part.32 (STB_LOCAL)
ffffffff81774260-ffffffff8177427b: mmc_power_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_up(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817e9fb8)
Location: drivers/mmc/core/core.c:1835
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_power_restore_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_power_restore_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff817e9d70-ffffffff817e9f53: mmc_power_up.part.34 (STB_LOCAL)
ffffffff817ea600-ffffffff817ea61b: mmc_power_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_up(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8183310a)
Location: drivers/mmc/core/core.c:1645
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_power_restore_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_power_restore_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81832f80-ffffffff818330a6: mmc_power_up.part.33 (STB_LOCAL)
ffffffff81833560-ffffffff8183357a: mmc_power_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_up(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8185ff53)
Location: drivers/mmc/core/core.c:1648
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff8185f050-ffffffff8185f176: mmc_power_up.part.35 (STB_LOCAL)
ffffffff8185f4f0-ffffffff8185f50a: mmc_power_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_up(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818a3b05)
Location: drivers/mmc/core/core.c:1330
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff818a2bd0-ffffffff818a2cf2: mmc_power_up.part.0 (STB_LOCAL)
ffffffff818a30b0-ffffffff818a30ca: mmc_power_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_up(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818d6075)
Location: drivers/mmc/core/core.c:1330
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff818d4ec0-ffffffff818d4fe2: mmc_power_up.part.0 (STB_LOCAL)
ffffffff818d53a0-ffffffff818d53ba: mmc_power_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_up(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a89b2)
Location: drivers/mmc/core/core.c:1313
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff819a74e0-ffffffff819a7602: mmc_power_up.part.0 (STB_LOCAL)
ffffffff819a7b80-ffffffff819a7b9a: mmc_power_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_up(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819aba72)
Location: drivers/mmc/core/core.c:1313
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff819aa730-ffffffff819aa852: mmc_power_up.part.0 (STB_LOCAL)
ffffffff819aade0-ffffffff819aadfa: mmc_power_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_up(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8198fffc)
Location: drivers/mmc/core/core.c:1319
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff8198efd0-ffffffff8198f0f2: mmc_power_up.part.0 (STB_LOCAL)
ffffffff8198f680-ffffffff8198f69a: mmc_power_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_up(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81a3b7cc)
Location: drivers/mmc/core/core.c:1320
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81a3a6b0-ffffffff81a3a7ee: mmc_power_up.part.0 (STB_LOCAL)
ffffffff81d2d12b-ffffffff81d2d15a: mmc_power_up.part.0.cold (STB_LOCAL)
ffffffff81a3adc0-ffffffff81a3adda: mmc_power_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_up(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81ba875a)
Location: drivers/mmc/core/core.c:1320
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81ba7510-ffffffff81ba767d: mmc_power_up.part.0 (STB_LOCAL)
ffffffff81ef94e9-ffffffff81ef9517: mmc_power_up.part.0.cold (STB_LOCAL)
ffffffff81ba7c60-ffffffff81ba7c8a: mmc_power_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_up(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81d4afba)
Location: drivers/mmc/core/core.c:1327
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81d49b90-ffffffff81d49cfd: mmc_power_up.part.0 (STB_LOCAL)
ffffffff820a963c-ffffffff820a966a: mmc_power_up.part.0.cold (STB_LOCAL)
ffffffff81d4a330-ffffffff81d4a35a: mmc_power_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_up(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81db586a)
Location: drivers/mmc/core/core.c:1327
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81db4400-ffffffff81db456d: mmc_power_up.part.0 (STB_LOCAL)
ffffffff8212aa3b-ffffffff8212aa69: mmc_power_up.part.0.cold (STB_LOCAL)
ffffffff81db4b90-ffffffff81db4bba: mmc_power_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void mmc_power_up(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1332
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff8220c870-ffffffff8220c89e: mmc_power_up.cold (STB_LOCAL)
ffffffff81e6cc30-ffffffff81e6cdbc: mmc_power_up (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_up(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffff800010b2fe00)
Location: drivers/mmc/core/core.c:1330
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffff800010b2e690-ffff800010b2e800: mmc_power_up.part.0 (STB_LOCAL)
ffff800010b2eb78-ffff800010b2ebb8: mmc_power_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_up(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (c0c0af94)
Location: drivers/mmc/core/core.c:1330
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
c0c09bc0-c0c09d18: mmc_power_up.part.0 (STB_LOCAL)
c0c0a080-c0c0a0a8: mmc_power_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_up(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (c000000000c298e0)
Location: drivers/mmc/core/core.c:1330
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
c000000000c27ee0-c000000000c28098: mmc_power_up.part.0 (STB_LOCAL)
c000000000c28580-c000000000c285a0: mmc_power_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_up(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffe000708dfc)
Location: drivers/mmc/core/core.c:1330
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffe000707ebe-ffffffe000708054: mmc_power_up.part.0 (STB_LOCAL)
ffffffe00070833a-ffffffe000708376: mmc_power_up (STB_GLOBAL)
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
void mmc_power_up(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81879a35)
Location: drivers/mmc/core/core.c:1330
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81878880-ffffffff818789a2: mmc_power_up.part.0 (STB_LOCAL)
ffffffff81878d60-ffffffff81878d7a: mmc_power_up (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_up(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818caed5)
Location: drivers/mmc/core/core.c:1330
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff818c9d20-ffffffff818c9e42: mmc_power_up.part.0 (STB_LOCAL)
ffffffff818ca200-ffffffff818ca21a: mmc_power_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_up(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818e79f5)
Location: drivers/mmc/core/core.c:1330
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff818e6840-ffffffff818e6962: mmc_power_up.part.0 (STB_LOCAL)
ffffffff818e6d20-ffffffff818e6d3a: mmc_power_up (STB_GLOBAL)
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
