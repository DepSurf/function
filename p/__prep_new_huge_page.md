# Function: <code>__prep_new_huge_page</code>

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
void __prep_new_huge_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d6620)
Location: mm/hugetlb.c:1494
Inline: False
Direct callers:
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
**Symbols:**

```
ffffffff812d6620-ffffffff812d668a: __prep_new_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __prep_new_huge_page(struct hstate *h, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8131c420)
Location: mm/hugetlb.c:1649
Inline: False
Direct callers:
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
**Symbols:**

```
ffffffff8131c420-ffffffff8131c497: __prep_new_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81393e39)
Location: mm/hugetlb.c:1741
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:prep_new_huge_page
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct hstate *h</code>
</li>
<li>
<b>Param reordered. </b>
<code>page</code> ➡️ <code>h, page</code>
</li>
</ul>
</details>
</li>
</ul>
