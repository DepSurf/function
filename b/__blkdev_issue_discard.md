# Function: <code>__blkdev_issue_discard</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio **biop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814062d0)
Location: block/blk-lib.c:25
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_discard
```
**Symbols:**

```
ffffffff814062d0-ffffffff81406481: __blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio **biop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff81420560)
Location: block/blk-lib.c:25
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_discard
```
**Symbols:**

```
ffffffff81420560-ffffffff8142072f: __blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio **biop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8142e510)
Location: block/blk-lib.c:25
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - block/blk-lib.c:blkdev_issue_discard
```
**Symbols:**

```
ffffffff8142e510-ffffffff8142e6b2: __blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio **biop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff81459710)
Location: block/blk-lib.c:26
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - block/blk-lib.c:blkdev_issue_discard
```
**Symbols:**

```
ffffffff81459710-ffffffff814598cf: __blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio **biop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8148cc80)
Location: block/blk-lib.c:26
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - block/blk-lib.c:blkdev_issue_discard
```
**Symbols:**

```
ffffffff8148cc80-ffffffff8148cf01: __blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio **biop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814a65b0)
Location: block/blk-lib.c:25
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - block/blk-lib.c:blkdev_issue_discard
```
**Symbols:**

```
ffffffff814a65b0-ffffffff814a6744: __blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio **biop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814d44c0)
Location: block/blk-lib.c:25
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - block/blk-lib.c:blkdev_issue_discard
```
**Symbols:**

```
ffffffff814d44c0-ffffffff814d4654: __blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio **biop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814ed7e0)
Location: block/blk-lib.c:25
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - block/blk-lib.c:blkdev_issue_discard
```
**Symbols:**

```
ffffffff814ed7e0-ffffffff814ed96a: __blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio **biop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8154d4e0)
Location: block/blk-lib.c:25
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - block/blk-lib.c:blkdev_issue_discard
```
**Symbols:**

```
ffffffff8154d4e0-ffffffff8154d695: __blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio **biop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-lib.c (0)
Location: block/blk-lib.c:25
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - block/blk-lib.c:blkdev_issue_discard
```
**Symbols:**

```
ffffffff81bf2788-ffffffff81bf279d: __blkdev_issue_discard.cold (STB_LOCAL)
ffffffff81569d00-ffffffff81569f7e: __blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio **biop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-lib.c (0)
Location: block/blk-lib.c:25
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - block/blk-lib.c:blkdev_issue_discard
  - drivers/md/md.c:md_submit_discard_bio
```
**Symbols:**

```
ffffffff81be474f-ffffffff81be4764: __blkdev_issue_discard.cold (STB_LOCAL)
ffffffff81571c70-ffffffff81571ee3: __blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio **biop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-lib.c (0)
Location: block/blk-lib.c:26
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_discard
  - drivers/md/md.c:md_submit_discard_bio
```
**Symbols:**

```
ffffffff81cd825a-ffffffff81cd826f: __blkdev_issue_discard.cold (STB_LOCAL)
ffffffff815d6380-ffffffff815d65f3: __blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-lib.c (0)
Location: block/blk-lib.c:38
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_discard
  - drivers/md/md.c:md_submit_discard_bio
```
**Symbols:**

```
ffffffff81e8b64b-ffffffff81e8b690: __blkdev_issue_discard.cold (STB_LOCAL)
ffffffff81681b10-ffffffff81681cf5: __blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-lib.c (0)
Location: block/blk-lib.c:38
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_discard
  - drivers/md/md.c:md_submit_discard_bio
```
**Symbols:**

```
ffffffff82075df9-ffffffff82075e29: __blkdev_issue_discard.cold (STB_LOCAL)
ffffffff8173f160-ffffffff8173f31b: __blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-lib.c (0)
Location: block/blk-lib.c:38
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_discard
  - drivers/md/md.c:md_submit_discard_bio
```
**Symbols:**

```
ffffffff820f5ce5-ffffffff820f5d15: __blkdev_issue_discard.cold (STB_LOCAL)
ffffffff8177b6d0-ffffffff8177b87f: __blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-lib.c (0)
Location: block/blk-lib.c:38
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_discard
  - drivers/md/md.c:md_submit_discard_bio
```
**Symbols:**

```
ffffffff821d31ef-ffffffff821d321f: __blkdev_issue_discard.cold (STB_LOCAL)
ffffffff817bdac0-ffffffff817bdc6f: __blkdev_issue_discard (STB_GLOBAL)
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
int __blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio **biop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffff8000105ec3e8)
Location: block/blk-lib.c:25
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - block/blk-lib.c:blkdev_issue_discard
```
**Symbols:**

```
ffff8000105ec3e8-ffff8000105ec568: __blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio **biop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (c079883c)
Location: block/blk-lib.c:25
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - block/blk-lib.c:blkdev_issue_discard
```
**Symbols:**

```
c079883c-c0798a08: __blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio **biop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (c000000000781a70)
Location: block/blk-lib.c:25
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - block/blk-lib.c:blkdev_issue_discard
```
**Symbols:**

```
c000000000781a70-c000000000781c70: __blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio **biop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffe00042bffa)
Location: block/blk-lib.c:25
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - block/blk-lib.c:blkdev_issue_discard
```
**Symbols:**

```
ffffffe00042bffa-ffffffe00042c140: __blkdev_issue_discard (STB_GLOBAL)
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
int __blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio **biop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814e5dc0)
Location: block/blk-lib.c:25
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - block/blk-lib.c:blkdev_issue_discard
```
**Symbols:**

```
ffffffff814e5dc0-ffffffff814e5f4a: __blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio **biop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814d6330)
Location: block/blk-lib.c:25
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - block/blk-lib.c:blkdev_issue_discard
```
**Symbols:**

```
ffffffff814d6330-ffffffff814d64ba: __blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio **biop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814e1e50)
Location: block/blk-lib.c:25
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - block/blk-lib.c:blkdev_issue_discard
```
**Symbols:**

```
ffffffff814e1e50-ffffffff814e1fda: __blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio **biop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814fad10)
Location: block/blk-lib.c:25
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - block/blk-lib.c:blkdev_issue_discard
```
**Symbols:**

```
ffffffff814fad10-ffffffff814fae8e: __blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>bdev, sector, nr_sects, gfp_mask, flags, biop</code> ➡️ <code>bdev, sector, nr_sects, gfp_mask, biop</code>
</li>
</ul>
</details>
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
