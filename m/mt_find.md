# Function: <code>mt_find</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
void *mt_find(struct maple_tree *mt, long unsigned int *index, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff820308f0)
Location: lib/maple_tree.c:6427
Inline: False
Direct callers:
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:find_extend_vma
  - mm/mmap.c:do_mmap
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - lib/maple_tree.c:mt_find_after
```
**Symbols:**

```
ffffffff820308f0-ffffffff82030d61: mt_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *mt_find(struct maple_tree *mt, long unsigned int *index, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff820ac420)
Location: lib/maple_tree.c:6484
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_get_next_irq
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:find_extend_vma_locked
  - mm/mmap.c:do_mmap
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - lib/maple_tree.c:mt_find_after
```
**Symbols:**

```
ffffffff820ac420-ffffffff820ac64f: mt_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *mt_find(struct maple_tree *mt, long unsigned int *index, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff8218daf0)
Location: lib/maple_tree.c:6829
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_get_next_irq
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:find_extend_vma_locked
  - mm/mmap.c:do_mmap
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - lib/maple_tree.c:mt_find_after
```
**Symbols:**

```
ffffffff8218daf0-ffffffff8218dfff: mt_find (STB_GLOBAL)
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
