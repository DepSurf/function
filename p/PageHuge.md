# Function: <code>PageHuge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int PageHuge(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811daaa0)
Location: mm/hugetlb.c:1297
Inline: True
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__delete_from_page_cache
  - mm/swap.c:__put_compound_page
  - mm/rmap.c:__page_check_address
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/migrate.c:new_page_node
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:SyS_move_pages
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:put_hwpoison_page
  - mm/memory-failure.c:put_hwpoison_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/page_isolation.c:alloc_migrate_target
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff811daaa0-ffffffff811daad3: PageHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int PageHuge(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811f8ab0)
Location: mm/hugetlb.c:1324
Inline: True
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/swap.c:__put_compound_page
  - mm/util.c:__page_mapcount
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:__page_check_address
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:__basepage_index
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:SyS_move_pages
  - mm/migrate.c:new_page_node
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:me_huge_page
  - mm/page_isolation.c:alloc_migrate_target
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff811f8ab0-ffffffff811f8ae3: PageHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int PageHuge(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812094c0)
Location: mm/hugetlb.c:1324
Inline: True
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/swap.c:__put_compound_page
  - mm/util.c:__page_mapcount
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:__page_check_address
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:new_page_node
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:me_huge_page
  - mm/page_isolation.c:alloc_migrate_target
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff812094c0-ffffffff812094f3: PageHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int PageHuge(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81215f31)
Location: mm/hugetlb.c:1342
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:__basepage_index
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/swap.c:__put_compound_page
  - mm/util.c:__page_mapcount
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:new_page_node
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:me_huge_page
  - mm/page_isolation.c:alloc_migrate_target
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff81213c60-ffffffff81213c93: PageHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int PageHuge(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81230ad5)
Location: mm/hugetlb.c:1348
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:__basepage_index
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
  - mm/swap.c:__put_compound_page
  - mm/util.c:__page_mapcount
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:new_page_node
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:me_huge_page
  - mm/page_isolation.c:alloc_migrate_target
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff8122e830-ffffffff8122e863: PageHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int PageHuge(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812587a2)
Location: mm/hugetlb.c:1336
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:free_huge_page
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
  - mm/page_alloc.c:has_unmovable_pages
  - mm/swap.c:__put_compound_page
  - mm/util.c:__page_mapcount
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:me_huge_page
  - mm/page_isolation.c:alloc_migrate_target
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff812516c0-ffffffff812516f3: PageHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int PageHuge(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8126ce74)
Location: mm/hugetlb.c:1337
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:free_huge_page
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
  - mm/page_alloc.c:has_unmovable_pages
  - mm/swap.c:__put_compound_page
  - mm/util.c:__page_mapcount
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:me_huge_page
  - mm/page_isolation.c:alloc_migrate_target
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff81265ac0-ffffffff81265af5: PageHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int PageHuge(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81281410)
Location: mm/hugetlb.c:1368
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
  - mm/swap.c:__put_compound_page
  - mm/util.c:__page_mapcount
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/page_alloc.c:has_unmovable_pages
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:free_huge_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:me_huge_page
  - mm/page_isolation.c:alloc_migrate_target
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff81281410-ffffffff81281445: PageHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int PageHuge(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81290f10)
Location: mm/hugetlb.c:1416
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
  - mm/swap.c:__put_compound_page
  - mm/util.c:__page_mapcount
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/page_alloc.c:has_unmovable_pages
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__free_huge_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:me_huge_page
  - mm/page_isolation.c:alloc_migrate_target
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff81290f10-ffffffff81290f45: PageHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int PageHuge(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812cb55f)
Location: mm/hugetlb.c:1561
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__free_huge_page
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:page_cache_delete
  - mm/swap.c:release_pages
  - mm/swap.c:__put_page
  - mm/util.c:__page_mapcount
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/page_alloc.c:pfn_range_valid_contig
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:scan_movable_pages
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:copy_huge_page
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:me_huge_page
  - mm/page_isolation.c:alloc_migrate_target
  - mm/memfd.c:memfd_wait_for_pins
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff812c37c0-ffffffff812c37f5: PageHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int PageHuge(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d717f)
Location: mm/hugetlb.c:1589
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__free_huge_page
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:page_cache_delete
  - mm/swap.c:release_pages
  - mm/util.c:__page_mapcount
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_referenced_one
  - mm/page_alloc.c:pfn_range_valid_contig
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/swap_state.c:find_get_incore_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/ksm.c:write_protect_page
  - mm/memory_hotplug.c:scan_movable_pages
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:copy_huge_page
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:isolate_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:__get_hwpoison_page
  - mm/memory-failure.c:me_huge_page
  - mm/memfd.c:memfd_wait_for_pins
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff812cf4f0-ffffffff812cf525: PageHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int PageHuge(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812de3d1)
Location: mm/hugetlb.c:1547
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
Direct callers:
  - kernel/futex.c:get_futex_key
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
  - mm/swap.c:release_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/util.c:__page_mapcount
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_referenced_one
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:page_address_in_vma
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/swap_state.c:find_get_incore_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/ksm.c:write_protect_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/huge_memory.c:split_huge_pages_all
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memfd.c:memfd_wait_for_pins
  - fs/proc/page.c:stable_page_flags
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff812d63a0-ffffffff812d63d5: PageHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int PageHuge(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81325648)
Location: mm/hugetlb.c:1738
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
Direct callers:
  - kernel/futex.c:get_futex_key
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
  - mm/swap.c:release_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/util.c:__page_mapcount
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_mlock_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_referenced_one
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:page_address_in_vma
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/swap_state.c:find_get_incore_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/ksm.c:write_protect_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/huge_memory.c:split_huge_pages_all
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memfd.c:memfd_wait_for_pins
  - fs/proc/kcore.c:read_kcore
  - fs/proc/page.c:stable_page_flags
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff8131c1b0-ffffffff8131c1e5: PageHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int PageHuge(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff813940d8)
Location: mm/hugetlb.c:1849
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
Direct callers:
  - kernel/futex/core.c:get_futex_key
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
  - mm/swap.c:__put_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/util.c:__page_mapcount
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/page_vma_mapped.c:vma_address
  - mm/page_vma_mapped.c:vma_address
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_address_in_vma
  - mm/memory_hotplug.c:offline_pages
  - mm/swap_state.c:find_get_incore_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
  - mm/huge_memory.c:split_huge_pages_all
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/memfd.c:memfd_wait_for_pins
  - fs/proc/kcore.c:read_kcore
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - lib/iov_iter.c:iter_xarray_populate_pages
```
**Symbols:**

```
ffffffff81389fe0-ffffffff8138a043: PageHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int PageHuge(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff814074e0)
Location: mm/hugetlb.c:2045
Inline: False
Direct callers:
  - kernel/futex/core.c:get_futex_key
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_address_in_vma
  - mm/memory_hotplug.c:offline_pages
  - mm/ksm.c:write_protect_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:putback_movable_pages
  - mm/huge_memory.c:split_huge_pages_all
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/memfd.c:memfd_wait_for_pins
  - fs/proc/kcore.c:read_kcore
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - lib/iov_iter.c:iter_xarray_populate_pages
```
**Symbols:**

```
ffffffff814074e0-ffffffff8140754c: PageHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int PageHuge(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8143b060)
Location: mm/hugetlb.c:2066
Inline: False
Direct callers:
  - kernel/futex/core.c:get_futex_key
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/page_vma_mapped.c:vma_address
  - mm/rmap.c:vma_address
  - mm/page_alloc.c:alloc_contig_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/ksm.c:write_protect_page
  - mm/migrate.c:add_page_for_migration
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:collect_procs_anon
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/memfd.c:memfd_wait_for_pins
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - lib/iov_iter.c:iter_xarray_populate_pages
```
**Symbols:**

```
ffffffff8143b060-ffffffff8143b0cc: PageHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int PageHuge(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81474b30)
Location: mm/hugetlb.c:2166
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/page_alloc.c:alloc_contig_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/memfd.c:memfd_wait_for_pins
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - lib/iov_iter.c:iter_xarray_populate_pages
```
**Symbols:**

```
ffffffff81474b30-ffffffff81474b9f: PageHuge (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int PageHuge(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff8000103362e0)
Location: mm/hugetlb.c:1416
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:alloc_gigantic_page
Direct callers:
  - virt/kvm/arm/mmu.c:user_mem_abort
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
  - mm/swap.c:__put_compound_page
  - mm/util.c:__page_mapcount
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/page_alloc.c:has_unmovable_pages
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:me_huge_page
  - mm/page_isolation.c:alloc_migrate_target
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffff80001032d700-ffff80001032d758: PageHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (0)
Location: include/linux/page-flags.h:577
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/page-flags.h:577
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/page-flags.h:577
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/page-flags.h:577
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/page-flags.h:577
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/page-flags.h:577
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/page-flags.h:577
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/page-flags.h:577
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/page-flags.h:577
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/page-flags.h:577
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/page-flags.h:577
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int PageHuge(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c000000000410bbc)
Location: mm/hugetlb.c:1416
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__free_huge_page
Direct callers:
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_do_alloc
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
  - mm/swap.c:__put_compound_page
  - mm/util.c:__page_mapcount
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/page_alloc.c:has_unmovable_pages
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:me_huge_page
  - mm/page_isolation.c:alloc_migrate_target
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
c000000000405220-c000000000405278: PageHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int PageHuge(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe0002322c0)
Location: mm/hugetlb.c:1416
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__free_huge_page
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
  - mm/swap.c:__put_compound_page
  - mm/util.c:__page_mapcount
  - mm/gup.c:__gup_longterm_locked
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/page_alloc.c:has_unmovable_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/page_isolation.c:alloc_migrate_target
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffe00022bcda-ffffffe00022bd24: PageHuge (STB_GLOBAL)
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
int PageHuge(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812894f0)
Location: mm/hugetlb.c:1416
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
  - mm/swap.c:__put_compound_page
  - mm/util.c:__page_mapcount
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/page_alloc.c:has_unmovable_pages
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__free_huge_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:me_huge_page
  - mm/page_isolation.c:alloc_migrate_target
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff812894f0-ffffffff81289525: PageHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int PageHuge(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127b390)
Location: mm/hugetlb.c:1416
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
  - mm/swap.c:__put_compound_page
  - mm/util.c:__page_mapcount
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/page_alloc.c:has_unmovable_pages
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__free_huge_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:me_huge_page
  - mm/page_isolation.c:alloc_migrate_target
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff8127b390-ffffffff8127b3c5: PageHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int PageHuge(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81287300)
Location: mm/hugetlb.c:1416
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
  - mm/swap.c:__put_compound_page
  - mm/util.c:__page_mapcount
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/page_alloc.c:has_unmovable_pages
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__free_huge_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:me_huge_page
  - mm/page_isolation.c:alloc_migrate_target
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff81287300-ffffffff81287335: PageHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int PageHuge(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81297830)
Location: mm/hugetlb.c:1416
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
  - mm/swap.c:__put_compound_page
  - mm/util.c:__page_mapcount
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/page_alloc.c:has_unmovable_pages
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__free_huge_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:me_huge_page
  - mm/page_isolation.c:alloc_migrate_target
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff81297830-ffffffff81297865: PageHuge (STB_GLOBAL)
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
