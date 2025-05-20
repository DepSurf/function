# Function: <code>blk_schedule_flush_plug</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8181f8c5)
Location: include/linux/blkdev.h:1079
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/core.c:schedule
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
In kernel/sched/core.c (ffffffff81899fc5)
Location: include/linux/blkdev.h:1103
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff81264a16)
Location: include/linux/blkdev.h:1103
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
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
In kernel/sched/core.c (ffffffff818ce665)
Location: include/linux/blkdev.h:1265
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff81277e56)
Location: include/linux/blkdev.h:1265
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
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
In kernel/sched/core.c (ffffffff810b310a)
Location: include/linux/blkdev.h:1299
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule_prepare
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff81285152)
Location: include/linux/blkdev.h:1299
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
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
In kernel/sched/core.c (ffffffff810ba50a)
Location: include/linux/blkdev.h:1314
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule_prepare
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff812a7c75)
Location: include/linux/blkdev.h:1314
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
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
In kernel/sched/core.c (ffffffff810c1bb1)
Location: include/linux/blkdev.h:1350
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule_prepare
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff812ce805)
Location: include/linux/blkdev.h:1350
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
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
In kernel/sched/core.c (ffffffff810caee1)
Location: include/linux/blkdev.h:1152
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule_prepare
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff812e3b4d)
Location: include/linux/blkdev.h:1152
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
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
In kernel/sched/core.c (ffffffff810d2bb5)
Location: include/linux/blkdev.h:1166
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule_prepare
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff813022ed)
Location: include/linux/blkdev.h:1166
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
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
In kernel/sched/core.c (ffffffff810dd025)
Location: include/linux/blkdev.h:1193
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule_prepare
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff813153fd)
Location: include/linux/blkdev.h:1193
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
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
In kernel/sched/core.c (ffffffff81bc8971)
Location: include/linux/blkdev.h:1220
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff8134ec3f)
Location: include/linux/blkdev.h:1220
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
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
In kernel/sched/core.c (ffffffff81c41742)
Location: include/linux/blkdev.h:1275
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff8135babf)
Location: include/linux/blkdev.h:1275
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
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
In kernel/sched/core.c (ffffffff81c336b2)
Location: include/linux/blkdev.h:1260
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff813626cf)
Location: include/linux/blkdev.h:1260
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
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
In kernel/sched/core.c (ffffffff81d51fb2)
Location: include/linux/blkdev.h:1232
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff813b0ed6)
Location: include/linux/blkdev.h:1232
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
```
</details>
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013cad4)
Location: include/linux/blkdev.h:1193
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule_prepare
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffff8000103cb658)
Location: include/linux/blkdev.h:1193
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
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
In kernel/sched/core.c (c038ce08)
Location: include/linux/blkdev.h:1193
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule_prepare
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (0)
Location: include/linux/blkdev.h:1193
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
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
In kernel/sched/core.c (c00000000018b198)
Location: include/linux/blkdev.h:1193
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule_prepare
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (c0000000004cd304)
Location: include/linux/blkdev.h:1193
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
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
In kernel/sched/core.c (ffffffe0000ec100)
Location: include/linux/blkdev.h:1193
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule_prepare
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffe0002894a0)
Location: include/linux/blkdev.h:1193
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
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
In kernel/sched/core.c (ffffffff810d7235)
Location: include/linux/blkdev.h:1193
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule_prepare
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff8130d9dd)
Location: include/linux/blkdev.h:1193
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
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
In kernel/sched/core.c (ffffffff810c5b25)
Location: include/linux/blkdev.h:1193
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule_prepare
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff812fe5ed)
Location: include/linux/blkdev.h:1193
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
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
In kernel/sched/core.c (ffffffff810d3e75)
Location: include/linux/blkdev.h:1193
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule_prepare
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff8130b7cd)
Location: include/linux/blkdev.h:1193
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
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
In kernel/sched/core.c (ffffffff810dee15)
Location: include/linux/blkdev.h:1193
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule_prepare
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff8131cfed)
Location: include/linux/blkdev.h:1193
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
```
</details>
</li>
</ul>

## Differences
