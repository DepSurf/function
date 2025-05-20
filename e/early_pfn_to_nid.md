# Function: <code>early_pfn_to_nid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int early_pfn_to_nid(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8181cdc6)
Location: mm/page_alloc.c:1032
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - mm/sparse.c:node_memmap_size_bytes
```
**Symbols:**

```
ffffffff8181cdc6-ffffffff8181ce06: early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int early_pfn_to_nid(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81897010)
Location: mm/page_alloc.c:1262
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - mm/sparse.c:node_memmap_size_bytes
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
**Symbols:**

```
ffffffff81897010-ffffffff81897068: early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int early_pfn_to_nid(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff818cb75a)
Location: mm/page_alloc.c:1278
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
  - mm/sparse.c:node_memmap_size_bytes
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
**Symbols:**

```
ffffffff818cb75a-ffffffff818cb7b4: early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int early_pfn_to_nid(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81902d29)
Location: mm/page_alloc.c:1283
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
  - mm/sparse.c:node_memmap_size_bytes
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
**Symbols:**

```
ffffffff81902d29-ffffffff81902d83: early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int early_pfn_to_nid(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8198cc6c)
Location: mm/page_alloc.c:1299
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
  - mm/sparse.c:node_memmap_size_bytes
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
**Symbols:**

```
ffffffff8198cc6c-ffffffff8198ccc6: early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int early_pfn_to_nid(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff819e94fa)
Location: mm/page_alloc.c:1280
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
  - mm/sparse.c:sparse_early_usemaps_alloc_node
  - mm/sparse-vmemmap.c:vmemmap_verify
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
**Symbols:**

```
ffffffff819e94fa-ffffffff819e9552: early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int early_pfn_to_nid(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a24f0a)
Location: mm/page_alloc.c:1331
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
  - mm/sparse.c:sparse_init_nid
  - mm/sparse-vmemmap.c:vmemmap_verify
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
**Symbols:**

```
ffffffff81a24f0a-ffffffff81a24f62: early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int early_pfn_to_nid(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a952f2)
Location: mm/page_alloc.c:1455
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
  - mm/sparse.c:sparse_init_nid
  - mm/sparse-vmemmap.c:vmemmap_verify
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
**Symbols:**

```
ffffffff81a952f2-ffffffff81a95350: early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int early_pfn_to_nid(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81accbd5)
Location: mm/page_alloc.c:1442
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
  - mm/sparse.c:sparse_init_nid
  - mm/sparse-vmemmap.c:vmemmap_verify
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
**Symbols:**

```
ffffffff81accbd5-ffffffff81accc33: early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int early_pfn_to_nid(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81bc5539)
Location: mm/page_alloc.c:1521
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
  - mm/sparse.c:sparse_init_nid
  - mm/sparse-vmemmap.c:vmemmap_verify
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
**Symbols:**

```
ffffffff81bc5539-ffffffff81bc5597: early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int early_pfn_to_nid(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81c3e448)
Location: mm/page_alloc.c:1604
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
  - mm/sparse.c:sparse_init_nid
  - mm/sparse-vmemmap.c:vmemmap_verify
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
**Symbols:**

```
ffffffff81c3e448-ffffffff81c3e510: early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int early_pfn_to_nid(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81c306d0)
Location: mm/page_alloc.c:1639
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/sparse.c:sparse_init_nid
  - mm/sparse-vmemmap.c:vmemmap_verify
```
**Symbols:**

```
ffffffff81c306d0-ffffffff81c30796: early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int early_pfn_to_nid(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81d4eef9)
Location: mm/page_alloc.c:1725
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
  - mm/sparse.c:sparse_init_nid
  - mm/sparse-vmemmap.c:vmemmap_verify
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
**Symbols:**

```
ffffffff81d4eef9-ffffffff81d4efbf: early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int early_pfn_to_nid(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81f1edd7)
Location: mm/page_alloc.c:1708
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init_nid
  - mm/sparse-vmemmap.c:vmemmap_verify
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
**Symbols:**

```
ffffffff81f1edd7-ffffffff81f1eea9: early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int early_pfn_to_nid(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff820c7d30)
Location: mm/page_alloc.c:1789
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init_nid
  - mm/sparse-vmemmap.c:vmemmap_verify
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
**Symbols:**

```
ffffffff820c7d30-ffffffff820c7e09: early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int early_pfn_to_nid(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff8214bd30)
Location: mm/mm_init.c:608
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
  - mm/sparse.c:sparse_init_nid
  - mm/sparse-vmemmap.c:vmemmap_verify
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
**Symbols:**

```
ffffffff8214bd30-ffffffff8214be09: early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int early_pfn_to_nid(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff8222e7e0)
Location: mm/mm_init.c:618
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
  - mm/sparse.c:sparse_init_nid
  - mm/sparse-vmemmap.c:vmemmap_verify
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
**Symbols:**

```
ffffffff8222e7e0-ffffffff8222e8b9: early_pfn_to_nid (STB_GLOBAL)
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
int early_pfn_to_nid(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010d9fb58)
Location: mm/page_alloc.c:1442
Inline: False
Direct callers:
  - arch/arm64/mm/numa.c:numa_init
  - mm/sparse-vmemmap.c:vmemmap_verify
```
**Symbols:**

```
ffff800010d9fb58-ffff800010d9fbcc: early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int early_pfn_to_nid(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c000000000eec530)
Location: mm/page_alloc.c:1442
Inline: False
Direct callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:radix__vmemmap_create_mapping
  - arch/powerpc/mm/numa.c:initmem_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse-vmemmap.c:vmemmap_verify
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
**Symbols:**

```
c000000000eec530-c000000000eec5e8: early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int early_pfn_to_nid(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe000046f7c)
Location: mm/page_alloc.c:1442
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_verify
```
**Symbols:**

```
ffffffe000046f7c-ffffffe000046fd0: early_pfn_to_nid (STB_GLOBAL)
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
int early_pfn_to_nid(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a6ba45)
Location: mm/page_alloc.c:1442
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
  - mm/sparse.c:sparse_init_nid
  - mm/sparse-vmemmap.c:vmemmap_verify
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
**Symbols:**

```
ffffffff81a6ba45-ffffffff81a6baa3: early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int early_pfn_to_nid(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a27f8c)
Location: mm/page_alloc.c:1442
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
  - mm/sparse.c:sparse_init_nid
  - mm/sparse-vmemmap.c:vmemmap_verify
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
**Symbols:**

```
ffffffff81a27f8c-ffffffff81a27fea: early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int early_pfn_to_nid(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81ad7e55)
Location: mm/page_alloc.c:1442
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
  - mm/sparse.c:sparse_init_nid
  - mm/sparse-vmemmap.c:vmemmap_verify
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
**Symbols:**

```
ffffffff81ad7e55-ffffffff81ad7eb3: early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int early_pfn_to_nid(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81ae4315)
Location: mm/page_alloc.c:1442
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
  - mm/sparse.c:sparse_init_nid
  - mm/sparse-vmemmap.c:vmemmap_verify
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
**Symbols:**

```
ffffffff81ae4315-ffffffff81ae4373: early_pfn_to_nid (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
