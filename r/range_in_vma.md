# Function: <code>range_in_vma</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8126b614)
Location: include/linux/mm.h:2561
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:adjust_range_if_pmd_sharing_possible
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
In mm/hugetlb.c (ffffffff81286904)
Location: include/linux/mm.h:2555
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:adjust_range_if_pmd_sharing_possible
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
In mm/hugetlb.c (ffffffff81296504)
Location: include/linux/mm.h:2529
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:adjust_range_if_pmd_sharing_possible
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c9aa6)
Location: include/linux/mm.h:2739
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d56e6)
Location: include/linux/mm.h:2739
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
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
In mm/hugetlb.c (ffffffff812dc8e1)
Location: include/linux/mm.h:2735
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/huge_memory.c (ffffffff812ff394)
Location: include/linux/mm.h:2735
Inline: True
Inline callers:
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
```
```
In mm/khugepaged.c (ffffffff813059fa)
Location: include/linux/mm.h:2735
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
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
In mm/hugetlb.c (ffffffff81323aac)
Location: include/linux/mm.h:2793
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/huge_memory.c (ffffffff81348fa4)
Location: include/linux/mm.h:2793
Inline: True
Inline callers:
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
```
```
In mm/khugepaged.c (ffffffff8134f86a)
Location: include/linux/mm.h:2793
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
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
In kernel/bpf/stackmap.c (ffffffff812c0abb)
Location: include/linux/mm.h:2868
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In mm/memory.c (ffffffff81342325)
Location: include/linux/mm.h:2868
Inline: True
```
```
In mm/hugetlb.c (ffffffff81391699)
Location: include/linux/mm.h:2868
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/huge_memory.c (ffffffff813bf461)
Location: include/linux/mm.h:2868
Inline: True
Inline callers:
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
```
```
In mm/khugepaged.c (ffffffff813c7b0a)
Location: include/linux/mm.h:2868
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
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
In kernel/bpf/stackmap.c (ffffffff81324356)
Location: include/linux/mm.h:3019
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In mm/memory.c (ffffffff813ba455)
Location: include/linux/mm.h:3019
Inline: True
```
```
In mm/hugetlb.c (ffffffff8140e203)
Location: include/linux/mm.h:3019
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:want_pmd_share
```
```
In mm/huge_memory.c (ffffffff81441989)
Location: include/linux/mm.h:3019
Inline: True
Inline callers:
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
```
```
In mm/khugepaged.c (ffffffff8144bb13)
Location: include/linux/mm.h:3019
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
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
In kernel/bpf/stackmap.c (ffffffff813545ad)
Location: include/linux/mm.h:3325
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In mm/memory.c (ffffffff813eee15)
Location: include/linux/mm.h:3325
Inline: True
```
```
In mm/hugetlb.c (ffffffff81441622)
Location: include/linux/mm.h:3325
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:want_pmd_share
```
```
In mm/huge_memory.c (ffffffff81477359)
Location: include/linux/mm.h:3325
Inline: True
Inline callers:
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
```
```
In mm/khugepaged.c (ffffffff814813c2)
Location: include/linux/mm.h:3325
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/userfaultfd.c (ffffffff814a1d97)
Location: include/linux/mm.h:3325
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_copy
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
In kernel/bpf/stackmap.c (ffffffff8137cf1d)
Location: include/linux/mm.h:3513
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In mm/memory.c (ffffffff8141a8e5)
Location: include/linux/mm.h:3513
Inline: True
```
```
In mm/hugetlb.c (ffffffff8147b902)
Location: include/linux/mm.h:3513
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:want_pmd_share
```
```
In mm/huge_memory.c (ffffffff814a6ad9)
Location: include/linux/mm.h:3513
Inline: True
Inline callers:
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
```
```
In mm/khugepaged.c (ffffffff814b0426)
Location: include/linux/mm.h:3513
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/userfaultfd.c (ffffffff814d1e82)
Location: include/linux/mm.h:3513
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_copy
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
In mm/hugetlb.c (ffff8000103335ac)
Location: include/linux/mm.h:2529
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:adjust_range_if_pmd_sharing_possible
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
In mm/hugetlb.c (ffffffe000230f34)
Location: include/linux/mm.h:2529
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:adjust_range_if_pmd_sharing_possible
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
In mm/hugetlb.c (ffffffff8128eae4)
Location: include/linux/mm.h:2529
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:adjust_range_if_pmd_sharing_possible
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
In mm/hugetlb.c (ffffffff81280884)
Location: include/linux/mm.h:2529
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:adjust_range_if_pmd_sharing_possible
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
In mm/hugetlb.c (ffffffff8128c8f4)
Location: include/linux/mm.h:2529
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:adjust_range_if_pmd_sharing_possible
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
In mm/hugetlb.c (ffffffff8129c6c4)
Location: include/linux/mm.h:2529
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:adjust_range_if_pmd_sharing_possible
```
</details>
</li>
</ul>

## Differences
