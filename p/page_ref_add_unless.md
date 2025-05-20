# Function: <code>page_ref_add_unless</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a1749)
Location: include/linux/page_ref.h:154
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/swap.c (ffffffff811b3a5e)
Location: include/linux/page_ref.h:154
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff811b89bd)
Location: include/linux/page_ref.h:154
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/hugetlb.c (ffffffff811fe14f)
Location: include/linux/page_ref.h:154
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff812035c0)
Location: include/linux/page_ref.h:154
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff818940d6)
Location: include/linux/page_ref.h:154
Inline: True
```
```
In mm/migrate.c (ffffffff8121186b)
Location: include/linux/page_ref.h:154
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff81217fbb)
Location: include/linux/page_ref.h:154
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff8121e9cf)
Location: include/linux/page_ref.h:154
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81225f96)
Location: include/linux/page_ref.h:154
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff8122db83)
Location: include/linux/page_ref.h:154
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b15b9)
Location: include/linux/page_ref.h:154
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/swap.c (ffffffff811c40ee)
Location: include/linux/page_ref.h:154
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff811c8fed)
Location: include/linux/page_ref.h:154
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/hugetlb.c (ffffffff8120ec1f)
Location: include/linux/page_ref.h:154
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff812155ca)
Location: include/linux/page_ref.h:154
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff818c87d3)
Location: include/linux/page_ref.h:154
Inline: True
```
```
In mm/migrate.c (ffffffff81223a27)
Location: include/linux/page_ref.h:154
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff8122a55b)
Location: include/linux/page_ref.h:154
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff81230fb3)
Location: include/linux/page_ref.h:154
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81238576)
Location: include/linux/page_ref.h:154
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff812400c8)
Location: include/linux/page_ref.h:154
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b7854)
Location: include/linux/page_ref.h:154
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/swap.c (ffffffff811cc4e0)
Location: include/linux/page_ref.h:154
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff811d1b27)
Location: include/linux/page_ref.h:154
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff811f0b92)
Location: include/linux/page_ref.h:154
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
```
```
In mm/hugetlb.c (ffffffff8121a4cf)
Location: include/linux/page_ref.h:154
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff81220bea)
Location: include/linux/page_ref.h:154
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff818ffdd2)
Location: include/linux/page_ref.h:154
Inline: True
```
```
In mm/migrate.c (ffffffff8122f387)
Location: include/linux/page_ref.h:154
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812361b5)
Location: include/linux/page_ref.h:154
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff8123c7d8)
Location: include/linux/page_ref.h:154
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812440b6)
Location: include/linux/page_ref.h:154
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff8124bf88)
Location: include/linux/page_ref.h:154
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cbdd4)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/swap.c (ffffffff811e14d0)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff811e6fc6)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff81205711)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
```
```
In mm/hugetlb.c (ffffffff8123563f)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff8123be75)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff81989f1c)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff8124cf65)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff81254ff8)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff8125c46b)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81263f36)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff8126c342)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ecea8)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/swap.c (ffffffff81202c2f)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff81208523)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff81226b68)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
```
```
In mm/hugetlb.c (ffffffff8125857f)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff8125f3f9)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff819e668b)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff81270a71)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff81278eb2)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff8127fdcb)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81288236)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff81290edf)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fd003)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_entries_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/swap.c (ffffffff812155af)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff8121b1b3)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff81239c69)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/hugetlb.c (ffffffff8126cc51)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff81273b39)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff81a21b66)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff8128508c)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff8128d562)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff81294732)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8129d188)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff812a5eff)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81215484)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/swap.c (ffffffff81224fcf)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff8122ae43)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff8124aeeb)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/hugetlb.c (ffffffff81288081)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff8128fbfa)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff8129c523)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff8129f6fb)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812a7ef1)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff812b09e3)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812b87f9)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff812c1657)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8122280f)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/swap.c (ffffffff81232d9f)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff81238d13)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff812593db)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/hugetlb.c (ffffffff81297c81)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff8129f98a)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff812abf82)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812b0a9b)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812b93e5)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff812c2443)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812ca6d9)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff812d3587)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8124ff3d)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/swap.c (ffffffff812602ef)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff81267817)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff81287e6b)
Location: include/linux/page_ref.h:164
Inline: True
```
```
In mm/hugetlb.c (ffffffff812cb341)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff812d3ffa)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff812e13e2)
Location: include/linux/page_ref.h:164
Inline: True
```
```
In mm/migrate.c (ffffffff812e6bdb)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812edf43)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff812f5e16)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/memcontrol.c:mc_handle_present_pte
```
```
In mm/memory-failure.c (ffffffff81300379)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff81309252)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125a147)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/swap.c (ffffffff8126a41f)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff812725fd)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/compaction.c (ffffffff8128cb89)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8129182b)
Location: include/linux/page_ref.h:164
Inline: True
```
```
In mm/hugetlb.c (ffffffff812d6f7a)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff812df9ea)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff812ec29a)
Location: include/linux/page_ref.h:164
Inline: True
```
```
In mm/migrate.c (ffffffff812f1f2b)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812f95b3)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff813050d1)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8130c629)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/memory-failure.c:__get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff813150a6)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125e112)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
```
```
In mm/swap.c (ffffffff8126f535)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff812777ca)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/compaction.c (ffffffff812919e1)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8129754a)
Location: include/linux/page_ref.h:164
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff812c69bd)
Location: include/linux/page_ref.h:164
Inline: True
```
```
In mm/hugetlb.c (ffffffff812de579)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/hugetlb.c:get_hwpoison_huge_page
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff812e6c0a)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff812f8266)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff813003a5)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff8130a5c0)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff813143d1)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_idle.c (ffffffff8131b79c)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
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
In mm/filemap.c (ffffffff8129a83b)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
```
```
In mm/swap.c (ffffffff812ac685)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff812b5179)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/compaction.c (ffffffff812d12a8)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff812d7efe)
Location: include/linux/page_ref.h:164
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff8130b460)
Location: include/linux/page_ref.h:164
Inline: True
```
```
In mm/hugetlb.c (ffffffff81325869)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/hugetlb.c:get_hwpoison_huge_page
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff8132eb3a)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff813428bc)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff8134a00d)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff81355d1d)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8135f7be)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_idle.c (ffffffff81368a6c)
Location: include/linux/page_ref.h:164
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
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
In mm/filemap.c (ffffffff812f148a)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_get_folio
```
```
In mm/vmscan.c (ffffffff8130d67c)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/compaction.c (ffffffff81330a57)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff81337e0c)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/gup.c:try_get_folio
```
```
In mm/memory_hotplug.c (ffffffff813741b4)
Location: include/linux/page_ref.h:236
Inline: True
```
```
In mm/hugetlb.c (ffffffff81394462)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/hugetlb.c:get_hwpoison_huge_page
  - mm/hugetlb.c:isolate_hugetlb
```
```
In mm/ksm.c (ffffffff8139ec09)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff813b2ff5)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff813c0a59)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff813ce822)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff813dd085)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_idle.c (ffffffff813e65ca)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
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
In mm/filemap.c (ffffffff8135be2a)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_get_folio
```
```
In mm/vmscan.c (ffffffff81379c00)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_folio
  - mm/vmscan.c:isolate_lru_folios
```
```
In mm/compaction.c (ffffffff813a7685)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff813af483)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory_hotplug.c (ffffffff813f1c87)
Location: include/linux/page_ref.h:236
Inline: True
```
```
In mm/hugetlb.c (ffffffff81412ebf)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/hugetlb.c:get_hwpoison_huge_page
  - mm/hugetlb.c:isolate_hugetlb
```
```
In mm/ksm.c (ffffffff8141e249)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff81433435)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff814387f2)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_range
```
```
In mm/huge_memory.c (ffffffff81442961)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff81453286)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81463e8b)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_idle.c (ffffffff8146e0ba)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
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
In mm/filemap.c (ffffffff8138e109)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_get_entry
```
```
In mm/vmscan.c (ffffffff813acdb8)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_folios
```
```
In mm/compaction.c (ffffffff813daea3)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff813e3b92)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff813ea8d0)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
```
```
In mm/memory_hotplug.c (ffffffff81425832)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/hugetlb.c (ffffffff814464e3)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/hugetlb.c:get_hwpoison_hugetlb_folio
  - mm/hugetlb.c:isolate_hugetlb
```
```
In mm/ksm.c (ffffffff81452ed9)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff81469125)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff8146e4f2)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_range
```
```
In mm/huge_memory.c (ffffffff81478295)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff81488ede)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff814999a2)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_idle.c (ffffffff814a2acb)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_folio
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
In mm/filemap.c (ffffffff813b905f)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_folio
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_get_entry
```
```
In mm/vmscan.c (ffffffff813d63e5)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_folios
```
```
In mm/compaction.c (ffffffff81404d9a)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8140e402)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff81416ffc)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
```
```
In mm/memory_hotplug.c (ffffffff81452a84)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/hugetlb.c (ffffffff8147ff83)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/hugetlb.c:get_hwpoison_hugetlb_folio
  - mm/hugetlb.c:isolate_hugetlb
```
```
In mm/ksm.c (ffffffff8148d739)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff81498045)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff8149ee82)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_range
```
```
In mm/huge_memory.c (ffffffff814a79d5)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff814b45e3)
Location: include/linux/page_ref.h:236
Inline: True
```
```
In mm/memory-failure.c (ffffffff814c9143)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_idle.c (ffffffff814d395b)
Location: include/linux/page_ref.h:236
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_folio
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102afe0c)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/swap.c (ffff8000102c2d78)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffff8000102c9b8c)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffff8000102f1188)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/hugetlb.c (ffff800010335fd4)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffff80001033f040)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffff800010350da0)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffff800010359b24)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffff800010363f6c)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffff80001036e4d0)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffff800010379114)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
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
In mm/filemap.c (c04dcc60)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/swap.c (c04eded8)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (c04f3a8c)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/ksm.c (c0545484)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (c055249c)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/memcontrol.c (c05562bc)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/page_idle.c (c056468c)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000364dd4)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/swap.c (c00000000037d010)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (c000000000386218)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (c0000000003b7830)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/hugetlb.c (c0000000004107dc)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (c00000000041b44c)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (c00000000042e1d4)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (c000000000437028)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (c0000000004432ac)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (c000000000450d74)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (c00000000045de5c)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (c00000000046c008)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d536a)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/swap.c (ffffffe0001e40ac)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffe0001e8e68)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/hugetlb.c (ffffffe000232126)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffe0002339da)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffe00023f760)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/memcontrol.c (ffffffe000241e06)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/page_idle.c (ffffffe00025095c)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121ae5f)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/swap.c (ffffffff8122b3ef)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff81231363)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff81251a2b)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/hugetlb.c (ffffffff81290261)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff81297f6a)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff812a4562)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812a907b)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812b19c5)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff812baa23)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812c2cb9)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff812cbb67)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8120e05f)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/swap.c (ffffffff8121e4df)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff81224423)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff812448d4)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/hugetlb.c (ffffffff81281ef1)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff81289b2a)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff81296032)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff8129a9f1)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812a2d95)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff812abbcf)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812b3d09)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff812bc9e7)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81218bff)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/swap.c (ffffffff8122918f)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff8122f103)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff8124f7cb)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/hugetlb.c (ffffffff8128e071)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff81295d7a)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff812a2372)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812a6e8b)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812af7d5)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff812b8833)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812c0ac9)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff812c9977)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81227cf4)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/swap.c (ffffffff812384ef)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff8123e513)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff8125f13b)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/hugetlb.c (ffffffff8129de13)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff812a5b8a)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff812b26d2)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812b71bd)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812bfb15)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff812c8e73)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812d1589)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff812da677)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
</details>
</li>
</ul>

## Differences
