# Function: <code>mmap_write_downgrade</code>

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
In mm/mmap.c (ffffffff8129b334)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
```
```
In fs/proc/task_mmu.c (ffffffff813b7280)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In mm/mmap.c (ffffffff812a64f4)
Location: include/linux/mmap_lock.h:108
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
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
In mm/mmap.c (ffffffff812ab817)
Location: include/linux/mmap_lock.h:108
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
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
In mm/mmap.c (ffffffff812ecea6)
Location: include/linux/mmap_lock.h:108
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
```
```
In mm/sparse-vmemmap.c (ffffffff8132c65f)
Location: include/linux/mmap_lock.h:108
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_remap_free
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
In mm/mmap.c (ffffffff81350208)
Location: include/linux/mmap_lock.h:108
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
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
In mm/mmap.c (ffffffff813c96f7)
Location: include/linux/mmap_lock.h:108
Inline: True
Inline callers:
  - mm/mmap.c:do_mas_align_munmap
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
In mm/memory.c (ffffffff813f17b1)
Location: include/linux/mmap_lock.h:138
Inline: True
Inline callers:
  - mm/memory.c:lock_mm_and_find_vma
```
```
In mm/mmap.c (ffffffff813fdd71)
Location: include/linux/mmap_lock.h:138
Inline: True
Inline callers:
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:expand_stack
```
```
In fs/exec.c (ffffffff814ba201)
Location: include/linux/mmap_lock.h:138
Inline: True
Inline callers:
  - fs/exec.c:get_arg_page
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
In mm/memory.c (ffffffff8141c491)
Location: include/linux/mmap_lock.h:136
Inline: True
Inline callers:
  - mm/memory.c:lock_mm_and_find_vma
```
```
In mm/mmap.c (ffffffff81427f6d)
Location: include/linux/mmap_lock.h:136
Inline: True
Inline callers:
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:expand_stack
```
```
In fs/exec.c (ffffffff814ec781)
Location: include/linux/mmap_lock.h:136
Inline: True
Inline callers:
  - fs/exec.c:get_arg_page
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
