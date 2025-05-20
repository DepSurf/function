# Function: <code>vmap_range_noflush</code>

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
<summary>In <code>5.13</code>: ✅</summary>

```c
int vmap_range_noflush(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot, unsigned int max_page_shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b7ec0)
Location: mm/vmalloc.c:256
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_range
```
**Symbols:**

```
ffffffff812b7ec0-ffffffff812b84df: vmap_range_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vmap_range_noflush(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot, unsigned int max_page_shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:285
Inline: False
Direct callers:
  - mm/vmalloc.c:ioremap_page_range
```
**Symbols:**

```
ffffffff812fa5f0-ffffffff812fac37: vmap_range_noflush (STB_LOCAL)
ffffffff81cbcde6-ffffffff81cbce4f: vmap_range_noflush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vmap_range_noflush(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot, unsigned int max_page_shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:286
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_pages_range_noflush
  - mm/vmalloc.c:vmap_pages_range_noflush
  - mm/vmalloc.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81361a40-ffffffff81362128: vmap_range_noflush (STB_LOCAL)
ffffffff81e6ea8b-ffffffff81e6eaf3: vmap_range_noflush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int vmap_range_noflush(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot, unsigned int max_page_shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:289
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmap_pages_range_noflush
  - mm/vmalloc.c:__vmap_pages_range_noflush
  - mm/vmalloc.c:ioremap_page_range
```
**Symbols:**

```
ffffffff813dd3f0-ffffffff813ddab5: vmap_range_noflush (STB_LOCAL)
ffffffff82064998-ffffffff82064a01: vmap_range_noflush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int vmap_range_noflush(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot, unsigned int max_page_shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:278
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmap_pages_range_noflush
  - mm/vmalloc.c:__vmap_pages_range_noflush
  - mm/vmalloc.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81411c50-ffffffff81412316: vmap_range_noflush (STB_LOCAL)
ffffffff820e409d-ffffffff820e4106: vmap_range_noflush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int vmap_range_noflush(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot, unsigned int max_page_shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:278
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmap_pages_range_noflush
  - mm/vmalloc.c:__vmap_pages_range_noflush
  - mm/vmalloc.c:ioremap_page_range
```
**Symbols:**

```
ffffffff8143e4b0-ffffffff8143eb76: vmap_range_noflush (STB_LOCAL)
ffffffff821c0cdc-ffffffff821c0d3a: vmap_range_noflush.cold (STB_LOCAL)
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
