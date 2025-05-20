# Function: <code>__blk_recalc_rq_segments</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int __blk_recalc_rq_segments(struct request_queue *q, struct bio *bio, bool no_sg_merge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff813bfb60)
Location: block/blk-merge.c:196
Inline: False
Direct callers:
  - block/blk-merge.c:blk_recount_segments
  - block/blk-merge.c:blk_recalc_rq_segments
```
**Symbols:**

```
ffffffff813bfb60-ffffffff813bfeee: __blk_recalc_rq_segments (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int __blk_recalc_rq_segments(struct request_queue *q, struct bio *bio, bool no_sg_merge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81403bd0)
Location: block/blk-merge.c:227
Inline: False
Direct callers:
  - block/blk-merge.c:blk_recount_segments
  - block/blk-merge.c:blk_recalc_rq_segments
```
**Symbols:**

```
ffffffff81403bd0-ffffffff81403f70: __blk_recalc_rq_segments (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int __blk_recalc_rq_segments(struct request_queue *q, struct bio *bio, bool no_sg_merge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8141d860)
Location: block/blk-merge.c:231
Inline: False
Direct callers:
  - block/blk-merge.c:blk_recount_segments
  - block/blk-merge.c:blk_recalc_rq_segments
```
**Symbols:**

```
ffffffff8141d860-ffffffff8141dc1e: __blk_recalc_rq_segments (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int __blk_recalc_rq_segments(struct request_queue *q, struct bio *bio, bool no_sg_merge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8142b760)
Location: block/blk-merge.c:221
Inline: False
Direct callers:
  - block/blk-merge.c:blk_recount_segments
  - block/blk-merge.c:blk_recalc_rq_segments
```
**Symbols:**

```
ffffffff8142b760-ffffffff8142babf: __blk_recalc_rq_segments (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int __blk_recalc_rq_segments(struct request_queue *q, struct bio *bio, bool no_sg_merge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81456970)
Location: block/blk-merge.c:222
Inline: False
Direct callers:
  - block/blk-merge.c:blk_recount_segments
  - block/blk-merge.c:blk_recalc_rq_segments
```
**Symbols:**

```
ffffffff81456970-ffffffff81456ccf: __blk_recalc_rq_segments (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int __blk_recalc_rq_segments(struct request_queue *q, struct bio *bio, bool no_sg_merge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81489db0)
Location: block/blk-merge.c:231
Inline: False
Direct callers:
  - block/blk-merge.c:blk_recount_segments
  - block/blk-merge.c:blk_recalc_rq_segments
```
**Symbols:**

```
ffffffff81489db0-ffffffff8148a136: __blk_recalc_rq_segments (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int __blk_recalc_rq_segments(struct request_queue *q, struct bio *bio, bool no_sg_merge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814a3b40)
Location: block/blk-merge.c:293
Inline: False
Direct callers:
  - block/blk-merge.c:blk_recount_segments
  - block/blk-merge.c:blk_recalc_rq_segments
```
**Symbols:**

```
ffffffff814a3b40-ffffffff814a3e88: __blk_recalc_rq_segments (STB_LOCAL)
```
</details>
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
</ul>
