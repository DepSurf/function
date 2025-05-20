# Function: <code>__vmap_pages_range_noflush</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __vmap_pages_range_noflush(long unsigned int addr, long unsigned int end, pgprot_t prot, struct page **pages, unsigned int page_shift);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (ffffffff813e2471)
Location: mm/vmalloc.c:590
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:vm_map_ram
Direct callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
**Symbols:**

```
ffffffff82064bf0-ffffffff82064c68: __vmap_pages_range_noflush.cold (STB_LOCAL)
ffffffff813e1a60-ffffffff813e1ba5: __vmap_pages_range_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __vmap_pages_range_noflush(long unsigned int addr, long unsigned int end, pgprot_t prot, struct page **pages, unsigned int page_shift);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (ffffffff81416cf6)
Location: mm/vmalloc.c:579
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:vm_map_ram
Direct callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
**Symbols:**

```
ffffffff820e4390-ffffffff820e4408: __vmap_pages_range_noflush.cold (STB_LOCAL)
ffffffff814167f0-ffffffff81416935: __vmap_pages_range_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __vmap_pages_range_noflush(long unsigned int addr, long unsigned int end, pgprot_t prot, struct page **pages, unsigned int page_shift);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (ffffffff814437c6)
Location: mm/vmalloc.c:579
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:vm_map_ram
Direct callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
**Symbols:**

```
ffffffff821c0fc4-ffffffff821c103c: __vmap_pages_range_noflush.cold (STB_LOCAL)
ffffffff814432c0-ffffffff81443405: __vmap_pages_range_noflush (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
