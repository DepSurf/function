# Function: <code>offline_mem_sections</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8121f3d0)
Location: mm/sparse.c:647
Inline: False
Direct callers:
  - mm/page_alloc.c:__offline_isolated_pages
```
**Symbols:**

```
ffffffff8121f3d0-ffffffff8121f434: offline_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8123a600)
Location: mm/sparse.c:659
Inline: False
Direct callers:
  - mm/page_alloc.c:__offline_isolated_pages
```
**Symbols:**

```
ffffffff8123a600-ffffffff8123a6a8: offline_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8125dbc0)
Location: mm/sparse.c:625
Inline: False
Direct callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
```
**Symbols:**

```
ffffffff8125dbc0-ffffffff8125dc2b: offline_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81272450)
Location: mm/sparse.c:560
Inline: False
Direct callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
```
**Symbols:**

```
ffffffff81272450-ffffffff812724bb: offline_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/sparse.c (0)
Location: mm/sparse.c:616
Inline: False
Direct callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
```
**Symbols:**

```
ffffffff8128dda7-ffffffff8128ddc2: offline_mem_sections.cold (STB_LOCAL)
ffffffff8128dc60-ffffffff8128dcdc: offline_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8129d970)
Location: mm/sparse.c:628
Inline: False
Direct callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
```
**Symbols:**

```
ffffffff8129d970-ffffffff8129d9da: offline_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812d1610)
Location: mm/sparse.c:625
Inline: False
Direct callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
```
**Symbols:**

```
ffffffff812d1610-ffffffff812d167a: offline_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812dd130)
Location: mm/sparse.c:628
Inline: False
Direct callers:
  - mm/page_alloc.c:__offline_isolated_pages
```
**Symbols:**

```
ffffffff812dd130-ffffffff812dd19a: offline_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812e4980)
Location: mm/sparse.c:637
Inline: False
Direct callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/memory_hotplug.c:mhp_deinit_memmap_on_memory
```
**Symbols:**

```
ffffffff812e4980-ffffffff812e49e9: offline_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8132bc00)
Location: mm/sparse.c:610
Inline: False
Direct callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/memory_hotplug.c:mhp_deinit_memmap_on_memory
```
**Symbols:**

```
ffffffff8132bc00-ffffffff8132bc69: offline_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8139b8e0)
Location: mm/sparse.c:611
Inline: False
Direct callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/memory_hotplug.c:mhp_deinit_memmap_on_memory
```
**Symbols:**

```
ffffffff8139b8e0-ffffffff8139b983: offline_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8141b960)
Location: mm/sparse.c:611
Inline: False
Direct callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/memory_hotplug.c:mhp_deinit_memmap_on_memory
```
**Symbols:**

```
ffffffff8141b960-ffffffff8141ba08: offline_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8144ef00)
Location: mm/sparse.c:611
Inline: False
Direct callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/memory_hotplug.c:mhp_deinit_memmap_on_memory
```
**Symbols:**

```
ffffffff8144ef00-ffffffff8144efa8: offline_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81488ac0)
Location: mm/sparse.c:610
Inline: False
Direct callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/memory_hotplug.c:mhp_deinit_memmap_on_memory
```
**Symbols:**

```
ffffffff81488ac0-ffffffff81488b68: offline_mem_sections (STB_GLOBAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (c000000000417c00)
Location: mm/sparse.c:628
Inline: False
Direct callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
```
**Symbols:**

```
c000000000417c00-c000000000417ca8: offline_mem_sections (STB_GLOBAL)
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
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81295f50)
Location: mm/sparse.c:628
Inline: False
Direct callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
```
**Symbols:**

```
ffffffff81295f50-ffffffff81295fba: offline_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81287b60)
Location: mm/sparse.c:628
Inline: False
Direct callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
```
**Symbols:**

```
ffffffff81287b60-ffffffff81287bca: offline_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81293d60)
Location: mm/sparse.c:628
Inline: False
Direct callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
```
**Symbols:**

```
ffffffff81293d60-ffffffff81293dca: offline_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812a3bc0)
Location: mm/sparse.c:628
Inline: False
Direct callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
```
**Symbols:**

```
ffffffff812a3bc0-ffffffff812a3c2a: offline_mem_sections (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
