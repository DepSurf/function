# Function: <code>__destroy_compound_gigantic_folio</code>

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
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __destroy_compound_gigantic_folio(struct folio *folio, unsigned int order, bool demote);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:1476
Inline: False
Direct callers:
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:__update_and_free_page
```
**Symbols:**

```
ffffffff814052f0-ffffffff8140539b: __destroy_compound_gigantic_folio (STB_LOCAL)
ffffffff82066034-ffffffff82066052: __destroy_compound_gigantic_folio.cold (STB_LOCAL)
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
In mm/hugetlb.c (ffffffff8143de60)
Location: mm/hugetlb.c:1473
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:__update_and_free_hugetlb_folio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __destroy_compound_gigantic_folio(struct folio *folio, unsigned int order, bool demote);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:1511
Inline: False
Direct callers:
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:__update_and_free_hugetlb_folio
```
**Symbols:**

```
ffffffff81472290-ffffffff81472322: __destroy_compound_gigantic_folio (STB_LOCAL)
ffffffff821c29a2-ffffffff821c29c5: __destroy_compound_gigantic_folio.cold (STB_LOCAL)
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
