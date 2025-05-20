# Function: <code>blk_needs_flush_plug</code>

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
In kernel/exit.c (ffffffff810838f9)
Location: include/linux/blkdev.h:1087
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffff81820403)
Location: include/linux/blkdev.h:1087
Inline: True
Inline callers:
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
In kernel/exit.c (ffffffff81086a19)
Location: include/linux/blkdev.h:1111
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffff8189a863)
Location: include/linux/blkdev.h:1111
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff812649f2)
Location: include/linux/blkdev.h:1111
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
In kernel/exit.c (ffffffff8108b989)
Location: include/linux/blkdev.h:1273
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffff818cee80)
Location: include/linux/blkdev.h:1273
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff81277e32)
Location: include/linux/blkdev.h:1273
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
In kernel/exit.c (ffffffff81088b19)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffff819063d0)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff8128512e)
Location: include/linux/blkdev.h:1307
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
In kernel/exit.c (ffffffff8108f849)
Location: include/linux/blkdev.h:1322
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffff8199045e)
Location: include/linux/blkdev.h:1322
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff812a7c55)
Location: include/linux/blkdev.h:1322
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
In kernel/exit.c (ffffffff810933b9)
Location: include/linux/blkdev.h:1358
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffff819ecc4e)
Location: include/linux/blkdev.h:1358
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff812ce7df)
Location: include/linux/blkdev.h:1358
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
In kernel/exit.c (ffffffff8109b679)
Location: include/linux/blkdev.h:1160
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffff81a27e9e)
Location: include/linux/blkdev.h:1160
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff812e3b1f)
Location: include/linux/blkdev.h:1160
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
In kernel/exit.c (ffffffff8109fcd9)
Location: include/linux/blkdev.h:1174
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffff81a985f6)
Location: include/linux/blkdev.h:1174
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff813022bf)
Location: include/linux/blkdev.h:1174
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
In kernel/exit.c (ffffffff810a62e9)
Location: include/linux/blkdev.h:1201
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffff81acff46)
Location: include/linux/blkdev.h:1201
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff813153cf)
Location: include/linux/blkdev.h:1201
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
In kernel/exit.c (ffffffff810ae09c)
Location: include/linux/blkdev.h:1228
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffff81bc88b9)
Location: include/linux/blkdev.h:1228
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff8134ec0f)
Location: include/linux/blkdev.h:1228
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
In kernel/exit.c (ffffffff810a974c)
Location: include/linux/blkdev.h:1283
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffff81c41680)
Location: include/linux/blkdev.h:1283
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff8135ba8f)
Location: include/linux/blkdev.h:1283
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
In kernel/exit.c (ffffffff810aa78c)
Location: include/linux/blkdev.h:1268
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffff81c335f0)
Location: include/linux/blkdev.h:1268
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff8136269f)
Location: include/linux/blkdev.h:1268
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
In kernel/exit.c (ffffffff810bc2bc)
Location: include/linux/blkdev.h:1240
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffff81d51f1f)
Location: include/linux/blkdev.h:1240
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff813b0e9f)
Location: include/linux/blkdev.h:1240
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
In kernel/exit.c (ffff8000100fd298)
Location: include/linux/blkdev.h:1201
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffff800010da1c30)
Location: include/linux/blkdev.h:1201
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffff8000103cb640)
Location: include/linux/blkdev.h:1201
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
In kernel/exit.c (c035a354)
Location: include/linux/blkdev.h:1201
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (c0e99d1c)
Location: include/linux/blkdev.h:1201
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (c05a7a48)
Location: include/linux/blkdev.h:1201
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
In kernel/exit.c (c0000000001440ac)
Location: include/linux/blkdev.h:1201
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (c000000000ee2e10)
Location: include/linux/blkdev.h:1201
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (c0000000004cd2e4)
Location: include/linux/blkdev.h:1201
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
In kernel/exit.c (ffffffe0000c5b4a)
Location: include/linux/blkdev.h:1201
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffe0008c5368)
Location: include/linux/blkdev.h:1201
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffe000289494)
Location: include/linux/blkdev.h:1201
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
In kernel/exit.c (ffffffff8109fc09)
Location: include/linux/blkdev.h:1201
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffff81a6edb6)
Location: include/linux/blkdev.h:1201
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff8130d9af)
Location: include/linux/blkdev.h:1201
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
In kernel/exit.c (ffffffff8108e639)
Location: include/linux/blkdev.h:1201
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffff81a2b196)
Location: include/linux/blkdev.h:1201
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff812fe5bf)
Location: include/linux/blkdev.h:1201
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
In kernel/exit.c (ffffffff8109fbb9)
Location: include/linux/blkdev.h:1201
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffff81adb1c6)
Location: include/linux/blkdev.h:1201
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff8130b79f)
Location: include/linux/blkdev.h:1201
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
In kernel/exit.c (ffffffff810a7b29)
Location: include/linux/blkdev.h:1201
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffff81ae7694)
Location: include/linux/blkdev.h:1201
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff8131cfbf)
Location: include/linux/blkdev.h:1201
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
```
</details>
</li>
</ul>

## Differences
