# Function: <code>bdi_has_dirty_io</code>

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
In mm/page-writeback.c (ffffffff8119b590)
Location: include/linux/backing-dev.h:48
Inline: True
Inline callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
```
```
In fs/fs-writeback.c (ffffffff81239c27)
Location: include/linux/backing-dev.h:48
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:wakeup_flusher_threads
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
In mm/page-writeback.c (ffffffff811b0640)
Location: include/linux/backing-dev.h:49
Inline: True
Inline callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
```
```
In fs/fs-writeback.c (ffffffff81261be7)
Location: include/linux/backing-dev.h:49
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
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
In mm/page-writeback.c (ffffffff811c0c30)
Location: include/linux/backing-dev.h:49
Inline: True
Inline callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
```
```
In fs/fs-writeback.c (ffffffff812750e7)
Location: include/linux/backing-dev.h:49
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
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
In mm/page-writeback.c (ffffffff811c8d87)
Location: include/linux/backing-dev.h:57
Inline: True
Inline callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
```
```
In fs/fs-writeback.c (ffffffff81282653)
Location: include/linux/backing-dev.h:57
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:wakeup_flusher_threads
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
In fs/fs-writeback.c (ffffffff812a51d3)
Location: include/linux/backing-dev.h:56
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
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
In fs/fs-writeback.c (ffffffff812cc090)
Location: include/linux/backing-dev.h:57
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
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
In fs/fs-writeback.c (ffffffff812e0fd0)
Location: include/linux/backing-dev.h:57
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
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
In fs/fs-writeback.c (ffffffff812ff6d3)
Location: include/linux/backing-dev.h:58
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
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
In fs/fs-writeback.c (ffffffff813145ea)
Location: include/linux/backing-dev.h:62
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
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
In fs/fs-writeback.c (ffffffff8134ec6c)
Location: include/linux/backing-dev.h:58
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
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
In fs/fs-writeback.c (ffffffff8135baec)
Location: include/linux/backing-dev.h:58
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
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
In fs/fs-writeback.c (ffffffff813626fc)
Location: include/linux/backing-dev.h:58
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
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
In fs/fs-writeback.c (ffffffff813b0efc)
Location: include/linux/backing-dev.h:58
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
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
In fs/fs-writeback.c (ffffffff81435d90)
Location: include/linux/backing-dev.h:56
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
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
In fs/fs-writeback.c (ffffffff814c3d9a)
Location: include/linux/backing-dev.h:56
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
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
In fs/fs-writeback.c (ffffffff814f918a)
Location: include/linux/backing-dev.h:56
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
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
In fs/fs-writeback.c (ffffffff8152d9ea)
Location: include/linux/backing-dev.h:55
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
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
In fs/fs-writeback.c (ffff8000103ca438)
Location: include/linux/backing-dev.h:62
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
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
In fs/fs-writeback.c (c05a6a7c)
Location: include/linux/backing-dev.h:62
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
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
In fs/fs-writeback.c (c0000000004cbd60)
Location: include/linux/backing-dev.h:62
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
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
In fs/fs-writeback.c (ffffffe00028864c)
Location: include/linux/backing-dev.h:62
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
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
In fs/fs-writeback.c (ffffffff8130cbca)
Location: include/linux/backing-dev.h:62
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
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
In fs/fs-writeback.c (ffffffff812fd7ea)
Location: include/linux/backing-dev.h:62
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
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
In fs/fs-writeback.c (ffffffff8130a9ba)
Location: include/linux/backing-dev.h:62
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
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
In fs/fs-writeback.c (ffffffff8131c0ea)
Location: include/linux/backing-dev.h:62
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
```
</details>
</li>
</ul>

## Differences
