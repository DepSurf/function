# Function: <code>__blk_flush_plug</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
void __blk_flush_plug(struct blk_plug *plug, bool from_schedule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81679d80)
Location: block/blk-core.c:1201
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/core.c:schedule
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:writeback_sb_inodes
  - block/blk-core.c:bio_poll
```
**Symbols:**

```
ffffffff81679d80-ffffffff81679eab: __blk_flush_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __blk_flush_plug(struct blk_plug *plug, bool from_schedule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81736210)
Location: block/blk-core.c:1139
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/core.c:schedule
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:writeback_sb_inodes
  - block/blk-core.c:bio_poll
```
**Symbols:**

```
ffffffff81736210-ffffffff8173633b: __blk_flush_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __blk_flush_plug(struct blk_plug *plug, bool from_schedule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81772870)
Location: block/blk-core.c:1137
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/core.c:schedule
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:writeback_sb_inodes
  - block/blk-core.c:bio_poll
```
**Symbols:**

```
ffffffff81772870-ffffffff81772991: __blk_flush_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __blk_flush_plug(struct blk_plug *plug, bool from_schedule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b4c10)
Location: block/blk-core.c:1172
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/core.c:rt_mutex_pre_schedule
  - kernel/sched/core.c:schedule
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:writeback_sb_inodes
  - block/blk-core.c:bio_poll
```
**Symbols:**

```
ffffffff817b4c10-ffffffff817b4d31: __blk_flush_plug (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
