# Function: <code>__add_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __add_pages(int nid, struct zone *zone, long unsigned int phys_start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff818195c0)
Location: mm/memory_hotplug.c:502
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_add_memory
```
**Symbols:**

```
ffffffff818195c0-ffffffff81819846: __add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __add_pages(int nid, struct zone *zone, long unsigned int phys_start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81893110)
Location: mm/memory_hotplug.c:542
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_add_memory
```
**Symbols:**

```
ffffffff81893110-ffffffff8189343a: __add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __add_pages(int nid, struct zone *zone, long unsigned int phys_start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff818c7960)
Location: mm/memory_hotplug.c:528
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_add_memory
```
**Symbols:**

```
ffffffff818c7960-ffffffff818c7c8d: __add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __add_pages(int nid, long unsigned int phys_start_pfn, long unsigned int nr_pages, bool want_memblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff818ff0a0)
Location: mm/memory_hotplug.c:288
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_add_memory
```
**Symbols:**

```
ffffffff818ff0a0-ffffffff818ff2d5: __add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __add_pages(int nid, long unsigned int phys_start_pfn, long unsigned int nr_pages, bool want_memblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81989200)
Location: mm/memory_hotplug.c:296
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:add_pages
```
**Symbols:**

```
ffffffff81989200-ffffffff819893e1: __add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __add_pages(int nid, long unsigned int phys_start_pfn, long unsigned int nr_pages, struct vmem_altmap *altmap, bool want_memblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff819e5cc0)
Location: mm/memory_hotplug.c:275
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:add_pages
```
**Symbols:**

```
ffffffff819e5cc0-ffffffff819e5e2c: __add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __add_pages(int nid, long unsigned int phys_start_pfn, long unsigned int nr_pages, struct vmem_altmap *altmap, bool want_memblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a21030)
Location: mm/memory_hotplug.c:275
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:add_pages
```
**Symbols:**

```
ffffffff81a21030-ffffffff81a211bc: __add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __add_pages(int nid, long unsigned int pfn, long unsigned int nr_pages, struct mhp_restrictions *restrictions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a91750)
Location: mm/memory_hotplug.c:289
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:add_pages
```
**Symbols:**

```
ffffffff81a91750-ffffffff81a91870: __add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __add_pages(int nid, long unsigned int pfn, long unsigned int nr_pages, struct mhp_restrictions *restrictions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81ac8ad0)
Location: mm/memory_hotplug.c:289
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:add_pages
```
**Symbols:**

```
ffffffff81ac8ad0-ffffffff81ac8bf3: __add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __add_pages(int nid, long unsigned int pfn, long unsigned int nr_pages, struct mhp_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81bc14b0)
Location: mm/memory_hotplug.c:311
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:add_pages
```
**Symbols:**

```
ffffffff81bc14b0-ffffffff81bc15ea: __add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __add_pages(int nid, long unsigned int pfn, long unsigned int nr_pages, struct mhp_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81c3a4b0)
Location: mm/memory_hotplug.c:311
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:add_pages
```
**Symbols:**

```
ffffffff81c3a4b0-ffffffff81c3a5ea: __add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __add_pages(int nid, long unsigned int pfn, long unsigned int nr_pages, struct mhp_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81c2ca90)
Location: mm/memory_hotplug.c:356
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:add_pages
```
**Symbols:**

```
ffffffff81c2ca90-ffffffff81c2cbc1: __add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __add_pages(int nid, long unsigned int pfn, long unsigned int nr_pages, struct mhp_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81d4b1f0)
Location: mm/memory_hotplug.c:305
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:add_pages
```
**Symbols:**

```
ffffffff81d4b1f0-ffffffff81d4b33a: __add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __add_pages(int nid, long unsigned int pfn, long unsigned int nr_pages, struct mhp_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81f1aac0)
Location: mm/memory_hotplug.c:315
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:add_pages
```
**Symbols:**

```
ffffffff81f1aac0-ffffffff81f1abf9: __add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __add_pages(int nid, long unsigned int pfn, long unsigned int nr_pages, struct mhp_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff820c2970)
Location: mm/memory_hotplug.c:302
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:add_pages
```
**Symbols:**

```
ffffffff820c2970-ffffffff820c2aa9: __add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __add_pages(int nid, long unsigned int pfn, long unsigned int nr_pages, struct mhp_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff82146710)
Location: mm/memory_hotplug.c:301
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:add_pages
```
**Symbols:**

```
ffffffff82146710-ffffffff82146849: __add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __add_pages(int nid, long unsigned int pfn, long unsigned int nr_pages, struct mhp_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff82228ea0)
Location: mm/memory_hotplug.c:369
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:add_pages
```
**Symbols:**

```
ffffffff82228ea0-ffffffff82228fd6: __add_pages (STB_GLOBAL)
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
int __add_pages(int nid, long unsigned int pfn, long unsigned int nr_pages, struct mhp_restrictions *restrictions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffff800010d9c690)
Location: mm/memory_hotplug.c:289
Inline: False
Direct callers:
  - arch/arm64/mm/mmu.c:arch_add_memory
```
**Symbols:**

```
ffff800010d9c690-ffff800010d9c7c0: __add_pages (STB_GLOBAL)
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
int __add_pages(int nid, long unsigned int pfn, long unsigned int nr_pages, struct mhp_restrictions *restrictions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (c00000000042f480)
Location: mm/memory_hotplug.c:289
Inline: False
Direct callers:
  - arch/powerpc/mm/mem.c:arch_add_memory
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
c00000000042f480-c00000000042f610: __add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __add_pages(int nid, long unsigned int pfn, long unsigned int nr_pages, struct mhp_restrictions *restrictions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a67940)
Location: mm/memory_hotplug.c:289
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:add_pages
```
**Symbols:**

```
ffffffff81a67940-ffffffff81a67a63: __add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __add_pages(int nid, long unsigned int pfn, long unsigned int nr_pages, struct mhp_restrictions *restrictions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a24400)
Location: mm/memory_hotplug.c:289
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:add_pages
```
**Symbols:**

```
ffffffff81a24400-ffffffff81a24523: __add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __add_pages(int nid, long unsigned int pfn, long unsigned int nr_pages, struct mhp_restrictions *restrictions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81ad3d50)
Location: mm/memory_hotplug.c:289
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:add_pages
```
**Symbols:**

```
ffffffff81ad3d50-ffffffff81ad3e73: __add_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __add_pages(int nid, long unsigned int pfn, long unsigned int nr_pages, struct mhp_restrictions *restrictions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81ae0240)
Location: mm/memory_hotplug.c:289
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:add_pages
```
**Symbols:**

```
ffffffff81ae0240-ffffffff81ae035e: __add_pages (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool want_memblock</code>
</li>
<li>
<b>Param removed. </b>
<code>struct zone *zone</code>
</li>
<li>
<b>Param reordered. </b>
<code>nid, zone, phys_start_pfn, nr_pages</code> ➡️ <code>nid, phys_start_pfn, nr_pages, want_memblock</code>
</li>
</ul>
</details>
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
<li>
<b>Param reordered. </b>
<code>nid, phys_start_pfn, nr_pages, want_memblock</code> ➡️ <code>nid, phys_start_pfn, nr_pages, altmap, want_memblock</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int pfn</code>
</li>
<li>
<b>Param added. </b>
<code>struct mhp_restrictions *restrictions</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int phys_start_pfn</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vmem_altmap *altmap</code>
</li>
<li>
<b>Param removed. </b>
<code>bool want_memblock</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mhp_params *params</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mhp_restrictions *restrictions</code>
</li>
</ul>
</details>
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
