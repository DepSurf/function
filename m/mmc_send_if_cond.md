# Function: <code>mmc_send_if_cond</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mmc_send_if_cond(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff816c8370)
Location: drivers/mmc/core/sd_ops.c:196
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff816c8370-ffffffff816c840d: mmc_send_if_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mmc_send_if_cond(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff8172b320)
Location: drivers/mmc/core/sd_ops.c:191
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff8172b320-ffffffff8172b3bc: mmc_send_if_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mmc_send_if_cond(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff8175e3d0)
Location: drivers/mmc/core/sd_ops.c:186
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff8175e3d0-ffffffff8175e46c: mmc_send_if_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mmc_send_if_cond(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff8177cb40)
Location: drivers/mmc/core/sd_ops.c:186
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffffffff8177cb40-ffffffff8177cbda: mmc_send_if_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mmc_send_if_cond(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff817f30c0)
Location: drivers/mmc/core/sd_ops.c:186
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffffffff817f30c0-ffffffff817f315a: mmc_send_if_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mmc_send_if_cond(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff8183c500)
Location: drivers/mmc/core/sd_ops.c:186
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffffffff8183c500-ffffffff8183c59a: mmc_send_if_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mmc_send_if_cond(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff81868490)
Location: drivers/mmc/core/sd_ops.c:186
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffffffff81868490-ffffffff8186852a: mmc_send_if_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mmc_send_if_cond(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff818ac3b0)
Location: drivers/mmc/core/sd_ops.c:161
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffffffff818ac3b0-ffffffff818ac44a: mmc_send_if_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mmc_send_if_cond(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff818de800)
Location: drivers/mmc/core/sd_ops.c:161
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffffffff818de800-ffffffff818de89a: mmc_send_if_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mmc_send_if_cond(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff819b1620)
Location: drivers/mmc/core/sd_ops.c:161
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff819b1620-ffffffff819b16b9: mmc_send_if_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mmc_send_if_cond(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff819b3940)
Location: drivers/mmc/core/sd_ops.c:196
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff819b3940-ffffffff819b39d9: mmc_send_if_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mmc_send_if_cond(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff81998120)
Location: drivers/mmc/core/sd_ops.c:196
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81998120-ffffffff819981b7: mmc_send_if_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mmc_send_if_cond(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff81a448e0)
Location: drivers/mmc/core/sd_ops.c:197
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81a448e0-ffffffff81a44977: mmc_send_if_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mmc_send_if_cond(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff81bb2410)
Location: drivers/mmc/core/sd_ops.c:197
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81bb2410-ffffffff81bb24b3: mmc_send_if_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mmc_send_if_cond(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff81d566f0)
Location: drivers/mmc/core/sd_ops.c:197
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81d566f0-ffffffff81d56793: mmc_send_if_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mmc_send_if_cond(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff81dc1060)
Location: drivers/mmc/core/sd_ops.c:197
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81dc1060-ffffffff81dc1103: mmc_send_if_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mmc_send_if_cond(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff81e799a0)
Location: drivers/mmc/core/sd_ops.c:197
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81e799a0-ffffffff81e79a43: mmc_send_if_cond (STB_GLOBAL)
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
int mmc_send_if_cond(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffff800010b38938)
Location: drivers/mmc/core/sd_ops.c:161
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffff800010b38938-ffff800010b389f4: mmc_send_if_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mmc_send_if_cond(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (c0c132c8)
Location: drivers/mmc/core/sd_ops.c:161
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
c0c132c8-c0c1338c: mmc_send_if_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mmc_send_if_cond(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (c000000000c34820)
Location: drivers/mmc/core/sd_ops.c:161
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
c000000000c34820-c000000000c34920: mmc_send_if_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mmc_send_if_cond(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffe0007106e8)
Location: drivers/mmc/core/sd_ops.c:161
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffffffe0007106e8-ffffffe00071077c: mmc_send_if_cond (STB_GLOBAL)
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
int mmc_send_if_cond(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff818821c0)
Location: drivers/mmc/core/sd_ops.c:161
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffffffff818821c0-ffffffff8188225a: mmc_send_if_cond (STB_GLOBAL)
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
int mmc_send_if_cond(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff818d3660)
Location: drivers/mmc/core/sd_ops.c:161
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffffffff818d3660-ffffffff818d36fa: mmc_send_if_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mmc_send_if_cond(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff818f0180)
Location: drivers/mmc/core/sd_ops.c:161
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffffffff818f0180-ffffffff818f021a: mmc_send_if_cond (STB_GLOBAL)
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
