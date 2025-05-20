# Function: <code>pages_per_huge_page</code>

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
In mm/hugetlb.c (0)
Location: include/linux/hugetlb.h:410
Inline: True
```
```
In mm/migrate.c (ffffffff811f1bf9)
Location: include/linux/hugetlb.h:410
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/hugetlb.h:410
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/hugetlb.h:410
Inline: True
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
In mm/hugetlb.c (ffffffff811fdb6e)
Location: include/linux/hugetlb.h:406
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_total_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffff812105b9)
Location: include/linux/hugetlb.h:406
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In fs/hugetlbfs/inode.c (ffffffff8132869f)
Location: include/linux/hugetlb.h:406
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In ipc/shm.c (ffffffff8135f319)
Location: include/linux/hugetlb.h:406
Inline: True
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
In mm/hugetlb.c (ffffffff8120e653)
Location: include/linux/hugetlb.h:406
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_total_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffff812226f9)
Location: include/linux/hugetlb.h:406
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In fs/hugetlbfs/inode.c (ffffffff8133e3ef)
Location: include/linux/hugetlb.h:406
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In ipc/shm.c (ffffffff81375b19)
Location: include/linux/hugetlb.h:406
Inline: True
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
In mm/hugetlb.c (ffffffff8121a04a)
Location: include/linux/hugetlb.h:428
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_total_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffff8122e379)
Location: include/linux/hugetlb.h:428
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/userfaultfd.c (ffffffff8124b87c)
Location: include/linux/hugetlb.h:428
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/hugetlbfs/inode.c (ffffffff81353032)
Location: include/linux/hugetlb.h:428
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In ipc/shm.c (ffffffff813896b9)
Location: include/linux/hugetlb.h:428
Inline: True
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
In mm/hugetlb.c (ffffffff8123510a)
Location: include/linux/hugetlb.h:422
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_total_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffff8124a5fd)
Location: include/linux/hugetlb.h:422
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/userfaultfd.c (ffffffff8126bbd5)
Location: include/linux/hugetlb.h:422
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/hugetlbfs/inode.c (ffffffff81377cdf)
Location: include/linux/hugetlb.h:422
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In ipc/shm.c (ffffffff813aea3d)
Location: include/linux/hugetlb.h:422
Inline: True
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
In mm/hugetlb.c (ffffffff81258139)
Location: include/linux/hugetlb.h:435
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_total_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffff8126d889)
Location: include/linux/hugetlb.h:435
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/userfaultfd.c (ffffffff8129071f)
Location: include/linux/hugetlb.h:435
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/hugetlbfs/inode.c (ffffffff813a6657)
Location: include/linux/hugetlb.h:435
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In ipc/shm.c (ffffffff813ddb18)
Location: include/linux/hugetlb.h:435
Inline: True
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
In mm/hugetlb.c (ffffffff8126c823)
Location: include/linux/hugetlb.h:446
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_total_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffff81281e8d)
Location: include/linux/hugetlb.h:446
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/userfaultfd.c (ffffffff812a56dd)
Location: include/linux/hugetlb.h:446
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/hugetlbfs/inode.c (ffffffff813bf437)
Location: include/linux/hugetlb.h:446
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In ipc/shm.c (ffffffff813f8198)
Location: include/linux/hugetlb.h:446
Inline: True
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
In mm/hugetlb.c (ffffffff81287bc9)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_total_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffff8129dfb1)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/userfaultfd.c (ffffffff812c0d37)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/hugetlbfs/inode.c (ffffffff813e9d8f)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In ipc/shm.c (ffffffff8142469b)
Location: include/linux/hugetlb.h:434
Inline: True
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
In mm/hugetlb.c (ffffffff81297801)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_total_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffff812ad861)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/userfaultfd.c (ffffffff812d2ca9)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/hugetlbfs/inode.c (ffffffff81403e2f)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In ipc/shm.c (ffffffff8143e3eb)
Location: include/linux/hugetlb.h:434
Inline: True
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
In mm/hugetlb.c (ffffffff812c7f88)
Location: include/linux/hugetlb.h:583
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_total_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
```
```
In mm/migrate.c (ffffffff812e26e2)
Location: include/linux/hugetlb.h:583
Inline: True
Inline callers:
  - mm/migrate.c:copy_huge_page
```
```
In fs/hugetlbfs/inode.c (ffffffff81451c7f)
Location: include/linux/hugetlb.h:583
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In ipc/shm.c (ffffffff8148f29b)
Location: include/linux/hugetlb.h:583
Inline: True
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
In mm/hugetlb.c (ffffffff812d3b6f)
Location: include/linux/hugetlb.h:581
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_total_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffff812edb12)
Location: include/linux/hugetlb.h:581
Inline: True
Inline callers:
  - mm/migrate.c:copy_huge_page
```
```
In fs/hugetlbfs/inode.c (ffffffff8146e13d)
Location: include/linux/hugetlb.h:581
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In ipc/shm.c (ffffffff814ac97b)
Location: include/linux/hugetlb.h:581
Inline: True
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
In mm/hugetlb.c (ffffffff812daa48)
Location: include/linux/hugetlb.h:694
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_total_pages
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffff812f429f)
Location: include/linux/hugetlb.h:694
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/hugetlb_cgroup.c (ffffffff81311a09)
Location: include/linux/hugetlb.h:694
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/hugetlbfs/inode.c (ffffffff8147357f)
Location: include/linux/hugetlb.h:694
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In ipc/shm.c (ffffffff814b2afb)
Location: include/linux/hugetlb.h:694
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff81321a00)
Location: include/linux/hugetlb.h:717
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_total_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
Direct callers:
  - mm/hugetlb.c:gather_bootmem_prealloc
```
```
In mm/hugetlb_vmemmap.c (ffffffff832dbaee)
Location: include/linux/hugetlb.h:717
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_init
```
```
In mm/hugetlb_cgroup.c (ffffffff8135d551)
Location: include/linux/hugetlb.h:717
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/hugetlbfs/inode.c (ffffffff814ca17b)
Location: include/linux/hugetlb.h:717
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In ipc/shm.c (ffffffff8150b135)
Location: include/linux/hugetlb.h:717
Inline: True
```
**Symbols:**

```
ffffffff81cbf22e-ffffffff81cbf259: pages_per_huge_page.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff8138ea25)
Location: include/linux/hugetlb.h:747
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_total_pages
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/hugetlb_vmemmap.c (ffffffff834912dd)
Location: include/linux/hugetlb.h:747
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_init
```
```
In mm/hugetlb_cgroup.c (ffffffff813d7651)
Location: include/linux/hugetlb.h:747
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/hugetlbfs/inode.c (ffffffff81555e9a)
Location: include/linux/hugetlb.h:747
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In ipc/shm.c (ffffffff8159caf5)
Location: include/linux/hugetlb.h:747
Inline: True
```
**Symbols:**

```
ffffffff81e715a8-ffffffff81e715df: pages_per_huge_page.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
unsigned int pages_per_huge_page(const struct hstate *h);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff8140d1b6)
Location: include/linux/hugetlb.h:786
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_total_pages
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_fresh_hugetlb_folio
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:__update_and_free_page
  - mm/hugetlb.c:add_reservation_in_range
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:add_reservation_in_range
```
```
In mm/hugetlb_vmemmap.c (ffffffff83ec46b8)
Location: include/linux/hugetlb.h:786
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_init
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_optimize
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_restore
```
```
In mm/hugetlb_cgroup.c (ffffffff8145d20c)
Location: include/linux/hugetlb.h:786
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/hugetlbfs/inode.c (ffffffff815f758a)
Location: include/linux/hugetlb.h:786
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
```
```
In ipc/shm.c (ffffffff81645fae)
Location: include/linux/hugetlb.h:786
Inline: True
```
**Symbols:**

```
ffffffff814052c0-ffffffff814052e0: pages_per_huge_page (STB_LOCAL)
ffffffff82065ffd-ffffffff82066034: pages_per_huge_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
unsigned int pages_per_huge_page(const struct hstate *h);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff81440955)
Location: include/linux/hugetlb.h:814
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_total_pages
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_fresh_hugetlb_folio
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:__update_and_free_hugetlb_folio
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
Direct callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/hugetlb_vmemmap.c (ffffffff836e97d8)
Location: include/linux/hugetlb.h:814
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_init
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_optimize
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_restore
```
```
In mm/hugetlb_cgroup.c (ffffffff81493259)
Location: include/linux/hugetlb.h:814
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/hugetlbfs/inode.c (ffffffff8162f69a)
Location: include/linux/hugetlb.h:814
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
```
```
In ipc/shm.c (ffffffff8167e508)
Location: include/linux/hugetlb.h:814
Inline: True
```
**Symbols:**

```
ffffffff81438980-ffffffff814389a0: pages_per_huge_page (STB_LOCAL)
ffffffff820e57c1-ffffffff820e57f8: pages_per_huge_page.cold (STB_LOCAL)
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
In mm/hugetlb.c (ffffffff8147aaa9)
Location: include/linux/hugetlb.h:835
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_total_pages
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:prep_and_add_bootmem_folios
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:__alloc_fresh_hugetlb_folio
  - mm/hugetlb.c:free_huge_folio
  - mm/hugetlb.c:free_huge_folio
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
```
```
In mm/hugetlb_vmemmap.c (ffffffff8391cb88)
Location: include/linux/hugetlb.h:835
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_init
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_optimize_folios
  - mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_optimize_folio
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize_folio
  - mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_restore_folio
```
```
In mm/hugetlb_cgroup.c (ffffffff814c2c89)
Location: include/linux/hugetlb.h:835
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/hugetlbfs/inode.c (ffffffff81668b76)
Location: include/linux/hugetlb.h:835
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
```
```
In ipc/shm.c (ffffffff816ba8f8)
Location: include/linux/hugetlb.h:835
Inline: True
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
In mm/hugetlb.c (ffff8000103355c8)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_total_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffff80001034f834)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/userfaultfd.c (ffff800010378948)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/hugetlbfs/inode.c (ffff8000104e25d8)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In ipc/shm.c (ffff8000105272f0)
Location: include/linux/hugetlb.h:434
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (0)
Location: include/linux/hugetlb.h:684
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
In mm/hugetlb.c (c00000000040f64c)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_total_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/migrate.c (c0000000004321a4)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/userfaultfd.c (c00000000046b49c)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/hugetlbfs/inode.c (c00000000061f6d4)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In ipc/shm.c (c00000000067075c)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - ipc/shm.c:shm_add_rss_swap
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
In mm/hugetlb.c (ffffffe000231c76)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_total_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffe00023e6bc)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/userfaultfd.c (ffffffe0002502be)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/hugetlbfs/inode.c (ffffffe00035605a)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In ipc/shm.c (ffffffe00038aa68)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - ipc/shm.c:shm_add_rss_swap
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
In mm/hugetlb.c (ffffffff8128fde1)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_total_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffff812a5e41)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/userfaultfd.c (ffffffff812cb289)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/hugetlbfs/inode.c (ffffffff813fc40f)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In ipc/shm.c (ffffffff814369cb)
Location: include/linux/hugetlb.h:434
Inline: True
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
In mm/hugetlb.c (ffffffff81281a97)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_total_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffff812978f1)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/userfaultfd.c (ffffffff812bc1c4)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/hugetlbfs/inode.c (ffffffff813ece8f)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In ipc/shm.c (ffffffff8142744b)
Location: include/linux/hugetlb.h:434
Inline: True
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
In mm/hugetlb.c (ffffffff8128dbf1)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_total_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffff812a3c51)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/userfaultfd.c (ffffffff812c9099)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/hugetlbfs/inode.c (ffffffff813f978f)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In ipc/shm.c (ffffffff81432b6b)
Location: include/linux/hugetlb.h:434
Inline: True
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
In mm/hugetlb.c (ffffffff8129d9a6)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_total_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffff812b4563)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/userfaultfd.c (ffffffff812d9d9a)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/hugetlbfs/inode.c (ffffffff8140f3ea)
Location: include/linux/hugetlb.h:434
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In ipc/shm.c (ffffffff81449deb)
Location: include/linux/hugetlb.h:434
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
