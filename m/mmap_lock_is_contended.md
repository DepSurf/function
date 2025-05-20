# Function: <code>mmap_lock_is_contended</code>

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
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813c9122)
Location: include/linux/mmap_lock.h:174
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
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
In kernel/bpf/task_iter.c (ffffffff8121bfae)
Location: include/linux/mmap_lock.h:174
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In fs/proc/task_mmu.c (ffffffff813d01ef)
Location: include/linux/mmap_lock.h:174
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
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
In kernel/bpf/task_iter.c (ffffffff81252eae)
Location: include/linux/mmap_lock.h:165
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In fs/proc/task_mmu.c (ffffffff8142180f)
Location: include/linux/mmap_lock.h:165
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
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
In kernel/bpf/task_iter.c (ffffffff8129b03e)
Location: include/linux/mmap_lock.h:165
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In fs/proc/task_mmu.c (ffffffff81498667)
Location: include/linux/mmap_lock.h:165
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
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
In kernel/bpf/task_iter.c (ffffffff812f7374)
Location: include/linux/mmap_lock.h:165
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In fs/proc/task_mmu.c (ffffffff8152c9b9)
Location: include/linux/mmap_lock.h:165
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
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
In kernel/bpf/task_iter.c (ffffffff81325244)
Location: include/linux/mmap_lock.h:184
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In fs/proc/task_mmu.c (ffffffff815657cb)
Location: include/linux/mmap_lock.h:184
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
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
In kernel/bpf/task_iter.c (ffffffff81349454)
Location: include/linux/mmap_lock.h:182
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In fs/proc/task_mmu.c (ffffffff8159c99d)
Location: include/linux/mmap_lock.h:182
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
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
