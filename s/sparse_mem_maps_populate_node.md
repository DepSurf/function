# Function: <code>sparse_mem_maps_populate_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sparse_mem_maps_populate_node(struct page **map_map, long unsigned int pnum_begin, long unsigned int pnum_end, long unsigned int map_count, int nodeid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81f8ca6a)
Location: mm/sparse-vmemmap.c:195
Inline: False
Direct callers:
  - mm/sparse.c:sparse_early_mem_maps_alloc_node
```
**Symbols:**

```
ffffffff81f8ca6a-ffffffff81f8cb99: sparse_mem_maps_populate_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sparse_mem_maps_populate_node(struct page **map_map, long unsigned int pnum_begin, long unsigned int pnum_end, long unsigned int map_count, int nodeid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81fb67ac)
Location: mm/sparse-vmemmap.c:267
Inline: False
Direct callers:
  - mm/sparse.c:sparse_early_mem_maps_alloc_node
```
**Symbols:**

```
ffffffff81fb67ac-ffffffff81fb690a: sparse_mem_maps_populate_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sparse_mem_maps_populate_node(struct page **map_map, long unsigned int pnum_begin, long unsigned int pnum_end, long unsigned int map_count, int nodeid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81ff3175)
Location: mm/sparse-vmemmap.c:267
Inline: False
Direct callers:
  - mm/sparse.c:sparse_early_mem_maps_alloc_node
```
**Symbols:**

```
ffffffff81ff3175-ffffffff81ff32d3: sparse_mem_maps_populate_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sparse_mem_maps_populate_node(struct page **map_map, long unsigned int pnum_begin, long unsigned int pnum_end, long unsigned int map_count, int nodeid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff820d58a4)
Location: mm/sparse-vmemmap.c:283
Inline: False
Direct callers:
  - mm/sparse.c:sparse_early_mem_maps_alloc_node
```
**Symbols:**

```
ffffffff820d58a4-ffffffff820d5a06: sparse_mem_maps_populate_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sparse_mem_maps_populate_node(struct page **map_map, long unsigned int pnum_begin, long unsigned int pnum_end, long unsigned int map_count, int nodeid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff826de4c9)
Location: mm/sparse-vmemmap.c:297
Inline: False
Direct callers:
  - mm/sparse.c:sparse_early_mem_maps_alloc_node
```
**Symbols:**

```
ffffffff826de4c9-ffffffff826de64e: sparse_mem_maps_populate_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sparse_mem_maps_populate_node(struct page **map_map, long unsigned int pnum_begin, long unsigned int pnum_end, long unsigned int map_count, int nodeid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff827089df)
Location: mm/sparse-vmemmap.c:276
Inline: False
Direct callers:
  - mm/sparse.c:sparse_early_mem_maps_alloc_node
```
**Symbols:**

```
ffffffff827089df-ffffffff82708b62: sparse_mem_maps_populate_node (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
