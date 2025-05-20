# Function: <code>__mem_cgroup_uncharge</code>

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
void __mem_cgroup_uncharge(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8135b6d0)
Location: mm/memcontrol.c:6928
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/page_alloc.c:free_compound_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memremap.c:free_devmap_managed_page
```
**Symbols:**

```
ffffffff8135b6d0-ffffffff8135b755: __mem_cgroup_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __mem_cgroup_uncharge(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d4ec0)
Location: mm/memcontrol.c:6911
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/swap.c:__put_page
  - mm/page_alloc.c:free_compound_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memremap.c:free_zone_device_page
```
**Symbols:**

```
ffffffff813d4ec0-ffffffff813d4f78: __mem_cgroup_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __mem_cgroup_uncharge(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8145a910)
Location: mm/memcontrol.c:7100
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/swap.c:__folio_put
  - mm/page_alloc.c:free_compound_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memremap.c:free_zone_device_page
```
**Symbols:**

```
ffffffff8145a910-ffffffff8145a9c8: __mem_cgroup_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __mem_cgroup_uncharge(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81490570)
Location: mm/memcontrol.c:7168
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/swap.c:__folio_put
  - mm/page_alloc.c:free_compound_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memremap.c:free_zone_device_page
```
**Symbols:**

```
ffffffff81490570-ffffffff81490628: __mem_cgroup_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __mem_cgroup_uncharge(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814bfe50)
Location: mm/memcontrol.c:7495
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/swap.c:__folio_put
  - mm/page_alloc.c:destroy_large_folio
  - mm/hugetlb.c:free_huge_folio
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memremap.c:free_zone_device_page
```
**Symbols:**

```
ffffffff814bfe50-ffffffff814bff08: __mem_cgroup_uncharge (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
</ul>
</details>
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
