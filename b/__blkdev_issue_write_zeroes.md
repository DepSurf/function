# Function: <code>__blkdev_issue_write_zeroes</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff81420a12)
Location: block/blk-lib.c:240
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zeroout
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8142e982)
Location: block/blk-lib.c:224
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zeroout
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __blkdev_issue_write_zeroes(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814598d0)
Location: block/blk-lib.c:225
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_zeroout
```
**Symbols:**

```
ffffffff814598d0-ffffffff814599d4: __blkdev_issue_write_zeroes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __blkdev_issue_write_zeroes(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8148cf10)
Location: block/blk-lib.c:247
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
```
**Symbols:**

```
ffffffff8148cf10-ffffffff8148d050: __blkdev_issue_write_zeroes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __blkdev_issue_write_zeroes(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814a6a60)
Location: block/blk-lib.c:212
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
```
**Symbols:**

```
ffffffff814a6a60-ffffffff814a6ba7: __blkdev_issue_write_zeroes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __blkdev_issue_write_zeroes(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814d4980)
Location: block/blk-lib.c:212
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
```
**Symbols:**

```
ffffffff814d4980-ffffffff814d4ac7: __blkdev_issue_write_zeroes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __blkdev_issue_write_zeroes(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814edc80)
Location: block/blk-lib.c:212
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
```
**Symbols:**

```
ffffffff814edc80-ffffffff814eddc7: __blkdev_issue_write_zeroes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __blkdev_issue_write_zeroes(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8154d760)
Location: block/blk-lib.c:212
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
```
**Symbols:**

```
ffffffff8154d760-ffffffff8154d8d8: __blkdev_issue_write_zeroes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __blkdev_issue_write_zeroes(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff815698e0)
Location: block/blk-lib.c:246
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
```
**Symbols:**

```
ffffffff815698e0-ffffffff81569a55: __blkdev_issue_write_zeroes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __blkdev_issue_write_zeroes(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff81571840)
Location: block/blk-lib.c:246
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
```
**Symbols:**

```
ffffffff81571840-ffffffff815719ae: __blkdev_issue_write_zeroes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __blkdev_issue_write_zeroes(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff815d5f50)
Location: block/blk-lib.c:247
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
```
**Symbols:**

```
ffffffff815d5f50-ffffffff815d60be: __blkdev_issue_write_zeroes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __blkdev_issue_write_zeroes(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-lib.c (0)
Location: block/blk-lib.c:120
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
```
**Symbols:**

```
ffffffff81681df0-ffffffff81681f2a: __blkdev_issue_write_zeroes (STB_LOCAL)
ffffffff81e8b690-ffffffff81e8b6d2: __blkdev_issue_write_zeroes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __blkdev_issue_write_zeroes(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-lib.c (0)
Location: block/blk-lib.c:118
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
```
**Symbols:**

```
ffffffff8173f430-ffffffff8173f56d: __blkdev_issue_write_zeroes (STB_LOCAL)
ffffffff82075e29-ffffffff82075e6b: __blkdev_issue_write_zeroes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __blkdev_issue_write_zeroes(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-lib.c (0)
Location: block/blk-lib.c:118
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
```
**Symbols:**

```
ffffffff8177b980-ffffffff8177bab7: __blkdev_issue_write_zeroes (STB_LOCAL)
ffffffff820f5d15-ffffffff820f5d57: __blkdev_issue_write_zeroes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __blkdev_issue_write_zeroes(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-lib.c (0)
Location: block/blk-lib.c:118
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
```
**Symbols:**

```
ffffffff817bdd70-ffffffff817bdea7: __blkdev_issue_write_zeroes (STB_LOCAL)
ffffffff821d321f-ffffffff821d3261: __blkdev_issue_write_zeroes.cold (STB_LOCAL)
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
int __blkdev_issue_write_zeroes(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffff8000105ec830)
Location: block/blk-lib.c:212
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
```
**Symbols:**

```
ffff8000105ec830-ffff8000105ec9a4: __blkdev_issue_write_zeroes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __blkdev_issue_write_zeroes(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (c0798d40)
Location: block/blk-lib.c:212
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
```
**Symbols:**

```
c0798d40-c0798ed0: __blkdev_issue_write_zeroes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __blkdev_issue_write_zeroes(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (c000000000782070)
Location: block/blk-lib.c:212
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
```
**Symbols:**

```
c000000000782070-c000000000782298: __blkdev_issue_write_zeroes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __blkdev_issue_write_zeroes(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffe00042c382)
Location: block/blk-lib.c:212
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
```
**Symbols:**

```
ffffffe00042c382-ffffffe00042c4b0: __blkdev_issue_write_zeroes (STB_LOCAL)
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
int __blkdev_issue_write_zeroes(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814e6260)
Location: block/blk-lib.c:212
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
```
**Symbols:**

```
ffffffff814e6260-ffffffff814e63a7: __blkdev_issue_write_zeroes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __blkdev_issue_write_zeroes(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814d67d0)
Location: block/blk-lib.c:212
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
```
**Symbols:**

```
ffffffff814d67d0-ffffffff814d6917: __blkdev_issue_write_zeroes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __blkdev_issue_write_zeroes(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814e22f0)
Location: block/blk-lib.c:212
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
```
**Symbols:**

```
ffffffff814e22f0-ffffffff814e2437: __blkdev_issue_write_zeroes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __blkdev_issue_write_zeroes(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814fb190)
Location: block/blk-lib.c:212
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
```
**Symbols:**

```
ffffffff814fb190-ffffffff814fb2c9: __blkdev_issue_write_zeroes (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
