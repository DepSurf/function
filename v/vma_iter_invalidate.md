# Function: <code>vma_iter_invalidate</code>

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
In mm/mmap.c (ffffffff813ff023)
Location: include/linux/mm.h:938
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_expand
  - mm/mmap.c:vma_complete
  - mm/mmap.c:vma_link
```
```
In fs/proc/task_mmu.c (ffffffff815657de)
Location: include/linux/mm.h:938
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
In mm/mmap.c (ffffffff8142b53c)
Location: include/linux/mm.h:1026
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_expand
  - mm/mmap.c:vma_complete
  - mm/mmap.c:vma_link
```
```
In fs/proc/task_mmu.c (ffffffff8159c9b0)
Location: include/linux/mm.h:1026
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
