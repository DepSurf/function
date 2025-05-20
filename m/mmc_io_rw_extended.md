# Function: <code>mmc_io_rw_extended</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mmc_io_rw_extended(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, int incr_addr, u8 *buf, unsigned int blocks, unsigned int blksz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff816ca2e0)
Location: drivers/mmc/core/sdio_ops.c:121
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
```
**Symbols:**

```
ffffffff816ca2e0-ffffffff816ca67c: mmc_io_rw_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mmc_io_rw_extended(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, int incr_addr, u8 *buf, unsigned int blocks, unsigned int blksz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff8172d2a0)
Location: drivers/mmc/core/sdio_ops.c:121
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
```
**Symbols:**

```
ffffffff8172d2a0-ffffffff8172d62a: mmc_io_rw_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mmc_io_rw_extended(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, int incr_addr, u8 *buf, unsigned int blocks, unsigned int blksz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff81760260)
Location: drivers/mmc/core/sdio_ops.c:118
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
```
**Symbols:**

```
ffffffff81760260-ffffffff817605ec: mmc_io_rw_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mmc_io_rw_extended(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, int incr_addr, u8 *buf, unsigned int blocks, unsigned int blksz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff8177eb10)
Location: drivers/mmc/core/sdio_ops.c:118
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
```
**Symbols:**

```
ffffffff8177eb10-ffffffff8177ee3b: mmc_io_rw_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mmc_io_rw_extended(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, int incr_addr, u8 *buf, unsigned int blocks, unsigned int blksz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff817f50b0)
Location: drivers/mmc/core/sdio_ops.c:118
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
```
**Symbols:**

```
ffffffff817f50b0-ffffffff817f53db: mmc_io_rw_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mmc_io_rw_extended(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, int incr_addr, u8 *buf, unsigned int blocks, unsigned int blksz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff8183e5a0)
Location: drivers/mmc/core/sdio_ops.c:118
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
```
**Symbols:**

```
ffffffff8183e5a0-ffffffff8183e8b4: mmc_io_rw_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mmc_io_rw_extended(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, int incr_addr, u8 *buf, unsigned int blocks, unsigned int blksz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff8186a550)
Location: drivers/mmc/core/sdio_ops.c:118
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
```
**Symbols:**

```
ffffffff8186a550-ffffffff8186a864: mmc_io_rw_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mmc_io_rw_extended(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, int incr_addr, u8 *buf, unsigned int blocks, unsigned int blksz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (0)
Location: drivers/mmc/core/sdio_ops.c:114
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
```
**Symbols:**

```
ffffffff818ae7c8-ffffffff818ae815: mmc_io_rw_extended.cold (STB_LOCAL)
ffffffff818ae440-ffffffff818ae73b: mmc_io_rw_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mmc_io_rw_extended(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, int incr_addr, u8 *buf, unsigned int blocks, unsigned int blksz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff818e08d0)
Location: drivers/mmc/core/sdio_ops.c:114
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
```
**Symbols:**

```
ffffffff818e08d0-ffffffff818e0be1: mmc_io_rw_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mmc_io_rw_extended(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, int incr_addr, u8 *buf, unsigned int blocks, unsigned int blksz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff819b38f0)
Location: drivers/mmc/core/sdio_ops.c:114
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
```
**Symbols:**

```
ffffffff819b38f0-ffffffff819b3c63: mmc_io_rw_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mmc_io_rw_extended(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, int incr_addr, u8 *buf, unsigned int blocks, unsigned int blksz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff819b5d70)
Location: drivers/mmc/core/sdio_ops.c:114
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
```
**Symbols:**

```
ffffffff819b5d70-ffffffff819b60e3: mmc_io_rw_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mmc_io_rw_extended(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, int incr_addr, u8 *buf, unsigned int blocks, unsigned int blksz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff8199a530)
Location: drivers/mmc/core/sdio_ops.c:114
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
```
**Symbols:**

```
ffffffff8199a530-ffffffff8199a89e: mmc_io_rw_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mmc_io_rw_extended(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, int incr_addr, u8 *buf, unsigned int blocks, unsigned int blksz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff81a46e70)
Location: drivers/mmc/core/sdio_ops.c:114
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
```
**Symbols:**

```
ffffffff81a46e70-ffffffff81a471de: mmc_io_rw_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mmc_io_rw_extended(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, int incr_addr, u8 *buf, unsigned int blocks, unsigned int blksz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff81bb4c90)
Location: drivers/mmc/core/sdio_ops.c:114
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
```
**Symbols:**

```
ffffffff81bb4c90-ffffffff81bb5063: mmc_io_rw_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mmc_io_rw_extended(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, int incr_addr, u8 *buf, unsigned int blocks, unsigned int blksz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff81d59390)
Location: drivers/mmc/core/sdio_ops.c:114
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
```
**Symbols:**

```
ffffffff81d59390-ffffffff81d59763: mmc_io_rw_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mmc_io_rw_extended(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, int incr_addr, u8 *buf, unsigned int blocks, unsigned int blksz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff81dc3d40)
Location: drivers/mmc/core/sdio_ops.c:114
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
```
**Symbols:**

```
ffffffff81dc3d40-ffffffff81dc4110: mmc_io_rw_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mmc_io_rw_extended(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, int incr_addr, u8 *buf, unsigned int blocks, unsigned int blksz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff81e7c620)
Location: drivers/mmc/core/sdio_ops.c:114
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
```
**Symbols:**

```
ffffffff81e7c620-ffffffff81e7c9f0: mmc_io_rw_extended (STB_GLOBAL)
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
int mmc_io_rw_extended(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, int incr_addr, u8 *buf, unsigned int blocks, unsigned int blksz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffff800010b3aac8)
Location: drivers/mmc/core/sdio_ops.c:114
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
```
**Symbols:**

```
ffff800010b3aac8-ffff800010b3ad7c: mmc_io_rw_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mmc_io_rw_extended(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, int incr_addr, u8 *buf, unsigned int blocks, unsigned int blksz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (c0c1546c)
Location: drivers/mmc/core/sdio_ops.c:114
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
```
**Symbols:**

```
c0c1546c-c0c15764: mmc_io_rw_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mmc_io_rw_extended(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, int incr_addr, u8 *buf, unsigned int blocks, unsigned int blksz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (c000000000c374a0)
Location: drivers/mmc/core/sdio_ops.c:114
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
```
**Symbols:**

```
c000000000c374a0-c000000000c37844: mmc_io_rw_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mmc_io_rw_extended(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, int incr_addr, u8 *buf, unsigned int blocks, unsigned int blksz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffe000712428)
Location: drivers/mmc/core/sdio_ops.c:114
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
```
**Symbols:**

```
ffffffe000712428-ffffffe0007126b0: mmc_io_rw_extended (STB_GLOBAL)
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
int mmc_io_rw_extended(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, int incr_addr, u8 *buf, unsigned int blocks, unsigned int blksz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff81884290)
Location: drivers/mmc/core/sdio_ops.c:114
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
```
**Symbols:**

```
ffffffff81884290-ffffffff818845a1: mmc_io_rw_extended (STB_GLOBAL)
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
int mmc_io_rw_extended(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, int incr_addr, u8 *buf, unsigned int blocks, unsigned int blksz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff818d5730)
Location: drivers/mmc/core/sdio_ops.c:114
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
```
**Symbols:**

```
ffffffff818d5730-ffffffff818d5a41: mmc_io_rw_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mmc_io_rw_extended(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, int incr_addr, u8 *buf, unsigned int blocks, unsigned int blksz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff818f2250)
Location: drivers/mmc/core/sdio_ops.c:114
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
  - drivers/mmc/core/sdio_io.c:sdio_io_rw_ext_helper
```
**Symbols:**

```
ffffffff818f2250-ffffffff818f2561: mmc_io_rw_extended (STB_GLOBAL)
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
