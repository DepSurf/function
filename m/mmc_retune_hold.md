# Function: <code>mmc_retune_hold</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mmc_retune_hold(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff816c2190)
Location: drivers/mmc/core/host.c:86
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffffffff816c2190-ffffffff816c21b5: mmc_retune_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_hold(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81724bab)
Location: drivers/mmc/core/host.c:109
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffffffff81724f10-ffffffff81724f35: mmc_retune_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_hold(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81757b2b)
Location: drivers/mmc/core/host.c:109
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffffffff81757e90-ffffffff81757eb5: mmc_retune_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_hold(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81775dcb)
Location: drivers/mmc/core/host.c:107
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_start_bkops
  - drivers/mmc/core/mmc_ops.c:mmc_start_bkops
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffffffff81776150-ffffffff81776175: mmc_retune_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_hold(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff817ec16b)
Location: drivers/mmc/core/host.c:107
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffffffff817ec4c0-ffffffff817ec4e5: mmc_retune_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_hold(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81835351)
Location: drivers/mmc/core/host.c:107
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffffffff818356d0-ffffffff818356f5: mmc_retune_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_hold(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81861301)
Location: drivers/mmc/core/host.c:107
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffffffff81861680-ffffffff818616a5: mmc_retune_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_hold(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff818a501b)
Location: drivers/mmc/core/host.c:104
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffffffff818a53a0-ffffffff818a53c5: mmc_retune_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_hold(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff818d749b)
Location: drivers/mmc/core/host.c:104
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffffffff818d7830-ffffffff818d7855: mmc_retune_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_hold(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff819a9e0b)
Location: drivers/mmc/core/host.c:104
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/mmc.c:mmc_sleep
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffffffff819aa190-ffffffff819aa1b5: mmc_retune_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_hold(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff819ac9c0)
Location: drivers/mmc/core/host.c:106
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/mmc.c:mmc_sleep
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffffffff819acda0-ffffffff819acdc5: mmc_retune_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_hold(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81990e5b)
Location: drivers/mmc/core/host.c:145
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffffffff819915f0-ffffffff81991615: mmc_retune_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_hold(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81a3c8db)
Location: drivers/mmc/core/host.c:163
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffffffff81a3cda0-ffffffff81a3cdc5: mmc_retune_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_hold(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81ba999b)
Location: drivers/mmc/core/host.c:163
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffffffff81ba9e60-ffffffff81ba9e8d: mmc_retune_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_hold(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81d4c79b)
Location: drivers/mmc/core/host.c:163
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffffffff81d4cd10-ffffffff81d4cd3d: mmc_retune_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_hold(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81db706b)
Location: drivers/mmc/core/host.c:163
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffffffff81db7670-ffffffff81db769d: mmc_retune_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_hold(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81e6f52f)
Location: drivers/mmc/core/host.c:162
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffffffff81e6fb40-ffffffff81e6fb6d: mmc_retune_hold (STB_GLOBAL)
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
void mmc_retune_hold(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffff800010b31814)
Location: drivers/mmc/core/host.c:104
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffff800010b31bb0-ffff800010b31bf0: mmc_retune_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_hold(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (c0c0c4cc)
Location: drivers/mmc/core/host.c:104
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
c0c0c810-c0c0c844: mmc_retune_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_hold(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (c000000000c2b5cc)
Location: drivers/mmc/core/host.c:104
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
c000000000c2bab0-c000000000c2badc: mmc_retune_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_hold(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffe00070a230)
Location: drivers/mmc/core/host.c:104
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffffffe00070a5ae-ffffffe00070a5e6: mmc_retune_hold (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_hold(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff8187ae5b)
Location: drivers/mmc/core/host.c:104
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffffffff8187b1f0-ffffffff8187b215: mmc_retune_hold (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_hold(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff818cc2fb)
Location: drivers/mmc/core/host.c:104
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffffffff818cc690-ffffffff818cc6b5: mmc_retune_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_hold(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff818e8e1b)
Location: drivers/mmc/core/host.c:104
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffffffff818e91b0-ffffffff818e91d5: mmc_retune_hold (STB_GLOBAL)
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
