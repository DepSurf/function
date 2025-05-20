# Function: <code>blk_get_flush_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b7b09)
Location: block/blk.h:39
Inline: True
Inline callers:
  - block/blk-core.c:__blk_drain_queue
  - block/blk-core.c:blk_peek_request
```
```
In block/blk-flush.c (ffffffff813bd748)
Location: block/blk.h:39
Inline: True
Inline callers:
  - block/blk-flush.c:flush_data_end_io
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:blk_insert_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fef71)
Location: block/blk.h:39
Inline: True
Inline callers:
  - block/blk-core.c:blk_peek_request
  - block/blk-core.c:__blk_drain_queue
```
```
In block/blk-flush.c (ffffffff81401a8f)
Location: block/blk.h:39
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814189a1)
Location: block/blk.h:39
Inline: True
Inline callers:
  - block/blk-core.c:blk_peek_request
  - block/blk-core.c:__blk_drain_queue
```
```
In block/blk-flush.c (ffffffff8141b6ef)
Location: block/blk.h:39
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_data_end_io
  - block/blk-flush.c:flush_end_io
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
In block/blk-core.c (ffffffff81426881)
Location: block/blk.h:43
Inline: True
Inline callers:
  - block/blk-core.c:blk_peek_request
  - block/blk-core.c:__blk_drain_queue
```
```
In block/blk-flush.c (ffffffff81429748)
Location: block/blk.h:43
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_data_end_io
  - block/blk-flush.c:flush_end_io
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
In block/blk-core.c (ffffffff814511be)
Location: block/blk.h:44
Inline: True
Inline callers:
  - block/blk-core.c:blk_peek_request
  - block/blk-core.c:__blk_drain_queue
```
```
In block/blk-flush.c (ffffffff81454928)
Location: block/blk.h:44
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_data_end_io
  - block/blk-flush.c:flush_end_io
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
In block/blk-core.c (ffffffff8148442e)
Location: block/blk.h:113
Inline: True
Inline callers:
  - block/blk-core.c:blk_peek_request
```
```
In block/blk-flush.c (ffffffff81487d65)
Location: block/blk.h:113
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814a1daa)
Location: block/blk.h:39
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814cfbf1)
Location: block/blk.h:40
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814e8f51)
Location: block/blk.h:42
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff815482fb)
Location: block/blk.h:44
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff8156403b)
Location: block/blk.h:36
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff8156c7aa)
Location: block/blk.h:37
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff815d0c8a)
Location: block/blk.h:37
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff8167c418)
Location: block/blk-flush.c:100
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81738ca8)
Location: block/blk-flush.c:100
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff817752d1)
Location: block/blk-flush.c:98
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff817b75dc)
Location: block/blk-flush.c:98
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffff8000105e6ecc)
Location: block/blk.h:42
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (c0793bd4)
Location: block/blk.h:42
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (c00000000077ba8c)
Location: block/blk.h:42
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffe00042803e)
Location: block/blk.h:42
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814e1531)
Location: block/blk.h:42
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814d1ec1)
Location: block/blk.h:42
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814dd5c1)
Location: block/blk.h:42
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814f6421)
Location: block/blk.h:42
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
</details>
</li>
</ul>

## Differences
