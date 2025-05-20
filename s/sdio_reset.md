# Function: <code>sdio_reset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sdio_reset(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff816ca680)
Location: drivers/mmc/core/sdio_ops.c:207
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff816ca680-ffffffff816ca708: sdio_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sdio_reset(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff8172d630)
Location: drivers/mmc/core/sdio_ops.c:207
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff8172d630-ffffffff8172d6b8: sdio_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sdio_reset(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff817605f0)
Location: drivers/mmc/core/sdio_ops.c:202
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff817605f0-ffffffff81760678: sdio_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sdio_reset(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff8177ee40)
Location: drivers/mmc/core/sdio_ops.c:201
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffffffff8177ee40-ffffffff8177eec8: sdio_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sdio_reset(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff817f53e0)
Location: drivers/mmc/core/sdio_ops.c:201
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffffffff817f53e0-ffffffff817f5468: sdio_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sdio_reset(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff8183e8c0)
Location: drivers/mmc/core/sdio_ops.c:201
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffffffff8183e8c0-ffffffff8183e946: sdio_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sdio_reset(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff8186a870)
Location: drivers/mmc/core/sdio_ops.c:201
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffffffff8186a870-ffffffff8186a8f6: sdio_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sdio_reset(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff818ae740)
Location: drivers/mmc/core/sdio_ops.c:197
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffffffff818ae740-ffffffff818ae7c8: sdio_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sdio_reset(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff818e0bf0)
Location: drivers/mmc/core/sdio_ops.c:197
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffffffff818e0bf0-ffffffff818e0c78: sdio_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sdio_reset(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff819b3c70)
Location: drivers/mmc/core/sdio_ops.c:202
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff819b3c70-ffffffff819b3d71: sdio_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sdio_reset(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff819b60f0)
Location: drivers/mmc/core/sdio_ops.c:202
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff819b60f0-ffffffff819b61f1: sdio_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sdio_reset(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff8199a8a0)
Location: drivers/mmc/core/sdio_ops.c:202
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff8199a8a0-ffffffff8199a9a1: sdio_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sdio_reset(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff81a471e0)
Location: drivers/mmc/core/sdio_ops.c:202
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81a471e0-ffffffff81a472e1: sdio_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sdio_reset(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff81bb5070)
Location: drivers/mmc/core/sdio_ops.c:202
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81bb5070-ffffffff81bb517e: sdio_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sdio_reset(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff81d59780)
Location: drivers/mmc/core/sdio_ops.c:202
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81d59780-ffffffff81d5988e: sdio_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sdio_reset(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff81dc4120)
Location: drivers/mmc/core/sdio_ops.c:202
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81dc4120-ffffffff81dc422e: sdio_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sdio_reset(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff81e7ca00)
Location: drivers/mmc/core/sdio_ops.c:202
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81e7ca00-ffffffff81e7cb0e: sdio_reset (STB_GLOBAL)
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
int sdio_reset(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffff800010b3ad80)
Location: drivers/mmc/core/sdio_ops.c:197
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffff800010b3ad80-ffff800010b3ae14: sdio_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sdio_reset(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (c0c15764)
Location: drivers/mmc/core/sdio_ops.c:197
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
c0c15764-c0c15804: sdio_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sdio_reset(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (c000000000c37850)
Location: drivers/mmc/core/sdio_ops.c:197
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
c000000000c37850-c000000000c378f8: sdio_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sdio_reset(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffe0007126b0)
Location: drivers/mmc/core/sdio_ops.c:197
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffffffe0007126b0-ffffffe000712710: sdio_reset (STB_GLOBAL)
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
int sdio_reset(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff818845b0)
Location: drivers/mmc/core/sdio_ops.c:197
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffffffff818845b0-ffffffff81884638: sdio_reset (STB_GLOBAL)
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
int sdio_reset(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff818d5a50)
Location: drivers/mmc/core/sdio_ops.c:197
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffffffff818d5a50-ffffffff818d5ad8: sdio_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sdio_reset(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff818f2570)
Location: drivers/mmc/core/sdio_ops.c:197
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffffffff818f2570-ffffffff818f25f8: sdio_reset (STB_GLOBAL)
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
