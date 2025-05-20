# Function: <code>mmc_detach_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void mmc_detach_bus(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff816c0bb0)
Location: drivers/mmc/core/core.c:1847
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff816c0bb0-ffffffff816c0c6e: mmc_detach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void mmc_detach_bus(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817238e0)
Location: drivers/mmc/core/core.c:1863
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffff817238e0-ffffffff8172399e: mmc_detach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mmc_detach_bus(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81756770)
Location: drivers/mmc/core/core.c:1928
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffff81756770-ffffffff8175685c: mmc_detach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mmc_detach_bus(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81774710)
Location: drivers/mmc/core/core.c:1753
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff81774710-ffffffff8177479e: mmc_detach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mmc_detach_bus(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817ea940)
Location: drivers/mmc/core/core.c:1967
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff817ea940-ffffffff817ea9ce: mmc_detach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mmc_detach_bus(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81833890)
Location: drivers/mmc/core/core.c:1771
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff81833890-ffffffff81833915: mmc_detach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mmc_detach_bus(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8185f820)
Location: drivers/mmc/core/core.c:1774
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff8185f820-ffffffff8185f8a5: mmc_detach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void mmc_detach_bus(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1456
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff818a40a2-ffffffff818a40c8: mmc_detach_bus.cold (STB_LOCAL)
ffffffff818a33c0-ffffffff818a344e: mmc_detach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mmc_detach_bus(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818d56b0)
Location: drivers/mmc/core/core.c:1456
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff818d56b0-ffffffff818d573e: mmc_detach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mmc_detach_bus(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a8080)
Location: drivers/mmc/core/core.c:1439
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffff819a8080-ffffffff819a810e: mmc_detach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mmc_detach_bus(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819ab2e0)
Location: drivers/mmc/core/core.c:1439
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffff819ab2e0-ffffffff819ab36e: mmc_detach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void mmc_detach_bus(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81990095)
Location: drivers/mmc/core/core.c:1395
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffff8198f990-ffffffff8198f9a6: mmc_detach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void mmc_detach_bus(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81a3b8b5)
Location: drivers/mmc/core/core.c:1396
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffff81a3b0e0-ffffffff81a3b0f6: mmc_detach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mmc_detach_bus(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81ba883c)
Location: drivers/mmc/core/core.c:1396
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffff81ba7fd0-ffffffff81ba7fec: mmc_detach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mmc_detach_bus(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81d4b0bc)
Location: drivers/mmc/core/core.c:1403
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffff81d4a7b0-ffffffff81d4a7cc: mmc_detach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mmc_detach_bus(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81db596c)
Location: drivers/mmc/core/core.c:1403
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffff81db5000-ffffffff81db501c: mmc_detach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mmc_detach_bus(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81e6ddbc)
Location: drivers/mmc/core/core.c:1408
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffff81e6d450-ffffffff81e6d46c: mmc_detach_bus (STB_GLOBAL)
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
void mmc_detach_bus(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffff800010b2efb0)
Location: drivers/mmc/core/core.c:1456
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffff800010b2efb0-ffff800010b2f120: mmc_detach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mmc_detach_bus(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c0c0a46c)
Location: drivers/mmc/core/core.c:1456
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
c0c0a46c-c0c0a558: mmc_detach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mmc_detach_bus(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c000000000c28ac0)
Location: drivers/mmc/core/core.c:1456
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
c000000000c28ac0-c000000000c28b98: mmc_detach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mmc_detach_bus(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffe00070872a)
Location: drivers/mmc/core/core.c:1456
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffe00070872a-ffffffe0007087cc: mmc_detach_bus (STB_GLOBAL)
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
void mmc_detach_bus(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81879070)
Location: drivers/mmc/core/core.c:1456
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff81879070-ffffffff818790fe: mmc_detach_bus (STB_GLOBAL)
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
void mmc_detach_bus(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818ca510)
Location: drivers/mmc/core/core.c:1456
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff818ca510-ffffffff818ca59e: mmc_detach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mmc_detach_bus(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818e7030)
Location: drivers/mmc/core/core.c:1456
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff818e7030-ffffffff818e70be: mmc_detach_bus (STB_GLOBAL)
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
