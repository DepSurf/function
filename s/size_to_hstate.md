# Function: <code>size_to_hstate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct hstate *size_to_hstate(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811db769)
Location: mm/hugetlb.c:1168
Inline: True
Inline callers:
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
  - mm/hugetlb.c:putback_active_hugepage
Direct callers:
  - mm/mmap.c:SyS_mmap_pgoff
  - mm/rmap.c:__page_check_address
  - mm/migrate.c:new_page_node
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_pages
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff811dc520-ffffffff811dc589: size_to_hstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct hstate *size_to_hstate(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811fe201)
Location: mm/hugetlb.c:1194
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
Direct callers:
  - mm/mmap.c:SyS_mmap_pgoff
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:__page_check_address
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:new_page_node
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff811fa780-ffffffff811fa7e9: size_to_hstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct hstate *size_to_hstate(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8120ecd1)
Location: mm/hugetlb.c:1194
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
Direct callers:
  - mm/mmap.c:SyS_mmap_pgoff
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:__page_check_address
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:new_page_node
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff8120b1b0-ffffffff8120b219: size_to_hstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct hstate *size_to_hstate(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8121a571)
Location: mm/hugetlb.c:1212
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
Direct callers:
  - mm/mmap.c:SyS_mmap_pgoff
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:new_page_node
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff81216710-ffffffff81216778: size_to_hstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct hstate *size_to_hstate(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812356e1)
Location: mm/hugetlb.c:1218
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
Direct callers:
  - mm/mmap.c:SyS_mmap_pgoff
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:new_page_node
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff812313c0-ffffffff81231428: size_to_hstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct hstate *size_to_hstate(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8125873c)
Location: mm/hugetlb.c:1181
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
Direct callers:
  - arch/x86/mm/hugetlbpage.c:gigantic_pages_init
  - mm/page_alloc.c:has_unmovable_pages
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff812542c0-ffffffff81254329: size_to_hstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct hstate *size_to_hstate(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8126ce0e)
Location: mm/hugetlb.c:1181
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
Direct callers:
  - arch/x86/mm/hugetlbpage.c:gigantic_pages_init
  - mm/page_alloc.c:has_unmovable_pages
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff812686a0-ffffffff81268709: size_to_hstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct hstate *size_to_hstate(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128823e)
Location: mm/hugetlb.c:1201
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
Direct callers:
  - arch/x86/mm/hugetlbpage.c:gigantic_pages_init
  - mm/gup.c:new_non_cma_page
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_alloc.c:has_unmovable_pages
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff81283790-ffffffff812837e5: size_to_hstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct hstate *size_to_hstate(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81297e3e)
Location: mm/hugetlb.c:1201
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
Direct callers:
  - arch/x86/mm/hugetlbpage.c:gigantic_pages_init
  - mm/gup.c:new_non_cma_page
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_alloc.c:has_unmovable_pages
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure
  - mm/page_isolation.c:alloc_migrate_target
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff81293330-ffffffff81293385: size_to_hstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct hstate *size_to_hstate(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812cb50e)
Location: mm/hugetlb.c:1340
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugepagesz_setup
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
Direct callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_alloc.c:has_unmovable_pages
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:copy_huge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/page_isolation.c:alloc_migrate_target
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff812c6700-ffffffff812c6755: size_to_hstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct hstate *size_to_hstate(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d712e)
Location: mm/hugetlb.c:1368
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugepagesz_setup
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
Direct callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_alloc.c:has_unmovable_pages
  - mm/mempolicy.c:new_page
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:copy_huge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/memory-failure.c:memory_failure_hugetlb
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff812d22f0-ffffffff812d2345: size_to_hstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct hstate *size_to_hstate(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812de71e)
Location: mm/hugetlb.c:1409
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugepagesz_setup
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
Direct callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_alloc.c:has_unmovable_pages
  - mm/mempolicy.c:new_page
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_page_copy
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/memory-failure.c:memory_failure_hugetlb
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff812d8c70-ffffffff812d8cc5: size_to_hstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct hstate *size_to_hstate(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff81325a8c)
Location: mm/hugetlb.c:1564
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_hpage_workfn
Direct callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_alloc.c:has_unmovable_pages
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugepagesz_setup
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/mempolicy.c:new_page
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/memory-failure.c:memory_failure_hugetlb
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff81cbf599-ffffffff81cbf5bf: size_to_hstate.cold (STB_LOCAL)
ffffffff8131ee00-ffffffff8131eec4: size_to_hstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct hstate *size_to_hstate(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff8139478a)
Location: mm/hugetlb.c:1654
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:demote_size_store
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_hpage_workfn
Direct callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugepagesz_setup
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/mempolicy.c:new_page
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff81e71924-ffffffff81e7194a: size_to_hstate.cold (STB_LOCAL)
ffffffff8138b720-ffffffff8138b806: size_to_hstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct hstate *size_to_hstate(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff81413203)
Location: mm/hugetlb.c:1843
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugepagesz_setup
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:demote_size_store
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_hpage_workfn
  - mm/hugetlb.c:hugetlb_add_hstate
Direct callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mempolicy.c:new_page
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff82066327-ffffffff8206634a: size_to_hstate.cold (STB_LOCAL)
ffffffff81408e60-ffffffff81408f42: size_to_hstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct hstate *size_to_hstate(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff81446763)
Location: mm/hugetlb.c:1866
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:folio_putback_active_hugetlb
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugepagesz_setup
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:demote_size_store
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_hpage_workfn
  - mm/hugetlb.c:hugetlb_add_hstate
Direct callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mempolicy.c:new_folio
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:migrate_hugetlbs
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff820e5ad9-ffffffff820e5afc: size_to_hstate.cold (STB_LOCAL)
ffffffff8143c4d0-ffffffff8143c5b2: size_to_hstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct hstate *size_to_hstate(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff81480206)
Location: mm/hugetlb.c:1961
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:folio_putback_active_hugetlb
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugepagesz_setup
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:demote_size_store
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_folio
  - mm/hugetlb.c:free_hpage_workfn
  - mm/hugetlb.c:hugetlb_add_hstate
Direct callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mempolicy.c:alloc_migration_target_by_mpol
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:migrate_hugetlbs
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff821c2bf7-ffffffff821c2c1a: size_to_hstate.cold (STB_LOCAL)
ffffffff81476ce0-ffffffff81476dc2: size_to_hstate (STB_GLOBAL)
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
struct hstate *size_to_hstate(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff800010336290)
Location: mm/hugetlb.c:1201
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
Direct callers:
  - arch/arm64/mm/hugetlbpage.c:add_huge_page_size
  - mm/gup.c:new_non_cma_page
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_alloc.c:has_unmovable_pages
  - mm/mempolicy.c:new_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure
  - mm/page_isolation.c:alloc_migrate_target
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffff8000103312f8-ffff800010331370: size_to_hstate (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct hstate *size_to_hstate(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c000000000410b5c)
Location: mm/hugetlb.c:1201
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
Direct callers:
  - arch/powerpc/mm/hugetlbpage.c:add_huge_page_size
  - mm/gup.c:new_non_cma_page
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_alloc.c:has_unmovable_pages
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure
  - mm/page_isolation.c:alloc_migrate_target
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - ipc/shm.c:newseg
```
**Symbols:**

```
c00000000040a070-c00000000040a0d4: size_to_hstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct hstate *size_to_hstate(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe0002321c6)
Location: mm/hugetlb.c:1201
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
Direct callers:
  - arch/riscv/mm/hugetlbpage.c:gigantic_pages_init
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_alloc.c:has_unmovable_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/page_isolation.c:alloc_migrate_target
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffe00022e438-ffffffe00022e498: size_to_hstate (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct hstate *size_to_hstate(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8129041e)
Location: mm/hugetlb.c:1201
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
Direct callers:
  - arch/x86/mm/hugetlbpage.c:gigantic_pages_init
  - mm/gup.c:new_non_cma_page
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_alloc.c:has_unmovable_pages
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure
  - mm/page_isolation.c:alloc_migrate_target
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff8128b910-ffffffff8128b965: size_to_hstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct hstate *size_to_hstate(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812820ae)
Location: mm/hugetlb.c:1201
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
Direct callers:
  - arch/x86/mm/hugetlbpage.c:gigantic_pages_init
  - mm/gup.c:new_non_cma_page
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_alloc.c:has_unmovable_pages
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure
  - mm/page_isolation.c:alloc_migrate_target
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff8127d740-ffffffff8127d795: size_to_hstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct hstate *size_to_hstate(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128e22e)
Location: mm/hugetlb.c:1201
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
Direct callers:
  - arch/x86/mm/hugetlbpage.c:gigantic_pages_init
  - mm/gup.c:new_non_cma_page
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_alloc.c:has_unmovable_pages
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure
  - mm/page_isolation.c:alloc_migrate_target
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff81289720-ffffffff81289775: size_to_hstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct hstate *size_to_hstate(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8129dfce)
Location: mm/hugetlb.c:1201
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
Direct callers:
  - arch/x86/mm/hugetlbpage.c:gigantic_pages_init
  - mm/gup.c:new_non_cma_page
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_alloc.c:has_unmovable_pages
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure
  - mm/page_isolation.c:alloc_migrate_target
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff81299500-ffffffff81299555: size_to_hstate (STB_GLOBAL)
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
