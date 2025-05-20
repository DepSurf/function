# Function: <code>pmd_young</code>

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
In arch/x86/mm/pgtable.c (ffffffff81071009)
Location: arch/x86/include/asm/pgtable.h:115
Inline: True
```
```
In mm/huge_memory.c (ffffffff811f76ae)
Location: arch/x86/include/asm/pgtable.h:115
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:115
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
In arch/x86/mm/pgtable.c (ffffffff81070f88)
Location: arch/x86/include/asm/pgtable.h:126
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/huge_memory.c (ffffffff812160b7)
Location: arch/x86/include/asm/pgtable.h:126
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:126
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
In arch/x86/mm/pgtable.c (ffffffff81074b08)
Location: arch/x86/include/asm/pgtable.h:126
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/huge_memory.c (ffffffff81228679)
Location: arch/x86/include/asm/pgtable.h:126
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:126
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
In arch/x86/mm/pgtable.c (ffffffff810740d8)
Location: arch/x86/include/asm/pgtable.h:138
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/huge_memory.c (ffffffff81231ce6)
Location: arch/x86/include/asm/pgtable.h:138
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff812c68fa)
Location: arch/x86/include/asm/pgtable.h:138
Inline: True
Inline callers:
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
In arch/x86/mm/pgtable.c (ffffffff81079b6f)
Location: arch/x86/include/asm/pgtable.h:148
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/huge_memory.c (ffffffff81252937)
Location: arch/x86/include/asm/pgtable.h:148
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:148
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
In arch/x86/mm/pgtable.c (ffffffff8107c64f)
Location: arch/x86/include/asm/pgtable.h:148
Inline: True
```
```
In mm/huge_memory.c (ffffffff81276d84)
Location: arch/x86/include/asm/pgtable.h:148
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81319404)
Location: arch/x86/include/asm/pgtable.h:148
Inline: True
Inline callers:
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
In arch/x86/mm/pgtable.c (ffffffff8108305f)
Location: arch/x86/include/asm/pgtable.h:150
Inline: True
```
```
In mm/huge_memory.c (ffffffff8128861a)
Location: arch/x86/include/asm/pgtable.h:150
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81330a18)
Location: arch/x86/include/asm/pgtable.h:150
Inline: True
Inline callers:
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
In arch/x86/mm/pgtable.c (ffffffff81086ccf)
Location: arch/x86/include/asm/pgtable.h:167
Inline: True
```
```
In mm/huge_memory.c (ffffffff812a3258)
Location: arch/x86/include/asm/pgtable.h:167
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8135883f)
Location: arch/x86/include/asm/pgtable.h:167
Inline: True
Inline callers:
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
In arch/x86/mm/pgtable.c (ffffffff810879bf)
Location: arch/x86/include/asm/pgtable.h:167
Inline: True
```
```
In mm/madvise.c (ffffffff81285325)
Location: arch/x86/include/asm/pgtable.h:167
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff812b4758)
Location: arch/x86/include/asm/pgtable.h:167
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81370a8f)
Location: arch/x86/include/asm/pgtable.h:167
Inline: True
Inline callers:
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
In arch/x86/mm/pgtable.c (ffffffff81089ecf)
Location: arch/x86/include/asm/pgtable.h:169
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/madvise.c (ffffffff812b7803)
Location: arch/x86/include/asm/pgtable.h:169
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff812e9d06)
Location: arch/x86/include/asm/pgtable.h:169
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff813b7a00)
Location: arch/x86/include/asm/pgtable.h:169
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
In arch/x86/mm/pgtable.c (ffffffff8108a14f)
Location: arch/x86/include/asm/pgtable.h:168
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/madvise.c (ffffffff812c2744)
Location: arch/x86/include/asm/pgtable.h:168
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff812f4ee6)
Location: arch/x86/include/asm/pgtable.h:168
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff813c9490)
Location: arch/x86/include/asm/pgtable.h:168
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
In arch/x86/mm/pgtable.c (ffffffff8108ada5)
Location: arch/x86/include/asm/pgtable.h:168
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/madvise.c (ffffffff812c95ca)
Location: arch/x86/include/asm/pgtable.h:168
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff812fb445)
Location: arch/x86/include/asm/pgtable.h:168
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff813d056d)
Location: arch/x86/include/asm/pgtable.h:168
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
In arch/x86/mm/pgtable.c (ffffffff8109a345)
Location: arch/x86/include/asm/pgtable.h:139
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/madvise.c (ffffffff8130e5f0)
Location: arch/x86/include/asm/pgtable.h:139
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff81345274)
Location: arch/x86/include/asm/pgtable.h:139
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81421d17)
Location: arch/x86/include/asm/pgtable.h:139
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
In arch/x86/mm/pgtable.c (ffffffff810ad4a5)
Location: arch/x86/include/asm/pgtable.h:142
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/madvise.c (ffffffff81377931)
Location: arch/x86/include/asm/pgtable.h:142
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff813bb114)
Location: arch/x86/include/asm/pgtable.h:142
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8149a202)
Location: arch/x86/include/asm/pgtable.h:142
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
In arch/x86/mm/pgtable.c (ffffffff810c75e5)
Location: arch/x86/include/asm/pgtable.h:143
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/vmscan.c (ffffffff8137fc50)
Location: arch/x86/include/asm/pgtable.h:143
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pmd_range
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/madvise.c (ffffffff813f51c6)
Location: arch/x86/include/asm/pgtable.h:143
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff81443ab2)
Location: arch/x86/include/asm/pgtable.h:143
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8152e4b5)
Location: arch/x86/include/asm/pgtable.h:143
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
In arch/x86/mm/pgtable.c (ffffffff810cad35)
Location: arch/x86/include/asm/pgtable.h:144
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/vmscan.c (ffffffff813b11d2)
Location: arch/x86/include/asm/pgtable.h:144
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pmd_range
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/madvise.c (ffffffff814283c8)
Location: arch/x86/include/asm/pgtable.h:144
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff81478fee)
Location: arch/x86/include/asm/pgtable.h:144
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff815667c8)
Location: arch/x86/include/asm/pgtable.h:144
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
In arch/x86/mm/pgtable.c (ffffffff810d3285)
Location: arch/x86/include/asm/pgtable.h:158
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/vmscan.c (ffffffff813da752)
Location: arch/x86/include/asm/pgtable.h:158
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pmd_range
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/madvise.c (ffffffff81461caf)
Location: arch/x86/include/asm/pgtable.h:158
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff814a85fe)
Location: arch/x86/include/asm/pgtable.h:158
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8159db13)
Location: arch/x86/include/asm/pgtable.h:158
Inline: True
Inline callers:
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
In arch/x86/mm/pgtable.c (ffffffff810869bf)
Location: arch/x86/include/asm/pgtable.h:167
Inline: True
```
```
In mm/madvise.c (ffffffff8127d975)
Location: arch/x86/include/asm/pgtable.h:167
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff812acd38)
Location: arch/x86/include/asm/pgtable.h:167
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8136906f)
Location: arch/x86/include/asm/pgtable.h:167
Inline: True
Inline callers:
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
In arch/x86/mm/pgtable.c (ffffffff8107564f)
Location: arch/x86/include/asm/pgtable.h:167
Inline: True
```
```
In mm/madvise.c (ffffffff8126f857)
Location: arch/x86/include/asm/pgtable.h:167
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff8129ddf8)
Location: arch/x86/include/asm/pgtable.h:167
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8135a31f)
Location: arch/x86/include/asm/pgtable.h:167
Inline: True
Inline callers:
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
In arch/x86/mm/pgtable.c (ffffffff8108696f)
Location: arch/x86/include/asm/pgtable.h:167
Inline: True
```
```
In mm/madvise.c (ffffffff8127b715)
Location: arch/x86/include/asm/pgtable.h:167
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff812aab48)
Location: arch/x86/include/asm/pgtable.h:167
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81366b3f)
Location: arch/x86/include/asm/pgtable.h:167
Inline: True
Inline callers:
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
In arch/x86/mm/pgtable.c (ffffffff81088a9f)
Location: arch/x86/include/asm/pgtable.h:167
Inline: True
```
```
In mm/madvise.c (ffffffff8128b5cf)
Location: arch/x86/include/asm/pgtable.h:167
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff812bae98)
Location: arch/x86/include/asm/pgtable.h:167
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8137a195)
Location: arch/x86/include/asm/pgtable.h:167
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
</details>
</li>
</ul>

## Differences
