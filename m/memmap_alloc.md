# Function: <code>memmap_alloc</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *memmap_alloc(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, int nid, bool exact_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff832d8adb)
Location: mm/page_alloc.c:6744
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff832d8adb-ffffffff832d8aff: memmap_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *memmap_alloc(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, int nid, bool exact_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8348d088)
Location: mm/page_alloc.c:6865
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff8348d088-ffffffff8348d0bb: memmap_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *memmap_alloc(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, int nid, bool exact_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff83ebef50)
Location: mm/page_alloc.c:7037
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff83ebef50-ffffffff83ebef92: memmap_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *memmap_alloc(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, int nid, bool exact_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff836e1470)
Location: mm/mm_init.c:1606
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff836e1470-ffffffff836e14b2: memmap_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *memmap_alloc(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, int nid, bool exact_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff83913d70)
Location: mm/mm_init.c:1614
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff83913d70-ffffffff83913db2: memmap_alloc (STB_GLOBAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
