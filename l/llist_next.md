# Function: <code>llist_next</code>

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
In kernel/sched/core.c (ffffffff810ac1ab)
Location: include/linux/llist.h:163
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/irq_work.c (ffffffff81170e84)
Location: include/linux/llist.h:163
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_run_list
```
```
In mm/vmalloc.c (ffffffff811cede8)
Location: include/linux/llist.h:163
Inline: True
Inline callers:
  - mm/vmalloc.c:free_work
```
```
In fs/file_table.c (ffffffff8120e668)
Location: include/linux/llist.h:163
Inline: True
Inline callers:
  - fs/file_table.c:flush_delayed_fput
```
```
In fs/namespace.c (ffffffff8122cc18)
Location: include/linux/llist.h:163
Inline: True
Inline callers:
  - fs/namespace.c:delayed_mntput
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
In kernel/sched/core.c (ffffffff810aeda6)
Location: include/linux/llist.h:163
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/irq_work.c (ffffffff8117e574)
Location: include/linux/llist.h:163
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_run_list
```
```
In mm/vmalloc.c (ffffffff811ebf78)
Location: include/linux/llist.h:163
Inline: True
Inline callers:
  - mm/vmalloc.c:free_work
```
```
In fs/file_table.c (ffffffff812350c8)
Location: include/linux/llist.h:163
Inline: True
Inline callers:
  - fs/file_table.c:flush_delayed_fput
```
```
In fs/namespace.c (ffffffff812553a8)
Location: include/linux/llist.h:163
Inline: True
Inline callers:
  - fs/namespace.c:delayed_mntput
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
In kernel/sched/core.c (ffffffff810b4ed6)
Location: include/linux/llist.h:163
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/irq_work.c (ffffffff8118a184)
Location: include/linux/llist.h:163
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_run_list
```
```
In mm/vmalloc.c (ffffffff811fd1b8)
Location: include/linux/llist.h:163
Inline: True
Inline callers:
  - mm/vmalloc.c:free_work
```
```
In fs/file_table.c (ffffffff81247c68)
Location: include/linux/llist.h:163
Inline: True
Inline callers:
  - fs/file_table.c:flush_delayed_fput
```
```
In fs/namespace.c (ffffffff812688e8)
Location: include/linux/llist.h:163
Inline: True
Inline callers:
  - fs/namespace.c:delayed_mntput
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
In kernel/irq_work.c (ffffffff8118cc94)
Location: include/linux/llist.h:204
Inline: True
```
```
In mm/vmalloc.c (ffffffff81207e98)
Location: include/linux/llist.h:204
Inline: True
Inline callers:
  - mm/vmalloc.c:free_work
```
```
In fs/file_table.c (ffffffff81253498)
Location: include/linux/llist.h:204
Inline: True
Inline callers:
  - fs/file_table.c:flush_delayed_fput
```
```
In fs/namespace.c (ffffffff81275c48)
Location: include/linux/llist.h:204
Inline: True
Inline callers:
  - fs/namespace.c:delayed_mntput
```
</details>
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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/lwq.c (ffffffff8185b8e4)
Location: include/linux/llist.h:221
Inline: True
Inline callers:
  - lib/lwq.c:__lwq_dequeue
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
