# Function: <code>__sbitmap_for_each_set</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145c842)
Location: include/linux/sbitmap.h:229
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
```
In block/blk-mq-tag.c (ffffffff8145fa12)
Location: include/linux/sbitmap.h:229
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814900ce)
Location: include/linux/sbitmap.h:237
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
```
In block/blk-mq-tag.c (ffffffff81493324)
Location: include/linux/sbitmap.h:237
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a9937)
Location: include/linux/sbitmap.h:254
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
```
In block/blk-mq-tag.c (ffffffff814ad2e4)
Location: include/linux/sbitmap.h:254
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d78d7)
Location: include/linux/sbitmap.h:243
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
```
In block/blk-mq-tag.c (ffffffff814db558)
Location: include/linux/sbitmap.h:243
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f0c57)
Location: include/linux/sbitmap.h:243
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
```
In block/blk-mq-tag.c (ffffffff814f4988)
Location: include/linux/sbitmap.h:243
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81551e65)
Location: include/linux/sbitmap.h:234
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
```
In block/blk-mq-tag.c (ffffffff81555479)
Location: include/linux/sbitmap.h:234
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156df95)
Location: include/linux/sbitmap.h:229
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
```
In block/blk-mq-tag.c (ffffffff815719df)
Location: include/linux/sbitmap.h:229
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81575ad6)
Location: include/linux/sbitmap.h:229
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
```
In block/blk-mq-tag.c (ffffffff81579a2a)
Location: include/linux/sbitmap.h:229
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815da00c)
Location: include/linux/sbitmap.h:229
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
```
In block/blk-mq-tag.c (ffffffff815ded20)
Location: include/linux/sbitmap.h:229
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81687a85)
Location: include/linux/sbitmap.h:241
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
```
In block/blk-mq-tag.c (ffffffff8168d06c)
Location: include/linux/sbitmap.h:241
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
In block/blk-mq.c (ffffffff81745e42)
Location: include/linux/sbitmap.h:247
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
```
In block/blk-mq-tag.c (ffffffff8174b88c)
Location: include/linux/sbitmap.h:247
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
In block/blk-mq.c (ffffffff81782650)
Location: include/linux/sbitmap.h:247
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
```
In block/blk-mq-tag.c (ffffffff81787fac)
Location: include/linux/sbitmap.h:247
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
In block/blk-mq.c (ffffffff817c49f0)
Location: include/linux/sbitmap.h:247
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
```
In block/blk-mq-tag.c (ffffffff817ca67c)
Location: include/linux/sbitmap.h:247
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
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f00bc)
Location: include/linux/sbitmap.h:243
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
```
In block/blk-mq-tag.c (ffff8000105f47c0)
Location: include/linux/sbitmap.h:243
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079c224)
Location: include/linux/sbitmap.h:243
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
```
In block/blk-mq-tag.c (c07a03f0)
Location: include/linux/sbitmap.h:243
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000786864)
Location: include/linux/sbitmap.h:243
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
```
In block/blk-mq-tag.c (c00000000078c254)
Location: include/linux/sbitmap.h:243
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042f054)
Location: include/linux/sbitmap.h:243
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
```
In block/blk-mq-tag.c (ffffffe000432740)
Location: include/linux/sbitmap.h:243
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e9237)
Location: include/linux/sbitmap.h:243
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
```
In block/blk-mq-tag.c (ffffffff814ecf68)
Location: include/linux/sbitmap.h:243
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d97a7)
Location: include/linux/sbitmap.h:243
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
```
In block/blk-mq-tag.c (ffffffff814dd4b8)
Location: include/linux/sbitmap.h:243
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e52c7)
Location: include/linux/sbitmap.h:243
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
```
In block/blk-mq-tag.c (ffffffff814e8ff8)
Location: include/linux/sbitmap.h:243
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fe227)
Location: include/linux/sbitmap.h:243
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
```
In block/blk-mq-tag.c (ffffffff81501fb8)
Location: include/linux/sbitmap.h:243
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
</details>
</li>
</ul>

## Differences
