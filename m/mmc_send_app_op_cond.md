# Function: <code>mmc_send_app_op_cond</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mmc_send_app_op_cond(struct mmc_host *host, u32 ocr, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff816c8250)
Location: drivers/mmc/core/sd_ops.c:150
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sd.c:mmc_attach_sd
```
**Symbols:**

```
ffffffff816c8250-ffffffff816c836d: mmc_send_app_op_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mmc_send_app_op_cond(struct mmc_host *host, u32 ocr, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff8172b200)
Location: drivers/mmc/core/sd_ops.c:145
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
**Symbols:**

```
ffffffff8172b200-ffffffff8172b317: mmc_send_app_op_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mmc_send_app_op_cond(struct mmc_host *host, u32 ocr, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff8175e2c0)
Location: drivers/mmc/core/sd_ops.c:142
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
**Symbols:**

```
ffffffff8175e2c0-ffffffff8175e3cc: mmc_send_app_op_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mmc_send_app_op_cond(struct mmc_host *host, u32 ocr, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff8177ca20)
Location: drivers/mmc/core/sd_ops.c:142
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
**Symbols:**

```
ffffffff8177ca20-ffffffff8177cb35: mmc_send_app_op_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mmc_send_app_op_cond(struct mmc_host *host, u32 ocr, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff817f2fa0)
Location: drivers/mmc/core/sd_ops.c:142
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
**Symbols:**

```
ffffffff817f2fa0-ffffffff817f30b5: mmc_send_app_op_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int mmc_send_app_op_cond(struct mmc_host *host, u32 ocr, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd_ops.c (0)
Location: drivers/mmc/core/sd_ops.c:142
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
```
**Symbols:**

```
ffffffff8183c9f3-ffffffff8183ca0e: mmc_send_app_op_cond.cold.1 (STB_LOCAL)
ffffffff8183c400-ffffffff8183c4fb: mmc_send_app_op_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int mmc_send_app_op_cond(struct mmc_host *host, u32 ocr, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd_ops.c (0)
Location: drivers/mmc/core/sd_ops.c:142
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
```
**Symbols:**

```
ffffffff81868983-ffffffff8186899e: mmc_send_app_op_cond.cold.1 (STB_LOCAL)
ffffffff81868390-ffffffff8186848b: mmc_send_app_op_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mmc_send_app_op_cond(struct mmc_host *host, u32 ocr, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd_ops.c (0)
Location: drivers/mmc/core/sd_ops.c:117
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
**Symbols:**

```
ffffffff818ac8ad-ffffffff818ac8c8: mmc_send_app_op_cond.cold (STB_LOCAL)
ffffffff818ac2b0-ffffffff818ac3a6: mmc_send_app_op_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int mmc_send_app_op_cond(struct mmc_host *host, u32 ocr, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd_ops.c (0)
Location: drivers/mmc/core/sd_ops.c:117
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
**Symbols:**

```
ffffffff818dece5-ffffffff818ded00: mmc_send_app_op_cond.cold (STB_LOCAL)
ffffffff818de700-ffffffff818de7f6: mmc_send_app_op_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mmc_send_app_op_cond(struct mmc_host *host, u32 ocr, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd_ops.c (0)
Location: drivers/mmc/core/sd_ops.c:117
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
**Symbols:**

```
ffffffff819b1af5-ffffffff819b1b10: mmc_send_app_op_cond.cold (STB_LOCAL)
ffffffff819b1520-ffffffff819b1616: mmc_send_app_op_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mmc_send_app_op_cond(struct mmc_host *host, u32 ocr, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd_ops.c (0)
Location: drivers/mmc/core/sd_ops.c:117
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
**Symbols:**

```
ffffffff81c2b125-ffffffff81c2b140: mmc_send_app_op_cond.cold (STB_LOCAL)
ffffffff819b3840-ffffffff819b3936: mmc_send_app_op_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mmc_send_app_op_cond(struct mmc_host *host, u32 ocr, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd_ops.c (0)
Location: drivers/mmc/core/sd_ops.c:117
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
**Symbols:**

```
ffffffff81c1d49f-ffffffff81c1d4ba: mmc_send_app_op_cond.cold (STB_LOCAL)
ffffffff81998020-ffffffff81998116: mmc_send_app_op_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mmc_send_app_op_cond(struct mmc_host *host, u32 ocr, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd_ops.c (0)
Location: drivers/mmc/core/sd_ops.c:118
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
**Symbols:**

```
ffffffff81d2e53f-ffffffff81d2e55a: mmc_send_app_op_cond.cold (STB_LOCAL)
ffffffff81a447e0-ffffffff81a448db: mmc_send_app_op_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mmc_send_app_op_cond(struct mmc_host *host, u32 ocr, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd_ops.c (0)
Location: drivers/mmc/core/sd_ops.c:118
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
**Symbols:**

```
ffffffff81efa962-ffffffff81efa97d: mmc_send_app_op_cond.cold (STB_LOCAL)
ffffffff81bb2300-ffffffff81bb2402: mmc_send_app_op_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mmc_send_app_op_cond(struct mmc_host *host, u32 ocr, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff81d565c0)
Location: drivers/mmc/core/sd_ops.c:118
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
**Symbols:**

```
ffffffff81d565c0-ffffffff81d566d3: mmc_send_app_op_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mmc_send_app_op_cond(struct mmc_host *host, u32 ocr, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff81dc0f30)
Location: drivers/mmc/core/sd_ops.c:118
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
**Symbols:**

```
ffffffff81dc0f30-ffffffff81dc1043: mmc_send_app_op_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mmc_send_app_op_cond(struct mmc_host *host, u32 ocr, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff81e79870)
Location: drivers/mmc/core/sd_ops.c:118
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
**Symbols:**

```
ffffffff81e79870-ffffffff81e79983: mmc_send_app_op_cond (STB_GLOBAL)
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
int mmc_send_app_op_cond(struct mmc_host *host, u32 ocr, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffff800010b38818)
Location: drivers/mmc/core/sd_ops.c:117
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
**Symbols:**

```
ffff800010b38818-ffff800010b38934: mmc_send_app_op_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mmc_send_app_op_cond(struct mmc_host *host, u32 ocr, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (c0c13198)
Location: drivers/mmc/core/sd_ops.c:117
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
**Symbols:**

```
c0c13198-c0c132c8: mmc_send_app_op_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mmc_send_app_op_cond(struct mmc_host *host, u32 ocr, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (c000000000c34680)
Location: drivers/mmc/core/sd_ops.c:117
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
**Symbols:**

```
c000000000c34680-c000000000c34818: mmc_send_app_op_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mmc_send_app_op_cond(struct mmc_host *host, u32 ocr, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffe0007105dc)
Location: drivers/mmc/core/sd_ops.c:117
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
**Symbols:**

```
ffffffe0007105dc-ffffffe0007106e8: mmc_send_app_op_cond (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int mmc_send_app_op_cond(struct mmc_host *host, u32 ocr, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd_ops.c (0)
Location: drivers/mmc/core/sd_ops.c:117
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
**Symbols:**

```
ffffffff818826a5-ffffffff818826c0: mmc_send_app_op_cond.cold (STB_LOCAL)
ffffffff818820c0-ffffffff818821b6: mmc_send_app_op_cond (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int mmc_send_app_op_cond(struct mmc_host *host, u32 ocr, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd_ops.c (0)
Location: drivers/mmc/core/sd_ops.c:117
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
**Symbols:**

```
ffffffff818d3b45-ffffffff818d3b60: mmc_send_app_op_cond.cold (STB_LOCAL)
ffffffff818d3560-ffffffff818d3656: mmc_send_app_op_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int mmc_send_app_op_cond(struct mmc_host *host, u32 ocr, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd_ops.c (0)
Location: drivers/mmc/core/sd_ops.c:117
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
**Symbols:**

```
ffffffff818f0665-ffffffff818f0680: mmc_send_app_op_cond.cold (STB_LOCAL)
ffffffff818f0080-ffffffff818f0176: mmc_send_app_op_cond (STB_GLOBAL)
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
