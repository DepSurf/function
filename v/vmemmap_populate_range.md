# Function: <code>vmemmap_populate_range</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
int vmemmap_populate_range(long unsigned int start, long unsigned int end, int node, struct vmem_altmap *altmap, struct page *reuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81f2181a)
Location: mm/sparse-vmemmap.c:664
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:__populate_section_memmap
  - mm/sparse-vmemmap.c:__populate_section_memmap
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81f2181a-ffffffff81f2187d: vmemmap_populate_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff820cbb40)
Location: mm/sparse-vmemmap.c:275
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_populate_compound_pages
  - mm/sparse-vmemmap.c:vmemmap_populate_compound_pages
  - mm/sparse-vmemmap.c:vmemmap_populate_hugepages
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff8214fdf0)
Location: mm/sparse-vmemmap.c:275
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_populate_compound_pages
  - mm/sparse-vmemmap.c:vmemmap_populate_compound_pages
  - mm/sparse-vmemmap.c:vmemmap_populate_hugepages
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff82232c20)
Location: mm/sparse-vmemmap.c:275
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_populate_compound_pages
  - mm/sparse-vmemmap.c:vmemmap_populate_compound_pages
  - mm/sparse-vmemmap.c:vmemmap_populate_hugepages
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
</ul>
