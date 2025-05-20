# Function: <code>do_vmi_munmap</code>

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
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_vmi_munmap(struct vma_iterator *vmi, struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf, bool unlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813fde60)
Location: mm/mmap.c:2596
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_munmap
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff813fde60-ffffffff813fdfe7: do_vmi_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_vmi_munmap(struct vma_iterator *vmi, struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf, bool unlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8142a240)
Location: mm/mmap.c:2678
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_munmap
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff8142a240-ffffffff8142a3c7: do_vmi_munmap (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
