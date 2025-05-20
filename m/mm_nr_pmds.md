# Function: <code>mm_nr_pmds</code>

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
In kernel/fork.c (ffffffff8107dd43)
Location: include/linux/mm.h:1484
Inline: True
```
```
In mm/oom_kill.c (ffffffff81208be5)
Location: include/linux/mm.h:1484
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In fs/proc/task_mmu.c (ffffffff8127903e)
Location: include/linux/mm.h:1484
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:task_mem
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
In kernel/fork.c (ffffffff8107f939)
Location: include/linux/mm.h:1601
Inline: True
```
```
In mm/oom_kill.c (ffffffff8122e8be)
Location: include/linux/mm.h:1601
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812a5a6e)
Location: include/linux/mm.h:1601
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:task_mem
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
In kernel/fork.c (ffffffff81084020)
Location: include/linux/mm.h:1575
Inline: True
```
```
In mm/oom_kill.c (ffffffff81240e0a)
Location: include/linux/mm.h:1575
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812bb3be)
Location: include/linux/mm.h:1575
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:task_mem
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
In kernel/fork.c (ffffffff81080f70)
Location: include/linux/mm.h:1617
Inline: True
```
```
In mm/oom_kill.c (ffffffff811bdeeb)
Location: include/linux/mm.h:1617
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In fs/proc/task_mmu.c (ffffffff812c87f1)
Location: include/linux/mm.h:1617
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:task_mem
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
