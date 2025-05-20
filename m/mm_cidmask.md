# Function: <code>mm_cidmask</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f15a6)
Location: include/linux/mm_types.h:980
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/sched/core.c (ffffffff81152356)
Location: include/linux/mm_types.h:980
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_mm_cid_before_execve
  - kernel/sched/core.c:task_mm_cid_work
  - kernel/sched/core.c:sched_mm_cid_remote_clear
  - kernel/sched/core.c:sched_mm_cid_migrate_to
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
```
```
In fs/exec.c (ffffffff814b888a)
Location: include/linux/mm_types.h:980
Inline: True
Inline callers:
  - fs/exec.c:mm_init_cid
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
In kernel/fork.c (ffffffff810fa988)
Location: include/linux/mm_types.h:1122
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/sched/core.c (ffffffff8115e208)
Location: include/linux/mm_types.h:1122
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_mm_cid_before_execve
  - kernel/sched/core.c:task_mm_cid_work
  - kernel/sched/core.c:sched_mm_cid_remote_clear
  - kernel/sched/core.c:sched_mm_cid_migrate_to
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
```
```
In fs/exec.c (ffffffff814ead9a)
Location: include/linux/mm_types.h:1122
Inline: True
Inline callers:
  - fs/exec.c:mm_init_cid
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
