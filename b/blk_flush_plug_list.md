# Function: <code>blk_flush_plug_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_flush_plug_list(struct blk_plug *plug, bool from_schedule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813bb530)
Location: block/blk-core.c:3247
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/core.c:schedule
  - fs/fs-writeback.c:writeback_sb_inodes
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_poll
  - block/blk-mq.c:blk_sq_make_request
```
**Symbols:**

```
ffffffff813bb530-ffffffff813bb76a: blk_flush_plug_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_flush_plug_list(struct blk_plug *plug, bool from_schedule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813ff330)
Location: block/blk-core.c:3219
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/core.c:schedule
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:writeback_sb_inodes
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_sq_make_request
```
**Symbols:**

```
ffffffff813ff330-ffffffff813ff589: blk_flush_plug_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_flush_plug_list(struct blk_plug *plug, bool from_schedule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81418d50)
Location: block/blk-core.c:3219
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/core.c:schedule
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:writeback_sb_inodes
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_sq_make_request
```
**Symbols:**

```
ffffffff81418d50-ffffffff81418fa8: blk_flush_plug_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_flush_plug_list(struct blk_plug *plug, bool from_schedule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81426c60)
Location: block/blk-core.c:3324
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule_prepare
  - kernel/sched/core.c:schedule
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:writeback_sb_inodes
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81426c60-ffffffff81426ec2: blk_flush_plug_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_flush_plug_list(struct blk_plug *plug, bool from_schedule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81451c70)
Location: block/blk-core.c:3548
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule_prepare
  - kernel/sched/core.c:schedule
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:writeback_sb_inodes
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81451c70-ffffffff81451ed5: blk_flush_plug_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_flush_plug_list(struct blk_plug *plug, bool from_schedule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81484ed0)
Location: block/blk-core.c:3685
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule_prepare
  - kernel/sched/core.c:schedule
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:writeback_sb_inodes
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81484ed0-ffffffff814850f7: blk_flush_plug_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_flush_plug_list(struct blk_plug *plug, bool from_schedule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149fd70)
Location: block/blk-core.c:1772
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule_prepare
  - kernel/sched/core.c:schedule
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:writeback_sb_inodes
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff8149fd70-ffffffff8149fe75: blk_flush_plug_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_flush_plug_list(struct blk_plug *plug, bool from_schedule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cddc0)
Location: block/blk-core.c:1723
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule_prepare
  - kernel/sched/core.c:schedule
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:writeback_sb_inodes
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814cddc0-ffffffff814cdec6: blk_flush_plug_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_flush_plug_list(struct blk_plug *plug, bool from_schedule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e70e0)
Location: block/blk-core.c:1764
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule_prepare
  - kernel/sched/core.c:schedule
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:writeback_sb_inodes
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814e70e0-ffffffff814e71e6: blk_flush_plug_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_flush_plug_list(struct blk_plug *plug, bool from_schedule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81546060)
Location: block/blk-core.c:1855
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/core.c:schedule
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:writeback_sb_inodes
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81546060-ffffffff81546160: blk_flush_plug_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_flush_plug_list(struct blk_plug *plug, bool from_schedule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81561e90)
Location: block/blk-core.c:1750
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/core.c:schedule
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:writeback_sb_inodes
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff81561e90-ffffffff81561f90: blk_flush_plug_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_flush_plug_list(struct blk_plug *plug, bool from_schedule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8156a5f0)
Location: block/blk-core.c:1742
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/core.c:schedule
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:writeback_sb_inodes
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff8156a5f0-ffffffff8156a6f0: blk_flush_plug_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_flush_plug_list(struct blk_plug *plug, bool from_schedule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815ceaf0)
Location: block/blk-core.c:1728
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/core.c:schedule
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:writeback_sb_inodes
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff815ceaf0-ffffffff815cebf0: blk_flush_plug_list (STB_GLOBAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void blk_flush_plug_list(struct blk_plug *plug, bool from_schedule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e4ac8)
Location: block/blk-core.c:1764
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule_prepare
  - kernel/sched/core.c:schedule
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:writeback_sb_inodes
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffff8000105e4ac8-ffff8000105e4bdc: blk_flush_plug_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_flush_plug_list(struct blk_plug *plug, bool from_schedule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c0791cec)
Location: block/blk-core.c:1764
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule_prepare
  - kernel/sched/core.c:schedule
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:writeback_sb_inodes
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
c0791cec-c0791df0: blk_flush_plug_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_flush_plug_list(struct blk_plug *plug, bool from_schedule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000778a40)
Location: block/blk-core.c:1764
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule_prepare
  - kernel/sched/core.c:schedule
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:writeback_sb_inodes
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
c000000000778a40-c000000000778bd4: blk_flush_plug_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_flush_plug_list(struct blk_plug *plug, bool from_schedule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe00042618e)
Location: block/blk-core.c:1764
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule_prepare
  - kernel/sched/core.c:schedule
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:writeback_sb_inodes
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffe00042618e-ffffffe000426240: blk_flush_plug_list (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void blk_flush_plug_list(struct blk_plug *plug, bool from_schedule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814df6c0)
Location: block/blk-core.c:1764
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule_prepare
  - kernel/sched/core.c:schedule
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:writeback_sb_inodes
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814df6c0-ffffffff814df7c6: blk_flush_plug_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_flush_plug_list(struct blk_plug *plug, bool from_schedule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814d0060)
Location: block/blk-core.c:1764
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule_prepare
  - kernel/sched/core.c:schedule
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:writeback_sb_inodes
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814d0060-ffffffff814d0166: blk_flush_plug_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_flush_plug_list(struct blk_plug *plug, bool from_schedule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814db750)
Location: block/blk-core.c:1764
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule_prepare
  - kernel/sched/core.c:schedule
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:writeback_sb_inodes
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814db750-ffffffff814db856: blk_flush_plug_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_flush_plug_list(struct blk_plug *plug, bool from_schedule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f45c0)
Location: block/blk-core.c:1764
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule_prepare
  - kernel/sched/core.c:schedule
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:writeback_sb_inodes
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814f45c0-ffffffff814f46c6: blk_flush_plug_list (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
