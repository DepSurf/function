# Function: <code>do_vmi_align_munmap</code>

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
int do_vmi_align_munmap(struct vma_iterator *vmi, struct vm_area_struct *vma, struct mm_struct *mm, long unsigned int start, long unsigned int end, struct list_head *uf, bool unlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813fd8a0)
Location: mm/mmap.c:2429
Inline: False
Direct callers:
  - mm/mmap.c:do_vmi_munmap
  - mm/mmap.c:__do_sys_brk
```
**Symbols:**

```
ffffffff813fd8a0-ffffffff813fdde1: do_vmi_align_munmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_vmi_align_munmap(struct vma_iterator *vmi, struct vm_area_struct *vma, struct mm_struct *mm, long unsigned int start, long unsigned int end, struct list_head *uf, bool unlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81427a50)
Location: mm/mmap.c:2512
Inline: False
Direct callers:
  - mm/mmap.c:do_vmi_munmap
  - mm/mmap.c:__do_sys_brk
```
**Symbols:**

```
ffffffff81427a50-ffffffff81427ff5: do_vmi_align_munmap (STB_LOCAL)
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
