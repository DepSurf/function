# Function: <code>__blkdev_issue_zeroout</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff813c2ae9)
Location: block/blk-lib.c:215
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8140672e)
Location: block/blk-lib.c:199
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, bool discard);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814209e0)
Location: block/blk-lib.c:290
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_zeroout
```
**Symbols:**

```
ffffffff814209e0-ffffffff81420bad: __blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8142e950)
Location: block/blk-lib.c:302
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_zeroout
```
**Symbols:**

```
ffffffff8142e950-ffffffff8142eb6b: __blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8145a010)
Location: block/blk-lib.c:331
Inline: True
```
**Symbols:**

```
ffffffff8145a010-ffffffff8145a0bf: __blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8148d4c0)
Location: block/blk-lib.c:359
Inline: False
```
**Symbols:**

```
ffffffff8148d4c0-ffffffff8148d55f: __blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814a6d50)
Location: block/blk-lib.c:324
Inline: False
```
**Symbols:**

```
ffffffff814a6d50-ffffffff814a6def: __blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814d4c60)
Location: block/blk-lib.c:324
Inline: False
```
**Symbols:**

```
ffffffff814d4c60-ffffffff814d4d08: __blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814edf60)
Location: block/blk-lib.c:324
Inline: False
```
**Symbols:**

```
ffffffff814edf60-ffffffff814ee000: __blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8154d8e0)
Location: block/blk-lib.c:324
Inline: False
```
**Symbols:**

```
ffffffff8154d8e0-ffffffff8154d980: __blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff81569a60)
Location: block/blk-lib.c:358
Inline: False
```
**Symbols:**

```
ffffffff81569a60-ffffffff81569afd: __blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff815719b0)
Location: block/blk-lib.c:358
Inline: False
```
**Symbols:**

```
ffffffff815719b0-ffffffff81571a4d: __blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff815d60c0)
Location: block/blk-lib.c:359
Inline: False
```
**Symbols:**

```
ffffffff815d60c0-ffffffff815d615d: __blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff816820b0)
Location: block/blk-lib.c:220
Inline: False
```
**Symbols:**

```
ffffffff816820b0-ffffffff8168215d: __blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8173f720)
Location: block/blk-lib.c:218
Inline: False
```
**Symbols:**

```
ffffffff8173f720-ffffffff8173f7cd: __blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8177bc60)
Location: block/blk-lib.c:218
Inline: False
```
**Symbols:**

```
ffffffff8177bc60-ffffffff8177bd0a: __blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff817be050)
Location: block/blk-lib.c:218
Inline: False
```
**Symbols:**

```
ffffffff817be050-ffffffff817be0fa: __blkdev_issue_zeroout (STB_GLOBAL)
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
int __blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffff8000105ecb30)
Location: block/blk-lib.c:324
Inline: False
```
**Symbols:**

```
ffff8000105ecb30-ffff8000105ecbe8: __blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (c0799044)
Location: block/blk-lib.c:324
Inline: False
```
**Symbols:**

```
c0799044-c0799114: __blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (c000000000782490)
Location: block/blk-lib.c:324
Inline: False
```
**Symbols:**

```
c000000000782490-c000000000782598: __blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffe00042c60c)
Location: block/blk-lib.c:324
Inline: False
```
**Symbols:**

```
ffffffe00042c60c-ffffffe00042c6a2: __blkdev_issue_zeroout (STB_GLOBAL)
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
int __blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814e6540)
Location: block/blk-lib.c:324
Inline: False
```
**Symbols:**

```
ffffffff814e6540-ffffffff814e65e0: __blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814d6ab0)
Location: block/blk-lib.c:324
Inline: False
```
**Symbols:**

```
ffffffff814d6ab0-ffffffff814d6b50: __blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814e25d0)
Location: block/blk-lib.c:324
Inline: False
```
**Symbols:**

```
ffffffff814e25d0-ffffffff814e2670: __blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio **biop, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814fb450)
Location: block/blk-lib.c:324
Inline: False
```
**Symbols:**

```
ffffffff814fb450-ffffffff814fb4f0: __blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool discard</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
