# Function: <code>blk_mq_init_bitmaps</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blk_mq_init_bitmaps(struct sbitmap_queue *bitmap_tags, struct sbitmap_queue *breserved_tags, unsigned int queue_depth, unsigned int reserved, int node, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff815def90)
Location: block/blk-mq-tag.c:475
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_shared_sbitmap
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff815def90-ffffffff815df033: blk_mq_init_bitmaps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blk_mq_init_bitmaps(struct sbitmap_queue *bitmap_tags, struct sbitmap_queue *breserved_tags, unsigned int queue_depth, unsigned int reserved, int node, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8168d700)
Location: block/blk-mq-tag.c:546
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
**Symbols:**

```
ffffffff8168d700-ffffffff8168d7ac: blk_mq_init_bitmaps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blk_mq_init_bitmaps(struct sbitmap_queue *bitmap_tags, struct sbitmap_queue *breserved_tags, unsigned int queue_depth, unsigned int reserved, int node, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8174bf00)
Location: block/blk-mq-tag.c:539
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
**Symbols:**

```
ffffffff8174bf00-ffffffff8174bfac: blk_mq_init_bitmaps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blk_mq_init_bitmaps(struct sbitmap_queue *bitmap_tags, struct sbitmap_queue *breserved_tags, unsigned int queue_depth, unsigned int reserved, int node, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81788620)
Location: block/blk-mq-tag.c:546
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
**Symbols:**

```
ffffffff81788620-ffffffff817886cc: blk_mq_init_bitmaps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blk_mq_init_bitmaps(struct sbitmap_queue *bitmap_tags, struct sbitmap_queue *breserved_tags, unsigned int queue_depth, unsigned int reserved, int node, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff817cacf0)
Location: block/blk-mq-tag.c:546
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
**Symbols:**

```
ffffffff817cacf0-ffffffff817cad9c: blk_mq_init_bitmaps (STB_GLOBAL)
```
</details>
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
