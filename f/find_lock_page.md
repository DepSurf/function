# Function: <code>find_lock_page</code>

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
In mm/truncate.c (ffffffff8119e631)
Location: include/linux/pagemap.h:299
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/hugetlb.c (ffffffff811def0d)
Location: include/linux/pagemap.h:299
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In fs/dax.c (ffffffff8125dffb)
Location: include/linux/pagemap.h:299
Inline: True
Inline callers:
  - fs/dax.c:__dax_fault
```
```
In fs/ext4/inode.c (ffffffff8129ebf0)
Location: include/linux/pagemap.h:299
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/hugetlbfs/inode.c (ffffffff812f3c95)
Location: include/linux/pagemap.h:299
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
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
In mm/truncate.c (ffffffff811b4e38)
Location: include/linux/pagemap.h:271
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811bfddd)
Location: include/linux/pagemap.h:271
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/hugetlb.c (ffffffff811fd3d6)
Location: include/linux/pagemap.h:271
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In fs/ext4/inode.c (ffffffff812cd1aa)
Location: include/linux/pagemap.h:271
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/hugetlbfs/inode.c (ffffffff81328271)
Location: include/linux/pagemap.h:271
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
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
In mm/truncate.c (ffffffff811c5459)
Location: include/linux/pagemap.h:281
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811d0653)
Location: include/linux/pagemap.h:281
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/hugetlb.c (ffffffff8120dea5)
Location: include/linux/pagemap.h:281
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In fs/ext4/inode.c (ffffffff812e2f26)
Location: include/linux/pagemap.h:281
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/hugetlbfs/inode.c (ffffffff8133dfc1)
Location: include/linux/pagemap.h:281
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
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
In mm/truncate.c (ffffffff811cd902)
Location: include/linux/pagemap.h:297
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811d8aed)
Location: include/linux/pagemap.h:297
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/hugetlb.c (ffffffff81219e1a)
Location: include/linux/pagemap.h:297
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In fs/ext4/inode.c (ffffffff813074b1)
Location: include/linux/pagemap.h:297
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/hugetlbfs/inode.c (ffffffff81352c4b)
Location: include/linux/pagemap.h:297
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
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
In mm/truncate.c (ffffffff811e2bee)
Location: include/linux/pagemap.h:294
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/hugetlb.c (ffffffff81234eea)
Location: include/linux/pagemap.h:294
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In fs/ext4/inode.c (ffffffff8132c09f)
Location: include/linux/pagemap.h:294
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/hugetlbfs/inode.c (ffffffff8137777b)
Location: include/linux/pagemap.h:294
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
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
In mm/truncate.c (ffffffff8120419f)
Location: include/linux/pagemap.h:294
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/hugetlb.c (ffffffff81257ce9)
Location: include/linux/pagemap.h:294
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In fs/ext4/inode.c (ffffffff8135a639)
Location: include/linux/pagemap.h:294
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/hugetlbfs/inode.c (ffffffff813a5b8e)
Location: include/linux/pagemap.h:294
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
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
In mm/truncate.c (ffffffff81216b5f)
Location: include/linux/pagemap.h:294
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/hugetlb.c (ffffffff8126c3a2)
Location: include/linux/pagemap.h:294
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In fs/ext4/inode.c (ffffffff81372985)
Location: include/linux/pagemap.h:294
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/hugetlbfs/inode.c (ffffffff813bee25)
Location: include/linux/pagemap.h:294
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/fuse/readdir.c (ffffffff813e9d6b)
Location: include/linux/pagemap.h:294
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
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
In mm/truncate.c (ffffffff81225ec1)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/hugetlb.c (ffffffff81287753)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In fs/ext4/inode.c (ffffffff8139bd8d)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/hugetlbfs/inode.c (ffffffff813e96a0)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/fuse/readdir.c (ffffffff81415ed4)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
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
In mm/truncate.c (ffffffff8123438f)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/hugetlb.c (ffffffff81297363)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/khugepaged.c (ffffffff812bc469)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/ext4/inode.c (ffffffff813b4895)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/hugetlbfs/inode.c (ffffffff81403740)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/fuse/readdir.c (ffffffff8142fdb4)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
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
In mm/truncate.c (ffffffff81261347)
Location: include/linux/pagemap.h:320
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/hugetlb.c (ffffffff812ca94d)
Location: include/linux/pagemap.h:320
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/khugepaged.c (ffffffff812f1b09)
Location: include/linux/pagemap.h:320
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/ext4/inode.c (ffffffff813ffd42)
Location: include/linux/pagemap.h:320
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/hugetlbfs/inode.c (ffffffff8145166b)
Location: include/linux/pagemap.h:320
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/fuse/readdir.c (ffffffff8147fd35)
Location: include/linux/pagemap.h:320
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
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
In mm/truncate.c (ffffffff8126b747)
Location: include/linux/pagemap.h:357
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/hugetlb.c (ffffffff812d657a)
Location: include/linux/pagemap.h:357
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/khugepaged.c (ffffffff812fe090)
Location: include/linux/pagemap.h:357
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/ext4/inode.c (ffffffff81412558)
Location: include/linux/pagemap.h:357
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/hugetlbfs/inode.c (ffffffff8146db8b)
Location: include/linux/pagemap.h:357
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/fuse/readdir.c (ffffffff8149b415)
Location: include/linux/pagemap.h:357
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
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
In mm/truncate.c (ffffffff812702d7)
Location: include/linux/pagemap.h:373
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/hugetlb.c (ffffffff812da58d)
Location: include/linux/pagemap.h:373
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/khugepaged.c (ffffffff81304a57)
Location: include/linux/pagemap.h:373
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/ext4/inode.c (ffffffff814189d0)
Location: include/linux/pagemap.h:373
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/hugetlbfs/inode.c (ffffffff81473101)
Location: include/linux/pagemap.h:373
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/fuse/readdir.c (ffffffff814a0625)
Location: include/linux/pagemap.h:373
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
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
In mm/truncate.c (ffffffff812ad57f)
Location: include/linux/pagemap.h:373
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/hugetlb.c (ffffffff81321512)
Location: include/linux/pagemap.h:373
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/khugepaged.c (ffffffff8134e7c7)
Location: include/linux/pagemap.h:373
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/secretmem.c (ffffffff81366710)
Location: include/linux/pagemap.h:373
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In fs/ext4/inode.c (ffffffff8146bbcb)
Location: include/linux/pagemap.h:373
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/hugetlbfs/inode.c (ffffffff814c9c47)
Location: include/linux/pagemap.h:373
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/fuse/readdir.c (ffffffff814f84f3)
Location: include/linux/pagemap.h:373
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
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
In mm/truncate.c (ffffffff81308007)
Location: include/linux/pagemap.h:587
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
```
```
In mm/hugetlb.c (ffffffff8138e21c)
Location: include/linux/pagemap.h:587
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/khugepaged.c (ffffffff813c4ea3)
Location: include/linux/pagemap.h:587
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/secretmem.c (ffffffff813e3a16)
Location: include/linux/pagemap.h:587
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In fs/hugetlbfs/inode.c (ffffffff81555002)
Location: include/linux/pagemap.h:587
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/fuse/readdir.c (ffffffff815888b6)
Location: include/linux/pagemap.h:587
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
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
In mm/truncate.c (ffffffff81371fb7)
Location: include/linux/pagemap.h:584
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
```
```
In mm/hugetlb.c (ffffffff8140ce28)
Location: include/linux/pagemap.h:584
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/khugepaged.c (ffffffff81449750)
Location: include/linux/pagemap.h:584
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/secretmem.c (ffffffff8146b3f3)
Location: include/linux/pagemap.h:584
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In fs/hugetlbfs/inode.c (ffffffff815f7b2e)
Location: include/linux/pagemap.h:584
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/fuse/readdir.c (ffffffff8162ed76)
Location: include/linux/pagemap.h:584
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
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
In mm/truncate.c (ffffffff813a4157)
Location: include/linux/pagemap.h:611
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
```
```
In mm/khugepaged.c (ffffffff8147f75c)
Location: include/linux/pagemap.h:611
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/secretmem.c (ffffffff814a01d9)
Location: include/linux/pagemap.h:611
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In fs/hugetlbfs/inode.c (ffffffff8162faa6)
Location: include/linux/pagemap.h:611
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/fuse/readdir.c (ffffffff81666fd9)
Location: include/linux/pagemap.h:611
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
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
In mm/truncate.c (ffffffff813cdca7)
Location: include/linux/pagemap.h:729
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
```
```
In mm/khugepaged.c (ffffffff814ad85d)
Location: include/linux/pagemap.h:729
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/secretmem.c (ffffffff814cf85f)
Location: include/linux/pagemap.h:729
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In fs/fuse/readdir.c (ffffffff816a1329)
Location: include/linux/pagemap.h:729
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
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
In mm/truncate.c (ffff8000102c49c8)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/hugetlb.c (ffff8000103351c8)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/khugepaged.c (ffff80001035d8f0)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/ext4/inode.c (ffff800010488f80)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/hugetlbfs/inode.c (ffff8000104e18e4)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/fuse/readdir.c (ffff800010514948)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
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
In mm/truncate.c (c04ef2bc)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/ext4/inode.c (c064b4f8)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/fuse/readdir.c (c06cf560)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
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
In mm/truncate.c (c00000000037e810)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/hugetlb.c (c00000000040ea3c)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/khugepaged.c (c000000000448bdc)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/ext4/inode.c (c0000000005afd50)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/hugetlbfs/inode.c (c00000000061ede8)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/fuse/readdir.c (c00000000065cc70)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
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
In mm/truncate.c (ffffffe0001e527a)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/hugetlb.c (ffffffe000231906)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In fs/ext4/inode.c (ffffffe000310888)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/hugetlbfs/inode.c (ffffffe000355ca2)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/fuse/readdir.c (ffffffe00037e338)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
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
In mm/truncate.c (ffffffff8122c9df)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/hugetlb.c (ffffffff8128f943)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/khugepaged.c (ffffffff812b4a49)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/ext4/inode.c (ffffffff813ace75)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/hugetlbfs/inode.c (ffffffff813fbd20)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/fuse/readdir.c (ffffffff81428394)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
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
In mm/truncate.c (ffffffff8121fabf)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/hugetlb.c (ffffffff812815f8)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/khugepaged.c (ffffffff812a5a9b)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/ext4/inode.c (ffffffff8139d905)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/hugetlbfs/inode.c (ffffffff813ec7a0)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/fuse/readdir.c (ffffffff81418e14)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
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
In mm/truncate.c (ffffffff8122a77f)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/hugetlb.c (ffffffff8128d753)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/khugepaged.c (ffffffff812b2859)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/ext4/inode.c (ffffffff813aa6d5)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/hugetlbfs/inode.c (ffffffff813f90a0)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/fuse/readdir.c (ffffffff81424534)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
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
In mm/truncate.c (ffffffff81239b57)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/hugetlb.c (ffffffff8129d4e2)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/khugepaged.c (ffffffff812c2a92)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/ext4/inode.c (ffffffff813befca)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/hugetlbfs/inode.c (ffffffff8140eee0)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/fuse/readdir.c (ffffffff8143b7ee)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
</details>
</li>
</ul>

## Differences
