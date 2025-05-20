# Function: <code>blk_flush_plug</code>

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
In fs/fs-writeback.c (ffffffff8123bb1e)
Location: include/linux/blkdev.h:1071
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812639c7)
Location: include/linux/blkdev.h:1095
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81276e11)
Location: include/linux/blkdev.h:1257
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8128421d)
Location: include/linux/blkdev.h:1291
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812a6d85)
Location: include/linux/blkdev.h:1306
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812cd753)
Location: include/linux/blkdev.h:1342
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
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
In fs/fs-writeback.c (ffffffff812e2a72)
Location: include/linux/blkdev.h:1144
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
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
In fs/fs-writeback.c (ffffffff81301630)
Location: include/linux/blkdev.h:1158
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
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
In fs/fs-writeback.c (ffffffff81313d10)
Location: include/linux/blkdev.h:1185
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
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
In fs/fs-writeback.c (ffffffff8134d5f0)
Location: include/linux/blkdev.h:1212
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
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
In fs/fs-writeback.c (ffffffff8135a4ee)
Location: include/linux/blkdev.h:1267
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
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
In fs/fs-writeback.c (ffffffff8136115e)
Location: include/linux/blkdev.h:1252
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
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
In fs/fs-writeback.c (ffffffff813af7c8)
Location: include/linux/blkdev.h:1224
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
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
In kernel/sched/core.c (ffffffff81f22592)
Location: include/linux/blkdev.h:1063
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff81435d65)
Location: include/linux/blkdev.h:1063
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In block/blk-core.c (ffffffff81679f07)
Location: include/linux/blkdev.h:1063
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
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
In kernel/sched/core.c (ffffffff820cce32)
Location: include/linux/blkdev.h:1011
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff814c3d73)
Location: include/linux/blkdev.h:1011
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In block/blk-core.c (ffffffff817363ad)
Location: include/linux/blkdev.h:1011
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
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
In kernel/sched/core.c (ffffffff82151242)
Location: include/linux/blkdev.h:991
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff814f9163)
Location: include/linux/blkdev.h:991
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In block/blk-core.c (ffffffff81772a0c)
Location: include/linux/blkdev.h:991
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
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
In kernel/sched/core.c (ffffffff82233ff2)
Location: include/linux/blkdev.h:969
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/core.c:rt_mutex_pre_schedule
  - kernel/sched/core.c:schedule
```
```
In fs/fs-writeback.c (ffffffff8152d9c3)
Location: include/linux/blkdev.h:969
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In block/blk-core.c (ffffffff817b4da9)
Location: include/linux/blkdev.h:969
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
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
In fs/fs-writeback.c (ffff8000103c9860)
Location: include/linux/blkdev.h:1185
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
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
In fs/fs-writeback.c (c05a5db4)
Location: include/linux/blkdev.h:1185
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
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
In fs/fs-writeback.c (c0000000004cac08)
Location: include/linux/blkdev.h:1185
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
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
In fs/fs-writeback.c (ffffffe000287da4)
Location: include/linux/blkdev.h:1185
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
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
In fs/fs-writeback.c (ffffffff8130c2f0)
Location: include/linux/blkdev.h:1185
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
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
In fs/fs-writeback.c (ffffffff812fcf10)
Location: include/linux/blkdev.h:1185
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
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
In fs/fs-writeback.c (ffffffff8130a0e0)
Location: include/linux/blkdev.h:1185
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
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
In fs/fs-writeback.c (ffffffff8131b508)
Location: include/linux/blkdev.h:1185
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
</details>
</li>
</ul>

## Differences
