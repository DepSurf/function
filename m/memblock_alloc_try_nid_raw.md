# Function: <code>memblock_alloc_try_nid_raw</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828bdfc0)
Location: mm/memblock.c:1462
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/sparse.c:sparse_init_nid
  - mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc
```
**Symbols:**

```
ffffffff828bdfc0-ffffffff828be034: memblock_alloc_try_nid_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828d7241)
Location: mm/memblock.c:1503
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/sparse.c:sparse_init_nid
  - mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc
```
**Symbols:**

```
ffffffff828d7241-ffffffff828d72b5: memblock_alloc_try_nid_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828df6b2)
Location: mm/memblock.c:1503
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/sparse.c:sparse_init_nid
  - mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc
```
**Symbols:**

```
ffffffff828df6b2-ffffffff828df726: memblock_alloc_try_nid_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82cfcc68)
Location: mm/memblock.c:1557
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc
```
**Symbols:**

```
ffffffff82cfcc68-ffffffff82cfccdf: memblock_alloc_try_nid_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82fe96eb)
Location: mm/memblock.c:1519
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc
```
**Symbols:**

```
ffffffff82fe96eb-ffffffff82fe9762: memblock_alloc_try_nid_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff831f3d94)
Location: mm/memblock.c:1520
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc
```
**Symbols:**

```
ffffffff831f3d94-ffffffff831f3e0b: memblock_alloc_try_nid_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff832da0da)
Location: mm/memblock.c:1549
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:memmap_alloc
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc
```
**Symbols:**

```
ffffffff832da0da-ffffffff832da151: memblock_alloc_try_nid_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8348f146)
Location: mm/memblock.c:1556
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:memmap_alloc
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc
```
**Symbols:**

```
ffffffff8348f146-ffffffff8348f1cf: memblock_alloc_try_nid_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff83ec1600)
Location: mm/memblock.c:1574
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:memmap_alloc
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc
```
**Symbols:**

```
ffffffff83ec1600-ffffffff83ec168a: memblock_alloc_try_nid_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff836e6e10)
Location: mm/memblock.c:1596
Inline: False
Direct callers:
  - mm/mm_init.c:alloc_large_system_hash
  - mm/mm_init.c:memmap_alloc
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc
```
**Symbols:**

```
ffffffff836e6e10-ffffffff836e6e9a: memblock_alloc_try_nid_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff839193c0)
Location: mm/memblock.c:1654
Inline: False
Direct callers:
  - mm/mm_init.c:alloc_large_system_hash
  - mm/mm_init.c:memmap_alloc
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc
```
**Symbols:**

```
ffffffff839193c0-ffffffff8391944a: memblock_alloc_try_nid_raw (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void *memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffff8000114586f0)
Location: mm/memblock.c:1503
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/sparse.c:sparse_init_nid
  - mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc
```
**Symbols:**

```
ffff8000114586f0-ffff80001145877c: memblock_alloc_try_nid_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c1532638)
Location: mm/memblock.c:1503
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
**Symbols:**

```
c1532638-c15326d4: memblock_alloc_try_nid_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c000000001381ef8)
Location: mm/memblock.c:1503
Inline: False
Direct callers:
  - arch/powerpc/kernel/prom.c:early_init_devtree
  - arch/powerpc/kernel/paca.c:allocate_paca_ptrs
  - arch/powerpc/platforms/pseries/setup.c:pSeries_setup_arch
  - arch/powerpc/platforms/pseries/setup.c:pSeries_setup_arch
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
c000000001381ef8-c000000001381fa4: memblock_alloc_try_nid_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffe000016dcc)
Location: mm/memblock.c:1503
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/sparse.c:sparse_init_nid
  - mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc
```
**Symbols:**

```
ffffffe000016dcc-ffffffe000016e4e: memblock_alloc_try_nid_raw (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828c8566)
Location: mm/memblock.c:1503
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/sparse.c:sparse_init_nid
  - mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc
```
**Symbols:**

```
ffffffff828c8566-ffffffff828c85da: memblock_alloc_try_nid_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828c0c8b)
Location: mm/memblock.c:1503
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/sparse.c:sparse_init_nid
  - mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc
```
**Symbols:**

```
ffffffff828c0c8b-ffffffff828c0cff: memblock_alloc_try_nid_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828db2e6)
Location: mm/memblock.c:1503
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/sparse.c:sparse_init_nid
  - mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc
```
**Symbols:**

```
ffffffff828db2e6-ffffffff828db35a: memblock_alloc_try_nid_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828e0707)
Location: mm/memblock.c:1503
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/sparse.c:sparse_init_nid
  - mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc
```
**Symbols:**

```
ffffffff828e0707-ffffffff828e077b: memblock_alloc_try_nid_raw (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
