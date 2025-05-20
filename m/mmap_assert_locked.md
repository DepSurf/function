# Function: <code>mmap_assert_locked</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: include/linux/mmap_lock.h:78
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mmap_lock.h:78
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/linux/mmap_lock.h:78
Inline: True
```
```
In mm/hmm.c (ffffffff8130aad5)
Location: include/linux/mmap_lock.h:78
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_fault
```
```
In fs/userfaultfd.c (0)
Location: include/linux/mmap_lock.h:78
Inline: True
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
In mm/gup.c (0)
Location: include/linux/mmap_lock.h:162
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mmap_lock.h:162
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/linux/mmap_lock.h:162
Inline: True
```
```
In mm/hmm.c (ffffffff813169a5)
Location: include/linux/mmap_lock.h:162
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_fault
```
```
In fs/userfaultfd.c (0)
Location: include/linux/mmap_lock.h:162
Inline: True
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
In mm/gup.c (0)
Location: include/linux/mmap_lock.h:162
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mmap_lock.h:162
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/linux/mmap_lock.h:162
Inline: True
```
```
In mm/hmm.c (ffffffff8131cbf5)
Location: include/linux/mmap_lock.h:162
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_fault
```
```
In fs/userfaultfd.c (0)
Location: include/linux/mmap_lock.h:162
Inline: True
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
In mm/gup.c (0)
Location: include/linux/mmap_lock.h:153
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mmap_lock.h:153
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/mmap_lock.h:153
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/linux/mmap_lock.h:153
Inline: True
```
```
In mm/hmm.c (ffffffff81369f35)
Location: include/linux/mmap_lock.h:153
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_fault
```
```
In fs/userfaultfd.c (0)
Location: include/linux/mmap_lock.h:153
Inline: True
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
In mm/gup.c (0)
Location: include/linux/mmap_lock.h:153
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mmap_lock.h:153
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/mmap_lock.h:153
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/linux/mmap_lock.h:153
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/mmap_lock.h:153
Inline: True
```
```
In mm/hmm.c (ffffffff813e7d15)
Location: include/linux/mmap_lock.h:153
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_fault
```
```
In fs/userfaultfd.c (0)
Location: include/linux/mmap_lock.h:153
Inline: True
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
In mm/gup.c (0)
Location: include/linux/mmap_lock.h:153
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mmap_lock.h:153
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/mmap_lock.h:153
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/linux/mmap_lock.h:153
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/mmap_lock.h:153
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/mmap_lock.h:153
Inline: True
```
```
In mm/hmm.c (ffffffff8146fbd5)
Location: include/linux/mmap_lock.h:153
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_fault
```
```
In fs/userfaultfd.c (0)
Location: include/linux/mmap_lock.h:153
Inline: True
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
In kernel/trace/trace_events_user.c (0)
Location: include/linux/mmap_lock.h:63
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/mmap_lock.h:63
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mmap_lock.h:63
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/mmap_lock.h:63
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/linux/mmap_lock.h:63
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/mmap_lock.h:63
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/mmap_lock.h:63
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/mmap_lock.h:63
Inline: True
```
```
In mm/hmm.c (ffffffff814a43b5)
Location: include/linux/mmap_lock.h:63
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_fault
```
```
In fs/userfaultfd.c (0)
Location: include/linux/mmap_lock.h:63
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mmap_lock.h:63
Inline: True
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
In kernel/trace/trace_events_user.c (0)
Location: include/linux/mmap_lock.h:63
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/mmap_lock.h:63
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mmap_lock.h:63
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/mmap_lock.h:63
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/linux/mmap_lock.h:63
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/mmap_lock.h:63
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/mmap_lock.h:63
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/mmap_lock.h:63
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/mmap_lock.h:63
Inline: True
```
```
In mm/hmm.c (ffffffff814d51f5)
Location: include/linux/mmap_lock.h:63
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_fault
```
```
In fs/userfaultfd.c (0)
Location: include/linux/mmap_lock.h:63
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mmap_lock.h:63
Inline: True
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
