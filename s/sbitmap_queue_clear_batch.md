# Function: <code>sbitmap_queue_clear_batch</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void sbitmap_queue_clear_batch(struct sbitmap_queue *sbq, int offset, int *tags, int nr_tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:657
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_put_tags
```
**Symbols:**

```
ffffffff81ea57d2-ffffffff81ea58a8: sbitmap_queue_clear_batch.cold (STB_LOCAL)
ffffffff81773a20-ffffffff81773b6f: sbitmap_queue_clear_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void sbitmap_queue_clear_batch(struct sbitmap_queue *sbq, int offset, int *tags, int nr_tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:617
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_put_tags
```
**Symbols:**

```
ffffffff8208dd53-ffffffff8208de49: sbitmap_queue_clear_batch.cold (STB_LOCAL)
ffffffff818a43b0-ffffffff818a4515: sbitmap_queue_clear_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void sbitmap_queue_clear_batch(struct sbitmap_queue *sbq, int offset, int *tags, int nr_tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:609
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_put_tags
```
**Symbols:**

```
ffffffff8210e061-ffffffff8210e149: sbitmap_queue_clear_batch.cold (STB_LOCAL)
ffffffff818e6840-ffffffff818e699b: sbitmap_queue_clear_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void sbitmap_queue_clear_batch(struct sbitmap_queue *sbq, int offset, int *tags, int nr_tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:604
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_put_tags
```
**Symbols:**

```
ffffffff821ebc9e-ffffffff821ebd86: sbitmap_queue_clear_batch.cold (STB_LOCAL)
ffffffff8192d860-ffffffff8192d9bb: sbitmap_queue_clear_batch (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
