# Function: <code>page_hstate</code>

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
In mm/rmap.c (ffffffff811caa59)
Location: include/linux/hugetlb.h:430
Inline: True
Inline callers:
  - mm/rmap.c:__page_check_address
```
```
In mm/hugetlb.c (ffffffff811db746)
Location: include/linux/hugetlb.h:430
Inline: True
Inline callers:
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
  - mm/hugetlb.c:putback_active_hugepage
```
```
In mm/mempolicy.c (ffffffff811e027f)
Location: include/linux/hugetlb.h:430
Inline: True
```
```
In mm/migrate.c (ffffffff811f085d)
Location: include/linux/hugetlb.h:430
Inline: True
Inline callers:
  - mm/migrate.c:new_page_node
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_pages
```
```
In mm/hugetlb_cgroup.c (ffffffff812014ae)
Location: include/linux/hugetlb.h:430
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffffffff81201eb3)
Location: include/linux/hugetlb.h:430
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffffffff8120410f)
Location: include/linux/hugetlb.h:430
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
In mm/rmap.c (ffffffff811e789b)
Location: include/linux/hugetlb.h:426
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:__page_check_address
```
```
In mm/hugetlb.c (ffffffff811fe1ee)
Location: include/linux/hugetlb.h:426
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff811fe55f)
Location: include/linux/hugetlb.h:426
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff8120ed20)
Location: include/linux/hugetlb.h:426
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff8120fc16)
Location: include/linux/hugetlb.h:426
Inline: True
Inline callers:
  - mm/migrate.c:new_page_node
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/hugetlb_cgroup.c (ffffffff81225c6e)
Location: include/linux/hugetlb.h:426
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffffffff81226273)
Location: include/linux/hugetlb.h:426
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffffffff812290c2)
Location: include/linux/hugetlb.h:426
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
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
In mm/page_vma_mapped.c (ffffffff811f70c4)
Location: include/linux/hugetlb.h:426
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff811f8c2a)
Location: include/linux/hugetlb.h:426
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:__page_check_address
```
```
In mm/hugetlb.c (ffffffff8120ecbe)
Location: include/linux/hugetlb.h:426
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff8120f29f)
Location: include/linux/hugetlb.h:426
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff81220e04)
Location: include/linux/hugetlb.h:426
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff81221d4c)
Location: include/linux/hugetlb.h:426
Inline: True
Inline callers:
  - mm/migrate.c:new_page_node
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/hugetlb_cgroup.c (ffffffff8123824e)
Location: include/linux/hugetlb.h:426
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffffffff81238843)
Location: include/linux/hugetlb.h:426
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffffffff8123b662)
Location: include/linux/hugetlb.h:426
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
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
In mm/page_vma_mapped.c (ffffffff81201fb4)
Location: include/linux/hugetlb.h:448
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/hugetlb.c (ffffffff8121a55e)
Location: include/linux/hugetlb.h:448
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff8121abdf)
Location: include/linux/hugetlb.h:448
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff8122c730)
Location: include/linux/hugetlb.h:448
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff8122d9ac)
Location: include/linux/hugetlb.h:448
Inline: True
Inline callers:
  - mm/migrate.c:new_page_node
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/hugetlb_cgroup.c (ffffffff81243eb6)
Location: include/linux/hugetlb.h:448
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffffffff81244803)
Location: include/linux/hugetlb.h:448
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffffffff81247284)
Location: include/linux/hugetlb.h:448
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
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
In mm/page_vma_mapped.c (ffffffff8121ab17)
Location: include/linux/hugetlb.h:442
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/hugetlb.c (ffffffff812356ce)
Location: include/linux/hugetlb.h:442
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff81235db3)
Location: include/linux/hugetlb.h:442
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff81247f10)
Location: include/linux/hugetlb.h:442
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff812494e4)
Location: include/linux/hugetlb.h:442
Inline: True
Inline callers:
  - mm/migrate.c:new_page_node
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/hugetlb_cgroup.c (ffffffff81263d16)
Location: include/linux/hugetlb.h:442
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffffffff812646a7)
Location: include/linux/hugetlb.h:442
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffffffff812673d8)
Location: include/linux/hugetlb.h:442
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
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
In mm/page_alloc.c (ffffffff811fa2d8)
Location: include/linux/hugetlb.h:455
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/page_vma_mapped.c (ffffffff8123c9ba)
Location: include/linux/hugetlb.h:455
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/hugetlb.c (ffffffff81258715)
Location: include/linux/hugetlb.h:455
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff8125c129)
Location: include/linux/hugetlb.h:455
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/memory_hotplug.c (ffffffff819e64f5)
Location: include/linux/hugetlb.h:455
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff81270cf5)
Location: include/linux/hugetlb.h:455
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/hugetlb_cgroup.c (ffffffff81288025)
Location: include/linux/hugetlb.h:455
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffffffff812887bb)
Location: include/linux/hugetlb.h:455
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffffffff8128bd6b)
Location: include/linux/hugetlb.h:455
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
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
In mm/page_alloc.c (ffffffff8120c9e9)
Location: include/linux/hugetlb.h:466
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/page_vma_mapped.c (ffffffff81250dc9)
Location: include/linux/hugetlb.h:466
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/hugetlb.c (ffffffff8126cde5)
Location: include/linux/hugetlb.h:466
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff812709eb)
Location: include/linux/hugetlb.h:466
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/memory_hotplug.c (ffffffff81a21959)
Location: include/linux/hugetlb.h:466
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff81285305)
Location: include/linux/hugetlb.h:466
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/hugetlb_cgroup.c (ffffffff8129cf65)
Location: include/linux/hugetlb.h:466
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffffffff8129da8e)
Location: include/linux/hugetlb.h:466
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffffffff812a0cce)
Location: include/linux/hugetlb.h:466
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
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
In mm/gup.c (ffffffff8124a6e4)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/gup.c:new_non_cma_page
```
```
In mm/page_vma_mapped.c (ffffffff812630a6)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/page_alloc.c (ffffffff81272db7)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff81288215)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff8128bb41)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/memory_hotplug.c (ffffffff8129c12a)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff8129f981)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/hugetlb_cgroup.c (ffffffff812b8115)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffffffff812b88f6)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffffffff812bbed7)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
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
In mm/gup.c (ffffffff81258bb4)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/gup.c:new_non_cma_page
```
```
In mm/page_vma_mapped.c (ffffffff81271856)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/page_alloc.c (ffffffff81281c17)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff81297e15)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffffffff8129b721)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/memory_hotplug.c (ffffffff812ac1da)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff812b0d21)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/hugetlb_cgroup.c (ffffffff812c9ff5)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffffffff812ca7d6)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812cddb7)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
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
In mm/page_vma_mapped.c (ffffffff812a1f1c)
Location: include/linux/hugetlb.h:617
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/page_alloc.c (ffffffff812b400b)
Location: include/linux/hugetlb.h:617
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff812cb4e5)
Location: include/linux/hugetlb.h:617
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffffffff812cf2a1)
Location: include/linux/hugetlb.h:617
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/memory_hotplug.c (ffffffff812e10ba)
Location: include/linux/hugetlb.h:617
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff812e26c8)
Location: include/linux/hugetlb.h:617
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:copy_huge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff812ffd35)
Location: include/linux/hugetlb.h:617
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffffffff81300416)
Location: include/linux/hugetlb.h:617
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In mm/page_isolation.c (ffffffff813040c7)
Location: include/linux/hugetlb.h:617
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
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
In mm/page_vma_mapped.c (ffffffff812ad805)
Location: include/linux/hugetlb.h:615
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/page_alloc.c (ffffffff812bfa9f)
Location: include/linux/hugetlb.h:615
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff812d7105)
Location: include/linux/hugetlb.h:615
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffffffff812dad21)
Location: include/linux/hugetlb.h:615
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/migrate.c (ffffffff812ed3b0)
Location: include/linux/hugetlb.h:615
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:copy_huge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff8130c0d5)
Location: include/linux/hugetlb.h:615
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffffffff8130d4d1)
Location: include/linux/hugetlb.h:615
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_hugetlb
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
In mm/page_vma_mapped.c (ffffffff812b2bf6)
Location: include/linux/hugetlb.h:728
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/page_alloc.c (ffffffff812c51ff)
Location: include/linux/hugetlb.h:728
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff812de6f5)
Location: include/linux/hugetlb.h:728
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff812e2581)
Location: include/linux/hugetlb.h:728
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/migrate.c (ffffffff812f3750)
Location: include/linux/hugetlb.h:728
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_page_copy
```
```
In mm/hugetlb_cgroup.c (ffffffff813126d5)
Location: include/linux/hugetlb.h:728
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffffffff813145da)
Location: include/linux/hugetlb.h:728
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_hugetlb
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
In mm/page_vma_mapped.c (ffffffff812f47a0)
Location: include/linux/hugetlb.h:751
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/page_alloc.c (ffffffff8130973f)
Location: include/linux/hugetlb.h:751
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff81325a55)
Location: include/linux/hugetlb.h:751
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff813297a4)
Location: include/linux/hugetlb.h:751
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/migrate.c (ffffffff8133dca7)
Location: include/linux/hugetlb.h:751
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff8135e135)
Location: include/linux/hugetlb.h:751
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffffffff81360752)
Location: include/linux/hugetlb.h:751
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_hugetlb
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
In mm/hugetlb.c (ffffffff81394745)
Location: include/linux/hugetlb.h:781
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff81398b88)
Location: include/linux/hugetlb.h:781
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/migrate.c (ffffffff813b1787)
Location: include/linux/hugetlb.h:781
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff813d8565)
Location: include/linux/hugetlb.h:781
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffffffff813dc122)
Location: include/linux/hugetlb.h:781
Inline: True
Inline callers:
  - mm/memory-failure.c:try_memory_failure_hugetlb
```
```
In mm/page_isolation.c (ffffffff813ddd20)
Location: include/linux/hugetlb.h:781
Inline: True
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
In mm/hugetlb.c (ffffffff81412f97)
Location: include/linux/hugetlb.h:826
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
```
```
In mm/mempolicy.c (ffffffff81418a35)
Location: include/linux/hugetlb.h:826
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/migrate.c (ffffffff814346bb)
Location: include/linux/hugetlb.h:826
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In mm/page_isolation.c (ffffffff814649b8)
Location: include/linux/hugetlb.h:826
Inline: True
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
In mm/page_isolation.c (ffffffff8149a4b8)
Location: include/linux/hugetlb.h:854
Inline: True
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In mm/gup.c (ffff8000102f0cf8)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/gup.c:new_non_cma_page
```
```
In mm/page_vma_mapped.c (ffff8000103074e0)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/page_alloc.c (ffff80001031a35c)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffff800010336278)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffff80001033a6b4)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/migrate.c (ffff800010351204)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/hugetlb_cgroup.c (ffff80001036d920)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffff80001036def0)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffff800010372300)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
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
In mm/page_vma_mapped.c (0)
Location: include/linux/hugetlb.h:644
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/hugetlb.h:644
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/hugetlb.h:644
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/hugetlb.h:644
Inline: True
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
In mm/gup.c (c0000000003b5890)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/gup.c:new_non_cma_page
```
```
In mm/page_vma_mapped.c (c0000000003d5c54)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/page_alloc.c (c0000000003ed470)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (c000000000410b3c)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (c000000000414ed8)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/memory_hotplug.c (c00000000042db9c)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (c000000000437510)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/hugetlb_cgroup.c (c00000000045da98)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (c00000000045ef0c)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (c000000000463c3c)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
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
In mm/gup.c (ffffffe0002043e2)
Location: include/linux/hugetlb.h:454
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffe000212794)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/page_alloc.c (ffffffe00021fcbe)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffe0002322b0)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/migrate.c (ffffffe00023fb28)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/hugetlb_cgroup.c (ffffffe00024a5e0)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/page_isolation.c (ffffffe00024b556)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
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
In mm/gup.c (ffffffff81251204)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/gup.c:new_non_cma_page
```
```
In mm/page_vma_mapped.c (ffffffff81269ea6)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/page_alloc.c (ffffffff8127a267)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff812903f5)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffffffff81293d01)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/memory_hotplug.c (ffffffff812a47ba)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff812a9301)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/hugetlb_cgroup.c (ffffffff812c25d5)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffffffff812c2db6)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812c6397)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
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
In mm/gup.c (ffffffff812440f4)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/gup.c:new_non_cma_page
```
```
In mm/page_vma_mapped.c (ffffffff8125c139)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/page_alloc.c (ffffffff8126c157)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff81282085)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffffffff81285911)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/memory_hotplug.c (ffffffff8129628a)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff8129ac61)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/hugetlb_cgroup.c (ffffffff812b3625)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffffffff812b3e06)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812b73d7)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
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
In mm/gup.c (ffffffff8124efa4)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/gup.c:new_non_cma_page
```
```
In mm/page_vma_mapped.c (ffffffff81267c46)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/page_alloc.c (ffffffff81278007)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff8128e205)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffffffff81291b11)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/memory_hotplug.c (ffffffff812a25ca)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff812a7111)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/hugetlb_cgroup.c (ffffffff812c03e5)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffffffff812c0bc6)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812c41a7)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
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
In mm/gup.c (ffffffff8125e914)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/gup.c:new_non_cma_page
```
```
In mm/page_vma_mapped.c (ffffffff812775dc)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/page_alloc.c (ffffffff81287bf7)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff8129dfa5)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffffffff812a1921)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/memory_hotplug.c (ffffffff812b292a)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff812b7421)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/hugetlb_cgroup.c (ffffffff812d0e75)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffffffff812d1686)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812d4c67)
Location: include/linux/hugetlb.h:454
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
</details>
</li>
</ul>

## Differences
