# Function: <code>vmemmap_remap_alloc</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
int vmemmap_remap_alloc(long unsigned int start, long unsigned int end, long unsigned int reuse, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff8132c7d0)
Location: mm/sparse-vmemmap.c:364
Inline: False
Direct callers:
  - mm/hugetlb_vmemmap.c:alloc_huge_page_vmemmap
```
**Symbols:**

```
ffffffff8132c7d0-ffffffff8132c94d: vmemmap_remap_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vmemmap_remap_alloc(long unsigned int start, long unsigned int end, long unsigned int reuse, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff8139c840)
Location: mm/sparse-vmemmap.c:409
Inline: False
Direct callers:
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_alloc
```
**Symbols:**

```
ffffffff8139c840-ffffffff8139c9c9: vmemmap_remap_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb_vmemmap.c (ffffffff81413e60)
Location: mm/hugetlb_vmemmap.c:420
Inline: True
Direct callers:
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_restore
```
**Symbols:**

```
ffffffff81413e60-ffffffff81413fe7: vmemmap_remap_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vmemmap_remap_alloc(long unsigned int start, long unsigned int end, long unsigned int reuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_vmemmap.c (ffffffff81447160)
Location: mm/hugetlb_vmemmap.c:420
Inline: False
Direct callers:
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_restore
```
**Symbols:**

```
ffffffff81447160-ffffffff814472e7: vmemmap_remap_alloc (STB_LOCAL)
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
In mm/hugetlb_vmemmap.c (ffffffff8148094c)
Location: mm/hugetlb_vmemmap.c:415
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_restore_folio
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
</ul>
