# Function: <code>bvec_split_segs</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-merge.c (ffffffff814d1dc0)
Location: block/blk-merge.c:164
Inline: True
Direct callers:
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:__blk_queue_split
```
**Symbols:**

```
ffffffff814d1dc0-ffffffff814d1e64: bvec_split_segs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-merge.c (ffffffff814eb100)
Location: block/blk-merge.c:193
Inline: True
Direct callers:
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:__blk_queue_split
```
**Symbols:**

```
ffffffff814eb100-ffffffff814eb1df: bvec_split_segs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool bvec_split_segs(const struct request_queue *q, const struct bio_vec *bv, unsigned int *nsegs, unsigned int *sectors, unsigned int max_segs, unsigned int max_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8154af00)
Location: block/blk-merge.c:196
Inline: False
Direct callers:
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:blk_bio_segment_split
```
**Symbols:**

```
ffffffff8154af00-ffffffff8154afee: bvec_split_segs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool bvec_split_segs(const struct request_queue *q, const struct bio_vec *bv, unsigned int *nsegs, unsigned int *sectors, unsigned int max_segs, unsigned int max_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81566c90)
Location: block/blk-merge.c:197
Inline: False
Direct callers:
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:blk_bio_segment_split
```
**Symbols:**

```
ffffffff81566c90-ffffffff81566d7e: bvec_split_segs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool bvec_split_segs(const struct request_queue *q, const struct bio_vec *bv, unsigned int *nsegs, unsigned int *sectors, unsigned int max_segs, unsigned int max_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8156f1d0)
Location: block/blk-merge.c:197
Inline: False
Direct callers:
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:blk_bio_segment_split
```
**Symbols:**

```
ffffffff8156f1d0-ffffffff8156f2b8: bvec_split_segs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool bvec_split_segs(const struct request_queue *q, const struct bio_vec *bv, unsigned int *nsegs, unsigned int *sectors, unsigned int max_segs, unsigned int max_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff815d3870)
Location: block/blk-merge.c:197
Inline: False
Direct callers:
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:blk_bio_segment_split
```
**Symbols:**

```
ffffffff815d3870-ffffffff815d3958: bvec_split_segs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool bvec_split_segs(const struct request_queue *q, const struct bio_vec *bv, unsigned int *nsegs, unsigned int *sectors, unsigned int max_segs, unsigned int max_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8167f660)
Location: block/blk-merge.c:217
Inline: False
Direct callers:
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:blk_bio_segment_split
```
**Symbols:**

```
ffffffff8167f660-ffffffff8167f770: bvec_split_segs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool bvec_split_segs(const struct queue_limits *lim, const struct bio_vec *bv, unsigned int *nsegs, unsigned int *bytes, unsigned int max_segs, unsigned int max_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8173c980)
Location: block/blk-merge.c:231
Inline: False
Direct callers:
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:bio_split_rw
```
**Symbols:**

```
ffffffff8173c980-ffffffff8173ca54: bvec_split_segs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool bvec_split_segs(const struct queue_limits *lim, const struct bio_vec *bv, unsigned int *nsegs, unsigned int *bytes, unsigned int max_segs, unsigned int max_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81778f00)
Location: block/blk-merge.c:231
Inline: False
Direct callers:
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:bio_split_rw
```
**Symbols:**

```
ffffffff81778f00-ffffffff81778fd4: bvec_split_segs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool bvec_split_segs(const struct queue_limits *lim, const struct bio_vec *bv, unsigned int *nsegs, unsigned int *bytes, unsigned int max_segs, unsigned int max_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff817bb2d0)
Location: block/blk-merge.c:227
Inline: False
Direct callers:
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:bio_split_rw
```
**Symbols:**

```
ffffffff817bb2d0-ffffffff817bb3a4: bvec_split_segs (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-merge.c (ffff8000105e9b88)
Location: block/blk-merge.c:193
Inline: True
Direct callers:
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:__blk_queue_split
```
**Symbols:**

```
ffff8000105e9b88-ffff8000105e9cdc: bvec_split_segs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool bvec_split_segs(const struct request_queue *q, const struct bio_vec *bv, unsigned int *nsegs, unsigned int *sectors, unsigned int max_segs, unsigned int max_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (c0795fcc)
Location: block/blk-merge.c:193
Inline: False
Direct callers:
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:__blk_queue_split
```
**Symbols:**

```
c0795fcc-c07960d0: bvec_split_segs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-merge.c (c00000000077e970)
Location: block/blk-merge.c:193
Inline: True
Direct callers:
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:__blk_queue_split
```
**Symbols:**

```
c00000000077e970-c00000000077eaf8: bvec_split_segs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-merge.c (ffffffe00042a052)
Location: block/blk-merge.c:193
Inline: True
Direct callers:
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:__blk_queue_split
```
**Symbols:**

```
ffffffe00042a052-ffffffe00042a176: bvec_split_segs.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-merge.c (ffffffff814e36e0)
Location: block/blk-merge.c:193
Inline: True
Direct callers:
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:__blk_queue_split
```
**Symbols:**

```
ffffffff814e36e0-ffffffff814e37bf: bvec_split_segs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-merge.c (ffffffff814d4060)
Location: block/blk-merge.c:193
Inline: True
Direct callers:
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:__blk_queue_split
```
**Symbols:**

```
ffffffff814d4060-ffffffff814d413f: bvec_split_segs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-merge.c (ffffffff814df770)
Location: block/blk-merge.c:193
Inline: True
Direct callers:
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:__blk_queue_split
```
**Symbols:**

```
ffffffff814df770-ffffffff814df84f: bvec_split_segs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-merge.c (ffffffff814f85d0)
Location: block/blk-merge.c:193
Inline: True
Direct callers:
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:__blk_queue_split
```
**Symbols:**

```
ffffffff814f85d0-ffffffff814f86af: bvec_split_segs.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct queue_limits *lim</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int *bytes</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int max_bytes</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct request_queue *q</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int *sectors</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int max_sectors</code>
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
</ul>
