# Function: <code>pmd_dirty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81278a06)
Location: arch/x86/include/asm/pgtable.h:110
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/huge_memory.c (ffffffff812161ac)
Location: arch/x86/include/asm/pgtable.h:121
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff812a55ad)
Location: arch/x86/include/asm/pgtable.h:121
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
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
In mm/huge_memory.c (ffffffff81228766)
Location: arch/x86/include/asm/pgtable.h:121
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In fs/dax.c (ffffffff8129bb68)
Location: arch/x86/include/asm/pgtable.h:121
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812baefd)
Location: arch/x86/include/asm/pgtable.h:121
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
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
In mm/rmap.c (ffffffff8120323e)
Location: arch/x86/include/asm/pgtable.h:133
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/huge_memory.c (ffffffff81231e0d)
Location: arch/x86/include/asm/pgtable.h:133
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
```
```
In fs/dax.c (ffffffff812aaab5)
Location: arch/x86/include/asm/pgtable.h:133
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (ffffffff812c807d)
Location: arch/x86/include/asm/pgtable.h:133
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/rmap.c (ffffffff8121bd2a)
Location: arch/x86/include/asm/pgtable.h:143
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/huge_memory.c (ffffffff81255992)
Location: arch/x86/include/asm/pgtable.h:143
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
```
```
In fs/dax.c (ffffffff812ce079)
Location: arch/x86/include/asm/pgtable.h:143
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (ffffffff812eb937)
Location: arch/x86/include/asm/pgtable.h:143
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/rmap.c (ffffffff8123dc32)
Location: arch/x86/include/asm/pgtable.h:143
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/huge_memory.c (ffffffff81279859)
Location: arch/x86/include/asm/pgtable.h:143
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In fs/dax.c (ffffffff812f869a)
Location: arch/x86/include/asm/pgtable.h:143
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (ffffffff81318e01)
Location: arch/x86/include/asm/pgtable.h:143
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/rmap.c (ffffffff81252217)
Location: arch/x86/include/asm/pgtable.h:145
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/huge_memory.c (ffffffff8128de8f)
Location: arch/x86/include/asm/pgtable.h:145
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In fs/dax.c (ffffffff8130c41f)
Location: arch/x86/include/asm/pgtable.h:145
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff8132feb1)
Location: arch/x86/include/asm/pgtable.h:145
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/rmap.c (ffffffff81264a7c)
Location: arch/x86/include/asm/pgtable.h:162
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/huge_memory.c (ffffffff812a880f)
Location: arch/x86/include/asm/pgtable.h:162
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In fs/dax.c (ffffffff81333962)
Location: arch/x86/include/asm/pgtable.h:162
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81357ce8)
Location: arch/x86/include/asm/pgtable.h:162
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/rmap.c (ffffffff81273303)
Location: arch/x86/include/asm/pgtable.h:162
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/huge_memory.c (ffffffff812b9d8f)
Location: arch/x86/include/asm/pgtable.h:162
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In fs/dax.c (ffffffff81347527)
Location: arch/x86/include/asm/pgtable.h:162
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff8136ff18)
Location: arch/x86/include/asm/pgtable.h:162
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/rmap.c (ffffffff812a3ed3)
Location: arch/x86/include/asm/pgtable.h:164
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/huge_memory.c (ffffffff812ee933)
Location: arch/x86/include/asm/pgtable.h:164
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/mapping_dirty_helpers.c (0)
Location: arch/x86/include/asm/pgtable.h:164
Inline: True
```
```
In fs/dax.c (ffffffff8138d902)
Location: arch/x86/include/asm/pgtable.h:164
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813b7f43)
Location: arch/x86/include/asm/pgtable.h:164
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/rmap.c (ffffffff812afbe0)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/huge_memory.c (ffffffff812f9fa3)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/mapping_dirty_helpers.c (0)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
```
```
In fs/dax.c (ffffffff8139f382)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813c9e03)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/rmap.c (ffffffff812b5181)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/huge_memory.c (ffffffff81300d4f)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/mapping_dirty_helpers.c (0)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
```
```
In fs/dax.c (ffffffff813a60ef)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813d1463)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/rmap.c (ffffffff812f6d1d)
Location: arch/x86/include/asm/pgtable.h:134
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/huge_memory.c (ffffffff8134a9ef)
Location: arch/x86/include/asm/pgtable.h:134
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/mapping_dirty_helpers.c (0)
Location: arch/x86/include/asm/pgtable.h:134
Inline: True
```
```
In fs/dax.c (ffffffff813f5b5f)
Location: arch/x86/include/asm/pgtable.h:134
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81422963)
Location: arch/x86/include/asm/pgtable.h:134
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/rmap.c (ffffffff8135b21a)
Location: arch/x86/include/asm/pgtable.h:137
Inline: True
```
```
In mm/huge_memory.c (ffffffff813c199c)
Location: arch/x86/include/asm/pgtable.h:137
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/mapping_dirty_helpers.c (0)
Location: arch/x86/include/asm/pgtable.h:137
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81499a73)
Location: arch/x86/include/asm/pgtable.h:137
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/vmscan.c (ffffffff8137f6c8)
Location: arch/x86/include/asm/pgtable.h:137
Inline: True
```
```
In mm/rmap.c (ffffffff813d6115)
Location: arch/x86/include/asm/pgtable.h:137
Inline: True
```
```
In mm/huge_memory.c (ffffffff81443a5c)
Location: arch/x86/include/asm/pgtable.h:137
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/mapping_dirty_helpers.c (0)
Location: arch/x86/include/asm/pgtable.h:137
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8152dca3)
Location: arch/x86/include/asm/pgtable.h:137
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/vmscan.c (ffffffff813b0bf8)
Location: arch/x86/include/asm/pgtable.h:138
Inline: True
```
```
In mm/rmap.c (ffffffff8140b219)
Location: arch/x86/include/asm/pgtable.h:138
Inline: True
```
```
In mm/huge_memory.c (ffffffff81478f9a)
Location: arch/x86/include/asm/pgtable.h:138
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/mapping_dirty_helpers.c (0)
Location: arch/x86/include/asm/pgtable.h:138
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff815660fc)
Location: arch/x86/include/asm/pgtable.h:138
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/vmscan.c (ffffffff813da231)
Location: arch/x86/include/asm/pgtable.h:145
Inline: True
```
```
In mm/rmap.c (ffffffff81437b56)
Location: arch/x86/include/asm/pgtable.h:145
Inline: True
```
```
In mm/huge_memory.c (ffffffff814a85a3)
Location: arch/x86/include/asm/pgtable.h:145
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:can_change_pmd_writable
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d7a53)
Location: arch/x86/include/asm/pgtable.h:145
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/proc/task_mmu.c (ffffffff8159e0e8)
Location: arch/x86/include/asm/pgtable.h:145
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In mm/rmap.c (ffffffff8126b953)
Location: arch/x86/include/asm/pgtable.h:162
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/huge_memory.c (ffffffff812b236f)
Location: arch/x86/include/asm/pgtable.h:162
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In fs/dax.c (ffffffff8133fb07)
Location: arch/x86/include/asm/pgtable.h:162
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813684f8)
Location: arch/x86/include/asm/pgtable.h:162
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/rmap.c (ffffffff8125d563)
Location: arch/x86/include/asm/pgtable.h:162
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/huge_memory.c (ffffffff812a36ff)
Location: arch/x86/include/asm/pgtable.h:162
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In fs/dax.c (ffffffff81330726)
Location: arch/x86/include/asm/pgtable.h:162
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81359838)
Location: arch/x86/include/asm/pgtable.h:162
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/rmap.c (ffffffff812696f3)
Location: arch/x86/include/asm/pgtable.h:162
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/huge_memory.c (ffffffff812b017f)
Location: arch/x86/include/asm/pgtable.h:162
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In fs/dax.c (ffffffff8133d5d7)
Location: arch/x86/include/asm/pgtable.h:162
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81365fc8)
Location: arch/x86/include/asm/pgtable.h:162
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/rmap.c (ffffffff8127920c)
Location: arch/x86/include/asm/pgtable.h:162
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/huge_memory.c (ffffffff812c04bf)
Location: arch/x86/include/asm/pgtable.h:162
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In fs/dax.c (ffffffff813504ed)
Location: arch/x86/include/asm/pgtable.h:162
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81379bb3)
Location: arch/x86/include/asm/pgtable.h:162
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
</details>
</li>
</ul>

## Differences
