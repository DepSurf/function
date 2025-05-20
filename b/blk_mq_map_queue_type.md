# Function: <code>blk_mq_map_queue_type</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814a1daa)
Location: block/blk-mq.h:88
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff814abe83)
Location: block/blk-mq.h:88
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814ad0a1)
Location: block/blk-mq.h:88
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff814af0d8)
Location: block/blk-mq.h:88
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
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
In block/blk-mq.c (ffffffff814da0dc)
Location: block/blk-mq.h:89
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
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
In block/blk-mq.c (ffffffff814f3482)
Location: block/blk-mq.h:90
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
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
In block/blk-mq.c (ffffffff8155363e)
Location: block/blk-mq.h:89
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_init_cpu_queues
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
In block/blk-mq.c (ffffffff8156fcf1)
Location: block/blk-mq.h:91
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_init_cpu_queues
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
In block/blk-mq.c (ffffffff81577fd7)
Location: block/blk-mq.h:92
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queues
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
In block/blk-mq.c (ffffffff815dcf83)
Location: block/blk-mq.h:92
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queues
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
In block/blk-mq.c (ffffffff8168ab6b)
Location: block/blk-mq.h:82
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
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
In block/blk-mq.c (ffffffff81749d4f)
Location: block/blk-mq.h:82
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
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
In block/blk-mq.c (ffffffff81786461)
Location: block/blk-mq.h:78
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
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
In block/blk-mq.c (ffffffff817c8b3a)
Location: block/blk-mq.h:78
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
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
In block/blk-mq.c (ffff8000105f2cc4)
Location: block/blk-mq.h:90
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
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
In block/blk-mq.c (c079edec)
Location: block/blk-mq.h:90
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
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
In block/blk-mq.c (c00000000078a200)
Location: block/blk-mq.h:90
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
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
In block/blk-mq.c (ffffffe0004314dc)
Location: block/blk-mq.h:90
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
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
In block/blk-mq.c (ffffffff814eba62)
Location: block/blk-mq.h:90
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
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
In block/blk-mq.c (ffffffff814dbfb2)
Location: block/blk-mq.h:90
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
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
In block/blk-mq.c (ffffffff814e7af2)
Location: block/blk-mq.h:90
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
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
In block/blk-mq.c (ffffffff81500a92)
Location: block/blk-mq.h:90
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
```
</details>
</li>
</ul>

## Differences
