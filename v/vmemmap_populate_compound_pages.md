# Function: <code>vmemmap_populate_compound_pages</code>

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
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81f21917)
Location: mm/sparse-vmemmap.c:724
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:__populate_section_memmap
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vmemmap_populate_compound_pages(long unsigned int start_pfn, long unsigned int start, long unsigned int end, int node, struct dev_pagemap *pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff820cba30)
Location: mm/sparse-vmemmap.c:398
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:__populate_section_memmap
```
**Symbols:**

```
ffffffff820cba30-ffffffff820cbc89: vmemmap_populate_compound_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vmemmap_populate_compound_pages(long unsigned int start_pfn, long unsigned int start, long unsigned int end, int node, struct dev_pagemap *pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff8214fce0)
Location: mm/sparse-vmemmap.c:398
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:__populate_section_memmap
```
**Symbols:**

```
ffffffff8214fce0-ffffffff8214ff39: vmemmap_populate_compound_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vmemmap_populate_compound_pages(long unsigned int start_pfn, long unsigned int start, long unsigned int end, int node, struct dev_pagemap *pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff82232b10)
Location: mm/sparse-vmemmap.c:399
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:__populate_section_memmap
```
**Symbols:**

```
ffffffff82232b10-ffffffff82232d69: vmemmap_populate_compound_pages (STB_LOCAL)
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
