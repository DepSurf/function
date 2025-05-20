# Function: <code>i_mmap_unlock_write</code>

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
In kernel/fork.c (ffffffff8107fafe)
Location: include/linux/fs.h:502
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/memory.c (ffffffff811bdd9e)
Location: include/linux/fs.h:502
Inline: True
Inline callers:
  - mm/memory.c:unmap_single_vma
  - mm/memory.c:unmap_mapping_range
```
```
In mm/mmap.c (ffffffff811c4a91)
Location: include/linux/fs.h:502
Inline: True
Inline callers:
  - mm/mmap.c:unlink_file_vma
  - mm/mmap.c:vma_link
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/mremap.c (ffffffff811c97e9)
Location: include/linux/fs.h:502
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff811ddf25)
Location: include/linux/fs.h:502
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:huge_pmd_share
```
```
In fs/hugetlbfs/inode.c (ffffffff812f4d90)
Location: include/linux/fs.h:502
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In kernel/fork.c (ffffffff81080f5d)
Location: include/linux/fs.h:505
Inline: True
```
```
In mm/memory.c (ffffffff811d97a6)
Location: include/linux/fs.h:505
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff811e4413)
Location: include/linux/fs.h:505
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff811e5e30)
Location: include/linux/fs.h:505
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff811fc82b)
Location: include/linux/fs.h:505
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/khugepaged.c (ffffffff8121ae9d)
Location: include/linux/fs.h:505
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/hugetlbfs/inode.c (ffffffff81328623)
Location: include/linux/fs.h:505
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In kernel/fork.c (ffffffff81085962)
Location: include/linux/fs.h:456
Inline: True
```
```
In mm/memory.c (ffffffff811e8bb6)
Location: include/linux/fs.h:456
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff811f4454)
Location: include/linux/fs.h:456
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff811f6127)
Location: include/linux/fs.h:456
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff8120d31b)
Location: include/linux/fs.h:456
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/khugepaged.c (ffffffff8122ccf2)
Location: include/linux/fs.h:456
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/hugetlbfs/inode.c (ffffffff8133e373)
Location: include/linux/fs.h:456
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In kernel/fork.c (ffffffff81082fca)
Location: include/linux/fs.h:467
Inline: True
```
```
In mm/memory.c (ffffffff811f3e0e)
Location: include/linux/fs.h:467
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff811ff3d4)
Location: include/linux/fs.h:467
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff81200f19)
Location: include/linux/fs.h:467
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff812191d0)
Location: include/linux/fs.h:467
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/khugepaged.c (ffffffff81239576)
Location: include/linux/fs.h:467
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/hugetlbfs/inode.c (ffffffff81352fb0)
Location: include/linux/fs.h:467
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In kernel/fork.c (ffffffff810890e5)
Location: include/linux/fs.h:471
Inline: True
```
```
In mm/memory.c (ffffffff8120bace)
Location: include/linux/fs.h:471
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff812179d4)
Location: include/linux/fs.h:471
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff81219866)
Location: include/linux/fs.h:471
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff81234185)
Location: include/linux/fs.h:471
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/khugepaged.c (ffffffff81257ce5)
Location: include/linux/fs.h:471
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/hugetlbfs/inode.c (ffffffff81377b1c)
Location: include/linux/fs.h:471
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In kernel/fork.c (ffffffff8108ba20)
Location: include/linux/fs.h:473
Inline: True
Inline callers:
  - kernel/fork.c:copy_mm
```
```
In mm/memory.c (ffffffff8122d09a)
Location: include/linux/fs.h:473
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff81238d30)
Location: include/linux/fs.h:473
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff8123b190)
Location: include/linux/fs.h:473
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff8125727b)
Location: include/linux/fs.h:473
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/khugepaged.c (ffffffff8127bc20)
Location: include/linux/fs.h:473
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/hugetlbfs/inode.c (ffffffff813a624a)
Location: include/linux/fs.h:473
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In kernel/fork.c (ffffffff81095535)
Location: include/linux/fs.h:510
Inline: True
```
```
In mm/memory.c (ffffffff8124062a)
Location: include/linux/fs.h:510
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff8124c6f0)
Location: include/linux/fs.h:510
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff8124e9f6)
Location: include/linux/fs.h:510
Inline: True
```
```
In mm/hugetlb.c (ffffffff8126b8ef)
Location: include/linux/fs.h:510
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/khugepaged.c (ffffffff8129002b)
Location: include/linux/fs.h:510
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/hugetlbfs/inode.c (ffffffff813bec7a)
Location: include/linux/fs.h:510
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In kernel/fork.c (ffffffff8109785d)
Location: include/linux/fs.h:522
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/memory.c (ffffffff812528d8)
Location: include/linux/fs.h:522
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff8125eb20)
Location: include/linux/fs.h:522
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff81260d46)
Location: include/linux/fs.h:522
Inline: True
```
```
In mm/hugetlb.c (ffffffff81286be9)
Location: include/linux/fs.h:522
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/khugepaged.c (ffffffff812ab147)
Location: include/linux/fs.h:522
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/hugetlbfs/inode.c (ffffffff813e950e)
Location: include/linux/fs.h:522
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In kernel/fork.c (ffffffff8109df1d)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/memory.c (ffffffff81260e38)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff8126d331)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff8126f4d6)
Location: include/linux/fs.h:529
Inline: True
```
```
In mm/hugetlb.c (ffffffff812967e9)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/khugepaged.c (ffffffff812bcae0)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/hugetlbfs/inode.c (ffffffff814035ae)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In kernel/fork.c (ffffffff810a559e)
Location: include/linux/fs.h:537
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/memory.c (ffffffff812912b8)
Location: include/linux/fs.h:537
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff8129d531)
Location: include/linux/fs.h:537
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff812a072d)
Location: include/linux/fs.h:537
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff812c98d5)
Location: include/linux/fs.h:537
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_page_mapping_lock_write
  - mm/hugetlb.c:hugetlb_page_mapping_lock_write
```
```
In mm/migrate.c (ffffffff812e6085)
Location: include/linux/fs.h:537
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In mm/khugepaged.c (ffffffff812f127e)
Location: include/linux/fs.h:537
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
```
```
In mm/memory-failure.c (ffffffff813011fc)
Location: include/linux/fs.h:537
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff81451374)
Location: include/linux/fs.h:537
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_punch_hole
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In kernel/fork.c (ffffffff810a0d1a)
Location: include/linux/fs.h:501
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/memory.c (ffffffff8129bc28)
Location: include/linux/fs.h:501
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff812a8942)
Location: include/linux/fs.h:501
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff812abcff)
Location: include/linux/fs.h:501
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff812d5463)
Location: include/linux/fs.h:501
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/migrate.c (ffffffff812f153d)
Location: include/linux/fs.h:501
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In mm/khugepaged.c (ffffffff812fc7d9)
Location: include/linux/fs.h:501
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
```
```
In mm/memory-failure.c (ffffffff8130d266)
Location: include/linux/fs.h:501
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff8146d894)
Location: include/linux/fs.h:501
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_punch_hole
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In kernel/fork.c (ffffffff810a1a8c)
Location: include/linux/fs.h:502
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/memory.c (ffffffff812a0ec5)
Location: include/linux/fs.h:502
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_mapping_page
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff812addef)
Location: include/linux/fs.h:502
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff812b10cf)
Location: include/linux/fs.h:502
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff812de9c2)
Location: include/linux/fs.h:502
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff812f783b)
Location: include/linux/fs.h:502
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In mm/khugepaged.c (ffffffff81303546)
Location: include/linux/fs.h:502
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
```
```
In mm/memory-failure.c (ffffffff81313803)
Location: include/linux/fs.h:502
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff81472e07)
Location: include/linux/fs.h:502
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In kernel/fork.c (ffffffff810b3651)
Location: include/linux/fs.h:509
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/memory.c (ffffffff812e1845)
Location: include/linux/fs.h:509
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_mapping_page
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff812ef565)
Location: include/linux/fs.h:509
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff812f2934)
Location: include/linux/fs.h:509
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff81325da7)
Location: include/linux/fs.h:509
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff81341ea5)
Location: include/linux/fs.h:509
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In mm/khugepaged.c (ffffffff8134d2b0)
Location: include/linux/fs.h:509
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
```
```
In mm/memory-failure.c (ffffffff81360511)
Location: include/linux/fs.h:509
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/hugetlbfs/inode.c (ffffffff814c9917)
Location: include/linux/fs.h:509
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In kernel/fork.c (ffffffff810c988a)
Location: include/linux/fs.h:459
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/memory.c (ffffffff81341fbb)
Location: include/linux/fs.h:459
Inline: True
Inline callers:
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff81352a22)
Location: include/linux/fs.h:459
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff81356ae6)
Location: include/linux/fs.h:459
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff81394b12)
Location: include/linux/fs.h:459
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:move_hugetlb_page_tables
```
```
In mm/migrate.c (ffffffff813b3c6e)
Location: include/linux/fs.h:459
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In mm/khugepaged.c (ffffffff813c3ceb)
Location: include/linux/fs.h:459
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
```
```
In mm/memory-failure.c (ffffffff813dbeae)
Location: include/linux/fs.h:459
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/hugetlbfs/inode.c (ffffffff81555ad0)
Location: include/linux/fs.h:459
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In kernel/fork.c (ffffffff810e6e9a)
Location: include/linux/fs.h:474
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/mmap.c (ffffffff813cca7d)
Location: include/linux/fs.h:474
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_expand
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff813d1085)
Location: include/linux/fs.h:474
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff8140de56)
Location: include/linux/fs.h:474
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range_final
  - mm/hugetlb.c:__unmap_hugepage_range_final
  - mm/hugetlb.c:move_hugetlb_page_tables
```
```
In mm/migrate.c (ffffffff814348bb)
Location: include/linux/fs.h:474
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In mm/khugepaged.c (ffffffff81447bf5)
Location: include/linux/fs.h:474
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/memory-failure.c (ffffffff81462cc0)
Location: include/linux/fs.h:474
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/hugetlbfs/inode.c (ffffffff815f6d50)
Location: include/linux/fs.h:474
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
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
In kernel/fork.c (ffffffff810f28d2)
Location: include/linux/fs.h:489
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/mmap.c (ffffffff81401352)
Location: include/linux/fs.h:489
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_complete
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff81405a6b)
Location: include/linux/fs.h:489
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff81441237)
Location: include/linux/fs.h:489
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range_final
  - mm/hugetlb.c:__unmap_hugepage_range_final
  - mm/hugetlb.c:move_hugetlb_page_tables
```
```
In mm/migrate.c (ffffffff8146a1ef)
Location: include/linux/fs.h:489
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In mm/khugepaged.c (ffffffff8147d54f)
Location: include/linux/fs.h:489
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/memory-failure.c (ffffffff8149860c)
Location: include/linux/fs.h:489
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/hugetlbfs/inode.c (ffffffff8162ee10)
Location: include/linux/fs.h:489
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
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
In kernel/fork.c (ffffffff810fb588)
Location: include/linux/fs.h:522
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/mmap.c (ffffffff8142d9a0)
Location: include/linux/fs.h:522
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_complete
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff81431ecc)
Location: include/linux/fs.h:522
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff8147b348)
Location: include/linux/fs.h:522
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__hugetlb_zap_end
  - mm/hugetlb.c:move_hugetlb_page_tables
```
```
In mm/migrate.c (ffffffff814991b9)
Location: include/linux/fs.h:522
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In mm/memory-failure.c (ffffffff814c7fee)
Location: include/linux/fs.h:522
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/task_mmu.c (ffffffff8159d4f8)
Location: include/linux/fs.h:522
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_scan_hugetlb_entry
```
```
In fs/hugetlbfs/inode.c (ffffffff81668300)
Location: include/linux/fs.h:522
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
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
In kernel/fork.c (ffff8000100f2b74)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/memory.c (ffff8000102f81ec)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffff800010304408)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffff800010306530)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffff800010333808)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/khugepaged.c (ffff80001035dd10)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/hugetlbfs/inode.c (ffff8000104e2030)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In kernel/fork.c (c0351424)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/memory.c (c051a9c4)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_pages
```
```
In mm/mmap.c (c0522b5c)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (c0524154)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
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
In kernel/fork.c (c00000000013874c)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/memory.c (c0000000003c1518)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (c0000000003d1230)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (c0000000003d427c)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (c00000000040fde4)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/khugepaged.c (c000000000449420)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/hugetlbfs/inode.c (c00000000061eae8)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In kernel/fork.c (ffffffe0000bf74a)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/memory.c (ffffffe00020879a)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffe000210c36)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffe000211da4)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffe000231034)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In fs/hugetlbfs/inode.c (ffffffe000355b4e)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In kernel/fork.c (ffffffff8109783d)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/memory.c (ffffffff81259488)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff81265981)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff81267b26)
Location: include/linux/fs.h:529
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128edc9)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/khugepaged.c (ffffffff812b50c0)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/hugetlbfs/inode.c (ffffffff813fbb8e)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In kernel/fork.c (ffffffff810862bd)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/memory.c (ffffffff8124b908)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff81257da1)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff81259e76)
Location: include/linux/fs.h:529
Inline: True
```
```
In mm/hugetlb.c (ffffffff81280b42)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/khugepaged.c (ffffffff812a60e8)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/hugetlbfs/inode.c (ffffffff813ec60e)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In kernel/fork.c (ffffffff810977ed)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/memory.c (ffffffff81257228)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff81263721)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff812658c6)
Location: include/linux/fs.h:529
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128cbd9)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/khugepaged.c (ffffffff812b2ed0)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/hugetlbfs/inode.c (ffffffff813f8f0e)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In kernel/fork.c (ffffffff8109f3ed)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/memory.c (ffffffff81266c18)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff812730e1)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff81275276)
Location: include/linux/fs.h:529
Inline: True
```
```
In mm/hugetlb.c (ffffffff8129c9a7)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/khugepaged.c (ffffffff812c330c)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/hugetlbfs/inode.c (ffffffff8140ed4e)
Location: include/linux/fs.h:529
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
</details>
</li>
</ul>

## Differences
