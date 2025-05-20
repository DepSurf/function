# Function: <code>mm_tlb_flush_nested</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f2759)
Location: include/linux/mm_types.h:546
Inline: True
Inline callers:
  - mm/memory.c:tlb_finish_mmu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81209809)
Location: include/linux/mm_types.h:607
Inline: True
Inline callers:
  - mm/memory.c:tlb_finish_mmu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122a679)
Location: include/linux/mm_types.h:593
Inline: True
Inline callers:
  - mm/memory.c:tlb_finish_mmu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8124d0d9)
Location: include/linux/mm_types.h:605
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8125f3b2)
Location: include/linux/mm_types.h:625
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8126dbc2)
Location: include/linux/mm_types.h:633
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
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
In mm/mmu_gather.c (ffffffff8129de14)
Location: include/linux/mm_types.h:647
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130c387)
Location: include/linux/mm_types.h:647
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
In mm/mmu_gather.c (ffffffff812a9194)
Location: include/linux/mm_types.h:671
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mapping_dirty_helpers.c (ffffffff813182c7)
Location: include/linux/mm_types.h:671
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
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
In mm/mmu_gather.c (ffffffff812ae604)
Location: include/linux/mm_types.h:681
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131e4b7)
Location: include/linux/mm_types.h:681
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
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
In mm/mmu_gather.c (ffffffff812efda4)
Location: include/linux/mm_types.h:688
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136b897)
Location: include/linux/mm_types.h:688
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
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
In mm/mmu_gather.c (ffffffff813532b2)
Location: include/linux/mm_inline.h:309
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mapping_dirty_helpers.c (ffffffff813e9a17)
Location: include/linux/mm_inline.h:309
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
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
In mm/mmu_gather.c (ffffffff813cd572)
Location: include/linux/mm_inline.h:526
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mapping_dirty_helpers.c (ffffffff81471a57)
Location: include/linux/mm_inline.h:526
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
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
In mm/mmu_gather.c (ffffffff81401ed2)
Location: include/linux/mm_inline.h:514
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a63a7)
Location: include/linux/mm_inline.h:514
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
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
In mm/mmu_gather.c (ffffffff8142e522)
Location: include/linux/mm_inline.h:501
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d72f7)
Location: include/linux/mm_inline.h:501
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffff800010304dd4)
Location: include/linux/mm_types.h:633
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
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
In mm/mmu_gather.c (c052301c)
Location: include/linux/mm_types.h:633
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
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
In arch/powerpc/mm/book3s64/radix_tlb.c (c00000000009c1e0)
Location: include/linux/mm_types.h:633
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
```
```
In mm/mmu_gather.c (c0000000003d1c54)
Location: include/linux/mm_types.h:633
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffe000210fa8)
Location: include/linux/mm_types.h:633
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81266212)
Location: include/linux/mm_types.h:633
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81258632)
Location: include/linux/mm_types.h:633
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81263fb2)
Location: include/linux/mm_types.h:633
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81273972)
Location: include/linux/mm_types.h:633
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
</details>
</li>
</ul>

## Differences
