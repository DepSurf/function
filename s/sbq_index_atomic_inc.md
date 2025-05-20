# Function: <code>sbq_index_atomic_inc</code>

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
In block/blk-mq-tag.c (ffffffff81425a72)
Location: include/linux/sbitmap.h:343
Inline: True
```
```
In lib/sbitmap.c (ffffffff814824ae)
Location: include/linux/sbitmap.h:343
Inline: True
Inline callers:
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
In block/blk-mq.c (ffffffff814319a6)
Location: include/linux/sbitmap.h:418
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff81433b24)
Location: include/linux/sbitmap.h:418
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff8148b8fb)
Location: include/linux/sbitmap.h:418
Inline: True
Inline callers:
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
In block/blk-mq.c (ffffffff8145d61d)
Location: include/linux/sbitmap.h:448
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff8145f7e4)
Location: include/linux/sbitmap.h:448
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff814c7a1b)
Location: include/linux/sbitmap.h:448
Inline: True
Inline callers:
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
In block/blk-mq.c (ffffffff81490d1a)
Location: include/linux/sbitmap.h:485
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff81493182)
Location: include/linux/sbitmap.h:485
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff814f86d0)
Location: include/linux/sbitmap.h:485
Inline: True
Inline callers:
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
In block/blk-mq.c (ffffffff814a9ed7)
Location: include/linux/sbitmap.h:515
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff814ad108)
Location: include/linux/sbitmap.h:515
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff8150c957)
Location: include/linux/sbitmap.h:515
Inline: True
Inline callers:
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
In block/blk-mq.c (ffffffff814d7e65)
Location: include/linux/sbitmap.h:504
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff814db3ad)
Location: include/linux/sbitmap.h:504
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff8153b05e)
Location: include/linux/sbitmap.h:504
Inline: True
Inline callers:
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
In block/blk-mq.c (ffffffff814f11f7)
Location: include/linux/sbitmap.h:504
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff814f47dd)
Location: include/linux/sbitmap.h:504
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff8155be7e)
Location: include/linux/sbitmap.h:504
Inline: True
Inline callers:
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
In block/blk-mq.c (ffffffff81551a18)
Location: include/linux/sbitmap.h:495
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff81554fab)
Location: include/linux/sbitmap.h:495
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff815e5973)
Location: include/linux/sbitmap.h:495
Inline: True
Inline callers:
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
In block/blk-mq.c (ffffffff8156db6c)
Location: include/linux/sbitmap.h:490
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff81571660)
Location: include/linux/sbitmap.h:490
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff81609d33)
Location: include/linux/sbitmap.h:490
Inline: True
Inline callers:
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
In block/blk-mq.c (ffffffff8157564c)
Location: include/linux/sbitmap.h:523
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff81579690)
Location: include/linux/sbitmap.h:523
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff815ecf13)
Location: include/linux/sbitmap.h:523
Inline: True
Inline callers:
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
In block/blk-mq.c (ffffffff815da34c)
Location: include/linux/sbitmap.h:523
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff815de8a9)
Location: include/linux/sbitmap.h:523
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff81659e33)
Location: include/linux/sbitmap.h:523
Inline: True
Inline callers:
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
In block/blk-mq.c (ffffffff8168840d)
Location: include/linux/sbitmap.h:544
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff8168cb08)
Location: include/linux/sbitmap.h:544
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff81772506)
Location: include/linux/sbitmap.h:544
Inline: True
Inline callers:
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
In block/blk-mq.c (ffffffff817468c5)
Location: include/linux/sbitmap.h:550
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff8174b2fd)
Location: include/linux/sbitmap.h:550
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
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
In block/blk-mq.c (ffffffff81783b25)
Location: include/linux/sbitmap.h:550
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff81787a1d)
Location: include/linux/sbitmap.h:550
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
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
In block/blk-mq.c (ffffffff817c5ea8)
Location: include/linux/sbitmap.h:550
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff817ca0ed)
Location: include/linux/sbitmap.h:550
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
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
Location: include/linux/sbitmap.h:504
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffff8000105f45c4)
Location: include/linux/sbitmap.h:504
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffff80001066a35c)
Location: include/linux/sbitmap.h:504
Inline: True
Inline callers:
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
Location: include/linux/sbitmap.h:504
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (c07a021c)
Location: include/linux/sbitmap.h:504
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (c0811c40)
Location: include/linux/sbitmap.h:504
Inline: True
Inline callers:
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
In block/blk-mq.c (c00000000078701c)
Location: include/linux/sbitmap.h:504
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (c00000000078bde8)
Location: include/linux/sbitmap.h:504
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (c00000000081eb60)
Location: include/linux/sbitmap.h:504
Inline: True
Inline callers:
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
In block/blk-mq.c (ffffffe00042f4c6)
Location: include/linux/sbitmap.h:504
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffe0004325a6)
Location: include/linux/sbitmap.h:504
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffe0004942b2)
Location: include/linux/sbitmap.h:504
Inline: True
Inline callers:
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
In block/blk-mq.c (ffffffff814e97d7)
Location: include/linux/sbitmap.h:504
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff814ecdbd)
Location: include/linux/sbitmap.h:504
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff8155446e)
Location: include/linux/sbitmap.h:504
Inline: True
Inline callers:
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
In block/blk-mq.c (ffffffff814d9d47)
Location: include/linux/sbitmap.h:504
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff814dd30d)
Location: include/linux/sbitmap.h:504
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff815446ee)
Location: include/linux/sbitmap.h:504
Inline: True
Inline callers:
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
In block/blk-mq.c (ffffffff814e5867)
Location: include/linux/sbitmap.h:504
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff814e8e4d)
Location: include/linux/sbitmap.h:504
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff815501ae)
Location: include/linux/sbitmap.h:504
Inline: True
Inline callers:
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
In block/blk-mq.c (ffffffff814fe7cd)
Location: include/linux/sbitmap.h:504
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff81501ded)
Location: include/linux/sbitmap.h:504
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In lib/sbitmap.c (ffffffff81569fee)
Location: include/linux/sbitmap.h:504
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
</details>
</li>
</ul>

## Differences
