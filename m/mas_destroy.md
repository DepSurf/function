# Function: <code>mas_destroy</code>

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
void mas_destroy(struct ma_state *mas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff82032340)
Location: lib/maple_tree.c:5745
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:do_mas_align_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - lib/maple_tree.c:mtree_insert_range
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mas_expected_entries
  - lib/maple_tree.c:mas_preallocate
  - lib/maple_tree.c:mas_store_prealloc
```
**Symbols:**

```
ffffffff82032340-ffffffff820327b4: mas_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mas_destroy(struct ma_state *mas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff820b1300)
Location: lib/maple_tree.c:5576
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:__split_vma
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:vma_merge
  - lib/maple_tree.c:mtree_insert_range
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mas_expected_entries
  - lib/maple_tree.c:mas_preallocate
  - lib/maple_tree.c:mas_store_prealloc
```
**Symbols:**

```
ffffffff820b1300-ffffffff820b156b: mas_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mas_destroy(struct ma_state *mas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff8218e120)
Location: lib/maple_tree.c:5530
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:__split_vma
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:expand_downwards
  - lib/maple_tree.c:mtree_insert_range
  - lib/maple_tree.c:mas_expected_entries
  - lib/maple_tree.c:mas_preallocate
  - lib/maple_tree.c:mas_store_prealloc
```
**Symbols:**

```
ffffffff8218e120-ffffffff8218e578: mas_destroy (STB_GLOBAL)
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
