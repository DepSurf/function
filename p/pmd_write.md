# Function: <code>pmd_write</code>

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
In mm/memory.c (ffffffff811beda2)
Location: arch/x86/include/asm/pgtable.h:824
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff811f61f5)
Location: arch/x86/include/asm/pgtable.h:824
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:875
Inline: True
```
```
In mm/huge_memory.c (ffffffff8121617a)
Location: arch/x86/include/asm/pgtable.h:875
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:875
Inline: True
```
```
In mm/huge_memory.c (ffffffff8122872c)
Location: arch/x86/include/asm/pgtable.h:875
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:875
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1074
Inline: True
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:1074
Inline: True
```
```
In mm/huge_memory.c (ffffffff81231ddd)
Location: arch/x86/include/asm/pgtable.h:1074
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:1074
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
In mm/memory.c (ffffffff8120e904)
Location: arch/x86/include/asm/pgtable.h:1080
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:1080
Inline: True
```
```
In mm/huge_memory.c (ffffffff81255bb8)
Location: arch/x86/include/asm/pgtable.h:1080
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/hmm.c (ffffffff8126e61f)
Location: arch/x86/include/asm/pgtable.h:1080
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:1080
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
In mm/memory.c (ffffffff8123009f)
Location: arch/x86/include/asm/pgtable.h:1131
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:1131
Inline: True
```
```
In mm/huge_memory.c (ffffffff81279992)
Location: arch/x86/include/asm/pgtable.h:1131
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/hmm.c (ffffffff81293246)
Location: arch/x86/include/asm/pgtable.h:1131
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:1131
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
In mm/memory.c (ffffffff81241d8d)
Location: arch/x86/include/asm/pgtable.h:1156
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:1156
Inline: True
```
```
In mm/huge_memory.c (ffffffff8128df8c)
Location: arch/x86/include/asm/pgtable.h:1156
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/hmm.c (ffffffff812a7799)
Location: arch/x86/include/asm/pgtable.h:1156
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:1156
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
In mm/memory.c (ffffffff812546f7)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
```
```
In mm/huge_memory.c (ffffffff812a890f)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/hmm.c (ffffffff812c48c8)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:1176
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
In mm/memory.c (ffffffff81262c57)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b9e8f)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/hmm.c (ffffffff812d62e5)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:1176
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
In mm/memory.c (ffffffff81294b52)
Location: arch/x86/include/asm/pgtable.h:1136
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:1136
Inline: True
```
```
In mm/huge_memory.c (ffffffff812eeb1d)
Location: arch/x86/include/asm/pgtable.h:1136
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/hmm.c (0)
Location: arch/x86/include/asm/pgtable.h:1136
Inline: True
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130c8a6)
Location: arch/x86/include/asm/pgtable.h:1136
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff8137244c)
Location: arch/x86/include/asm/pgtable.h:1136
Inline: True
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:1136
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
In mm/memory.c (ffffffff8129f3d2)
Location: arch/x86/include/asm/pgtable.h:1132
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:1132
Inline: True
```
```
In mm/huge_memory.c (ffffffff812fa17d)
Location: arch/x86/include/asm/pgtable.h:1132
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/hmm.c (0)
Location: arch/x86/include/asm/pgtable.h:1132
Inline: True
```
```
In mm/mapping_dirty_helpers.c (ffffffff813187e6)
Location: arch/x86/include/asm/pgtable.h:1132
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff8138029c)
Location: arch/x86/include/asm/pgtable.h:1132
Inline: True
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:1132
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
In mm/memory.c (ffffffff812a42b3)
Location: arch/x86/include/asm/pgtable.h:1132
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:1132
Inline: True
```
```
In mm/huge_memory.c (ffffffff81300f2e)
Location: arch/x86/include/asm/pgtable.h:1132
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/hmm.c (0)
Location: arch/x86/include/asm/pgtable.h:1132
Inline: True
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131e9d6)
Location: arch/x86/include/asm/pgtable.h:1132
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff81387623)
Location: arch/x86/include/asm/pgtable.h:1132
Inline: True
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:1132
Inline: True
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
In mm/memory.c (ffffffff812e5710)
Location: arch/x86/include/asm/pgtable.h:1103
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:1103
Inline: True
```
```
In mm/huge_memory.c (ffffffff8134ab9e)
Location: arch/x86/include/asm/pgtable.h:1103
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/hmm.c (0)
Location: arch/x86/include/asm/pgtable.h:1103
Inline: True
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136bdb6)
Location: arch/x86/include/asm/pgtable.h:1103
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff813d48fa)
Location: arch/x86/include/asm/pgtable.h:1103
Inline: True
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:1103
Inline: True
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
In mm/gup.c (ffffffff8133aa51)
Location: arch/x86/include/asm/pgtable.h:1106
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pmd
```
```
In mm/memory.c (ffffffff81347a64)
Location: arch/x86/include/asm/pgtable.h:1106
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:1106
Inline: True
```
```
In mm/huge_memory.c (ffffffff813c1d2c)
Location: arch/x86/include/asm/pgtable.h:1106
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/hmm.c (ffffffff813e8af1)
Location: arch/x86/include/asm/pgtable.h:1106
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff813e9fcf)
Location: arch/x86/include/asm/pgtable.h:1106
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff8145fdaa)
Location: arch/x86/include/asm/pgtable.h:1106
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
In mm/gup.c (ffffffff813b2577)
Location: arch/x86/include/asm/pgtable.h:1124
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pmd
```
```
In mm/memory.c (ffffffff813bfe1a)
Location: arch/x86/include/asm/pgtable.h:1124
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:1124
Inline: True
```
```
In mm/huge_memory.c (ffffffff81443f0c)
Location: arch/x86/include/asm/pgtable.h:1124
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/hmm.c (ffffffff81470a79)
Location: arch/x86/include/asm/pgtable.h:1124
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff8147207e)
Location: arch/x86/include/asm/pgtable.h:1124
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff814ef69d)
Location: arch/x86/include/asm/pgtable.h:1124
Inline: True
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
In mm/gup.c (ffffffff813e72d2)
Location: arch/x86/include/asm/pgtable.h:1125
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pmd
```
```
In mm/memory.c (ffffffff813f4ad5)
Location: arch/x86/include/asm/pgtable.h:1125
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:1125
Inline: True
```
```
In mm/huge_memory.c (ffffffff8147948c)
Location: arch/x86/include/asm/pgtable.h:1125
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/hmm.c (ffffffff814a4fed)
Location: arch/x86/include/asm/pgtable.h:1125
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a693d)
Location: arch/x86/include/asm/pgtable.h:1125
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff81524e20)
Location: arch/x86/include/asm/pgtable.h:1125
Inline: True
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
In mm/gup.c (ffffffff81411f52)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pmd
```
```
In mm/memory.c (ffffffff81421181)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
```
```
In mm/huge_memory.c (ffffffff814a8748)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/hmm.c (0)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d79cd)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff81558ab1)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:890
Inline: False
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:890
Inline: True
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
In mm/memory.c (ffffffff8125b2a7)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b246f)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/hmm.c (ffffffff812ce8c5)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:1176
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
In mm/memory.c (ffffffff8124d5c9)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
```
```
In mm/huge_memory.c (ffffffff812a37fb)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/hmm.c (ffffffff812bf5e7)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:1176
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
In mm/memory.c (ffffffff81259047)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b027f)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/hmm.c (ffffffff812cc6d5)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:1176
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
In mm/memory.c (ffffffff81268a47)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
```
```
In mm/huge_memory.c (ffffffff812c05bf)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/hmm.c (ffffffff812dd435)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
```
</details>
</li>
</ul>

## Differences
