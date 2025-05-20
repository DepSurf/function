# Function: <code>radix_tree_gang_lookup_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup_slot(struct radix_tree_root *root, void ***results, long unsigned int *indices, long unsigned int first_index, unsigned int max_items);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff813ee800)
Location: lib/radix-tree.c:1056
Inline: False
```
**Symbols:**

```
ffffffff813ee800-ffffffff813ee8d3: radix_tree_gang_lookup_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup_slot(struct radix_tree_root *root, void ***results, long unsigned int *indices, long unsigned int first_index, unsigned int max_items);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81434900)
Location: lib/radix-tree.c:1198
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_add_to_page_cache
```
**Symbols:**

```
ffffffff81434900-ffffffff81434a20: radix_tree_gang_lookup_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup_slot(struct radix_tree_root *root, void ***results, long unsigned int *indices, long unsigned int first_index, unsigned int max_items);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81450e40)
Location: lib/radix-tree.c:1727
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_add_to_page_cache
```
**Symbols:**

```
ffffffff81450e40-ffffffff81450f3c: radix_tree_gang_lookup_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup_slot(const struct radix_tree_root *root, void ***results, long unsigned int *indices, long unsigned int first_index, unsigned int max_items);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f0a80)
Location: lib/radix-tree.c:1871
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_add_to_page_cache
```
**Symbols:**

```
ffffffff818f0a80-ffffffff818f0b7b: radix_tree_gang_lookup_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup_slot(const struct radix_tree_root *root, void ***results, long unsigned int *indices, long unsigned int first_index, unsigned int max_items);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81976ed0)
Location: lib/radix-tree.c:1869
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_add_to_page_cache
```
**Symbols:**

```
ffffffff81976ed0-ffffffff81976fcb: radix_tree_gang_lookup_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup_slot(const struct radix_tree_root *root, void ***results, long unsigned int *indices, long unsigned int first_index, unsigned int max_items);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d3670)
Location: lib/radix-tree.c:1868
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_add_to_page_cache
```
**Symbols:**

```
ffffffff819d3670-ffffffff819d376b: radix_tree_gang_lookup_slot (STB_GLOBAL)
```
</details>
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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct radix_tree_root *root</code> ➡️ <code>const struct radix_tree_root *root</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
