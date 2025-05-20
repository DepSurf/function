# Function: <code>blk_next_bio</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct bio *blk_next_bio(struct bio *bio, unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814a6570)
Location: block/blk-lib.c:13
Inline: False
Direct callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
```
**Symbols:**

```
ffffffff814a6570-ffffffff814a65b0: blk_next_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct bio *blk_next_bio(struct bio *bio, unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814d4470)
Location: block/blk-lib.c:13
Inline: False
Direct callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
```
**Symbols:**

```
ffffffff814d4470-ffffffff814d44b2: blk_next_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct bio *blk_next_bio(struct bio *bio, unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814ed790)
Location: block/blk-lib.c:13
Inline: False
Direct callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
```
**Symbols:**

```
ffffffff814ed790-ffffffff814ed7d2: blk_next_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct bio *blk_next_bio(struct bio *bio, unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8154d3a7)
Location: block/blk-lib.c:13
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
Direct callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
```
**Symbols:**

```
ffffffff8154de40-ffffffff8154de82: blk_next_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct bio *blk_next_bio(struct bio *bio, unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff815697a4)
Location: block/blk-lib.c:13
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
Direct callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
```
**Symbols:**

```
ffffffff8156a300-ffffffff8156a342: blk_next_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct bio *blk_next_bio(struct bio *bio, unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8157170e)
Location: block/blk-lib.c:13
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
Direct callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
```
**Symbols:**

```
ffffffff81572240-ffffffff81572285: blk_next_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct bio *blk_next_bio(struct bio *bio, unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff815d5e1e)
Location: block/blk-lib.c:13
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
Direct callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
```
**Symbols:**

```
ffffffff815d5d60-ffffffff815d5da5: blk_next_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bio *blk_next_bio(struct bio *bio, struct block_device *bdev, unsigned int nr_pages, unsigned int opf, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff816732d0)
Location: block/bio.c:343
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
```
**Symbols:**

```
ffffffff816732d0-ffffffff81673344: blk_next_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bio *blk_next_bio(struct bio *bio, struct block_device *bdev, unsigned int nr_pages, blk_opf_t opf, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172ee40)
Location: block/bio.c:349
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
```
**Symbols:**

```
ffffffff8172ee40-ffffffff8172eeb4: blk_next_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bio *blk_next_bio(struct bio *bio, struct block_device *bdev, unsigned int nr_pages, blk_opf_t opf, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8176b070)
Location: block/bio.c:348
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
```
**Symbols:**

```
ffffffff8176b070-ffffffff8176b0e4: blk_next_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bio *blk_next_bio(struct bio *bio, struct block_device *bdev, unsigned int nr_pages, blk_opf_t opf, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817ad500)
Location: block/bio.c:348
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
```
**Symbols:**

```
ffffffff817ad500-ffffffff817ad574: blk_next_bio (STB_GLOBAL)
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
struct bio *blk_next_bio(struct bio *bio, unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffff8000105ec380)
Location: block/blk-lib.c:13
Inline: False
Direct callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
```
**Symbols:**

```
ffff8000105ec380-ffff8000105ec3e8: blk_next_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bio *blk_next_bio(struct bio *bio, unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (c07987e8)
Location: block/blk-lib.c:13
Inline: False
Direct callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
```
**Symbols:**

```
c07987e8-c079883c: blk_next_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct bio *blk_next_bio(struct bio *bio, unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (c0000000007819f0)
Location: block/blk-lib.c:13
Inline: False
Direct callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
```
**Symbols:**

```
c0000000007819f0-c000000000781a70: blk_next_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct bio *blk_next_bio(struct bio *bio, unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffe00042bf9e)
Location: block/blk-lib.c:13
Inline: False
Direct callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
```
**Symbols:**

```
ffffffe00042bf9e-ffffffe00042bffa: blk_next_bio (STB_GLOBAL)
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
struct bio *blk_next_bio(struct bio *bio, unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814e5d70)
Location: block/blk-lib.c:13
Inline: False
Direct callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
```
**Symbols:**

```
ffffffff814e5d70-ffffffff814e5db2: blk_next_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct bio *blk_next_bio(struct bio *bio, unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814d62e0)
Location: block/blk-lib.c:13
Inline: False
Direct callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
```
**Symbols:**

```
ffffffff814d62e0-ffffffff814d6322: blk_next_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct bio *blk_next_bio(struct bio *bio, unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814e1e00)
Location: block/blk-lib.c:13
Inline: False
Direct callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
```
**Symbols:**

```
ffffffff814e1e00-ffffffff814e1e42: blk_next_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct bio *blk_next_bio(struct bio *bio, unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814facc0)
Location: block/blk-lib.c:13
Inline: False
Direct callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
```
**Symbols:**

```
ffffffff814facc0-ffffffff814fad02: blk_next_bio (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Param added. </b>
<code>struct block_device *bdev</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int opf</code>
</li>
<li>
<b>Param reordered. </b>
<code>bio, nr_pages, gfp</code> ➡️ <code>bio, bdev, nr_pages, opf, gfp</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int opf</code> ➡️ <code>blk_opf_t opf</code>
</li>
</ul>
</details>
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
