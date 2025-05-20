# Function: <code>ClearPageDirty</code>

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
In mm/page-writeback.c (ffffffff8119b966)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - mm/page-writeback.c:cancel_dirty_page
```
```
In mm/vmscan.c (ffffffff811a0a41)
Location: include/linux/page-flags.h:213
Inline: True
```
```
In mm/shmem.c (ffffffff811a971c)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/migrate.c (ffffffff811f176d)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memory-failure.c (ffffffff81201939)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/ext4/inline.c (ffffffff812e1061)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/hugetlbfs/inode.c (ffffffff812f38c3)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In mm/page-writeback.c (ffffffff811b0a28)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/page-writeback.c:cancel_dirty_page
```
```
In mm/vmscan.c (ffffffff811b6e41)
Location: include/linux/page-flags.h:260
Inline: True
```
```
In mm/shmem.c (ffffffff811c0c5e)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/madvise.c (ffffffff811eeef1)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (ffffffff81210d5f)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81218371)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff812267e5)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/ext4/inline.c (ffffffff81310e62)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/hugetlbfs/inode.c (ffffffff81327d72)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
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
In mm/page-writeback.c (ffffffff811c1008)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/page-writeback.c:cancel_dirty_page
```
```
In mm/vmscan.c (ffffffff811c7441)
Location: include/linux/page-flags.h:270
Inline: True
```
```
In mm/shmem.c (ffffffff811d1263)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/madvise.c (ffffffff811ff7a4)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (ffffffff81222ee0)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8122a915)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff81238db5)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/ext4/inline.c (ffffffff81326d1a)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/hugetlbfs/inode.c (ffffffff8133dabd)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
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
In mm/page-writeback.c (ffffffff811c9244)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/page-writeback.c:cancel_dirty_page
```
```
In mm/vmscan.c (ffffffff811cfbd6)
Location: include/linux/page-flags.h:270
Inline: True
```
```
In mm/shmem.c (ffffffff811d9c82)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/madvise.c (ffffffff8120a332)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (ffffffff8122e925)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812365ad)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff812450d5)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/ext4/inline.c (ffffffff812fac2e)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/hugetlbfs/inode.c (ffffffff813518b5)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
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
In mm/page-writeback.c (ffffffff811de044)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/vmscan.c (ffffffff811e51cc)
Location: include/linux/page-flags.h:271
Inline: True
```
```
In mm/shmem.c (ffffffff811ef96e)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/madvise.c (ffffffff8122359b)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (ffffffff8124aa6c)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8125553c)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff81264ff5)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/ext4/inline.c (ffffffff8131f31e)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/hugetlbfs/inode.c (ffffffff813763c5)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
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
In mm/page-writeback.c (ffffffff811ff67a)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/vmscan.c (ffffffff812068fc)
Location: include/linux/page-flags.h:278
Inline: True
```
```
In mm/shmem.c (ffffffff81211035)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/madvise.c (ffffffff81246411)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (ffffffff8126e897)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81278a9c)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff81289315)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/ext4/inline.c (ffffffff8134d3ec)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/hugetlbfs/inode.c (ffffffff813a4cd5)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
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
In mm/page-writeback.c (ffffffff81211f4a)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/vmscan.c (ffffffff812194be)
Location: include/linux/page-flags.h:287
Inline: True
```
```
In mm/shmem.c (ffffffff81222893)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/madvise.c (ffffffff8125a835)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (ffffffff8128255d)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8128d138)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff8129e265)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/ext4/inline.c (ffffffff8136557c)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/hugetlbfs/inode.c (ffffffff813bdad5)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
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
In mm/page-writeback.c (ffffffff81221887)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/vmscan.c (ffffffff81228cb4)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In mm/shmem.c (ffffffff81231e98)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/madvise.c (ffffffff81275a60)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (ffffffff8129e50f)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812a2414)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff812b9435)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/ext4/inline.c (ffffffff8138e8bd)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/hugetlbfs/inode.c (ffffffff813e83b5)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
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
In mm/page-writeback.c (ffffffff8122f337)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/vmscan.c (ffffffff81236b54)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In mm/shmem.c (ffffffff8123ff58)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/madvise.c (ffffffff81284a30)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (ffffffff812addbd)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812b37ce)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff812cb325)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/ext4/inline.c (ffffffff813a731d)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/hugetlbfs/inode.c (ffffffff81402455)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
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
In mm/page-writeback.c (ffffffff8125c3e7)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/vmscan.c (ffffffff81265e23)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff8126e6ae)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/madvise.c (ffffffff812b6c19)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (ffffffff812e48f3)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812e9192)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff81301645)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/ext4/inline.c (ffffffff813f34bd)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/hugetlbfs/inode.c (ffffffff81450ba5)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
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
In mm/page-writeback.c (ffffffff81266757)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/vmscan.c (ffffffff812707be)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff812790ac)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/madvise.c (ffffffff812c2f10)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (ffffffff812ef2e1)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812f461d)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff8130d705)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/ext4/inline.c (ffffffff81405c4d)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/hugetlbfs/inode.c (ffffffff8146d0b5)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
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
In mm/page-writeback.c (ffffffff8126b267)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/vmscan.c (ffffffff81274d5e)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff8127e05a)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/madvise.c (ffffffff812c9d89)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (ffffffff812f5f51)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812fab9d)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff81313a45)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/ext4/inline.c (ffffffff8140bf85)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/hugetlbfs/inode.c (ffffffff814727a5)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
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
In mm/page-writeback.c (ffffffff812a7d47)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/vmscan.c (ffffffff812b200e)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff812bd429)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
```
```
In mm/madvise.c (ffffffff8130eda9)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (ffffffff81340533)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff813449e3)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff8135ed35)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/ext4/inline.c (ffffffff8145eb86)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/hugetlbfs/inode.c (ffffffff814c9025)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
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
In mm/shmem.c (ffffffff8131b969)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/madvise.c (ffffffff81376997)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffffffff813c05a4)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff813d9435)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/ext4/inline.c (ffffffff814dd2e2)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff814e2055)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/hugetlbfs/inode.c (ffffffff81555435)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
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
In mm/huge_memory.c (ffffffff81442870)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff8145f705)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/ext4/inline.c (ffffffff81576312)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff8157b3be)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
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
In mm/memory-failure.c (ffffffff81495915)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
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
In mm/page-writeback.c (ffff8000102be6a8)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/vmscan.c (ffff8000102c88e8)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In mm/shmem.c (ffff8000102d32ac)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/madvise.c (ffff80001031ebf0)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (ffff80001034fcb4)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffff80001035499c)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffff80001036e788)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/ext4/inline.c (ffff80001047ab04)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/hugetlbfs/inode.c (ffff8000104e1b20)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
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
In mm/page-writeback.c (c04e7364)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/vmscan.c (c04f50c8)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (c04fb284)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/madvise.c (c0537820)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (c0550fdc)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In fs/ext4/inline.c (c063c4d8)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
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
In mm/page-writeback.c (c000000000375040)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/vmscan.c (c000000000384a18)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In mm/shmem.c (c000000000391d5c)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/madvise.c (c0000000003f3424)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (c0000000004331e4)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (c00000000043b9d4)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (c00000000045fc2c)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/ext4/inline.c (c00000000059db6c)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/hugetlbfs/inode.c (c00000000061d21c)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
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
In mm/page-writeback.c (ffffffe0001df6f0)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/vmscan.c (ffffffe0001e7244)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In mm/shmem.c (ffffffe0001ee488)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/madvise.c (ffffffe00022061e)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (ffffffe00023eaba)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In fs/ext4/inline.c (ffffffe0003052a8)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/hugetlbfs/inode.c (ffffffe000354a92)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
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
In mm/page-writeback.c (ffffffff81227987)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/vmscan.c (ffffffff8122f1a4)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In mm/shmem.c (ffffffff812385a8)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/madvise.c (ffffffff8127d080)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (ffffffff812a639d)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812abdae)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff812c3905)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/ext4/inline.c (ffffffff8139f8fd)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/hugetlbfs/inode.c (ffffffff813faa35)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
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
In mm/page-writeback.c (ffffffff8121aad7)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/vmscan.c (ffffffff81222264)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In mm/shmem.c (ffffffff8122b5a6)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/madvise.c (ffffffff8126eefd)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (ffffffff81297e4d)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8129d91e)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff812b4945)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/ext4/inline.c (ffffffff8139038d)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/hugetlbfs/inode.c (ffffffff813eb4b5)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
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
In mm/page-writeback.c (ffffffff81225727)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/vmscan.c (ffffffff8122cf44)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In mm/shmem.c (ffffffff81236348)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/madvise.c (ffffffff8127ae20)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (ffffffff812a41ad)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812a9bbe)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff812c1715)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/ext4/inline.c (ffffffff8139d15d)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/hugetlbfs/inode.c (ffffffff813f7db5)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
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
In mm/page-writeback.c (ffffffff81234a27)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/vmscan.c (ffffffff8123c388)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In mm/shmem.c (ffffffff8124661f)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/madvise.c (ffffffff8128a9f9)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (ffffffff812b391d)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812b9e3e)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff812d21d5)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/ext4/inline.c (ffffffff813b16a5)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/hugetlbfs/inode.c (ffffffff8140db05)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
```
</details>
</li>
</ul>

## Differences
