# Function: <code>vmemmap_remap_range</code>

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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vmemmap_remap_range(long unsigned int start, long unsigned int end, struct vmemmap_remap_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/sparse-vmemmap.c (0)
Location: mm/sparse-vmemmap.c:178
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_remap_alloc
  - mm/sparse-vmemmap.c:vmemmap_remap_free
  - mm/sparse-vmemmap.c:vmemmap_remap_free
```
**Symbols:**

```
ffffffff8132bea0-ffffffff8132c3c2: vmemmap_remap_range (STB_LOCAL)
ffffffff81cc0798-ffffffff81cc07f3: vmemmap_remap_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vmemmap_remap_range(long unsigned int start, long unsigned int end, struct vmemmap_remap_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/sparse-vmemmap.c (0)
Location: mm/sparse-vmemmap.c:204
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_remap_alloc
  - mm/sparse-vmemmap.c:vmemmap_remap_free
  - mm/sparse-vmemmap.c:vmemmap_remap_free
```
**Symbols:**

```
ffffffff8139c1e0-ffffffff8139c2fa: vmemmap_remap_range (STB_LOCAL)
ffffffff81e72c11-ffffffff81e72c91: vmemmap_remap_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int vmemmap_remap_range(long unsigned int start, long unsigned int end, struct vmemmap_remap_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb_vmemmap.c (0)
Location: mm/hugetlb_vmemmap.c:186
Inline: False
Direct callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_free
  - mm/hugetlb_vmemmap.c:vmemmap_remap_free
```
**Symbols:**

```
ffffffff81413800-ffffffff81413bf0: vmemmap_remap_range (STB_LOCAL)
ffffffff820670b1-ffffffff82067112: vmemmap_remap_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int vmemmap_remap_range(long unsigned int start, long unsigned int end, struct vmemmap_remap_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb_vmemmap.c (0)
Location: mm/hugetlb_vmemmap.c:186
Inline: False
Direct callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_alloc
  - mm/hugetlb_vmemmap.c:vmemmap_remap_free
  - mm/hugetlb_vmemmap.c:vmemmap_remap_free
```
**Symbols:**

```
ffffffff81446d50-ffffffff81447144: vmemmap_remap_range (STB_LOCAL)
ffffffff820e696d-ffffffff820e69ce: vmemmap_remap_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int vmemmap_remap_range(long unsigned int start, long unsigned int end, struct vmemmap_remap_walk *walk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb_vmemmap.c (ffffffff81480580)
Location: mm/hugetlb_vmemmap.c:159
Inline: True
Direct callers:
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_optimize_folios
  - mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_optimize_folio
  - mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_optimize_folio
  - mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_restore_folio
```
**Symbols:**

```
ffffffff81480580-ffffffff8148066f: vmemmap_remap_range (STB_LOCAL)
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
