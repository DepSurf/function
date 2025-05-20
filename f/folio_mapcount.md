# Function: <code>folio_mapcount</code>

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
int folio_mapcount(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8131df00)
Location: mm/util.c:845
Inline: False
Direct callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:folio_referenced
  - mm/migrate.c:numamigrate_isolate_page
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/khugepaged.c:is_refcount_suitable
  - mm/memfd.c:memfd_wait_for_pins
```
**Symbols:**

```
ffffffff8131df00-ffffffff8131dfdd: folio_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff813d7685)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:folio_referenced
```
```
In mm/madvise.c (ffffffff813f4495)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffffffff81441a2a)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - mm/huge_memory.c:can_split_folio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813db20e)
Location: include/linux/mm.h:1151
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/rmap.c (ffffffff8140bb90)
Location: include/linux/mm.h:1151
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:folio_referenced
```
```
In mm/madvise.c (ffffffff814279f9)
Location: include/linux/mm.h:1151
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff81443901)
Location: include/linux/mm.h:1151
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_wp
```
```
In mm/huge_memory.c (ffffffff814773fa)
Location: include/linux/mm.h:1151
Inline: True
Inline callers:
  - mm/huge_memory.c:can_split_folio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff814052c8)
Location: include/linux/mm.h:1234
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/rmap.c (ffffffff8143844a)
Location: include/linux/mm.h:1234
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:folio_referenced
```
```
In mm/madvise.c (ffffffff81461210)
Location: include/linux/mm.h:1234
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff8147d989)
Location: include/linux/mm.h:1234
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_wp
```
```
In mm/huge_memory.c (ffffffff814a6b7a)
Location: include/linux/mm.h:1234
Inline: True
Inline callers:
  - mm/huge_memory.c:can_split_folio
```
```
In mm/khugepaged.c (ffffffff814aa775)
Location: include/linux/mm.h:1234
Inline: True
Inline callers:
  - mm/khugepaged.c:is_refcount_suitable
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
