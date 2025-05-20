# Function: <code>radix_tree_exception</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (0)
Location: include/linux/radix-tree.h:243
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/radix-tree.h:243
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (0)
Location: include/linux/radix-tree.h:246
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/radix-tree.h:246
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/radix-tree.h:246
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (0)
Location: include/linux/radix-tree.h:280
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/radix-tree.h:280
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/radix-tree.h:280
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (0)
Location: include/linux/radix-tree.h:284
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/radix-tree.h:284
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/radix-tree.h:284
Inline: True
```
```
In lib/idr.c (0)
Location: include/linux/radix-tree.h:284
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (0)
Location: include/linux/radix-tree.h:283
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/radix-tree.h:283
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/radix-tree.h:283
Inline: True
```
```
In lib/idr.c (0)
Location: include/linux/radix-tree.h:283
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ece8e)
Location: include/linux/radix-tree.h:287
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/khugepaged.c (0)
Location: include/linux/radix-tree.h:287
Inline: True
```
```
In mm/memfd.c (ffffffff812941be)
Location: include/linux/radix-tree.h:287
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In lib/idr.c (ffffffff819cf5bb)
Location: include/linux/radix-tree.h:287
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_remove
  - lib/idr.c:ida_get_new_above
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
