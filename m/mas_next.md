# Function: <code>mas_next</code>

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
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void *mas_next(struct ma_state *mas, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff82030e14)
Location: lib/maple_tree.c:5855
Inline: True
Inline callers:
  - lib/maple_tree.c:mt_next
Direct callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_mas_align_munmap
  - mm/mmap.c:find_vma_prev
  - mm/mempolicy.c:mbind_range
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/coredump.c:dump_vma_snapshot
```
**Symbols:**

```
ffffffff820307c0-ffffffff82030840: mas_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void *mas_next(struct ma_state *mas, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff820ac1c0)
Location: lib/maple_tree.c:5719
Inline: True
Direct callers:
  - mm/mmap.c:find_vma_prev
  - mm/mmap.c:vm_unmapped_area
  - mm/mmap.c:vm_unmapped_area
  - lib/maple_tree.c:mt_next
```
**Symbols:**

```
ffffffff820ac1c0-ffffffff820ac28d: mas_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void *mas_next(struct ma_state *mas, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff8218e0b0)
Location: lib/maple_tree.c:5704
Inline: True
Inline callers:
  - lib/maple_tree.c:mt_next
  - lib/maple_tree.c:mt_next
Direct callers:
  - mm/mmap.c:find_vma_prev
  - mm/mmap.c:vm_unmapped_area
  - mm/mmap.c:vm_unmapped_area
```
**Symbols:**

```
ffffffff8218d700-ffffffff8218d76f: mas_next (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
