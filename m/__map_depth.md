# Function: <code>__map_depth</code>

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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81687ac7)
Location: include/linux/sbitmap.h:163
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
```
In block/blk-mq-tag.c (ffffffff8168d0a0)
Location: include/linux/sbitmap.h:163
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
```
```
In lib/sbitmap.c (ffffffff817738ba)
Location: include/linux/sbitmap.h:163
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_queue_get_batch
  - lib/sbitmap.c:__sbitmap_queue_get_batch
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:__sbitmap_weight
  - lib/sbitmap.c:__sbitmap_weight
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:__sbitmap_get
  - lib/sbitmap.c:__sbitmap_get
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81745e80)
Location: include/linux/sbitmap.h:169
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
```
In block/blk-mq-tag.c (ffffffff8174b8c0)
Location: include/linux/sbitmap.h:169
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
```
```
In lib/sbitmap.c (ffffffff818a424f)
Location: include/linux/sbitmap.h:169
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_queue_get_batch
  - lib/sbitmap.c:__sbitmap_queue_get_batch
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:__sbitmap_weight
  - lib/sbitmap.c:__sbitmap_weight
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:__sbitmap_get
  - lib/sbitmap.c:__sbitmap_get
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817826ae)
Location: include/linux/sbitmap.h:169
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
```
In block/blk-mq-tag.c (ffffffff81787fe0)
Location: include/linux/sbitmap.h:169
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
```
```
In lib/sbitmap.c (ffffffff818e66df)
Location: include/linux/sbitmap.h:169
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_queue_get_batch
  - lib/sbitmap.c:__sbitmap_queue_get_batch
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:__sbitmap_weight
  - lib/sbitmap.c:__sbitmap_weight
  - lib/sbitmap.c:sbitmap_find_bit
  - lib/sbitmap.c:sbitmap_find_bit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c4a4e)
Location: include/linux/sbitmap.h:169
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
```
In block/blk-mq-tag.c (ffffffff817ca6b0)
Location: include/linux/sbitmap.h:169
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
```
```
In lib/sbitmap.c (ffffffff8192d6ff)
Location: include/linux/sbitmap.h:169
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_queue_get_batch
  - lib/sbitmap.c:__sbitmap_queue_get_batch
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:__sbitmap_weight
  - lib/sbitmap.c:__sbitmap_weight
  - lib/sbitmap.c:sbitmap_find_bit
  - lib/sbitmap.c:sbitmap_find_bit
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
