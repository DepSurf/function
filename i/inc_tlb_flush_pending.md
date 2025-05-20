# Function: <code>inc_tlb_flush_pending</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f2742)
Location: include/linux/mm_types.h:556
Inline: True
Inline callers:
  - mm/memory.c:tlb_gather_mmu
```
```
In mm/mprotect.c (ffffffff811ff60c)
Location: include/linux/mm_types.h:556
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
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
In mm/memory.c (ffffffff812097f2)
Location: include/linux/mm_types.h:540
Inline: True
Inline callers:
  - mm/memory.c:tlb_gather_mmu
```
```
In mm/mprotect.c (ffffffff81217bec)
Location: include/linux/mm_types.h:540
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
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
In mm/memory.c (ffffffff8122a662)
Location: include/linux/mm_types.h:526
Inline: True
Inline callers:
  - mm/memory.c:tlb_gather_mmu
```
```
In mm/mprotect.c (ffffffff81239a08)
Location: include/linux/mm_types.h:526
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection
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
In mm/mmu_gather.c (ffffffff8124d07f)
Location: include/linux/mm_types.h:538
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_gather_mmu
```
```
In mm/mprotect.c (ffffffff8124d31a)
Location: include/linux/mm_types.h:538
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
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
In mm/mmu_gather.c (ffffffff8125f347)
Location: include/linux/mm_types.h:558
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_gather_mmu
```
```
In mm/mprotect.c (ffffffff8125fb14)
Location: include/linux/mm_types.h:558
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
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
In mm/mmu_gather.c (ffffffff8126db57)
Location: include/linux/mm_types.h:566
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_gather_mmu
```
```
In mm/mprotect.c (ffffffff8126e3d4)
Location: include/linux/mm_types.h:566
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
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
In mm/mmu_gather.c (ffffffff8129dd97)
Location: include/linux/mm_types.h:580
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_gather_mmu
```
```
In mm/mprotect.c (ffffffff8129f049)
Location: include/linux/mm_types.h:580
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130c4eb)
Location: include/linux/mm_types.h:580
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
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
In mm/mmu_gather.c (ffffffff812a9117)
Location: include/linux/mm_types.h:604
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_gather_mmu
```
```
In mm/mprotect.c (ffffffff812aa409)
Location: include/linux/mm_types.h:604
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131842b)
Location: include/linux/mm_types.h:604
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
```
```
In fs/proc/task_mmu.c (ffffffff813c8b48)
Location: include/linux/mm_types.h:604
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In mm/mmu_gather.c (ffffffff812ae5e6)
Location: include/linux/mm_types.h:614
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_gather_mmu_fullmm
  - mm/mmu_gather.c:tlb_gather_mmu
```
```
In mm/mprotect.c (ffffffff812af849)
Location: include/linux/mm_types.h:614
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131e61b)
Location: include/linux/mm_types.h:614
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
```
```
In fs/proc/task_mmu.c (ffffffff813cfb87)
Location: include/linux/mm_types.h:614
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In mm/mmu_gather.c (ffffffff812efd86)
Location: include/linux/mm_types.h:621
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_gather_mmu_fullmm
  - mm/mmu_gather.c:tlb_gather_mmu
```
```
In mm/mprotect.c (ffffffff812f1082)
Location: include/linux/mm_types.h:621
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136b9fb)
Location: include/linux/mm_types.h:621
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
```
```
In fs/proc/task_mmu.c (ffffffff81420f64)
Location: include/linux/mm_types.h:621
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In mm/mmu_gather.c (ffffffff81353286)
Location: include/linux/mm_inline.h:242
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_gather_mmu_fullmm
  - mm/mmu_gather.c:tlb_gather_mmu
```
```
In mm/mapping_dirty_helpers.c (ffffffff813e9b83)
Location: include/linux/mm_inline.h:242
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
```
```
In fs/proc/task_mmu.c (ffffffff81498dfa)
Location: include/linux/mm_inline.h:242
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In mm/mmu_gather.c (ffffffff813cd53d)
Location: include/linux/mm_inline.h:459
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_gather_mmu_fullmm
  - mm/mmu_gather.c:tlb_gather_mmu
```
```
In mm/mapping_dirty_helpers.c (ffffffff81471bd3)
Location: include/linux/mm_inline.h:459
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
```
```
In fs/proc/task_mmu.c (ffffffff8152d153)
Location: include/linux/mm_inline.h:459
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In mm/mmu_gather.c (ffffffff81401e9d)
Location: include/linux/mm_inline.h:447
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_gather_mmu_fullmm
  - mm/mmu_gather.c:tlb_gather_mmu
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a651a)
Location: include/linux/mm_inline.h:447
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
```
```
In fs/proc/task_mmu.c (ffffffff81564e8c)
Location: include/linux/mm_inline.h:447
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In mm/mmu_gather.c (ffffffff8142e4ed)
Location: include/linux/mm_inline.h:434
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_gather_mmu_fullmm
  - mm/mmu_gather.c:tlb_gather_mmu
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d746a)
Location: include/linux/mm_inline.h:434
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
```
```
In fs/proc/task_mmu.c (ffffffff8159b94b)
Location: include/linux/mm_inline.h:434
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In mm/mmu_gather.c (ffff800010304d54)
Location: include/linux/mm_types.h:566
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_gather_mmu
```
```
In mm/mprotect.c (ffff800010304f14)
Location: include/linux/mm_types.h:566
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
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
In mm/mmu_gather.c (c0522fcc)
Location: include/linux/mm_types.h:566
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_gather_mmu
```
```
In mm/mprotect.c (c05231fc)
Location: include/linux/mm_types.h:566
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
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
In mm/mmu_gather.c (c0000000003d1bb4)
Location: include/linux/mm_types.h:566
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_gather_mmu
```
```
In mm/mprotect.c (c0000000003d1e24)
Location: include/linux/mm_types.h:566
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
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
In mm/mmu_gather.c (ffffffe000210f68)
Location: include/linux/mm_types.h:566
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_gather_mmu
```
```
In mm/mprotect.c (ffffffe0002110d2)
Location: include/linux/mm_types.h:566
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
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
In mm/mmu_gather.c (ffffffff812661a7)
Location: include/linux/mm_types.h:566
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_gather_mmu
```
```
In mm/mprotect.c (ffffffff81266a24)
Location: include/linux/mm_types.h:566
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
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
In mm/mmu_gather.c (ffffffff812585c7)
Location: include/linux/mm_types.h:566
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_gather_mmu
```
```
In mm/mprotect.c (ffffffff812588e4)
Location: include/linux/mm_types.h:566
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
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
In mm/mmu_gather.c (ffffffff81263f47)
Location: include/linux/mm_types.h:566
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_gather_mmu
```
```
In mm/mprotect.c (ffffffff812647c4)
Location: include/linux/mm_types.h:566
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
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
In mm/mmu_gather.c (ffffffff81273907)
Location: include/linux/mm_types.h:566
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_gather_mmu
```
```
In mm/mprotect.c (ffffffff81274184)
Location: include/linux/mm_types.h:566
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
</details>
</li>
</ul>

## Differences
