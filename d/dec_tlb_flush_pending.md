# Function: <code>dec_tlb_flush_pending</code>

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
In mm/memory.c (ffffffff811f2776)
Location: include/linux/mm_types.h:568
Inline: True
Inline callers:
  - mm/memory.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff811ffd1b)
Location: include/linux/mm_types.h:568
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
In mm/memory.c (ffffffff81209823)
Location: include/linux/mm_types.h:581
Inline: True
Inline callers:
  - mm/memory.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff812184f3)
Location: include/linux/mm_types.h:581
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
In mm/memory.c (ffffffff8122a693)
Location: include/linux/mm_types.h:567
Inline: True
Inline callers:
  - mm/memory.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff81239e02)
Location: include/linux/mm_types.h:567
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
In mm/mmu_gather.c (ffffffff8124d0f3)
Location: include/linux/mm_types.h:579
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff8124da2f)
Location: include/linux/mm_types.h:579
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
In mm/mmu_gather.c (ffffffff8125f407)
Location: include/linux/mm_types.h:599
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff81260047)
Location: include/linux/mm_types.h:599
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
In mm/mmu_gather.c (ffffffff8126dc17)
Location: include/linux/mm_types.h:607
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff8126e937)
Location: include/linux/mm_types.h:607
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
In mm/mmu_gather.c (ffffffff8129dec9)
Location: include/linux/mm_types.h:621
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff8129f15b)
Location: include/linux/mm_types.h:621
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130c3d6)
Location: include/linux/mm_types.h:621
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
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
In mm/mmu_gather.c (ffffffff812a9249)
Location: include/linux/mm_types.h:645
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff812aa51b)
Location: include/linux/mm_types.h:645
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff81318316)
Location: include/linux/mm_types.h:645
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/proc/task_mmu.c (ffffffff813c8bdb)
Location: include/linux/mm_types.h:645
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
In mm/mmu_gather.c (ffffffff812ae6b9)
Location: include/linux/mm_types.h:655
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff812af95b)
Location: include/linux/mm_types.h:655
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131e506)
Location: include/linux/mm_types.h:655
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/proc/task_mmu.c (ffffffff813cfc1a)
Location: include/linux/mm_types.h:655
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
In mm/mmu_gather.c (ffffffff812efe59)
Location: include/linux/mm_types.h:662
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff812f11a3)
Location: include/linux/mm_types.h:662
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136b8e6)
Location: include/linux/mm_types.h:662
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/proc/task_mmu.c (ffffffff81420ff7)
Location: include/linux/mm_types.h:662
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
In mm/mmu_gather.c (ffffffff81353338)
Location: include/linux/mm_inline.h:283
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mapping_dirty_helpers.c (ffffffff813e9a6a)
Location: include/linux/mm_inline.h:283
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/proc/task_mmu.c (ffffffff81498e8d)
Location: include/linux/mm_inline.h:283
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
In mm/mmu_gather.c (ffffffff813cd5f8)
Location: include/linux/mm_inline.h:500
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mapping_dirty_helpers.c (ffffffff81471aaa)
Location: include/linux/mm_inline.h:500
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/proc/task_mmu.c (ffffffff8152d1fc)
Location: include/linux/mm_inline.h:500
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
In mm/mmu_gather.c (ffffffff81401f58)
Location: include/linux/mm_inline.h:488
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a63f9)
Location: include/linux/mm_inline.h:488
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/proc/task_mmu.c (ffffffff81564f2a)
Location: include/linux/mm_inline.h:488
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
In mm/mmu_gather.c (ffffffff8142e5a8)
Location: include/linux/mm_inline.h:475
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d7349)
Location: include/linux/mm_inline.h:475
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/proc/task_mmu.c (ffffffff8159b9e9)
Location: include/linux/mm_inline.h:475
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
In mm/mmu_gather.c (ffff800010304e2c)
Location: include/linux/mm_types.h:607
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffff8000103053b8)
Location: include/linux/mm_types.h:607
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
In mm/mmu_gather.c (c0523128)
Location: include/linux/mm_types.h:607
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (c05235f0)
Location: include/linux/mm_types.h:607
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
In mm/mmu_gather.c (c0000000003d1cc8)
Location: include/linux/mm_types.h:607
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (c0000000003d241c)
Location: include/linux/mm_types.h:607
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
In mm/mmu_gather.c (ffffffe000211026)
Location: include/linux/mm_types.h:607
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffe000211442)
Location: include/linux/mm_types.h:607
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
In mm/mmu_gather.c (ffffffff81266267)
Location: include/linux/mm_types.h:607
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff81266f87)
Location: include/linux/mm_types.h:607
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
In mm/mmu_gather.c (ffffffff81258687)
Location: include/linux/mm_types.h:607
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff812590a7)
Location: include/linux/mm_types.h:607
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
In mm/mmu_gather.c (ffffffff81264007)
Location: include/linux/mm_types.h:607
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff81264d27)
Location: include/linux/mm_types.h:607
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
In mm/mmu_gather.c (ffffffff812739c7)
Location: include/linux/mm_types.h:607
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff812746c1)
Location: include/linux/mm_types.h:607
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
</details>
</li>
</ul>

## Differences
