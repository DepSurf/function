# Function: <code>isolate_hugetlb</code>

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
int isolate_hugetlb(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81393cd0)
Location: mm/hugetlb.c:6980
Inline: False
Direct callers:
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/migrate.c:add_page_for_migration
  - mm/memory-failure.c:__soft_offline_page
```
**Symbols:**

```
ffffffff81393cd0-ffffffff81393d68: isolate_hugetlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int isolate_hugetlb(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff814129f0)
Location: mm/hugetlb.c:7261
Inline: False
Direct callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/migrate.c:add_page_for_migration
  - mm/memory-failure.c:soft_offline_in_use_page
```
**Symbols:**

```
ffffffff814129f0-ffffffff81412a88: isolate_hugetlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool isolate_hugetlb(struct folio *folio, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81446040)
Location: mm/hugetlb.c:7360
Inline: False
Direct callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/mempolicy.c:queue_folios_hugetlb
  - mm/migrate.c:add_page_for_migration
  - mm/memory-failure.c:soft_offline_in_use_page
```
**Symbols:**

```
ffffffff81446040-ffffffff814460e4: isolate_hugetlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool isolate_hugetlb(struct folio *folio, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8147faa0)
Location: mm/hugetlb.c:7497
Inline: False
Direct callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/mempolicy.c:queue_folios_hugetlb
  - mm/migrate.c:add_page_for_migration
  - mm/memory-failure.c:soft_offline_in_use_page
```
**Symbols:**

```
ffffffff8147faa0-ffffffff8147fb44: isolate_hugetlb (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
