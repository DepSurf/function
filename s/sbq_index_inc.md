# Function: <code>sbq_index_inc</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81425a7a)
Location: include/linux/sbitmap.h:338
Inline: True
```
```
In lib/sbitmap.c (ffffffff81482536)
Location: include/linux/sbitmap.h:338
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:sbitmap_queue_clear
  - lib/sbitmap.c:sbitmap_queue_clear
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814319ac)
Location: include/linux/sbitmap.h:413
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff81433b2a)
Location: include/linux/sbitmap.h:413
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff8148b965)
Location: include/linux/sbitmap.h:413
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:sbitmap_queue_clear
  - lib/sbitmap.c:sbitmap_queue_clear
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145d623)
Location: include/linux/sbitmap.h:443
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff8145f7ea)
Location: include/linux/sbitmap.h:443
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff814c7a88)
Location: include/linux/sbitmap.h:443
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:sbitmap_queue_clear
  - lib/sbitmap.c:sbitmap_queue_clear
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
In block/blk-mq.c (ffffffff81490d20)
Location: include/linux/sbitmap.h:480
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff81493188)
Location: include/linux/sbitmap.h:480
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff814f87c8)
Location: include/linux/sbitmap.h:480
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
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
In block/blk-mq.c (ffffffff814a9edd)
Location: include/linux/sbitmap.h:510
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff814ad10e)
Location: include/linux/sbitmap.h:510
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff8150c9e8)
Location: include/linux/sbitmap.h:510
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
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
In block/blk-mq.c (ffffffff814d7e6b)
Location: include/linux/sbitmap.h:499
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff814db3b3)
Location: include/linux/sbitmap.h:499
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff8153b168)
Location: include/linux/sbitmap.h:499
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
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
In block/blk-mq.c (ffffffff814f11fd)
Location: include/linux/sbitmap.h:499
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff814f47e3)
Location: include/linux/sbitmap.h:499
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff8155bf88)
Location: include/linux/sbitmap.h:499
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
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
In block/blk-mq.c (ffffffff81551a1e)
Location: include/linux/sbitmap.h:490
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff81554fb1)
Location: include/linux/sbitmap.h:490
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff815e5a08)
Location: include/linux/sbitmap.h:490
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
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
In block/blk-mq.c (ffffffff8156db72)
Location: include/linux/sbitmap.h:485
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff81571666)
Location: include/linux/sbitmap.h:485
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff81609dc8)
Location: include/linux/sbitmap.h:485
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
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
In block/blk-mq.c (ffffffff81575652)
Location: include/linux/sbitmap.h:518
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff81579696)
Location: include/linux/sbitmap.h:518
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff815ecfa8)
Location: include/linux/sbitmap.h:518
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
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
In block/blk-mq.c (ffffffff815da352)
Location: include/linux/sbitmap.h:518
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff815de8af)
Location: include/linux/sbitmap.h:518
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff81659ec8)
Location: include/linux/sbitmap.h:518
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
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
In block/blk-mq.c (ffffffff81688413)
Location: include/linux/sbitmap.h:539
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff8168cb0e)
Location: include/linux/sbitmap.h:539
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff817725c8)
Location: include/linux/sbitmap.h:539
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
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
In block/blk-mq.c (ffffffff817468cb)
Location: include/linux/sbitmap.h:545
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff8174b303)
Location: include/linux/sbitmap.h:545
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff818a2e14)
Location: include/linux/sbitmap.h:545
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:sbitmap_queue_wake_up
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
In block/blk-mq.c (ffffffff81783b2b)
Location: include/linux/sbitmap.h:545
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff81787a23)
Location: include/linux/sbitmap.h:545
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff818e5304)
Location: include/linux/sbitmap.h:545
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:sbitmap_queue_wake_up
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
In block/blk-mq.c (ffffffff817c5eae)
Location: include/linux/sbitmap.h:545
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff817ca0f3)
Location: include/linux/sbitmap.h:545
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff8192c304)
Location: include/linux/sbitmap.h:545
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:sbitmap_queue_wake_up
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
In block/blk-mq.c (ffff8000105f0620)
Location: include/linux/sbitmap.h:499
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffff8000105f45c4)
Location: include/linux/sbitmap.h:499
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffff8000106691d8)
Location: include/linux/sbitmap.h:499
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
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
In block/blk-mq.c (c079c658)
Location: include/linux/sbitmap.h:499
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (c07a021c)
Location: include/linux/sbitmap.h:499
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (c0811cf0)
Location: include/linux/sbitmap.h:499
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
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
In block/blk-mq.c (c000000000787028)
Location: include/linux/sbitmap.h:499
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (c00000000078bdf4)
Location: include/linux/sbitmap.h:499
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (c00000000081ed74)
Location: include/linux/sbitmap.h:499
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
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
In block/blk-mq.c (ffffffe00042f4d2)
Location: include/linux/sbitmap.h:499
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffe0004325b2)
Location: include/linux/sbitmap.h:499
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffe0004943fe)
Location: include/linux/sbitmap.h:499
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
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
In block/blk-mq.c (ffffffff814e97dd)
Location: include/linux/sbitmap.h:499
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff814ecdc3)
Location: include/linux/sbitmap.h:499
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff81554578)
Location: include/linux/sbitmap.h:499
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
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
In block/blk-mq.c (ffffffff814d9d4d)
Location: include/linux/sbitmap.h:499
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff814dd313)
Location: include/linux/sbitmap.h:499
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff815447f8)
Location: include/linux/sbitmap.h:499
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
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
In block/blk-mq.c (ffffffff814e586d)
Location: include/linux/sbitmap.h:499
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff814e8e53)
Location: include/linux/sbitmap.h:499
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff815502b8)
Location: include/linux/sbitmap.h:499
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
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
In block/blk-mq.c (ffffffff814fe7d3)
Location: include/linux/sbitmap.h:499
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff81501df3)
Location: include/linux/sbitmap.h:499
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff8156a0f8)
Location: include/linux/sbitmap.h:499
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
</details>
</li>
</ul>

## Differences
