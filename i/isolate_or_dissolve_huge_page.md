# Function: <code>isolate_or_dissolve_huge_page</code>

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
int isolate_or_dissolve_huge_page(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812de3b0)
Location: mm/hugetlb.c:2426
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
```
**Symbols:**

```
ffffffff812de3b0-ffffffff812de52c: isolate_or_dissolve_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int isolate_or_dissolve_huge_page(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:2705
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
```
**Symbols:**

```
ffffffff81cc040f-ffffffff81cc0446: isolate_or_dissolve_huge_page.cold (STB_LOCAL)
ffffffff81325620-ffffffff81325812: isolate_or_dissolve_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int isolate_or_dissolve_huge_page(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:2816
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
```
**Symbols:**

```
ffffffff81e7280e-ffffffff81e72853: isolate_or_dissolve_huge_page.cold (STB_LOCAL)
ffffffff813940b0-ffffffff81394416: isolate_or_dissolve_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int isolate_or_dissolve_huge_page(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:2979
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
```
**Symbols:**

```
ffffffff82066ffa-ffffffff82067035: isolate_or_dissolve_huge_page.cold (STB_LOCAL)
ffffffff81412c50-ffffffff81412e3a: isolate_or_dissolve_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int isolate_or_dissolve_huge_page(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:3011
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
```
**Symbols:**

```
ffffffff820e68b6-ffffffff820e68f1: isolate_or_dissolve_huge_page.cold (STB_LOCAL)
ffffffff814462a0-ffffffff81446456: isolate_or_dissolve_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int isolate_or_dissolve_huge_page(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:3110
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
```
**Symbols:**

```
ffffffff821c39eb-ffffffff821c3a25: isolate_or_dissolve_huge_page.cold (STB_LOCAL)
ffffffff8147fd30-ffffffff8147fefe: isolate_or_dissolve_huge_page (STB_GLOBAL)
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
