# Function: <code>sparse_mem_map_populate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *sparse_mem_map_populate(long unsigned int pnum, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff8181f5b3)
Location: mm/sparse-vmemmap.c:179
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
**Symbols:**

```
ffffffff8181f5b3-ffffffff8181f5e9: sparse_mem_map_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *sparse_mem_map_populate(long unsigned int pnum, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81899ca6)
Location: mm/sparse-vmemmap.c:251
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
**Symbols:**

```
ffffffff81899ca6-ffffffff81899cde: sparse_mem_map_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *sparse_mem_map_populate(long unsigned int pnum, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff818ce358)
Location: mm/sparse-vmemmap.c:251
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
**Symbols:**

```
ffffffff818ce358-ffffffff818ce38a: sparse_mem_map_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *sparse_mem_map_populate(long unsigned int pnum, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81905814)
Location: mm/sparse-vmemmap.c:267
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
**Symbols:**

```
ffffffff81905814-ffffffff81905846: sparse_mem_map_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *sparse_mem_map_populate(long unsigned int pnum, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff8198f887)
Location: mm/sparse-vmemmap.c:281
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
**Symbols:**

```
ffffffff8198f887-ffffffff8198f8b9: sparse_mem_map_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *sparse_mem_map_populate(long unsigned int pnum, int nid, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff819ec0ef)
Location: mm/sparse-vmemmap.c:259
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
**Symbols:**

```
ffffffff819ec0ef-ffffffff819ec126: sparse_mem_map_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *sparse_mem_map_populate(long unsigned int pnum, int nid, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81a2735d)
Location: mm/sparse-vmemmap.c:248
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff81a2735d-ffffffff81a27394: sparse_mem_map_populate (STB_GLOBAL)
```
</details>
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vmem_altmap *altmap</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
