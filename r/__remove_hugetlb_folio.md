# Function: <code>__remove_hugetlb_folio</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
void __remove_hugetlb_folio(struct hstate *h, struct folio *folio, bool adjust_surplus, bool demote);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff814051c0)
Location: mm/hugetlb.c:1594
Inline: False
Direct callers:
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:free_huge_page
```
**Symbols:**

```
ffffffff814051c0-ffffffff81405262: __remove_hugetlb_folio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __remove_hugetlb_folio(struct hstate *h, struct folio *folio, bool adjust_surplus, bool demote);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81438880)
Location: mm/hugetlb.c:1618
Inline: False
Direct callers:
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:free_huge_page
```
**Symbols:**

```
ffffffff81438880-ffffffff8143892b: __remove_hugetlb_folio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __remove_hugetlb_folio(struct hstate *h, struct folio *folio, bool adjust_surplus, bool demote);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff814721d0)
Location: mm/hugetlb.c:1639
Inline: False
Direct callers:
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:remove_pool_hugetlb_folio
  - mm/hugetlb.c:free_huge_folio
```
**Symbols:**

```
ffffffff814721d0-ffffffff81472278: __remove_hugetlb_folio (STB_LOCAL)
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
