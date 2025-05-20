# Function: <code>isolate_lru_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int isolate_lru_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811a2890)
Location: mm/vmscan.c:1424
Inline: False
Direct callers:
  - mm/vmscan.c:putback_lru_page
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:mlock_vma_page
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:SyS_move_pages
  - mm/huge_memory.c:khugepaged
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff811a2890-ffffffff811a2a16: isolate_lru_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int isolate_lru_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811b8e50)
Location: mm/vmscan.c:1525
Inline: False
Direct callers:
  - mm/vmscan.c:putback_lru_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:SyS_move_pages
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
ffffffff811b8e50-ffffffff811b90c8: isolate_lru_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int isolate_lru_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811c9490)
Location: mm/vmscan.c:1559
Inline: False
Direct callers:
  - mm/vmscan.c:putback_lru_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:SYSC_move_pages
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
ffffffff811c9490-ffffffff811c970d: isolate_lru_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int isolate_lru_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811d1f70)
Location: mm/vmscan.c:1598
Inline: False
Direct callers:
  - mm/vmscan.c:putback_lru_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:SYSC_move_pages
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
ffffffff811d1f70-ffffffff811d21c0: isolate_lru_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int isolate_lru_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811e7410)
Location: mm/vmscan.c:1615
Inline: False
Direct callers:
  - mm/vmscan.c:putback_lru_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mempolicy.c:migrate_page_add
  - mm/memory_hotplug.c:__offline_pages
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:SYSC_move_pages
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
ffffffff811e7410-ffffffff811e7660: isolate_lru_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int isolate_lru_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81208970)
Location: mm/vmscan.c:1593
Inline: False
Direct callers:
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mempolicy.c:migrate_page_add
  - mm/memory_hotplug.c:__offline_pages
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:kernel_move_pages
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
ffffffff81208970-ffffffff81208bc2: isolate_lru_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int isolate_lru_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8121b610)
Location: mm/vmscan.c:1760
Inline: False
Direct callers:
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mempolicy.c:migrate_page_add
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:kernel_move_pages
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
ffffffff8121b610-ffffffff8121b865: isolate_lru_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int isolate_lru_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122b2c0)
Location: mm/vmscan.c:1797
Inline: False
Direct callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mempolicy.c:migrate_page_add
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:do_pages_move
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
ffffffff8122b2c0-ffffffff8122b4fc: isolate_lru_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int isolate_lru_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81239190)
Location: mm/vmscan.c:1796
Inline: False
Direct callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:migrate_page_add
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:do_pages_move
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
ffffffff81239190-ffffffff812393cc: isolate_lru_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int isolate_lru_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81269e70)
Location: mm/vmscan.c:1765
Inline: False
Direct callers:
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:migrate_page_add
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:add_page_for_migration
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
ffffffff81269e70-ffffffff8126a0a2: isolate_lru_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int isolate_lru_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81274980)
Location: mm/vmscan.c:1763
Inline: False
Direct callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:migrate_page_add
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:add_page_for_migration
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memory-failure.c:isolate_page
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
ffffffff81274980-ffffffff81274b59: isolate_lru_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int isolate_lru_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81279c90)
Location: mm/vmscan.c:1958
Inline: False
Direct callers:
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:migrate_page_add
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:add_page_for_migration
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
ffffffff81279c90-ffffffff81279e55: isolate_lru_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int isolate_lru_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812b7c50)
Location: mm/vmscan.c:2091
Inline: False
Direct callers:
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:migrate_page_add
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
ffffffff812b7c50-ffffffff812b7e52: isolate_lru_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int isolate_lru_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff81301320)
Location: mm/folio-compat.c:154
Inline: False
Direct callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:migrate_page_add
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate_device.c:migrate_vma_unmap
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
ffffffff81301320-ffffffff8130139b: isolate_lru_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int isolate_lru_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff8136b9b0)
Location: mm/folio-compat.c:115
Inline: False
Direct callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:migrate_page_add
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate_device.c:migrate_device_unmap
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
ffffffff8136b9b0-ffffffff8136ba2b: isolate_lru_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool isolate_lru_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff8139dc00)
Location: mm/folio-compat.c:114
Inline: False
Direct callers:
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate_device.c:migrate_device_unmap
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
ffffffff8139dc00-ffffffff8139dc7c: isolate_lru_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool isolate_lru_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff813c78e0)
Location: mm/folio-compat.c:108
Inline: False
Direct callers:
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate_device.c:migrate_device_unmap
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
**Symbols:**

```
ffffffff813c78e0-ffffffff813c7959: isolate_lru_page (STB_GLOBAL)
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
int isolate_lru_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102c9fe0)
Location: mm/vmscan.c:1796
Inline: False
Direct callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:migrate_page_add
  - mm/migrate.c:do_pages_move
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
ffff8000102c9fe0-ffff8000102ca28c: isolate_lru_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int isolate_lru_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f3ee8)
Location: mm/vmscan.c:1796
Inline: False
Direct callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
**Symbols:**

```
c04f3ee8-c04f40ec: isolate_lru_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int isolate_lru_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c000000000386860)
Location: mm/vmscan.c:1796
Inline: False
Direct callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:migrate_page_add
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:do_pages_move
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
c000000000386860-c000000000386bf8: isolate_lru_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int isolate_lru_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffe0001e91be)
Location: mm/vmscan.c:1796
Inline: False
Direct callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
**Symbols:**

```
ffffffe0001e91be-ffffffe0001e93be: isolate_lru_page (STB_GLOBAL)
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
int isolate_lru_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812317e0)
Location: mm/vmscan.c:1796
Inline: False
Direct callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:migrate_page_add
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:do_pages_move
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
ffffffff812317e0-ffffffff81231a1c: isolate_lru_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int isolate_lru_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812248a0)
Location: mm/vmscan.c:1796
Inline: False
Direct callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:migrate_page_add
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:do_pages_move
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
ffffffff812248a0-ffffffff81224ad6: isolate_lru_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int isolate_lru_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122f580)
Location: mm/vmscan.c:1796
Inline: False
Direct callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:migrate_page_add
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:do_pages_move
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
ffffffff8122f580-ffffffff8122f7bc: isolate_lru_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int isolate_lru_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8123e9b0)
Location: mm/vmscan.c:1796
Inline: False
Direct callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:migrate_page_add
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:do_pages_move
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
ffffffff8123e9b0-ffffffff8123ebe5: isolate_lru_page (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
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
