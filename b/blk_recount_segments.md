# Function: <code>blk_recount_segments</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_recount_segments(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff813c0a00)
Location: block/blk-merge.c:275
Inline: False
Direct callers:
  - block/bio.c:bio_phys_segments
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
```
**Symbols:**

```
ffffffff813c0a00-ffffffff813c0b64: blk_recount_segments (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_recount_segments(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81404b10)
Location: block/blk-merge.c:306
Inline: False
Direct callers:
  - block/bio.c:bio_phys_segments
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
**Symbols:**

```
ffffffff81404b10-ffffffff81404c98: blk_recount_segments (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_recount_segments(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8141e280)
Location: block/blk-merge.c:309
Inline: False
Direct callers:
  - block/bio.c:bio_phys_segments
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
**Symbols:**

```
ffffffff8141e280-ffffffff8141e424: blk_recount_segments (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_recount_segments(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8142bac0)
Location: block/blk-merge.c:299
Inline: False
Direct callers:
  - block/bio.c:bio_phys_segments
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
**Symbols:**

```
ffffffff8142bac0-ffffffff8142bc24: blk_recount_segments (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_recount_segments(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81456cd0)
Location: block/blk-merge.c:300
Inline: False
Direct callers:
  - block/bio.c:bio_phys_segments
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
**Symbols:**

```
ffffffff81456cd0-ffffffff81456e34: blk_recount_segments (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_recount_segments(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8148a140)
Location: block/blk-merge.c:309
Inline: False
Direct callers:
  - block/bio.c:bio_phys_segments
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
**Symbols:**

```
ffffffff8148a140-ffffffff8148a2a8: blk_recount_segments (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_recount_segments(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814a4a40)
Location: block/blk-merge.c:368
Inline: False
Direct callers:
  - block/bio.c:bio_phys_segments
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
**Symbols:**

```
ffffffff814a4a40-ffffffff814a4b9c: blk_recount_segments (STB_GLOBAL)
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
