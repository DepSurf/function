# Function: <code>__mpol_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __mpol_put(struct mempolicy *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811e0d50)
Location: mm/mempolicy.c:296
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - kernel/sched/debug.c:proc_sched_show_task
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_remount_fs
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_swapin
  - mm/mmap.c:remove_vma
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:copy_vma
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:sp_free
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - fs/proc/task_mmu.c:vma_stop
  - fs/proc/task_mmu.c:show_numa_map
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff811e0d50-ffffffff811e0d70: __mpol_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __mpol_put(struct mempolicy *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811ff720)
Location: mm/mempolicy.c:295
Inline: True
Direct callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_remount_fs
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
  - mm/mmap.c:copy_vma
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:remove_vma
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:sp_free
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:vma_stop
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff811ff720-ffffffff811ff740: __mpol_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __mpol_put(struct mempolicy *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81210b70)
Location: mm/mempolicy.c:297
Inline: True
Direct callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_remount_fs
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:sp_free
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:SYSC_get_mempolicy
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - fs/proc/task_mmu.c:vma_stop
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff81210b70-ffffffff81210b90: __mpol_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __mpol_put(struct mempolicy *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8121c500)
Location: mm/mempolicy.c:285
Inline: True
Direct callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_remount_fs
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:sp_free
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:SYSC_get_mempolicy
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - fs/proc/task_mmu.c:vma_stop
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff8121c500-ffffffff8121c521: __mpol_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __mpol_put(struct mempolicy *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812376b0)
Location: mm/mempolicy.c:287
Inline: True
Direct callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_remount_fs
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:sp_free
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:SYSC_get_mempolicy
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - fs/proc/task_mmu.c:vma_stop
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff812376b0-ffffffff812376d1: __mpol_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __mpol_put(struct mempolicy *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8125ab30)
Location: mm/mempolicy.c:287
Inline: True
Direct callers:
  - kernel/fork.c:copy_mm
  - kernel/sched/debug.c:proc_sched_show_task
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_remount_fs
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:sp_free
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - fs/proc/task_mmu.c:vma_stop
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff8125ab30-ffffffff8125ab51: __mpol_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __mpol_put(struct mempolicy *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8126f2f0)
Location: mm/mempolicy.c:287
Inline: True
Direct callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_remount_fs
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:sp_free
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:vma_stop
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff8126f2f0-ffffffff8126f311: __mpol_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __mpol_put(struct mempolicy *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8128a8e0)
Location: mm/mempolicy.c:287
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
  - kernel/sched/debug.c:proc_sched_show_task
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_remount_fs
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:sp_free
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:vma_stop
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff8128a8e0-ffffffff8128a900: __mpol_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __mpol_put(struct mempolicy *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8129a450)
Location: mm/mempolicy.c:287
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
  - kernel/sched/debug.c:proc_sched_show_task
  - mm/shmem.c:shmem_free_fc
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:sp_free
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:vma_stop
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff8129a450-ffffffff8129a470: __mpol_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __mpol_put(struct mempolicy *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812d070d)
Location: mm/mempolicy.c:313
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:vma_replace_policy
  - mm/mempolicy.c:vma_replace_policy
  - mm/mempolicy.c:vma_replace_policy
  - mm/mempolicy.c:vma_replace_policy
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
  - kernel/sched/debug.c:sched_show_numa
  - mm/shmem.c:shmem_free_fc
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:dequeue_huge_page_vma
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff812ce5a0-ffffffff812ce5c0: __mpol_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __mpol_put(struct mempolicy *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812dc22d)
Location: mm/mempolicy.c:313
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:vma_replace_policy
  - mm/mempolicy.c:vma_replace_policy
  - mm/mempolicy.c:vma_replace_policy
  - mm/mempolicy.c:vma_replace_policy
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
  - kernel/sched/debug.c:sched_show_numa
  - mm/shmem.c:shmem_free_fc
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:dequeue_huge_page_vma
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff812d9530-ffffffff812d9550: __mpol_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __mpol_put(struct mempolicy *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812e3aca)
Location: mm/mempolicy.c:313
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
  - kernel/sched/debug.c:sched_show_numa
  - mm/shmem.c:shmem_free_fc
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff812e0db0-ffffffff812e0dd0: __mpol_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __mpol_put(struct mempolicy *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8132adaa)
Location: mm/mempolicy.c:304
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
  - kernel/sched/debug.c:sched_show_numa
  - mm/shmem.c:shmem_free_fc
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff81327fb0-ffffffff81327fd0: __mpol_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __mpol_put(struct mempolicy *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8139a789)
Location: mm/mempolicy.c:308
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
  - mm/shmem.c:shmem_free_fc
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_alloc_folio
  - mm/shmem.c:shmem_alloc_hugefolio
  - mm/shmem.c:shmem_swapin
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:dequeue_huge_page_vma
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff81397200-ffffffff81397230: __mpol_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __mpol_put(struct mempolicy *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8141a77f)
Location: mm/mempolicy.c:308
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
  - mm/shmem.c:shmem_free_fc
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_alloc_folio
  - mm/shmem.c:shmem_alloc_hugefolio
  - mm/shmem.c:shmem_swapin
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_expand
  - mm/mmap.c:remove_vma
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:dequeue_huge_page_vma
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff81416cd0-ffffffff81416d00: __mpol_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __mpol_put(struct mempolicy *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8144dcf5)
Location: mm/mempolicy.c:308
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:vma_replace_policy
  - mm/mempolicy.c:vma_replace_policy
  - mm/mempolicy.c:vma_replace_policy
  - mm/mempolicy.c:vma_replace_policy
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
  - mm/shmem.c:shmem_free_fc
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_alloc_folio
  - mm/shmem.c:shmem_alloc_hugefolio
  - mm/shmem.c:shmem_swapin
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:vma_complete
  - mm/mmap.c:remove_vma
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio_vma
  - mm/hugetlb.c:dequeue_hugetlb_folio_vma
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff8144a210-ffffffff8144a240: __mpol_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __mpol_put(struct mempolicy *pol);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81487bbb)
Location: mm/mempolicy.c:311
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
  - mm/shmem.c:shmem_free_fc
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_alloc_and_add_folio
  - mm/shmem.c:shmem_alloc_folio
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:vma_complete
  - mm/mmap.c:remove_vma
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:read_swap_cache_async
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:dequeue_hugetlb_folio_vma
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
```
**Symbols:**

```
ffffffff81483ca0-ffffffff81483cd0: __mpol_put (STB_GLOBAL)
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
void __mpol_put(struct mempolicy *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffff800010338e40)
Location: mm/mempolicy.c:287
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
  - kernel/sched/debug.c:proc_sched_show_task
  - mm/shmem.c:shmem_free_fc
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:sp_free
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:vma_stop
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffff800010338e40-ffff800010338e9c: __mpol_put (STB_GLOBAL)
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
void __mpol_put(struct mempolicy *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c0000000004136f0)
Location: mm/mempolicy.c:287
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
  - kernel/sched/debug.c:proc_sched_show_task
  - mm/shmem.c:shmem_free_fc
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:sp_free
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:vma_stop
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
c0000000004136f0-c000000000413754: __mpol_put (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __mpol_put(struct mempolicy *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81292a30)
Location: mm/mempolicy.c:287
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
  - kernel/sched/debug.c:proc_sched_show_task
  - mm/shmem.c:shmem_free_fc
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:sp_free
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:vma_stop
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff81292a30-ffffffff81292a50: __mpol_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __mpol_put(struct mempolicy *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81284640)
Location: mm/mempolicy.c:287
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
  - kernel/sched/debug.c:proc_sched_show_task
  - mm/shmem.c:shmem_free_fc
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:sp_free
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:vma_stop
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff81284640-ffffffff81284660: __mpol_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __mpol_put(struct mempolicy *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81290840)
Location: mm/mempolicy.c:287
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
  - kernel/sched/debug.c:proc_sched_show_task
  - mm/shmem.c:shmem_free_fc
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:sp_free
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:vma_stop
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff81290840-ffffffff81290860: __mpol_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __mpol_put(struct mempolicy *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812a0670)
Location: mm/mempolicy.c:287
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
  - kernel/sched/debug.c:proc_sched_show_task
  - mm/shmem.c:shmem_free_fc
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:sp_free
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:vma_stop
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff812a0670-ffffffff812a0690: __mpol_put (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mempolicy *pol</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mempolicy *p</code>
</li>
</ul>
</details>
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
