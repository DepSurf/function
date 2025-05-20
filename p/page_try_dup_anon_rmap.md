# Function: <code>page_try_dup_anon_rmap</code>

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
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff81340295)
Location: include/linux/rmap.h:234
Inline: True
Inline callers:
  - mm/memory.c:copy_present_pte
Direct callers:
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/hugetlb.c (ffffffff81391b0f)
Location: include/linux/rmap.h:234
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/huge_memory.c (ffffffff813be959)
Location: include/linux/rmap.h:234
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
```
**Symbols:**

```
ffffffff8133d110-ffffffff8133d19d: page_try_dup_anon_rmap.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff813b8225)
Location: include/linux/rmap.h:234
Inline: True
Inline callers:
  - mm/memory.c:copy_present_pte
Direct callers:
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/hugetlb.c (ffffffff8140eb6f)
Location: include/linux/rmap.h:234
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/huge_memory.c (ffffffff814411c4)
Location: include/linux/rmap.h:234
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
```
**Symbols:**

```
ffffffff813b4d30-ffffffff813b4dbd: page_try_dup_anon_rmap.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff813ed006)
Location: include/linux/rmap.h:243
Inline: True
Inline callers:
  - mm/memory.c:copy_present_pte
Direct callers:
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/hugetlb.c (ffffffff81441f1f)
Location: include/linux/rmap.h:243
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/huge_memory.c (ffffffff81476a8d)
Location: include/linux/rmap.h:243
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
```
**Symbols:**

```
ffffffff813e9a00-ffffffff813e9a8d: page_try_dup_anon_rmap.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
