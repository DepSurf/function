# Function: <code>mem_cgroup_uncharge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mem_cgroup_uncharge(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81200320)
Location: mm/memcontrol.c:5515
Inline: False
Direct callers:
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
**Symbols:**

```
ffffffff81200320-ffffffff8120034c: mem_cgroup_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mem_cgroup_uncharge(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812240d0)
Location: mm/memcontrol.c:5593
Inline: False
Direct callers:
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
**Symbols:**

```
ffffffff812240d0-ffffffff812240fc: mem_cgroup_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mem_cgroup_uncharge(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812365d0)
Location: mm/memcontrol.c:5578
Inline: False
Direct callers:
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
**Symbols:**

```
ffffffff812365d0-ffffffff812365fc: mem_cgroup_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mem_cgroup_uncharge(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81242080)
Location: mm/memcontrol.c:5640
Inline: False
Direct callers:
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
ffffffff81242080-ffffffff812420ad: mem_cgroup_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mem_cgroup_uncharge(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81261dc0)
Location: mm/memcontrol.c:5737
Inline: False
Direct callers:
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:shrink_page_list
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
ffffffff81261dc0-ffffffff81261e2b: mem_cgroup_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mem_cgroup_uncharge(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81285dd0)
Location: mm/memcontrol.c:5805
Inline: False
Direct callers:
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:shrink_page_list
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
ffffffff81285dd0-ffffffff81285e39: mem_cgroup_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mem_cgroup_uncharge(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8129ad30)
Location: mm/memcontrol.c:6136
Inline: False
Direct callers:
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:shrink_page_list
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
ffffffff8129ad30-ffffffff8129ad99: mem_cgroup_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mem_cgroup_uncharge(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b5fe0)
Location: mm/memcontrol.c:6428
Inline: False
Direct callers:
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
ffffffff812b5fe0-ffffffff812b604b: mem_cgroup_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mem_cgroup_uncharge(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c7ed0)
Location: mm/memcontrol.c:6768
Inline: False
Direct callers:
  - mm/page_alloc.c:free_compound_page
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
ffffffff812c7ed0-ffffffff812c7f3b: mem_cgroup_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mem_cgroup_uncharge(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fd760)
Location: mm/memcontrol.c:6628
Inline: False
Direct callers:
  - mm/swap.c:__put_page
  - mm/page_alloc.c:free_compound_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memremap.c:free_devmap_managed_page
```
**Symbols:**

```
ffffffff812fd760-ffffffff812fd7d8: mem_cgroup_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mem_cgroup_uncharge(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81309b80)
Location: mm/memcontrol.c:6888
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
ffffffff81309b80-ffffffff81309bfd: mem_cgroup_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mem_cgroup_uncharge(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813103a0)
Location: mm/memcontrol.c:6743
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
ffffffff813103a0-ffffffff8131042a: mem_cgroup_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129c183)
Location: include/linux/memcontrol.h:703
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/swap.c (ffffffff812aae2f)
Location: include/linux/memcontrol.h:703
Inline: True
```
```
In mm/page_alloc.c (ffffffff813056d5)
Location: include/linux/memcontrol.h:703
Inline: True
Inline callers:
  - mm/page_alloc.c:free_compound_page
```
```
In mm/khugepaged.c (ffffffff8134e761)
Location: include/linux/memcontrol.h:703
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memory-failure.c (ffffffff8135ecb9)
Location: include/linux/memcontrol.h:703
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/memremap.c (ffffffff81369ed6)
Location: include/linux/memcontrol.h:703
Inline: True
Inline callers:
  - mm/memremap.c:free_devmap_managed_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f2858)
Location: include/linux/memcontrol.h:704
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/swap.c (ffffffff8130491c)
Location: include/linux/memcontrol.h:704
Inline: True
Inline callers:
  - mm/swap.c:__put_page
```
```
In mm/page_alloc.c (ffffffff8136d9e0)
Location: include/linux/memcontrol.h:704
Inline: True
Inline callers:
  - mm/page_alloc.c:free_compound_page
```
```
In mm/khugepaged.c (ffffffff813c4da7)
Location: include/linux/memcontrol.h:704
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memory-failure.c (ffffffff813d92d3)
Location: include/linux/memcontrol.h:704
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/memremap.c (ffffffff813e7c13)
Location: include/linux/memcontrol.h:704
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
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
In mm/filemap.c (ffffffff8135ad0b)
Location: include/linux/memcontrol.h:686
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/swap.c (ffffffff8136e8bb)
Location: include/linux/memcontrol.h:686
Inline: True
Inline callers:
  - mm/swap.c:__folio_put
```
```
In mm/page_alloc.c (ffffffff813e9e60)
Location: include/linux/memcontrol.h:686
Inline: True
Inline callers:
  - mm/page_alloc.c:free_compound_page
```
```
In mm/khugepaged.c (ffffffff814495e9)
Location: include/linux/memcontrol.h:686
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memory-failure.c (ffffffff8145f593)
Location: include/linux/memcontrol.h:686
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/memremap.c (ffffffff8146fa4d)
Location: include/linux/memcontrol.h:686
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
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
In mm/filemap.c (ffffffff8138c72f)
Location: include/linux/memcontrol.h:699
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/swap.c (ffffffff813a0adb)
Location: include/linux/memcontrol.h:699
Inline: True
Inline callers:
  - mm/swap.c:__folio_put
```
```
In mm/page_alloc.c (ffffffff8141ee90)
Location: include/linux/memcontrol.h:699
Inline: True
Inline callers:
  - mm/page_alloc.c:free_compound_page
```
```
In mm/memory-failure.c (ffffffff814957ae)
Location: include/linux/memcontrol.h:699
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/memremap.c (ffffffff814a422d)
Location: include/linux/memcontrol.h:699
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
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
In mm/filemap.c (ffffffff813b6292)
Location: include/linux/memcontrol.h:708
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/swap.c (ffffffff813ca758)
Location: include/linux/memcontrol.h:708
Inline: True
Inline callers:
  - mm/swap.c:__folio_put
```
```
In mm/page_alloc.c (ffffffff8144bb76)
Location: include/linux/memcontrol.h:708
Inline: True
Inline callers:
  - mm/page_alloc.c:destroy_large_folio
```
```
In mm/hugetlb.c (ffffffff81476f46)
Location: include/linux/memcontrol.h:708
Inline: True
Inline callers:
  - mm/hugetlb.c:free_huge_folio
```
```
In mm/memory-failure.c (ffffffff814c4a10)
Location: include/linux/memcontrol.h:708
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/memremap.c (ffffffff814d507d)
Location: include/linux/memcontrol.h:708
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void mem_cgroup_uncharge(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff80001036add8)
Location: mm/memcontrol.c:6768
Inline: False
Direct callers:
  - mm/swap.c:__put_page
  - mm/page_alloc.c:free_compound_page
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
ffff80001036add8-ffff80001036ae54: mem_cgroup_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mem_cgroup_uncharge(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055c410)
Location: mm/memcontrol.c:6768
Inline: False
Direct callers:
  - mm/page_alloc.c:free_compound_page
```
**Symbols:**

```
c055c410-c055c4a8: mem_cgroup_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mem_cgroup_uncharge(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c00000000045a3b0)
Location: mm/memcontrol.c:6768
Inline: False
Direct callers:
  - mm/page_alloc.c:free_compound_page
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
c00000000045a3b0-c00000000045a450: mem_cgroup_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mem_cgroup_uncharge(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000248568)
Location: mm/memcontrol.c:6768
Inline: False
Direct callers:
  - mm/swap.c:__put_page
  - mm/page_alloc.c:free_compound_page
```
**Symbols:**

```
ffffffe000248568-ffffffe0002485d2: mem_cgroup_uncharge (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void mem_cgroup_uncharge(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c04b0)
Location: mm/memcontrol.c:6768
Inline: False
Direct callers:
  - mm/page_alloc.c:free_compound_page
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
ffffffff812c04b0-ffffffff812c051b: mem_cgroup_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mem_cgroup_uncharge(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b1580)
Location: mm/memcontrol.c:6768
Inline: False
Direct callers:
  - mm/page_alloc.c:free_compound_page
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
ffffffff812b1580-ffffffff812b15eb: mem_cgroup_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mem_cgroup_uncharge(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812be2c0)
Location: mm/memcontrol.c:6768
Inline: False
Direct callers:
  - mm/page_alloc.c:free_compound_page
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
ffffffff812be2c0-ffffffff812be32b: mem_cgroup_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mem_cgroup_uncharge(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cecb0)
Location: mm/memcontrol.c:6768
Inline: False
Direct callers:
  - mm/page_alloc.c:free_compound_page
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
ffffffff812cecb0-ffffffff812ced1b: mem_cgroup_uncharge (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
