# Function: <code>mas_is_err</code>

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
bool mas_is_err(struct ma_state *mas);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff82038d1f)
Location: lib/maple_tree.c:248
Inline: True
Inline callers:
  - lib/maple_tree.c:mtree_alloc_rrange
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mtree_insert_range
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mas_expected_entries
  - lib/maple_tree.c:mas_preallocate
  - lib/maple_tree.c:mas_store_prealloc
  - lib/maple_tree.c:mas_store_gfp
  - lib/maple_tree.c:mas_empty_area_rev
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_rev_awalk
  - lib/maple_tree.c:mas_wr_modify
  - lib/maple_tree.c:mas_wr_bnode
  - lib/maple_tree.c:mas_wr_node_store
  - lib/maple_tree.c:mas_destroy_rebalance
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff820379c0-ffffffff820379e6: mas_is_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool mas_is_err(struct ma_state *mas);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff820b71fd)
Location: lib/maple_tree.c:253
Inline: True
Inline callers:
  - lib/maple_tree.c:mtree_alloc_rrange
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mtree_insert_range
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mas_expected_entries
  - lib/maple_tree.c:mas_preallocate
  - lib/maple_tree.c:mas_store_prealloc
  - lib/maple_tree.c:mas_store_gfp
  - lib/maple_tree.c:mas_empty_area_rev
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_rev_awalk
  - lib/maple_tree.c:mas_wr_modify
  - lib/maple_tree.c:mas_wr_bnode
  - lib/maple_tree.c:mas_wr_node_store
  - lib/maple_tree.c:mas_destroy_rebalance
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_vmi_align_munmap
```
**Symbols:**

```
ffffffff820b6b40-ffffffff820b6b66: mas_is_err (STB_GLOBAL)
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
In kernel/fork.c (ffffffff810fb2c6)
Location: include/linux/maple_tree.h:539
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/mmap.c (ffffffff8142b34d)
Location: include/linux/maple_tree.h:539
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_vmi_align_munmap
```
```
In lib/maple_tree.c (ffffffff821888f8)
Location: include/linux/maple_tree.h:539
Inline: True
Inline callers:
  - lib/maple_tree.c:mtree_dup
  - lib/maple_tree.c:__mt_dup
  - lib/maple_tree.c:mtree_alloc_rrange
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mtree_insert_range
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mas_erase
  - lib/maple_tree.c:mas_erase
  - lib/maple_tree.c:mas_expected_entries
  - lib/maple_tree.c:mas_preallocate
  - lib/maple_tree.c:mas_store_prealloc
  - lib/maple_tree.c:mas_store_gfp
  - lib/maple_tree.c:mas_empty_area_rev
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_rev_awalk
  - lib/maple_tree.c:mas_wr_bnode
  - lib/maple_tree.c:mas_wr_node_store
  - lib/maple_tree.c:mas_destroy_rebalance
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
</ul>
