# Function: <code>i_mmap_lock_write</code>

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
In kernel/fork.c (ffffffff8107fad7)
Location: include/linux/fs.h:497
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/memory.c (ffffffff811bdd73)
Location: include/linux/fs.h:497
Inline: True
Inline callers:
  - mm/memory.c:unmap_single_vma
  - mm/memory.c:unmap_mapping_range
```
```
In mm/mmap.c (ffffffff811c4a77)
Location: include/linux/fs.h:497
Inline: True
Inline callers:
  - mm/mmap.c:unlink_file_vma
  - mm/mmap.c:vma_link
  - mm/mmap.c:vma_adjust
```
```
In mm/mremap.c (ffffffff811c9823)
Location: include/linux/fs.h:497
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff811dde74)
Location: include/linux/fs.h:497
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:huge_pmd_share
```
```
In fs/hugetlbfs/inode.c (ffffffff812f4ade)
Location: include/linux/fs.h:497
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
In kernel/fork.c (ffffffff81080f36)
Location: include/linux/fs.h:500
Inline: True
```
```
In mm/memory.c (ffffffff811d974d)
Location: include/linux/fs.h:500
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff811e0be6)
Location: include/linux/fs.h:500
Inline: True
Inline callers:
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff811e5db3)
Location: include/linux/fs.h:500
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff811fc718)
Location: include/linux/fs.h:500
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/khugepaged.c (ffffffff8121b482)
Location: include/linux/fs.h:500
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/hugetlbfs/inode.c (ffffffff813285ed)
Location: include/linux/fs.h:500
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
In kernel/fork.c (ffffffff8108593b)
Location: include/linux/fs.h:451
Inline: True
```
```
In mm/memory.c (ffffffff811e8b5d)
Location: include/linux/fs.h:451
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff811f0acb)
Location: include/linux/fs.h:451
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff811f60a3)
Location: include/linux/fs.h:451
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff8120d208)
Location: include/linux/fs.h:451
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/khugepaged.c (ffffffff8122caf0)
Location: include/linux/fs.h:451
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/hugetlbfs/inode.c (ffffffff8133e33d)
Location: include/linux/fs.h:451
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
In kernel/fork.c (ffffffff81082fa4)
Location: include/linux/fs.h:462
Inline: True
```
```
In mm/memory.c (ffffffff811f3dbd)
Location: include/linux/fs.h:462
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff811fb9a9)
Location: include/linux/fs.h:462
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff81200e97)
Location: include/linux/fs.h:462
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff812190b6)
Location: include/linux/fs.h:462
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/khugepaged.c (ffffffff8123912a)
Location: include/linux/fs.h:462
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/hugetlbfs/inode.c (ffffffff81352f90)
Location: include/linux/fs.h:462
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
In kernel/fork.c (ffffffff810890b6)
Location: include/linux/fs.h:466
Inline: True
```
```
In mm/memory.c (ffffffff8120ba7d)
Location: include/linux/fs.h:466
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff81213ee9)
Location: include/linux/fs.h:466
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff812197f0)
Location: include/linux/fs.h:466
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff81234066)
Location: include/linux/fs.h:466
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/khugepaged.c (ffffffff81257839)
Location: include/linux/fs.h:466
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/hugetlbfs/inode.c (ffffffff81377af4)
Location: include/linux/fs.h:466
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
In kernel/fork.c (ffffffff8108b9f8)
Location: include/linux/fs.h:468
Inline: True
Inline callers:
  - kernel/fork.c:copy_mm
```
```
In mm/memory.c (ffffffff8122d083)
Location: include/linux/fs.h:468
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff81234e4d)
Location: include/linux/fs.h:468
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff8123b10e)
Location: include/linux/fs.h:468
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff81257037)
Location: include/linux/fs.h:468
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/khugepaged.c (ffffffff8127ba78)
Location: include/linux/fs.h:468
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/hugetlbfs/inode.c (ffffffff813a622d)
Location: include/linux/fs.h:468
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
In kernel/fork.c (ffffffff81095506)
Location: include/linux/fs.h:505
Inline: True
```
```
In mm/memory.c (ffffffff81240613)
Location: include/linux/fs.h:505
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff812485cd)
Location: include/linux/fs.h:505
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff8124e9a2)
Location: include/linux/fs.h:505
Inline: True
```
```
In mm/hugetlb.c (ffffffff8126b6b6)
Location: include/linux/fs.h:505
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/khugepaged.c (ffffffff8128fdb4)
Location: include/linux/fs.h:505
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/hugetlbfs/inode.c (ffffffff813bec5d)
Location: include/linux/fs.h:505
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
In kernel/fork.c (ffffffff8109782b)
Location: include/linux/fs.h:517
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/memory.c (ffffffff812528c3)
Location: include/linux/fs.h:517
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff8125a7cd)
Location: include/linux/fs.h:517
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff81260cf2)
Location: include/linux/fs.h:517
Inline: True
```
```
In mm/hugetlb.c (ffffffff812869b0)
Location: include/linux/fs.h:517
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/khugepaged.c (ffffffff812aafa9)
Location: include/linux/fs.h:517
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/hugetlbfs/inode.c (ffffffff813e94f1)
Location: include/linux/fs.h:517
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
In kernel/fork.c (ffffffff8109deeb)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/memory.c (ffffffff81260e23)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff81268dad)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff8126f482)
Location: include/linux/fs.h:524
Inline: True
```
```
In mm/hugetlb.c (ffffffff812965b0)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/khugepaged.c (ffffffff812bc938)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/hugetlbfs/inode.c (ffffffff81403591)
Location: include/linux/fs.h:524
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
In kernel/fork.c (ffffffff810a556c)
Location: include/linux/fs.h:527
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/memory.c (ffffffff812912a3)
Location: include/linux/fs.h:527
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff81299554)
Location: include/linux/fs.h:527
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff812a0677)
Location: include/linux/fs.h:527
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff812c96a2)
Location: include/linux/fs.h:527
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_page_mapping_lock_write
```
```
In mm/khugepaged.c (ffffffff812f10a5)
Location: include/linux/fs.h:527
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
```
```
In fs/hugetlbfs/inode.c (ffffffff8145133c)
Location: include/linux/fs.h:527
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
In kernel/fork.c (ffffffff810a0ce8)
Location: include/linux/fs.h:491
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/memory.c (ffffffff8129bc13)
Location: include/linux/fs.h:491
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff812a4717)
Location: include/linux/fs.h:491
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff812abc66)
Location: include/linux/fs.h:491
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff812d528b)
Location: include/linux/fs.h:491
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/khugepaged.c (ffffffff812fc6f5)
Location: include/linux/fs.h:491
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
```
```
In fs/hugetlbfs/inode.c (ffffffff8146d85c)
Location: include/linux/fs.h:491
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
In kernel/fork.c (ffffffff810a1a62)
Location: include/linux/fs.h:492
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/memory.c (ffffffff812a0eb7)
Location: include/linux/fs.h:492
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_mapping_page
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff812a9e87)
Location: include/linux/fs.h:492
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff812b1064)
Location: include/linux/fs.h:492
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff812de8dd)
Location: include/linux/fs.h:492
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/khugepaged.c (ffffffff81303465)
Location: include/linux/fs.h:492
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
```
```
In fs/hugetlbfs/inode.c (ffffffff81472dd0)
Location: include/linux/fs.h:492
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
In kernel/fork.c (ffffffff810b361e)
Location: include/linux/fs.h:499
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/memory.c (ffffffff812e1837)
Location: include/linux/fs.h:499
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_mapping_page
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff812eb487)
Location: include/linux/fs.h:499
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff812f2dfc)
Location: include/linux/fs.h:499
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff81325cb7)
Location: include/linux/fs.h:499
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/khugepaged.c (ffffffff8134d1d5)
Location: include/linux/fs.h:499
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
```
```
In fs/hugetlbfs/inode.c (ffffffff814c98e0)
Location: include/linux/fs.h:499
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
In kernel/fork.c (ffffffff810c9862)
Location: include/linux/fs.h:449
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/memory.c (ffffffff81341f94)
Location: include/linux/fs.h:449
Inline: True
Inline callers:
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff8134e253)
Location: include/linux/fs.h:449
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff81356a77)
Location: include/linux/fs.h:449
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff81394a26)
Location: include/linux/fs.h:449
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:move_hugetlb_page_tables
```
```
In mm/khugepaged.c (ffffffff813c3c05)
Location: include/linux/fs.h:449
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
```
```
In fs/hugetlbfs/inode.c (ffffffff81555a97)
Location: include/linux/fs.h:449
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
In kernel/fork.c (ffffffff810e6e58)
Location: include/linux/fs.h:464
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/mmap.c (ffffffff813cb9f8)
Location: include/linux/fs.h:464
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_expand
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff813d1024)
Location: include/linux/fs.h:464
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff8140dd57)
Location: include/linux/fs.h:464
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range_final
  - mm/hugetlb.c:move_hugetlb_page_tables
```
```
In mm/khugepaged.c (ffffffff81447ae2)
Location: include/linux/fs.h:464
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/hugetlbfs/inode.c (ffffffff815f6d1c)
Location: include/linux/fs.h:464
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
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
In kernel/fork.c (ffffffff810f2897)
Location: include/linux/fs.h:479
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/mmap.c (ffffffff814004e9)
Location: include/linux/fs.h:479
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff81405a0a)
Location: include/linux/fs.h:479
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff81441130)
Location: include/linux/fs.h:479
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range_final
  - mm/hugetlb.c:move_hugetlb_page_tables
```
```
In mm/khugepaged.c (ffffffff8147d432)
Location: include/linux/fs.h:479
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/hugetlbfs/inode.c (ffffffff8162eddc)
Location: include/linux/fs.h:479
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
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
In kernel/fork.c (ffffffff810fb550)
Location: include/linux/fs.h:512
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/mmap.c (ffffffff8142c70f)
Location: include/linux/fs.h:512
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff81431fb8)
Location: include/linux/fs.h:512
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff8147b25f)
Location: include/linux/fs.h:512
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__hugetlb_zap_begin
  - mm/hugetlb.c:move_hugetlb_page_tables
```
```
In fs/proc/task_mmu.c (ffffffff8159d461)
Location: include/linux/fs.h:512
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_scan_hugetlb_entry
```
```
In fs/hugetlbfs/inode.c (ffffffff816682cc)
Location: include/linux/fs.h:512
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
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
In kernel/fork.c (ffff8000100f2b50)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/memory.c (ffff8000102f81d8)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffff800010300348)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffff80001030649c)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffff800010333640)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/khugepaged.c (ffff80001035db78)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/hugetlbfs/inode.c (ffff8000104e201c)
Location: include/linux/fs.h:524
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
In kernel/fork.c (c03513bc)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/memory.c (c051a9b4)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_pages
```
```
In mm/mmap.c (c051edb8)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (c05240fc)
Location: include/linux/fs.h:524
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
In kernel/fork.c (c000000000138708)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/memory.c (c0000000003c1500)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (c0000000003cc1ec)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (c0000000003d41fc)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (c00000000040fb40)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/khugepaged.c (c0000000004491b4)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/hugetlbfs/inode.c (c00000000061ead0)
Location: include/linux/fs.h:524
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
In kernel/fork.c (ffffffe0000bf71a)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/memory.c (ffffffe000208782)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffe00020dc26)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffe000211d66)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffe000230f62)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In fs/hugetlbfs/inode.c (ffffffe000355b36)
Location: include/linux/fs.h:524
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
In kernel/fork.c (ffffffff8109780b)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/memory.c (ffffffff81259473)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff812613fd)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff81267ad2)
Location: include/linux/fs.h:524
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128eb90)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/khugepaged.c (ffffffff812b4f18)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/hugetlbfs/inode.c (ffffffff813fbb71)
Location: include/linux/fs.h:524
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
In kernel/fork.c (ffffffff8108628b)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/memory.c (ffffffff8124b8f3)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff8125381d)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff81259e22)
Location: include/linux/fs.h:524
Inline: True
```
```
In mm/hugetlb.c (ffffffff81280928)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/khugepaged.c (ffffffff812a5f46)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/hugetlbfs/inode.c (ffffffff813ec5f1)
Location: include/linux/fs.h:524
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
In kernel/fork.c (ffffffff810977bb)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/memory.c (ffffffff81257213)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff8125f19d)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff81265872)
Location: include/linux/fs.h:524
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128c9a0)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/khugepaged.c (ffffffff812b2d28)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/hugetlbfs/inode.c (ffffffff813f8ef1)
Location: include/linux/fs.h:524
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
In kernel/fork.c (ffffffff8109f3bb)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/memory.c (ffffffff81266c03)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_single_vma
```
```
In mm/mmap.c (ffffffff8126eb6d)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mremap.c (ffffffff81275222)
Location: include/linux/fs.h:524
Inline: True
```
```
In mm/hugetlb.c (ffffffff8129c770)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/khugepaged.c (ffffffff812c3165)
Location: include/linux/fs.h:524
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/hugetlbfs/inode.c (ffffffff8140ed31)
Location: include/linux/fs.h:524
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
