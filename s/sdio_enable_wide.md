# Function: <code>sdio_enable_wide</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int sdio_enable_wide(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff816c8af0)
Location: drivers/mmc/core/sdio.c:203
Inline: True
```
**Symbols:**

```
ffffffff816c8af0-ffffffff816c8bcb: sdio_enable_wide (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int sdio_enable_wide(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff8172baa0)
Location: drivers/mmc/core/sdio.c:201
Inline: True
```
**Symbols:**

```
ffffffff8172baa0-ffffffff8172bb7b: sdio_enable_wide (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int sdio_enable_wide(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff8175ec60)
Location: drivers/mmc/core/sdio.c:202
Inline: True
```
**Symbols:**

```
ffffffff8175ec60-ffffffff8175ed3b: sdio_enable_wide (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int sdio_enable_wide(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff8177d310)
Location: drivers/mmc/core/sdio.c:205
Inline: True
```
**Symbols:**

```
ffffffff8177d310-ffffffff8177d3e8: sdio_enable_wide (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int sdio_enable_wide(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff817f3890)
Location: drivers/mmc/core/sdio.c:205
Inline: True
```
**Symbols:**

```
ffffffff817f3890-ffffffff817f3968: sdio_enable_wide (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sdio_enable_wide(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio.c (0)
Location: drivers/mmc/core/sdio.c:205
Inline: True
```
**Symbols:**

```
ffffffff8183ccf0-ffffffff8183cda3: sdio_enable_wide (STB_LOCAL)
ffffffff8183e2bd-ffffffff8183e2e9: sdio_enable_wide.cold.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sdio_enable_wide(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff81868cbb)
Location: drivers/mmc/core/sdio.c:205
Inline: True
```
**Symbols:**

```
ffffffff81868c80-ffffffff81868d33: sdio_enable_wide (STB_LOCAL)
ffffffff8186a26d-ffffffff8186a299: sdio_enable_wide.cold.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sdio_enable_wide(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff818acc0c)
Location: drivers/mmc/core/sdio.c:201
Inline: True
```
**Symbols:**

```
ffffffff818acbd0-ffffffff818acc85: sdio_enable_wide (STB_LOCAL)
ffffffff818ae132-ffffffff818ae15f: sdio_enable_wide.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sdio_enable_wide(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff818df05c)
Location: drivers/mmc/core/sdio.c:201
Inline: True
```
**Symbols:**

```
ffffffff818df020-ffffffff818df0d5: sdio_enable_wide (STB_LOCAL)
ffffffff818e05e9-ffffffff818e0616: sdio_enable_wide.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff819b28a7)
Location: drivers/mmc/core/sdio.c:219
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:sdio_enable_4bit_bus
  - drivers/mmc/core/sdio.c:sdio_enable_4bit_bus
Direct callers:
  - drivers/mmc/core/sdio.c:sdio_enable_4bit_bus
  - drivers/mmc/core/sdio.c:sdio_enable_4bit_bus
```
**Symbols:**

```
ffffffff819b2420-ffffffff819b24b8: sdio_enable_wide.part.0 (STB_LOCAL)
ffffffff819b3637-ffffffff819b3664: sdio_enable_wide.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (0)
Location: drivers/mmc/core/sdio.c:246
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (0)
Location: drivers/mmc/core/sdio.c:246
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (0)
Location: drivers/mmc/core/sdio.c:246
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff81bb36ed)
Location: drivers/mmc/core/sdio.c:247
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff81d57c6d)
Location: drivers/mmc/core/sdio.c:261
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff81dc260d)
Location: drivers/mmc/core/sdio.c:261
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff81e7aecd)
Location: drivers/mmc/core/sdio.c:261
Inline: True
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
int sdio_enable_wide(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffff800010b391e8)
Location: drivers/mmc/core/sdio.c:201
Inline: True
```
**Symbols:**

```
ffff800010b391e8-ffff800010b392dc: sdio_enable_wide (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int sdio_enable_wide(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (c0c13b28)
Location: drivers/mmc/core/sdio.c:201
Inline: True
```
**Symbols:**

```
c0c13b28-c0c13c30: sdio_enable_wide (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int sdio_enable_wide(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (c000000000c354a0)
Location: drivers/mmc/core/sdio.c:201
Inline: True
```
**Symbols:**

```
c000000000c354a0-c000000000c355f8: sdio_enable_wide (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int sdio_enable_wide(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffe000710f76)
Location: drivers/mmc/core/sdio.c:201
Inline: True
```
**Symbols:**

```
ffffffe000710f76-ffffffe00071101a: sdio_enable_wide (STB_LOCAL)
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
int sdio_enable_wide(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff81882a1c)
Location: drivers/mmc/core/sdio.c:201
Inline: True
```
**Symbols:**

```
ffffffff818829e0-ffffffff81882a95: sdio_enable_wide (STB_LOCAL)
ffffffff81883fa9-ffffffff81883fd6: sdio_enable_wide.cold (STB_LOCAL)
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
int sdio_enable_wide(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff818d3ebc)
Location: drivers/mmc/core/sdio.c:201
Inline: True
```
**Symbols:**

```
ffffffff818d3e80-ffffffff818d3f35: sdio_enable_wide (STB_LOCAL)
ffffffff818d5449-ffffffff818d5476: sdio_enable_wide.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sdio_enable_wide(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff818f09dc)
Location: drivers/mmc/core/sdio.c:201
Inline: True
```
**Symbols:**

```
ffffffff818f09a0-ffffffff818f0a55: sdio_enable_wide (STB_LOCAL)
ffffffff818f1f69-ffffffff818f1f96: sdio_enable_wide.cold (STB_LOCAL)
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
