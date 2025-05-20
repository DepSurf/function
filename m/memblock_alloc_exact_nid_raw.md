# Function: <code>memblock_alloc_exact_nid_raw</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *memblock_alloc_exact_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82cfcbee)
Location: mm/memblock.c:1519
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff82cfcbee-ffffffff82cfcc68: memblock_alloc_exact_nid_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *memblock_alloc_exact_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82fe9671)
Location: mm/memblock.c:1481
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff82fe9671-ffffffff82fe96eb: memblock_alloc_exact_nid_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *memblock_alloc_exact_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff831f3d1a)
Location: mm/memblock.c:1482
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff831f3d1a-ffffffff831f3d94: memblock_alloc_exact_nid_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *memblock_alloc_exact_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff832da060)
Location: mm/memblock.c:1517
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_alloc
```
**Symbols:**

```
ffffffff832da060-ffffffff832da0da: memblock_alloc_exact_nid_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *memblock_alloc_exact_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8348f0ba)
Location: mm/memblock.c:1524
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_alloc
```
**Symbols:**

```
ffffffff8348f0ba-ffffffff8348f146: memblock_alloc_exact_nid_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *memblock_alloc_exact_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff83ec1560)
Location: mm/memblock.c:1542
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_alloc
```
**Symbols:**

```
ffffffff83ec1560-ffffffff83ec15ed: memblock_alloc_exact_nid_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *memblock_alloc_exact_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff836e6d70)
Location: mm/memblock.c:1564
Inline: False
Direct callers:
  - mm/mm_init.c:memmap_alloc
```
**Symbols:**

```
ffffffff836e6d70-ffffffff836e6dfd: memblock_alloc_exact_nid_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *memblock_alloc_exact_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff83919320)
Location: mm/memblock.c:1622
Inline: False
Direct callers:
  - mm/mm_init.c:memmap_alloc
```
**Symbols:**

```
ffffffff83919320-ffffffff839193ad: memblock_alloc_exact_nid_raw (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
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
