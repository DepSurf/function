# Function: <code>lookup_bdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct block_device *lookup_bdev(const char *pathname, int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (ffffffff812483d0)
Location: fs/block_dev.c:1771
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_by_path
Direct callers:
  - fs/block_dev.c:blkdev_get_by_path
  - fs/quota/quota.c:SyS_quotactl
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff812483d0-ffffffff8124849f: lookup_bdev.part.18 (STB_LOCAL)
ffffffff812484a0-ffffffff812484c2: lookup_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct block_device *lookup_bdev(const char *pathname, int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (ffffffff81271e7e)
Location: fs/block_dev.c:1850
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_by_path
Direct callers:
  - fs/block_dev.c:blkdev_get_by_path
  - fs/quota/quota.c:SyS_quotactl
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff81270c30-ffffffff81270d07: lookup_bdev.part.22 (STB_LOCAL)
ffffffff81270d10-ffffffff81270d33: lookup_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct block_device *lookup_bdev(const char *pathname, int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (ffffffff812855ee)
Location: fs/block_dev.c:2172
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_by_path
Direct callers:
  - fs/block_dev.c:blkdev_get_by_path
  - fs/quota/quota.c:SyS_quotactl
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff812845a0-ffffffff81284677: lookup_bdev.part.27 (STB_LOCAL)
ffffffff81284680-ffffffff812846a3: lookup_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct block_device *lookup_bdev(const char *pathname, int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (ffffffff8129320e)
Location: fs/block_dev.c:2088
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_by_path
Direct callers:
  - fs/block_dev.c:blkdev_get_by_path
  - fs/quota/quota.c:SyS_quotactl
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff812930e0-ffffffff812931b3: lookup_bdev.part.30 (STB_LOCAL)
ffffffff812931c0-ffffffff812931e3: lookup_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct block_device *lookup_bdev(const char *pathname, int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (ffffffff812b600e)
Location: fs/block_dev.c:2084
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_by_path
Direct callers:
  - fs/block_dev.c:blkdev_get_by_path
  - fs/quota/quota.c:SyS_quotactl
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff812b5ee0-ffffffff812b5fb3: lookup_bdev.part.35 (STB_LOCAL)
ffffffff812b5fc0-ffffffff812b5fe3: lookup_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct block_device *lookup_bdev(const char *pathname, int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (ffffffff812ddc7e)
Location: fs/block_dev.c:2100
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_by_path
Direct callers:
  - fs/block_dev.c:blkdev_get_by_path
  - fs/quota/quota.c:kernel_quotactl
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff812ddb40-ffffffff812ddc17: lookup_bdev.part.38 (STB_LOCAL)
ffffffff812ddc20-ffffffff812ddc42: lookup_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct block_device *lookup_bdev(const char *pathname, int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (ffffffff812f326e)
Location: fs/block_dev.c:2134
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_by_path
Direct callers:
  - fs/block_dev.c:blkdev_get_by_path
  - fs/quota/quota.c:kernel_quotactl
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff812f3130-ffffffff812f3207: lookup_bdev.part.40 (STB_LOCAL)
ffffffff812f3210-ffffffff812f3232: lookup_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct block_device *lookup_bdev(const char *pathname, int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (ffffffff81314cce)
Location: fs/block_dev.c:2175
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_by_path
Direct callers:
  - fs/block_dev.c:blkdev_get_by_path
  - fs/quota/quota.c:kernel_quotactl
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff81314b90-ffffffff81314c6c: lookup_bdev.part.0 (STB_LOCAL)
ffffffff81314c70-ffffffff81314c93: lookup_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct block_device *lookup_bdev(const char *pathname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (ffffffff81327b55)
Location: fs/block_dev.c:2157
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_by_path
Direct callers:
  - fs/block_dev.c:blkdev_get_by_path
  - fs/quota/quota.c:kernel_quotactl
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff81327280-ffffffff8132732c: lookup_bdev.part.0 (STB_LOCAL)
ffffffff81327330-ffffffff81327353: lookup_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct block_device *lookup_bdev(const char *pathname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81361210)
Location: fs/block_dev.c:2176
Inline: True
Direct callers:
  - fs/block_dev.c:blkdev_get_by_path
  - fs/quota/quota.c:kernel_quotactl
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff81361210-ffffffff813612cf: lookup_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int lookup_bdev(const char *pathname, dev_t *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136cb10)
Location: fs/block_dev.c:1856
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get_by_path
  - fs/quota/quota.c:quotactl_block
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff8136cb10-ffffffff8136cbc0: lookup_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int lookup_bdev(const char *pathname, dev_t *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813733b0)
Location: fs/block_dev.c:1865
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get_by_path
  - fs/quota/quota.c:quotactl_block
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff813733b0-ffffffff81373460: lookup_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int lookup_bdev(const char *pathname, dev_t *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff815c3c80)
Location: block/bdev.c:969
Inline: False
Direct callers:
  - fs/quota/quota.c:quotactl_block
  - block/bdev.c:blkdev_get_by_path
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff815c3c80-ffffffff815c3d30: lookup_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int lookup_bdev(const char *pathname, dev_t *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8166e5f0)
Location: block/bdev.c:973
Inline: False
Direct callers:
  - fs/quota/quota.c:quotactl_block
  - block/bdev.c:blkdev_get_by_path
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff8166e5f0-ffffffff8166e6bf: lookup_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int lookup_bdev(const char *pathname, dev_t *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff81729830)
Location: block/bdev.c:972
Inline: False
Direct callers:
  - fs/quota/quota.c:quotactl_block
  - block/bdev.c:blkdev_get_by_path
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff81729830-ffffffff817298ff: lookup_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int lookup_bdev(const char *pathname, dev_t *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff81765ba0)
Location: block/bdev.c:934
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - fs/quota/quota.c:quotactl_block
  - block/bdev.c:blkdev_get_by_path
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff81765ba0-ffffffff81765c6f: lookup_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int lookup_bdev(const char *pathname, dev_t *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff817a77a0)
Location: block/bdev.c:1005
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/quota/quota.c:quotactl_block
  - block/bdev.c:bdev_open_by_path
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff817a77a0-ffffffff817a786f: lookup_bdev (STB_GLOBAL)
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
struct block_device *lookup_bdev(const char *pathname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (ffff8000103e2a84)
Location: fs/block_dev.c:2157
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_by_path
Direct callers:
  - fs/block_dev.c:blkdev_get_by_path
  - fs/quota/quota.c:kernel_quotactl
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffff8000103e2150-ffff8000103e2214: lookup_bdev.part.0 (STB_LOCAL)
ffff8000103e2218-ffff8000103e2270: lookup_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct block_device *lookup_bdev(const char *pathname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (c05bacb8)
Location: fs/block_dev.c:2157
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_by_path
Direct callers:
  - fs/block_dev.c:blkdev_get_by_path
  - fs/quota/quota.c:kernel_quotactl
  - drivers/mtd/mtdsuper.c:get_tree_mtd
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
c05ba318-c05ba3d0: lookup_bdev.part.0 (STB_LOCAL)
c05ba3d0-c05ba408: lookup_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct block_device *lookup_bdev(const char *pathname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (c0000000004e8868)
Location: fs/block_dev.c:2157
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_by_path
Direct callers:
  - fs/block_dev.c:blkdev_get_by_path
  - fs/quota/quota.c:kernel_quotactl
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
c0000000004e7cc0-c0000000004e7d9c: lookup_bdev.part.0 (STB_LOCAL)
c0000000004e7da0-c0000000004e7dd4: lookup_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct block_device *lookup_bdev(const char *pathname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (ffffffe000298f4e)
Location: fs/block_dev.c:2157
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_by_path
Direct callers:
  - fs/block_dev.c:blkdev_get_by_path
  - fs/quota/quota.c:kernel_quotactl
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffe0002987b6-ffffffe000298836: lookup_bdev.part.0 (STB_LOCAL)
ffffffe000298836-ffffffe000298880: lookup_bdev (STB_GLOBAL)
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
struct block_device *lookup_bdev(const char *pathname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (ffffffff81320135)
Location: fs/block_dev.c:2157
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_by_path
Direct callers:
  - fs/block_dev.c:blkdev_get_by_path
  - fs/quota/quota.c:kernel_quotactl
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff8131f860-ffffffff8131f90c: lookup_bdev.part.0 (STB_LOCAL)
ffffffff8131f910-ffffffff8131f933: lookup_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct block_device *lookup_bdev(const char *pathname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (ffffffff81310cd5)
Location: fs/block_dev.c:2157
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_by_path
Direct callers:
  - fs/block_dev.c:blkdev_get_by_path
  - fs/quota/quota.c:kernel_quotactl
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff81310400-ffffffff813104ac: lookup_bdev.part.0 (STB_LOCAL)
ffffffff813104b0-ffffffff813104d3: lookup_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct block_device *lookup_bdev(const char *pathname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (ffffffff8131dc05)
Location: fs/block_dev.c:2157
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_by_path
Direct callers:
  - fs/block_dev.c:blkdev_get_by_path
  - fs/quota/quota.c:kernel_quotactl
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff8131d330-ffffffff8131d3dc: lookup_bdev.part.0 (STB_LOCAL)
ffffffff8131d3e0-ffffffff8131d403: lookup_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct block_device *lookup_bdev(const char *pathname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (ffffffff8132f905)
Location: fs/block_dev.c:2157
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_by_path
Direct callers:
  - fs/block_dev.c:blkdev_get_by_path
  - fs/quota/quota.c:kernel_quotactl
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff8132f030-ffffffff8132f0dc: lookup_bdev.part.0 (STB_LOCAL)
ffffffff8132f0e0-ffffffff8132f103: lookup_bdev (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int mask</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>dev_t *dev</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct block_device *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
