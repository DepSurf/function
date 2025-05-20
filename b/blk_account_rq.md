# Function: <code>blk_account_rq</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8141f6bf)
Location: include/linux/blkdev.h:740
Inline: True
Inline callers:
  - block/elevator.c:elv_completed_request
  - block/elevator.c:elv_requeue_request
```
```
In block/blk-core.c (ffffffff81426735)
Location: include/linux/blkdev.h:740
Inline: True
Inline callers:
  - block/blk-core.c:blk_dequeue_request
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
In block/elevator.c (ffffffff8144a1e3)
Location: include/linux/blkdev.h:760
Inline: True
Inline callers:
  - block/elevator.c:elv_completed_request
  - block/elevator.c:elv_requeue_request
```
```
In block/blk-core.c (ffffffff8144cc1e)
Location: include/linux/blkdev.h:760
Inline: True
Inline callers:
  - block/blk-core.c:blk_start_request
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
In block/elevator.c (ffffffff8147cf33)
Location: include/linux/blkdev.h:753
Inline: True
Inline callers:
  - block/elevator.c:elv_completed_request
  - block/elevator.c:elv_requeue_request
```
```
In block/blk-core.c (ffffffff8147fead)
Location: include/linux/blkdev.h:753
Inline: True
Inline callers:
  - block/blk-core.c:blk_start_request
```
</details>
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
