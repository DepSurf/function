# Function: <code>mmc_send_if_cond_pcie</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mmc_send_if_cond_pcie(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff819b39e0)
Location: drivers/mmc/core/sd_ops.c:201
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
```
**Symbols:**

```
ffffffff819b39e0-ffffffff819b3a9b: mmc_send_if_cond_pcie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mmc_send_if_cond_pcie(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff819981c0)
Location: drivers/mmc/core/sd_ops.c:201
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
```
**Symbols:**

```
ffffffff819981c0-ffffffff8199827b: mmc_send_if_cond_pcie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mmc_send_if_cond_pcie(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff81a44980)
Location: drivers/mmc/core/sd_ops.c:202
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
```
**Symbols:**

```
ffffffff81a44980-ffffffff81a44a3b: mmc_send_if_cond_pcie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mmc_send_if_cond_pcie(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff81bb24c0)
Location: drivers/mmc/core/sd_ops.c:202
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
```
**Symbols:**

```
ffffffff81bb24c0-ffffffff81bb2595: mmc_send_if_cond_pcie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mmc_send_if_cond_pcie(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff81d567b0)
Location: drivers/mmc/core/sd_ops.c:202
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
```
**Symbols:**

```
ffffffff81d567b0-ffffffff81d56885: mmc_send_if_cond_pcie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mmc_send_if_cond_pcie(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff81dc1120)
Location: drivers/mmc/core/sd_ops.c:202
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
```
**Symbols:**

```
ffffffff81dc1120-ffffffff81dc11f5: mmc_send_if_cond_pcie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mmc_send_if_cond_pcie(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff81e79a60)
Location: drivers/mmc/core/sd_ops.c:202
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
```
**Symbols:**

```
ffffffff81e79a60-ffffffff81e79b35: mmc_send_if_cond_pcie (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
