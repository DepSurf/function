# Function: <code>compound_order</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81194455)
Location: include/linux/mm.h:553
Inline: True
Inline callers:
  - mm/page_alloc.c:free_compound_page
  - mm/page_alloc.c:__free_page_frag
```
```
In mm/compaction.c (ffffffff811b57bb)
Location: include/linux/mm.h:553
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/rmap.c (ffffffff811ca5ef)
Location: include/linux/mm.h:553
Inline: True
Inline callers:
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:__page_check_address
  - mm/rmap.c:page_mapped_in_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:rmap_walk
```
```
In mm/madvise.c (ffffffff811d1dd1)
Location: include/linux/mm.h:553
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/hugetlb.c (ffffffff811da1d6)
Location: include/linux/mm.h:553
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
  - mm/hugetlb.c:putback_active_hugepage
```
```
In mm/mempolicy.c (ffffffff811e027f)
Location: include/linux/mm.h:553
Inline: True
```
```
In mm/slub.c (ffffffff811e8695)
Location: include/linux/mm.h:553
Inline: True
Inline callers:
  - mm/slub.c:on_freelist
  - mm/slub.c:ksize
  - mm/slub.c:check_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:kfree
```
```
In mm/memory_hotplug.c (ffffffff8181a46a)
Location: include/linux/mm.h:553
Inline: True
```
```
In mm/migrate.c (ffffffff811f085d)
Location: include/linux/mm.h:553
Inline: True
Inline callers:
  - mm/migrate.c:new_page_node
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff811f3d0c)
Location: include/linux/mm.h:553
Inline: True
Inline callers:
  - mm/huge_memory.c:get_huge_zero_page
```
```
In mm/memcontrol.c (ffffffff811fd983)
Location: include/linux/mm.h:553
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_list
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/hugetlb_cgroup.c (ffffffff81200fdf)
Location: include/linux/mm.h:553
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffffffff812015a6)
Location: include/linux/mm.h:553
Inline: True
Inline callers:
  - mm/memory-failure.c:set_page_hwpoison_huge_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
```
In mm/page_isolation.c (ffffffff8120410f)
Location: include/linux/mm.h:553
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a1d5d)
Location: include/linux/mm.h:600
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
```
```
In mm/page_alloc.c (ffffffff811a784b)
Location: include/linux/mm.h:600
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_page_frag
  - mm/page_alloc.c:free_compound_page
```
```
In mm/truncate.c (ffffffff811b4531)
Location: include/linux/mm.h:600
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811c0ce1)
Location: include/linux/mm.h:600
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/compaction.c (ffffffff811cfd37)
Location: include/linux/mm.h:600
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/debug.c (ffffffff811d4570)
Location: include/linux/mm.h:600
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/rmap.c (ffffffff811e6c0e)
Location: include/linux/mm.h:600
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:page_mapped_in_vma
  - mm/rmap.c:__page_check_address
  - mm/rmap.c:page_address_in_vma
```
```
In mm/madvise.c (ffffffff811ef8b2)
Location: include/linux/mm.h:600
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/hugetlb.c (ffffffff811fe1ee)
Location: include/linux/mm.h:600
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff811fe55f)
Location: include/linux/mm.h:600
Inline: True
```
```
In mm/slub.c (ffffffff8120aec3)
Location: include/linux/mm.h:600
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:kmem_cache_free_bulk
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/memory_hotplug.c (ffffffff8120ed20)
Location: include/linux/mm.h:600
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff8120fc16)
Location: include/linux/mm.h:600
Inline: True
Inline callers:
  - mm/migrate.c:new_page_node
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff8121408f)
Location: include/linux/mm.h:600
Inline: True
Inline callers:
  - mm/huge_memory.c:get_huge_zero_page
```
```
In mm/memcontrol.c (ffffffff812215e1)
Location: include/linux/mm.h:600
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_list
  - mm/memcontrol.c:uncharge_list
```
```
In mm/hugetlb_cgroup.c (ffffffff81225c6e)
Location: include/linux/mm.h:600
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff81227b81)
Location: include/linux/mm.h:600
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:set_page_hwpoison_huge_page
```
```
In mm/page_isolation.c (ffffffff812290c2)
Location: include/linux/mm.h:600
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In fs/proc/task_mmu.c (ffffffff812a4501)
Location: include/linux/mm.h:600
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In mm/filemap.c (ffffffff811b1bd7)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
```
```
In mm/page_alloc.c (ffffffff811b7c35)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:free_compound_page
```
```
In mm/shmem.c (ffffffff811d12dc)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/compaction.c (ffffffff811dfd6d)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/debug.c (ffffffff811e45ff)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffff811f6e0d)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff811f7fae)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:page_mapped_in_vma
  - mm/rmap.c:__page_check_address
  - mm/rmap.c:page_address_in_vma
```
```
In mm/madvise.c (ffffffff812001c1)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/hugetlb.c (ffffffff8120ecbe)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff8120f29f)
Location: include/linux/mm.h:587
Inline: True
```
```
In mm/slub.c (ffffffff8121cf0e)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:kmem_cache_free_bulk
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/memory_hotplug.c (ffffffff81220e04)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff81221d4c)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - mm/migrate.c:new_page_node
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff81225f2c)
Location: include/linux/mm.h:587
Inline: True
```
```
In mm/memcontrol.c (ffffffff81233d51)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_list
  - mm/memcontrol.c:uncharge_list
```
```
In mm/hugetlb_cgroup.c (ffffffff8123824e)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff8123a10e)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:set_page_hwpoison_huge_page
```
```
In mm/page_isolation.c (ffffffff8123b662)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In fs/proc/task_mmu.c (ffffffff812b9e61)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In mm/filemap.c (ffffffff811b7e1b)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
```
```
In mm/page_alloc.c (ffffffff811bfa76)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:free_compound_page
```
```
In mm/shmem.c (ffffffff811d9d3d)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/compaction.c (ffffffff811e9a6e)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/debug.c (ffffffff811eea43)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffff81202277)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8120350e)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/madvise.c (ffffffff8120adab)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/swap_state.c (ffffffff8120bc6c)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/hugetlb.c (ffffffff8121a55e)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff8121abdf)
Location: include/linux/mm.h:643
Inline: True
```
```
In mm/slub.c (ffffffff81228fee)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/memory_hotplug.c (ffffffff8122c730)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff8122d9ac)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/migrate.c:new_page_node
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812318ec)
Location: include/linux/mm.h:643
Inline: True
```
```
In mm/memcontrol.c (ffffffff8123f581)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_list
  - mm/memcontrol.c:uncharge_list
```
```
In mm/hugetlb_cgroup.c (ffffffff81243eb6)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff81244803)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffffffff81247284)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In fs/proc/task_mmu.c (ffffffff812c7551)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In lib/iov_iter.c (ffffffff81465c10)
Location: include/linux/mm.h:643
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
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
In mm/filemap.c (ffffffff811cc4aa)
Location: include/linux/mm.h:660
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
```
```
In mm/page_alloc.c (ffffffff811d45a9)
Location: include/linux/mm.h:660
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:free_compound_page
```
```
In mm/shmem.c (ffffffff811efa1f)
Location: include/linux/mm.h:660
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/compaction.c (ffffffff811ffdba)
Location: include/linux/mm.h:660
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/debug.c (ffffffff81204eb3)
Location: include/linux/mm.h:660
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffff8121ae77)
Location: include/linux/mm.h:660
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8121c059)
Location: include/linux/mm.h:660
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/madvise.c (ffffffff8122412c)
Location: include/linux/mm.h:660
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/swap_state.c (ffffffff8122525c)
Location: include/linux/mm.h:660
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/hugetlb.c (ffffffff812356ce)
Location: include/linux/mm.h:660
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff81235db3)
Location: include/linux/mm.h:660
Inline: True
```
```
In mm/slub.c (ffffffff81242ef9)
Location: include/linux/mm.h:660
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/memory_hotplug.c (ffffffff81989bf2)
Location: include/linux/mm.h:660
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff812494e4)
Location: include/linux/mm.h:660
Inline: True
Inline callers:
  - mm/migrate.c:new_page_node
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff8124f5a0)
Location: include/linux/mm.h:660
Inline: True
```
```
In mm/memcontrol.c (ffffffff8125f31f)
Location: include/linux/mm.h:660
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff81263d16)
Location: include/linux/mm.h:660
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff812646a7)
Location: include/linux/mm.h:660
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffffffff812673d8)
Location: include/linux/mm.h:660
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In fs/proc/task_mmu.c (ffffffff812eae31)
Location: include/linux/mm.h:660
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In lib/iov_iter.c (ffffffff81491d1d)
Location: include/linux/mm.h:660
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
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
In mm/filemap.c (ffffffff811ed890)
Location: include/linux/mm.h:702
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
```
```
In mm/page_alloc.c (ffffffff811fa2d8)
Location: include/linux/mm.h:702
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:free_compound_page
```
```
In mm/shmem.c (ffffffff81210ff0)
Location: include/linux/mm.h:702
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/compaction.c (ffffffff812211db)
Location: include/linux/mm.h:702
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/debug.c (ffffffff81225dee)
Location: include/linux/mm.h:702
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffff8123ccce)
Location: include/linux/mm.h:702
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8123e0ee)
Location: include/linux/mm.h:702
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/madvise.c (ffffffff81244e8a)
Location: include/linux/mm.h:702
Inline: True
Inline callers:
  - mm/madvise.c:madvise_inject_error
```
```
In mm/swap_state.c (ffffffff812477f5)
Location: include/linux/mm.h:702
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/hugetlb.c (ffffffff81258715)
Location: include/linux/mm.h:702
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff8125c129)
Location: include/linux/mm.h:702
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/slub.c (ffffffff812688ce)
Location: include/linux/mm.h:702
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/memory_hotplug.c (ffffffff819e65e5)
Location: include/linux/mm.h:702
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff81270cf5)
Location: include/linux/mm.h:702
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff81273140)
Location: include/linux/mm.h:702
Inline: True
```
```
In mm/memcontrol.c (ffffffff8128381b)
Location: include/linux/mm.h:702
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff81288025)
Location: include/linux/mm.h:702
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff812887bb)
Location: include/linux/mm.h:702
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:add_to_kill
```
```
In mm/page_isolation.c (ffffffff8128bd6b)
Location: include/linux/mm.h:702
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In fs/proc/task_mmu.c (ffffffff81318481)
Location: include/linux/mm.h:702
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In lib/iov_iter.c (ffffffff814c787a)
Location: include/linux/mm.h:702
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
```
```
In net/xdp/xsk.c (ffffffff819cb57a)
Location: include/linux/mm.h:702
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/filemap.c (ffffffff811fee82)
Location: include/linux/mm.h:730
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/page_alloc.c (ffffffff8120c9e9)
Location: include/linux/mm.h:730
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:free_compound_page
```
```
In mm/shmem.c (ffffffff8122309a)
Location: include/linux/mm.h:730
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff812274d1)
Location: include/linux/mm.h:730
Inline: True
```
```
In mm/compaction.c (ffffffff81234228)
Location: include/linux/mm.h:730
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/debug.c (ffffffff812394d8)
Location: include/linux/mm.h:730
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffff8125119e)
Location: include/linux/mm.h:730
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81252681)
Location: include/linux/mm.h:730
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/madvise.c (ffffffff812594da)
Location: include/linux/mm.h:730
Inline: True
Inline callers:
  - mm/madvise.c:madvise_inject_error
```
```
In mm/swap_state.c (ffffffff8125bae6)
Location: include/linux/mm.h:730
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/hugetlb.c (ffffffff8126cde5)
Location: include/linux/mm.h:730
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff812709eb)
Location: include/linux/mm.h:730
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/slub.c (ffffffff8127d370)
Location: include/linux/mm.h:730
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/memory_hotplug.c (ffffffff81a2188f)
Location: include/linux/mm.h:730
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff81285305)
Location: include/linux/mm.h:730
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812876b0)
Location: include/linux/mm.h:730
Inline: True
```
```
In mm/memcontrol.c (ffffffff8129738b)
Location: include/linux/mm.h:730
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff8129cf65)
Location: include/linux/mm.h:730
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff8129da8e)
Location: include/linux/mm.h:730
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:add_to_kill
```
```
In mm/page_isolation.c (ffffffff812a0cce)
Location: include/linux/mm.h:730
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In fs/proc/task_mmu.c (ffffffff8132f354)
Location: include/linux/mm.h:730
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In lib/iov_iter.c (ffffffff814db4ba)
Location: include/linux/mm.h:730
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
```
```
In net/xdp/xsk.c (ffffffff81a047cb)
Location: include/linux/mm.h:730
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/filemap.c (ffffffff812182f9)
Location: include/linux/mm.h:796
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/vmscan.c (ffffffff8122b011)
Location: include/linux/mm.h:796
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81233a26)
Location: include/linux/mm.h:796
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff81237254)
Location: include/linux/mm.h:796
Inline: True
```
```
In mm/compaction.c (ffffffff81243fbf)
Location: include/linux/mm.h:796
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff8124a566)
Location: include/linux/mm.h:796
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8124d7ed)
Location: include/linux/mm.h:796
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
```
```
In mm/page_vma_mapped.c (ffffffff81263481)
Location: include/linux/mm.h:796
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8126480d)
Location: include/linux/mm.h:796
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff81272db7)
Location: include/linux/mm.h:796
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:free_compound_page
```
```
In mm/madvise.c (ffffffff8127541d)
Location: include/linux/mm.h:796
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/swap_state.c (ffffffff81276c93)
Location: include/linux/mm.h:796
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/hugetlb.c (ffffffff81288215)
Location: include/linux/mm.h:796
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff8128bb41)
Location: include/linux/mm.h:796
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/slub.c (ffffffff81298a4a)
Location: include/linux/mm.h:796
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/memory_hotplug.c (ffffffff81a922d0)
Location: include/linux/mm.h:796
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff8129f981)
Location: include/linux/mm.h:796
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812a1fff)
Location: include/linux/mm.h:796
Inline: True
```
```
In mm/memcontrol.c (ffffffff812b2f02)
Location: include/linux/mm.h:796
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff812b8115)
Location: include/linux/mm.h:796
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff812b88f6)
Location: include/linux/mm.h:796
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/page_isolation.c (ffffffff812bbed7)
Location: include/linux/mm.h:796
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In fs/io_uring.c (ffffffff8132e01b)
Location: include/linux/mm.h:796
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In fs/proc/task_mmu.c (ffffffff81356f60)
Location: include/linux/mm.h:796
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In lib/iov_iter.c (ffffffff81506e71)
Location: include/linux/mm.h:796
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
```
```
In net/xdp/xsk.c (ffffffff81a74cf7)
Location: include/linux/mm.h:796
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/filemap.c (ffffffff8122285c)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/vmscan.c (ffffffff81238ee1)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff81241c29)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff812454c7)
Location: include/linux/mm.h:791
Inline: True
```
```
In mm/compaction.c (ffffffff8125247f)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff81258a06)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8125bd1f)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
```
```
In mm/page_vma_mapped.c (ffffffff81271c31)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8127307d)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff81281c17)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:free_compound_page
```
```
In mm/madvise.c (ffffffff81284427)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/swap_state.c (ffffffff81286783)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/hugetlb.c (ffffffff81297e15)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffffffff8129b721)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/slub.c (ffffffff812a88a9)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/memory_hotplug.c (ffffffff81ac9a60)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff812b0d21)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812b33af)
Location: include/linux/mm.h:791
Inline: True
```
```
In mm/memcontrol.c (ffffffff812c49d1)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff812c9ff5)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff812ca7d6)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/page_isolation.c (ffffffff812cddb7)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/memfd.c (ffffffff812d6eb9)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/io_uring.c (ffffffff81341251)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In fs/proc/task_mmu.c (ffffffff8136f530)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In lib/iov_iter.c (ffffffff81524f77)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
```
```
In net/xdp/xsk.c (ffffffff81aab8c7)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/filemap.c (ffffffff8124f33a)
Location: include/linux/mm.h:886
Inline: True
Inline callers:
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:page_cache_delete
  - mm/filemap.c:page_cache_delete
```
```
In mm/vmscan.c (ffffffff81267a17)
Location: include/linux/mm.h:886
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff8126ecea)
Location: include/linux/mm.h:886
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff81273017)
Location: include/linux/mm.h:886
Inline: True
```
```
In mm/compaction.c (ffffffff81282cd8)
Location: include/linux/mm.h:886
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff81287138)
Location: include/linux/mm.h:886
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff81287dd4)
Location: include/linux/mm.h:886
Inline: True
Inline callers:
  - mm/gup.c:put_compound_head
  - mm/gup.c:unpin_user_page
  - mm/gup.c:__unpin_devmap_managed_user_page
```
```
In mm/page_vma_mapped.c (ffffffff812a2261)
Location: include/linux/mm.h:886
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812a6b24)
Location: include/linux/mm.h:886
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff812b400b)
Location: include/linux/mm.h:886
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:free_compound_page
```
```
In mm/madvise.c (ffffffff812b5d12)
Location: include/linux/mm.h:886
Inline: True
Inline callers:
  - mm/madvise.c:madvise_inject_error
```
```
In mm/swap_state.c (ffffffff812b8d11)
Location: include/linux/mm.h:886
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/hugetlb.c (ffffffff812cb4e5)
Location: include/linux/mm.h:886
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:destroy_compound_gigantic_page
```
```
In mm/mempolicy.c (ffffffff812cf2a1)
Location: include/linux/mm.h:886
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/slub.c (ffffffff812ddc0a)
Location: include/linux/mm.h:886
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/memory_hotplug.c (ffffffff812e10ba)
Location: include/linux/mm.h:886
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:scan_movable_pages
```
```
In mm/migrate.c (ffffffff812e26c8)
Location: include/linux/mm.h:886
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:copy_huge_page
```
```
In mm/huge_memory.c (ffffffff812e8747)
Location: include/linux/mm.h:886
Inline: True
Inline callers:
  - mm/huge_memory.c:get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff812f0963)
Location: include/linux/mm.h:886
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff812f999d)
Location: include/linux/mm.h:886
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff812ffd35)
Location: include/linux/mm.h:886
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge_rsvd
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff81300416)
Location: include/linux/mm.h:886
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:collect_procs_file
  - mm/memory-failure.c:collect_procs_anon
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/page_isolation.c (ffffffff813040c7)
Location: include/linux/mm.h:886
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In fs/io_uring.c (ffffffff8137c35a)
Location: include/linux/mm.h:886
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In fs/proc/task_mmu.c (ffffffff813b6bf9)
Location: include/linux/mm.h:886
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In lib/iov_iter.c (ffffffff815897bb)
Location: include/linux/mm.h:886
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
```
```
In net/xdp/xsk.c (ffffffff81ba71d7)
Location: include/linux/mm.h:886
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/filemap.c (ffffffff8125895a)
Location: include/linux/mm.h:919
Inline: True
Inline callers:
  - mm/filemap.c:page_cache_delete
```
```
In mm/truncate.c (ffffffff8126ad98)
Location: include/linux/mm.h:919
Inline: True
```
```
In mm/vmscan.c (ffffffff81270f1f)
Location: include/linux/mm.h:919
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81279d7a)
Location: include/linux/mm.h:919
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/compaction.c (ffffffff8128ccc5)
Location: include/linux/mm.h:919
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff81291390)
Location: include/linux/mm.h:919
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff812919d1)
Location: include/linux/mm.h:919
Inline: True
Inline callers:
  - mm/gup.c:put_compound_head
```
```
In mm/memory.c (ffffffff81297a0f)
Location: include/linux/mm.h:919
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:copy_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812adba5)
Location: include/linux/mm.h:919
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812b1fc4)
Location: include/linux/mm.h:919
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff812bfa9f)
Location: include/linux/mm.h:919
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:free_compound_page
```
```
In mm/madvise.c (ffffffff812c178b)
Location: include/linux/mm.h:919
Inline: True
```
```
In mm/swap_state.c (ffffffff812c4474)
Location: include/linux/mm.h:919
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/hugetlb.c (ffffffff812d7105)
Location: include/linux/mm.h:919
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/mempolicy.c (ffffffff812dad21)
Location: include/linux/mm.h:919
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/slub.c (ffffffff812e6bc1)
Location: include/linux/mm.h:919
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/migrate.c (ffffffff812ed3b0)
Location: include/linux/mm.h:919
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:copy_huge_page
```
```
In mm/huge_memory.c (ffffffff812f7f02)
Location: include/linux/mm.h:919
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:get_huge_zero_page
```
```
In mm/hugetlb_cgroup.c (ffffffff8130c0d5)
Location: include/linux/mm.h:919
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge_rsvd
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff8130d4d1)
Location: include/linux/mm.h:919
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:collect_procs_file
  - mm/memory-failure.c:collect_procs_anon
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In fs/libfs.c (ffffffff81351d97)
Location: include/linux/mm.h:919
Inline: True
```
```
In fs/buffer.c (ffffffff81367617)
Location: include/linux/mm.h:919
Inline: True
```
```
In fs/direct-io.c (ffffffff8136f3bd)
Location: include/linux/mm.h:919
Inline: True
```
```
In fs/mpage.c (ffffffff813712b3)
Location: include/linux/mm.h:919
Inline: True
```
```
In fs/io_uring.c (ffffffff8138a52a)
Location: include/linux/mm.h:919
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
  - fs/io_uring.c:io_buffer_account_pin
```
```
In fs/iomap/buffered-io.c (ffffffff813bbca7)
Location: include/linux/mm.h:919
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813c8003)
Location: include/linux/mm.h:919
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
```
In fs/ext4/inline.c (ffffffff814056e8)
Location: include/linux/mm.h:919
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/inode.c (ffffffff81408427)
Location: include/linux/mm.h:919
Inline: True
```
```
In fs/ext4/move_extent.c (ffffffff81421d2d)
Location: include/linux/mm.h:919
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff8142aed3)
Location: include/linux/mm.h:919
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff8142c6a4)
Location: include/linux/mm.h:919
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff8147e574)
Location: include/linux/mm.h:919
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (ffffffff814917a8)
Location: include/linux/mm.h:919
Inline: True
```
```
In block/bio.c (ffffffff8155aac0)
Location: include/linux/mm.h:919
Inline: True
```
```
In lib/iov_iter.c (ffffffff815a5b0f)
Location: include/linux/mm.h:919
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8183b4f8)
Location: include/linux/mm.h:919
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
```
```
In net/xdp/xsk.c (ffffffff81bb694a)
Location: include/linux/mm.h:919
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/filemap.c (ffffffff8126132d)
Location: include/linux/mm.h:942
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffffffff8126ff4a)
Location: include/linux/mm.h:942
Inline: True
```
```
In mm/vmscan.c (ffffffff81275a54)
Location: include/linux/mm.h:942
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8127eeb1)
Location: include/linux/mm.h:942
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/compaction.c (ffffffff81291e51)
Location: include/linux/mm.h:942
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff81bd9350)
Location: include/linux/mm.h:942
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff812972d4)
Location: include/linux/mm.h:942
Inline: True
Inline callers:
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:put_compound_head
```
```
In mm/memory.c (ffffffff812a17b0)
Location: include/linux/mm.h:942
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:copy_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812b2bc2)
Location: include/linux/mm.h:942
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812b7694)
Location: include/linux/mm.h:942
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff812c51ff)
Location: include/linux/mm.h:942
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:free_compound_page
```
```
In mm/madvise.c (ffffffff812c8681)
Location: include/linux/mm.h:942
Inline: True
```
```
In mm/swap_state.c (ffffffff812cb0f9)
Location: include/linux/mm.h:942
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/hugetlb.c (ffffffff812de6f5)
Location: include/linux/mm.h:942
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:__prep_new_huge_page
  - mm/hugetlb.c:__prep_new_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff812e2581)
Location: include/linux/mm.h:942
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/slub.c (ffffffff812ee373)
Location: include/linux/mm.h:942
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/migrate.c (ffffffff812f3750)
Location: include/linux/mm.h:942
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812fe447)
Location: include/linux/mm.h:942
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hugetlb_cgroup.c (ffffffff813126d5)
Location: include/linux/mm.h:942
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge_rsvd
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff813145da)
Location: include/linux/mm.h:942
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:add_to_kill
```
```
In fs/libfs.c (ffffffff81358ab9)
Location: include/linux/mm.h:942
Inline: True
```
```
In fs/buffer.c (ffffffff8136e059)
Location: include/linux/mm.h:942
Inline: True
```
```
In fs/direct-io.c (ffffffff81375c6f)
Location: include/linux/mm.h:942
Inline: True
```
```
In fs/mpage.c (ffffffff81377c65)
Location: include/linux/mm.h:942
Inline: True
```
```
In fs/io_uring.c (ffffffff813915e2)
Location: include/linux/mm.h:942
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
  - fs/io_uring.c:io_buffer_account_pin
```
```
In fs/iomap/buffered-io.c (ffffffff813c3939)
Location: include/linux/mm.h:942
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813cf033)
Location: include/linux/mm.h:942
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
```
In fs/ext4/inline.c (ffffffff8140ba26)
Location: include/linux/mm.h:942
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/inode.c (ffffffff8140e739)
Location: include/linux/mm.h:942
Inline: True
```
```
In fs/ext4/move_extent.c (ffffffff8142852f)
Location: include/linux/mm.h:942
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff81431a45)
Location: include/linux/mm.h:942
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff81433373)
Location: include/linux/mm.h:942
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff81484048)
Location: include/linux/mm.h:942
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (ffffffff814966ca)
Location: include/linux/mm.h:942
Inline: True
```
```
In block/bio.c (ffffffff815630c7)
Location: include/linux/mm.h:942
Inline: True
```
```
In lib/iov_iter.c (ffffffff815ad9cd)
Location: include/linux/mm.h:942
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8181e703)
Location: include/linux/mm.h:942
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
```
```
In net/xdp/xsk.c (ffffffff81ba58ea)
Location: include/linux/mm.h:942
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/filemap.c (ffffffff8129df93)
Location: include/linux/mm.h:946
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffffffff812ad35b)
Location: include/linux/mm.h:946
Inline: True
```
```
In mm/vmscan.c (ffffffff812b3766)
Location: include/linux/mm.h:946
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff812bd35c)
Location: include/linux/mm.h:946
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/compaction.c (ffffffff812d15db)
Location: include/linux/mm.h:946
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff81cbbd92)
Location: include/linux/mm.h:946
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff812d7c84)
Location: include/linux/mm.h:946
Inline: True
Inline callers:
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:put_compound_head
```
```
In mm/memory.c (ffffffff812e277f)
Location: include/linux/mm.h:946
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:copy_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812f475e)
Location: include/linux/mm.h:946
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812f9da4)
Location: include/linux/mm.h:946
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff8130973f)
Location: include/linux/mm.h:946
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:free_compound_page
```
```
In mm/madvise.c (ffffffff8130d603)
Location: include/linux/mm.h:946
Inline: True
```
```
In mm/swap_state.c (ffffffff813100e5)
Location: include/linux/mm.h:946
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/hugetlb.c (ffffffff81325a55)
Location: include/linux/mm.h:946
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:__prep_new_huge_page
  - mm/hugetlb.c:__prep_new_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_hpage_workfn
```
```
In mm/mempolicy.c (ffffffff813297a4)
Location: include/linux/mm.h:946
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/slub.c (ffffffff813365ae)
Location: include/linux/mm.h:946
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/migrate.c (ffffffff8133dca7)
Location: include/linux/mm.h:946
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In mm/huge_memory.c (ffffffff81347fef)
Location: include/linux/mm.h:946
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hugetlb_cgroup.c (ffffffff8135e135)
Location: include/linux/mm.h:946
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge_rsvd
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff81360752)
Location: include/linux/mm.h:946
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:add_to_kill
```
```
In fs/libfs.c (ffffffff813a70ef)
Location: include/linux/mm.h:946
Inline: True
```
```
In fs/buffer.c (ffffffff813bcdbf)
Location: include/linux/mm.h:946
Inline: True
```
```
In fs/direct-io.c (ffffffff813c20b4)
Location: include/linux/mm.h:946
Inline: True
```
```
In fs/mpage.c (ffffffff813c4306)
Location: include/linux/mm.h:946
Inline: True
```
```
In fs/io_uring.c (ffffffff813df3ee)
Location: include/linux/mm.h:946
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
  - fs/io_uring.c:io_buffer_account_pin
```
```
In fs/iomap/buffered-io.c (ffffffff814121df)
Location: include/linux/mm.h:946
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8142051a)
Location: include/linux/mm.h:946
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
```
In fs/ext4/inline.c (ffffffff8145d276)
Location: include/linux/mm.h:946
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8146160f)
Location: include/linux/mm.h:946
Inline: True
```
```
In fs/ext4/move_extent.c (ffffffff8147c244)
Location: include/linux/mm.h:946
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff81485276)
Location: include/linux/mm.h:946
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff81486506)
Location: include/linux/mm.h:946
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff814db196)
Location: include/linux/mm.h:946
Inline: True
```
```
In fs/fuse/file.c (ffffffff814edf8b)
Location: include/linux/mm.h:946
Inline: True
```
```
In block/bio.c (ffffffff815c6c85)
Location: include/linux/mm.h:946
Inline: True
```
```
In lib/iov_iter.c (ffffffff81614f47)
Location: include/linux/mm.h:946
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff818a8be6)
Location: include/linux/mm.h:946
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
```
```
In net/xdp/xsk.c (ffffffff81c73498)
Location: include/linux/mm.h:946
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/filemap.c (ffffffff812f6a62)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_remove_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
  - mm/filemap.c:trace_event_raw_event_mm_filemap_op_page_cache
```
```
In mm/readahead.c (ffffffff81301ee6)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
```
```
In mm/truncate.c (ffffffff81308594)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/truncate.c:truncate_cleanup_folio
```
```
In mm/vmscan.c (ffffffff8130e511)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff813190f3)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/compaction.c (ffffffff81331c39)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/debug.c (ffffffff81e6da3b)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff81342f65)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/rmap.c (ffffffff8135f0d1)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
```
```
In mm/page_alloc.c (ffffffff8136e032)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:free_compound_page
```
```
In mm/madvise.c (ffffffff81375fdf)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - mm/madvise.c:madvise_inject_error
```
```
In mm/page_io.c (ffffffff8137a501)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/swap_state.c (ffffffff8137aaff)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/hugetlb.c (ffffffff81394745)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_hpage_workfn
```
```
In mm/mempolicy.c (ffffffff81398b88)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
```
```
In mm/slub.c (ffffffff813a7ee2)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:slab_pad_check
```
```
In mm/migrate.c (ffffffff813b2c56)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff813bfb51)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/hugetlb_cgroup.c (ffffffff813d8565)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge_rsvd
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff813dc122)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:add_to_kill
```
```
In mm/page_isolation.c (ffffffff813ddd20)
Location: include/linux/mm.h:679
Inline: True
```
```
In mm/secretmem.c (ffffffff813e3864)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_free_folio
```
```
In mm/usercopy.c (ffffffff813e6cbf)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
```
```
In fs/libfs.c (ffffffff8142c8e5)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - fs/libfs.c:simple_read_folio
```
```
In fs/remap_range.c (ffffffff81441fd3)
Location: include/linux/mm.h:679
Inline: True
```
```
In fs/buffer.c (ffffffff81446c50)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_is_partially_uptodate
  - fs/buffer.c:block_is_partially_uptodate
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:block_invalidate_folio
```
```
In fs/direct-io.c (ffffffff81448f83)
Location: include/linux/mm.h:679
Inline: True
```
```
In fs/mpage.c (ffffffff8144afa6)
Location: include/linux/mm.h:679
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8148a54b)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_invalidate_folio
  - fs/iomap/buffered-io.c:iomap_release_folio
  - fs/iomap/buffered-io.c:iomap_is_partially_uptodate
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_read_folio
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/ext4/inline.c (ffffffff814dbdb6)
Location: include/linux/mm.h:679
Inline: True
```
```
In fs/ext4/inode.c (ffffffff814e0cc4)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:__ext4_journalled_invalidate_folio
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/move_extent.c (ffffffff814fe8d3)
Location: include/linux/mm.h:679
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff815085c6)
Location: include/linux/mm.h:679
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff81509996)
Location: include/linux/mm.h:679
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff8153fd85)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
```
```
In fs/hugetlbfs/inode.c (ffffffff81554873)
Location: include/linux/mm.h:679
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff81568d56)
Location: include/linux/mm.h:679
Inline: True
```
```
In fs/fuse/file.c (ffffffff8157d67b)
Location: include/linux/mm.h:679
Inline: True
```
```
In block/bio.c (ffffffff81671bf3)
Location: include/linux/mm.h:679
Inline: True
```
```
In io_uring/io_uring.c (ffffffff81e90a4f)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_mmap
  - io_uring/io_uring.c:io_buffer_account_pin
```
```
In lib/iov_iter.c (ffffffff816e6be4)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:page_copy_sane
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff819f2b0e)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
```
```
In net/xdp/xsk.c (ffffffff81e16005)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/truncate.c (ffffffff813713b3)
Location: include/linux/mm.h:723
Inline: True
```
```
In mm/shmem.c (ffffffff8138a763)
Location: include/linux/mm.h:723
Inline: True
```
```
In mm/compaction.c (ffffffff813a6dcb)
Location: include/linux/mm.h:723
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff813ade9f)
Location: include/linux/mm.h:723
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff813baf03)
Location: include/linux/mm.h:723
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/rmap.c (ffffffff813d9707)
Location: include/linux/mm.h:723
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
```
```
In mm/page_alloc.c (ffffffff813ea372)
Location: include/linux/mm.h:723
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:free_compound_page
```
```
In mm/madvise.c (ffffffff813f3856)
Location: include/linux/mm.h:723
Inline: True
Inline callers:
  - mm/madvise.c:madvise_inject_error
```
```
In mm/page_io.c (ffffffff813f7fa5)
Location: include/linux/mm.h:723
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:swap_writepage_fs
```
```
In mm/hugetlb.c (ffffffff8140aea4)
Location: include/linux/mm.h:723
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:free_hpage_workfn
```
```
In mm/migrate.c (ffffffff81433046)
Location: include/linux/mm.h:723
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8143e36c)
Location: include/linux/mm.h:723
Inline: True
Inline callers:
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff8144ac37)
Location: include/linux/mm.h:723
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/memory-failure.c (ffffffff81460c4f)
Location: include/linux/mm.h:723
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/secretmem.c (ffffffff8146b0c0)
Location: include/linux/mm.h:723
Inline: True
```
```
In fs/libfs.c (ffffffff814b9b5f)
Location: include/linux/mm.h:723
Inline: True
Inline callers:
  - fs/libfs.c:zero_user_segments
  - fs/libfs.c:zero_user_segments
```
```
In fs/buffer.c (ffffffff814d256f)
Location: include/linux/mm.h:723
Inline: True
Inline callers:
  - fs/buffer.c:zero_user_segments
  - fs/buffer.c:zero_user_segments
```
```
In fs/direct-io.c (ffffffff814d7273)
Location: include/linux/mm.h:723
Inline: True
```
```
In fs/mpage.c (ffffffff814d97d6)
Location: include/linux/mm.h:723
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8151bdbf)
Location: include/linux/mm.h:723
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:zero_user_segments
  - fs/iomap/buffered-io.c:zero_user_segments
```
```
In fs/ext4/inline.c (ffffffff81574d36)
Location: include/linux/mm.h:723
Inline: True
```
```
In fs/ext4/inode.c (ffffffff815799bf)
Location: include/linux/mm.h:723
Inline: True
Inline callers:
  - fs/ext4/inode.c:zero_user_segments
  - fs/ext4/inode.c:zero_user_segments
```
```
In fs/ext4/move_extent.c (ffffffff81599113)
Location: include/linux/mm.h:723
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff815a30b6)
Location: include/linux/mm.h:723
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff815a4606)
Location: include/linux/mm.h:723
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff815f6343)
Location: include/linux/mm.h:723
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff8160c6c6)
Location: include/linux/mm.h:723
Inline: True
```
```
In fs/fuse/file.c (ffffffff8162317b)
Location: include/linux/mm.h:723
Inline: True
```
```
In block/bio.c (ffffffff8172d4b3)
Location: include/linux/mm.h:723
Inline: True
```
```
In io_uring/io_uring.c (ffffffff81789c13)
Location: include/linux/mm.h:723
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_mmap
```
```
In io_uring/rsrc.c (ffffffff817a0b2f)
Location: include/linux/mm.h:723
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_buffer_account_pin
```
```
In lib/iov_iter.c (ffffffff817d14c4)
Location: include/linux/mm.h:723
Inline: True
Inline callers:
  - lib/iov_iter.c:page_copy_sane
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81b70928)
Location: include/linux/mm.h:723
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
```
```
In net/xdp/xsk.c (ffffffff81fed052)
Location: include/linux/mm.h:723
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/truncate.c (ffffffff813a3584)
Location: include/linux/mm.h:982
Inline: True
```
```
In mm/shmem.c (ffffffff813bcaf4)
Location: include/linux/mm.h:982
Inline: True
```
```
In mm/compaction.c (ffffffff813db296)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff813e227a)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff813efa32)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/rmap.c (ffffffff8140dfa4)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
```
```
In mm/page_alloc.c (ffffffff8141f358)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:free_compound_page
```
```
In mm/madvise.c (ffffffff814293bb)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
```
```
In mm/page_io.c (ffffffff8142b1df)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage_bdev_sync
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_bdev_sync
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:swap_writepage_fs
```
```
In mm/hugetlb.c (ffffffff8143e551)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:free_hpage_workfn
```
```
In mm/migrate.c (ffffffff814689c0)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81473b6c)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff81480e70)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/memory-failure.c (ffffffff8149604c)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - mm/memory-failure.c:__add_to_kill
```
```
In mm/secretmem.c (ffffffff8149ff81)
Location: include/linux/mm.h:982
Inline: True
```
```
In fs/libfs.c (ffffffff814eeaff)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - fs/libfs.c:zero_user_segments
  - fs/libfs.c:zero_user_segments
```
```
In fs/buffer.c (ffffffff81508d1f)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - fs/buffer.c:zero_user_segments
  - fs/buffer.c:zero_user_segments
```
```
In fs/mpage.c (ffffffff8150d844)
Location: include/linux/mm.h:982
Inline: True
```
```
In fs/direct-io.c (ffffffff81510324)
Location: include/linux/mm.h:982
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff815540cf)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:zero_user_segments
  - fs/iomap/buffered-io.c:zero_user_segments
```
```
In fs/ext4/inline.c (ffffffff815acc14)
Location: include/linux/mm.h:982
Inline: True
```
```
In fs/ext4/inode.c (ffffffff815b094f)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - fs/ext4/inode.c:zero_user_segments
  - fs/ext4/inode.c:zero_user_segments
```
```
In fs/ext4/move_extent.c (ffffffff815cfbf4)
Location: include/linux/mm.h:982
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff815d9aa4)
Location: include/linux/mm.h:982
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff815daf54)
Location: include/linux/mm.h:982
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff8162e4c4)
Location: include/linux/mm.h:982
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff816445a6)
Location: include/linux/mm.h:982
Inline: True
```
```
In fs/fuse/file.c (ffffffff8165b5e6)
Location: include/linux/mm.h:982
Inline: True
```
```
In block/bio.c (ffffffff81769774)
Location: include/linux/mm.h:982
Inline: True
```
```
In io_uring/io_uring.c (ffffffff817c9a0a)
Location: include/linux/mm.h:982
Inline: True
```
```
In io_uring/rsrc.c (ffffffff817e1d7c)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_buffer_account_pin
```
```
In lib/iov_iter.c (ffffffff8181406c)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_to_iter_nofault
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81bc410d)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
```
```
In net/core/datagram.c (ffffffff81e20471)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
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
In arch/x86/mm/pgtable.c (0)
Location: include/linux/mm.h:1070
Inline: False
```
```
In mm/truncate.c (ffffffff813cd133)
Location: include/linux/mm.h:1070
Inline: True
```
```
In mm/shmem.c (ffffffff813e7942)
Location: include/linux/mm.h:1070
Inline: True
```
```
In mm/compaction.c (ffffffff81404fae)
Location: include/linux/mm.h:1070
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff8140ca57)
Location: include/linux/mm.h:1070
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff8141ca7a)
Location: include/linux/mm.h:1070
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
```
```
In mm/pgtable-generic.c (ffffffff81435844)
Location: include/linux/mm.h:1070
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pte_free_now
```
```
In mm/rmap.c (ffffffff8143a773)
Location: include/linux/mm.h:1070
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
```
```
In mm/page_alloc.c (ffffffff8144c015)
Location: include/linux/mm.h:1070
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/madvise.c (ffffffff81462beb)
Location: include/linux/mm.h:1070
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
```
```
In mm/hugetlb_vmemmap.c (ffffffff81480cd3)
Location: include/linux/mm.h:1070
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_split_pmd
```
```
In mm/mempolicy.c (ffffffff8148716b)
Location: include/linux/mm.h:1070
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
```
```
In mm/migrate.c (ffffffff81498c9c)
Location: include/linux/mm.h:1070
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff814a4f49)
Location: include/linux/mm.h:1070
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff814aee3e)
Location: include/linux/mm.h:1070
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff814c56fa)
Location: include/linux/mm.h:1070
Inline: True
Inline callers:
  - mm/memory-failure.c:__add_to_kill
```
```
In mm/secretmem.c (ffffffff814cf6d1)
Location: include/linux/mm.h:1070
Inline: True
```
```
In fs/libfs.c (ffffffff81522ae2)
Location: include/linux/mm.h:1070
Inline: True
Inline callers:
  - fs/libfs.c:zero_user_segments
  - fs/libfs.c:zero_user_segments
```
```
In fs/buffer.c (ffffffff8153da00)
Location: include/linux/mm.h:1070
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:decrypt_bh
  - fs/buffer.c:verify_bh
  - fs/buffer.c:zero_user_segments
  - fs/buffer.c:zero_user_segments
```
```
In fs/mpage.c (ffffffff81542563)
Location: include/linux/mm.h:1070
Inline: True
```
```
In fs/direct-io.c (ffffffff815447d3)
Location: include/linux/mm.h:1070
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:1070
Inline: False
```
```
In fs/crypto/inline_crypt.c (ffffffff8156fc2b)
Location: include/linux/mm.h:1070
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:bh_get_inode_and_lblk_num
```
```
In fs/iomap/buffered-io.c (ffffffff8158a0b2)
Location: include/linux/mm.h:1070
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:zero_user_segments
  - fs/iomap/buffered-io.c:zero_user_segments
```
```
In fs/ext4/inline.c (ffffffff815e5b41)
Location: include/linux/mm.h:1070
Inline: True
```
```
In fs/ext4/inode.c (ffffffff815ed71a)
Location: include/linux/mm.h:1070
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:zero_user_segments
  - fs/ext4/inode.c:zero_user_segments
```
```
In fs/ext4/move_extent.c (ffffffff81608483)
Location: include/linux/mm.h:1070
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff816131e3)
Location: include/linux/mm.h:1070
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff81613783)
Location: include/linux/mm.h:1070
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff8164c546)
Location: include/linux/mm.h:1070
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_freeze_jh_data
```
```
In fs/jbd2/commit.c (ffffffff816500de)
Location: include/linux/mm.h:1070
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/hugetlbfs/inode.c (ffffffff81667983)
Location: include/linux/mm.h:1070
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff8167dad6)
Location: include/linux/mm.h:1070
Inline: True
```
```
In fs/fuse/file.c (ffffffff816952c6)
Location: include/linux/mm.h:1070
Inline: True
```
```
In block/bio.c (ffffffff817ab993)
Location: include/linux/mm.h:1070
Inline: True
```
```
In io_uring/io_uring.c (ffffffff8180f59e)
Location: include/linux/mm.h:1070
Inline: True
```
```
In io_uring/rsrc.c (ffffffff81826122)
Location: include/linux/mm.h:1070
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_buffer_account_pin
```
```
In lib/iov_iter.c (ffffffff818584f7)
Location: include/linux/mm.h:1070
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_to_iter_nofault
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81c1893c)
Location: include/linux/mm.h:1070
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
```
```
In net/core/datagram.c (ffffffff81ede34e)
Location: include/linux/mm.h:1070
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
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
In arch/arm64/mm/flush.c (ffff8000100add20)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - arch/arm64/mm/flush.c:__sync_icache_dcache
```
```
In mm/filemap.c (ffff8000102afe6c)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/vmscan.c (ffff8000102c9d58)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffff8000102d40f8)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffff8000102d8444)
Location: include/linux/mm.h:791
Inline: True
```
```
In mm/compaction.c (ffff8000102eb0d0)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffff8000102f07dc)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffff8000102f30fc)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
```
```
In mm/page_vma_mapped.c (ffff800010307738)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffff800010308dc4)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffff80001031a35c)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:free_compound_page
```
```
In mm/madvise.c (ffff80001031e850)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/madvise.c:__arm64_sys_madvise
```
```
In mm/swap_state.c (ffff800010320f20)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/hugetlb.c (ffff800010336278)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffff80001033a6b4)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/slub.c (ffff80001034a2ac)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/migrate.c (ffff800010351204)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffff8000103543ac)
Location: include/linux/mm.h:791
Inline: True
```
```
In mm/memcontrol.c (ffff800010367574)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
```
```
In mm/hugetlb_cgroup.c (ffff80001036d920)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffff80001036def0)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:add_to_kill
```
```
In mm/page_isolation.c (ffff800010372300)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/memfd.c (ffff80001037be44)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/io_uring.c (ffff800010400374)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In fs/proc/task_mmu.c (ffff800010438ad8)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In lib/iov_iter.c (ffff80001062f2e8)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
```
```
In net/xdp/xsk.c (ffff800010d7dfa0)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In arch/arm/mm/flush.c (c031eb88)
Location: include/linux/mm.h:791
Inline: True
```
```
In mm/filemap.c (c04dccbc)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/vmscan.c (c04f3c38)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (c04fc2b8)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (c04ff6ec)
Location: include/linux/mm.h:791
Inline: True
```
```
In mm/compaction.c (c050e6f4)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (0)
Location: include/linux/mm.h:791
Inline: True
```
```
In mm/gup.c (c0515470)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/mm.h:791
Inline: True
```
```
In mm/rmap.c (c05264a0)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/page_alloc.c (c0531990)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:free_compound_page
```
```
In mm/swap_state.c (c053986c)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/slub.c (c054ebe4)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/memcontrol.c (c0558d58)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
```
```
In mm/memfd.c (c0566bec)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/io_uring.c (c05d2704)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:791
Inline: True
```
```
In lib/iov_iter.c (c07d5c84)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
```
```
In net/xdp/xsk.c (c0e78b2c)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In arch/powerpc/mm/book3s64/iommu_api.c (c0000000000a0b70)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_do_alloc
```
```
In arch/powerpc/mm/hugetlbpage.c (c0000000000a6608)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:flush_dcache_icache_hugepage
```
```
In mm/filemap.c (c000000000364e40)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/vmscan.c (c000000000386550)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (c000000000393414)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (c000000000398244)
Location: include/linux/mm.h:791
Inline: True
```
```
In mm/compaction.c (c0000000003ac580)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (c0000000003b5348)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (c0000000003b9b40)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
```
```
In mm/page_vma_mapped.c (c0000000003d62e8)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (c0000000003d8068)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (c0000000003ed470)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:free_compound_page
```
```
In mm/madvise.c (c0000000003f2bd4)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
```
```
In mm/swap_state.c (c0000000003f63f8)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/hugetlb.c (c000000000410b3c)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (c000000000414ed8)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/slub.c (c000000000429170)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/memory_hotplug.c (c000000000430924)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (c000000000437510)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (c00000000043b0b8)
Location: include/linux/mm.h:791
Inline: True
```
```
In mm/memcontrol.c (c000000000454b80)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
```
```
In mm/hugetlb_cgroup.c (c00000000045da98)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (c00000000045ef0c)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:add_to_kill
```
```
In mm/page_isolation.c (c000000000463c3c)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/memfd.c (c000000000471340)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/io_uring.c (c000000000509a8c)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In fs/proc/task_mmu.c (c00000000054c2e0)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In lib/iov_iter.c (c0000000007d7010)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
```
```
In drivers/vfio/vfio_iommu_spapr_tce.c (c000000000ab2558)
Location: include/linux/mm.h:791
Inline: True
```
```
In net/xdp/xsk.c (c000000000ebdb5c)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/filemap.c (ffffffe0001d53b4)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/vmscan.c (ffffffe0001e8f84)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffe0001eff8e)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffe0001f2cda)
Location: include/linux/mm.h:791
Inline: True
```
```
In mm/compaction.c (ffffffe0001ff5be)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffe000203fe4)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffe000205472)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/page_vma_mapped.c (ffffffe000212902)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffe000213450)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffe00021fcbe)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:free_compound_page
```
```
In mm/swap_state.c (ffffffe0002223f6)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/hugetlb.c (ffffffe0002322b0)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/slub.c (ffffffe00023bc0c)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/migrate.c (ffffffe00023fb28)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/memcontrol.c (ffffffe000245786)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
```
```
In mm/hugetlb_cgroup.c (ffffffe00024a5e0)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/page_isolation.c (ffffffe00024b556)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/memfd.c (ffffffe0002525fc)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/io_uring.c (ffffffe0002acad0)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:791
Inline: True
```
```
In lib/iov_iter.c (ffffffe00045e7c2)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
```
```
In net/xdp/xsk.c (ffffffe0008ab786)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/filemap.c (ffffffff8121aeac)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/vmscan.c (ffffffff81231531)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff8123a279)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff8123db17)
Location: include/linux/mm.h:791
Inline: True
```
```
In mm/compaction.c (ffffffff8124aacf)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff81251056)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8125436f)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
```
```
In mm/page_vma_mapped.c (ffffffff8126a281)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8126b6cd)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff8127a267)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:free_compound_page
```
```
In mm/madvise.c (ffffffff8127ca77)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/swap_state.c (ffffffff8127edd3)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/hugetlb.c (ffffffff812903f5)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffffffff81293d01)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/slub.c (ffffffff812a0e89)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/memory_hotplug.c (ffffffff81a688d0)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff812a9301)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812ab98f)
Location: include/linux/mm.h:791
Inline: True
```
```
In mm/memcontrol.c (ffffffff812bcfb1)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff812c25d5)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff812c2db6)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/page_isolation.c (ffffffff812c6397)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/memfd.c (ffffffff812cf499)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/io_uring.c (ffffffff81339831)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In fs/proc/task_mmu.c (ffffffff81367b10)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In lib/iov_iter.c (ffffffff8151d557)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
```
```
In net/xdp/xsk.c (ffffffff81a4ac57)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/filemap.c (ffffffff8120e0ac)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/vmscan.c (ffffffff812245f1)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff8122d283)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff81230b17)
Location: include/linux/mm.h:791
Inline: True
```
```
In mm/compaction.c (ffffffff8123da6f)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff81243f96)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff81246fbf)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
```
```
In mm/page_vma_mapped.c (ffffffff8125c471)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8125d96d)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff8126c157)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:free_compound_page
```
```
In mm/madvise.c (ffffffff8126e927)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/swap_state.c (ffffffff81270c03)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/hugetlb.c (ffffffff81282085)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffffffff81285911)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/slub.c (ffffffff81292969)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/memory_hotplug.c (ffffffff81a25390)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff8129ac61)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff8129d28f)
Location: include/linux/mm.h:791
Inline: True
```
```
In mm/memcontrol.c (ffffffff812ae0f1)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff812b3625)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff812b3e06)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:add_to_kill
```
```
In mm/page_isolation.c (ffffffff812b73d7)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/memfd.c (ffffffff812c011d)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/io_uring.c (ffffffff8132a561)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In fs/proc/task_mmu.c (ffffffff813587b0)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In lib/iov_iter.c (ffffffff8150d847)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
```
```
In net/xdp/xsk.c (ffffffff81a07847)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/filemap.c (ffffffff81218c4c)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/vmscan.c (ffffffff8122f2d1)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff81238019)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff8123b8b7)
Location: include/linux/mm.h:791
Inline: True
```
```
In mm/compaction.c (ffffffff8124886f)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff8124edf6)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8125210f)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
```
```
In mm/page_vma_mapped.c (ffffffff81268021)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8126946d)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff81278007)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:free_compound_page
```
```
In mm/madvise.c (ffffffff8127a817)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/swap_state.c (ffffffff8127cb73)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/hugetlb.c (ffffffff8128e205)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffffffff81291b11)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/slub.c (ffffffff8129ec99)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/memory_hotplug.c (ffffffff81ad4ce0)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff812a7111)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812a979f)
Location: include/linux/mm.h:791
Inline: True
```
```
In mm/memcontrol.c (ffffffff812badc1)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff812c03e5)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff812c0bc6)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/page_isolation.c (ffffffff812c41a7)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/memfd.c (ffffffff812cd2a9)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/io_uring.c (ffffffff81337301)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In fs/proc/task_mmu.c (ffffffff813655e0)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In lib/iov_iter.c (ffffffff815195e7)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
```
```
In net/xdp/xsk.c (ffffffff81ab6b07)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/filemap.c (ffffffff81227d41)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/vmscan.c (ffffffff8123e6e1)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff81247664)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff8124afc7)
Location: include/linux/mm.h:791
Inline: True
```
```
In mm/compaction.c (ffffffff81258094)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff8125e776)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff81261abf)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
```
```
In mm/page_vma_mapped.c (ffffffff8127799f)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81278f9d)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff81287bf7)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:free_compound_page
```
```
In mm/madvise.c (ffffffff8128a3f7)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/swap_state.c (ffffffff8128c743)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/hugetlb.c (ffffffff8129dfa5)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffffffff812a1921)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/slub.c (ffffffff812aeda5)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/memory_hotplug.c (ffffffff81ae11bb)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff812b7421)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812b9d3f)
Location: include/linux/mm.h:791
Inline: True
```
```
In mm/memcontrol.c (ffffffff812cb511)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff812d0e75)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff812d1686)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/page_isolation.c (ffffffff812d4c67)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/memfd.c (ffffffff812de02f)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/io_uring.c (ffffffff8134a3c1)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In fs/proc/task_mmu.c (ffffffff81378cc0)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In lib/iov_iter.c (ffffffff81532de7)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
```
```
In net/xdp/xsk.c (ffffffff81ac2c47)
Location: include/linux/mm.h:791
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
```
</details>
</li>
</ul>

## Differences
