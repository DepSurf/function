# Function: <code>next_bio</code>

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
struct bio *next_bio(struct bio *bio, unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff81406290)
Location: block/blk-lib.c:12
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
**Symbols:**

```
ffffffff81406290-ffffffff814062d0: next_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct bio *next_bio(struct bio *bio, unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff81420520)
Location: block/blk-lib.c:12
Inline: False
Direct callers:
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
**Symbols:**

```
ffffffff81420520-ffffffff81420560: next_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct bio *next_bio(struct bio *bio, unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8142e4d0)
Location: block/blk-lib.c:12
Inline: False
Direct callers:
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
**Symbols:**

```
ffffffff8142e4d0-ffffffff8142e510: next_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct bio *next_bio(struct bio *bio, unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814596d0)
Location: block/blk-lib.c:13
Inline: False
Direct callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
**Symbols:**

```
ffffffff814596d0-ffffffff81459710: next_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct bio *next_bio(struct bio *bio, unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8148cc40)
Location: block/blk-lib.c:13
Inline: False
Direct callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
**Symbols:**

```
ffffffff8148cc40-ffffffff8148cc80: next_bio (STB_LOCAL)
```
</details>
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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
