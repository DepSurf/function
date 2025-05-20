# Function: <code>vmap_pages_range_noflush</code>

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
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int vmap_pages_range_noflush(long unsigned int addr, long unsigned int end, pgprot_t prot, struct page **pages, unsigned int page_shift);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812bcf34)
Location: mm/vmalloc.c:549
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:vm_map_ram
Direct callers:
  - mm/percpu.c:pcpu_map_pages
```
**Symbols:**

```
ffffffff812bc8f0-ffffffff812bc90f: vmap_pages_range_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int vmap_pages_range_noflush(long unsigned int addr, long unsigned int end, pgprot_t prot, struct page **pages, unsigned int page_shift);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812ff6a4)
Location: mm/vmalloc.c:577
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:vm_map_ram
Direct callers:
  - mm/percpu.c:pcpu_map_pages
```
**Symbols:**

```
ffffffff812ff080-ffffffff812ff09f: vmap_pages_range_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vmap_pages_range_noflush(long unsigned int addr, long unsigned int end, pgprot_t prot, struct page **pages, unsigned int page_shift);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (ffffffff81366811)
Location: mm/vmalloc.c:578
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:vm_map_ram
Direct callers:
  - mm/percpu.c:pcpu_map_pages
  - mm/vmalloc.c:__vmalloc_area_node
```
**Symbols:**

```
ffffffff81e6ed0b-ffffffff81e6ed83: vmap_pages_range_noflush.cold (STB_LOCAL)
ffffffff81365ed0-ffffffff81366041: vmap_pages_range_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int vmap_pages_range_noflush(long unsigned int addr, long unsigned int end, pgprot_t prot, struct page **pages, unsigned int page_shift);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813e29fc)
Location: mm/vmalloc.c:616
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:vm_map_ram
Direct callers:
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_page_first_chunk
```
**Symbols:**

```
ffffffff813e1bc0-ffffffff813e1bdf: vmap_pages_range_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int vmap_pages_range_noflush(long unsigned int addr, long unsigned int end, pgprot_t prot, struct page **pages, unsigned int page_shift);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff814175cc)
Location: mm/vmalloc.c:605
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:vm_map_ram
Direct callers:
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_page_first_chunk
```
**Symbols:**

```
ffffffff81416950-ffffffff8141696f: vmap_pages_range_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int vmap_pages_range_noflush(long unsigned int addr, long unsigned int end, pgprot_t prot, struct page **pages, unsigned int page_shift);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff814440dc)
Location: mm/vmalloc.c:605
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:vm_map_ram
Direct callers:
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_page_first_chunk
```
**Symbols:**

```
ffffffff81443420-ffffffff8144343f: vmap_pages_range_noflush (STB_GLOBAL)
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
