# Function: <code>mmc_power_off</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_off(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff816c0300)
Location: drivers/mmc/core/core.c:1750
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_power_save_host
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_pm_notify
Direct callers:
  - drivers/mmc/core/core.c:mmc_power_save_host
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffff816c0300-ffffffff816c0339: mmc_power_off.part.22 (STB_LOCAL)
ffffffff816c06a0-ffffffff816c06ba: mmc_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_off(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81723a7a)
Location: drivers/mmc/core/core.c:1766
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_power_save_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_power_save_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffff81723050-ffffffff81723089: mmc_power_off.part.29 (STB_LOCAL)
ffffffff817233e0-ffffffff817233fa: mmc_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_off(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8175693a)
Location: drivers/mmc/core/core.c:1836
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_power_save_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_power_save_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffff81755e70-ffffffff81755ea9: mmc_power_off.part.35 (STB_LOCAL)
ffffffff81756250-ffffffff8175626a: mmc_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_off(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8177487a)
Location: drivers/mmc/core/core.c:1661
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_power_save_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_power_save_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
```
**Symbols:**

```
ffffffff81773f00-ffffffff81773f39: mmc_power_off.part.33 (STB_LOCAL)
ffffffff81774280-ffffffff8177429b: mmc_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_off(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817eaabb)
Location: drivers/mmc/core/core.c:1875
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_power_save_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_power_save_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
```
**Symbols:**

```
ffffffff817ea0b0-ffffffff817ea0e9: mmc_power_off.part.35 (STB_LOCAL)
ffffffff817ea620-ffffffff817ea63b: mmc_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_off(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81833a0b)
Location: drivers/mmc/core/core.c:1679
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_power_save_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_power_save_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
```
**Symbols:**

```
ffffffff81832c90-ffffffff81832cc9: mmc_power_off.part.34 (STB_LOCAL)
ffffffff81833580-ffffffff8183359a: mmc_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_off(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8185f99b)
Location: drivers/mmc/core/core.c:1682
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
```
**Symbols:**

```
ffffffff8185eea0-ffffffff8185eed9: mmc_power_off.part.36 (STB_LOCAL)
ffffffff8185f510-ffffffff8185f52a: mmc_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_off(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818a3533)
Location: drivers/mmc/core/core.c:1364
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
```
**Symbols:**

```
ffffffff818a2950-ffffffff818a2989: mmc_power_off.part.0 (STB_LOCAL)
ffffffff818a30d0-ffffffff818a30ea: mmc_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_off(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818d58b3)
Location: drivers/mmc/core/core.c:1364
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
```
**Symbols:**

```
ffffffff818d4c50-ffffffff818d4c89: mmc_power_off.part.0 (STB_LOCAL)
ffffffff818d53c0-ffffffff818d53da: mmc_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void mmc_power_off(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a823f)
Location: drivers/mmc/core/core.c:1347
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffff819a7ba0-ffffffff819a7be3: mmc_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void mmc_power_off(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819ab431)
Location: drivers/mmc/core/core.c:1347
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffff819aae00-ffffffff819aae43: mmc_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void mmc_power_off(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819900aa)
Location: drivers/mmc/core/core.c:1353
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffff8198f6a0-ffffffff8198f6e3: mmc_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void mmc_power_off(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81a3b8ca)
Location: drivers/mmc/core/core.c:1354
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffff81a3ade0-ffffffff81a3ae28: mmc_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mmc_power_off(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81ba884e)
Location: drivers/mmc/core/core.c:1354
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffff81ba7c90-ffffffff81ba7cf0: mmc_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mmc_power_off(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81d4b0ce)
Location: drivers/mmc/core/core.c:1361
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffff81d4a370-ffffffff81d4a3d0: mmc_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mmc_power_off(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81db597e)
Location: drivers/mmc/core/core.c:1361
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffff81db4bd0-ffffffff81db4c30: mmc_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mmc_power_off(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81e6ddce)
Location: drivers/mmc/core/core.c:1366
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffff81e6d320-ffffffff81e6d380: mmc_power_off (STB_GLOBAL)
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
void mmc_power_off(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffff800010b2f29c)
Location: drivers/mmc/core/core.c:1364
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
```
**Symbols:**

```
ffff800010b2e2e0-ffff800010b2e32c: mmc_power_off.part.0 (STB_LOCAL)
ffff800010b2ebb8-ffff800010b2ebec: mmc_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_off(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (c0c0a688)
Location: drivers/mmc/core/core.c:1364
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
```
**Symbols:**

```
c0c09844-c0c0988c: mmc_power_off.part.0 (STB_LOCAL)
c0c0a0a8-c0c0a0d0: mmc_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_off(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (c000000000c28d38)
Location: drivers/mmc/core/core.c:1364
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
c000000000c27950-c000000000c279bc: mmc_power_off.part.0 (STB_LOCAL)
c000000000c285a0-c000000000c285c0: mmc_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_off(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffe000708ee4)
Location: drivers/mmc/core/core.c:1364
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffe000707bf2-ffffffe000707c42: mmc_power_off.part.0 (STB_LOCAL)
ffffffe000708376-ffffffe0007083a6: mmc_power_off (STB_GLOBAL)
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
void mmc_power_off(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81879273)
Location: drivers/mmc/core/core.c:1364
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
```
**Symbols:**

```
ffffffff81878610-ffffffff81878649: mmc_power_off.part.0 (STB_LOCAL)
ffffffff81878d80-ffffffff81878d9a: mmc_power_off (STB_GLOBAL)
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
void mmc_power_off(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818ca713)
Location: drivers/mmc/core/core.c:1364
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
```
**Symbols:**

```
ffffffff818c9ab0-ffffffff818c9ae9: mmc_power_off.part.0 (STB_LOCAL)
ffffffff818ca220-ffffffff818ca23a: mmc_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_power_off(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818e7233)
Location: drivers/mmc/core/core.c:1364
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
```
**Symbols:**

```
ffffffff818e65d0-ffffffff818e6609: mmc_power_off.part.0 (STB_LOCAL)
ffffffff818e6d40-ffffffff818e6d5a: mmc_power_off (STB_GLOBAL)
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
