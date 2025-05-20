# Function: <code>pud_write</code>

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
In mm/memory.c (ffffffff811f64f7)
Location: include/linux/hugetlb.h:242
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff812333cb)
Location: include/linux/hugetlb.h:242
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
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
In mm/memory.c (ffffffff8120e67d)
Location: arch/x86/include/asm/pgtable.h:1107
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff81250b59)
Location: arch/x86/include/asm/pgtable.h:1107
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
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
In mm/memory.c (ffffffff8122fe05)
Location: arch/x86/include/asm/pgtable.h:1158
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff8127514c)
Location: arch/x86/include/asm/pgtable.h:1158
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
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
In mm/memory.c (ffffffff81241af5)
Location: arch/x86/include/asm/pgtable.h:1183
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff8128a0d0)
Location: arch/x86/include/asm/pgtable.h:1183
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
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
In mm/memory.c (ffffffff81254461)
Location: arch/x86/include/asm/pgtable.h:1203
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff812a4cf2)
Location: arch/x86/include/asm/pgtable.h:1203
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/hmm.c (ffffffff812c4ec9)
Location: arch/x86/include/asm/pgtable.h:1203
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
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
In mm/memory.c (ffffffff812629c1)
Location: arch/x86/include/asm/pgtable.h:1203
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff812b61b2)
Location: arch/x86/include/asm/pgtable.h:1203
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/hmm.c (ffffffff812d6879)
Location: arch/x86/include/asm/pgtable.h:1203
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
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
In mm/memory.c (ffffffff81294907)
Location: arch/x86/include/asm/pgtable.h:1163
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff812eb2de)
Location: arch/x86/include/asm/pgtable.h:1163
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/hmm.c (0)
Location: arch/x86/include/asm/pgtable.h:1163
Inline: True
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130ca22)
Location: arch/x86/include/asm/pgtable.h:1163
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
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
In mm/memory.c (ffffffff8129f187)
Location: arch/x86/include/asm/pgtable.h:1159
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff812f643e)
Location: arch/x86/include/asm/pgtable.h:1159
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/hmm.c (0)
Location: arch/x86/include/asm/pgtable.h:1159
Inline: True
```
```
In mm/mapping_dirty_helpers.c (ffffffff81318962)
Location: arch/x86/include/asm/pgtable.h:1159
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
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
In mm/memory.c (ffffffff812a4123)
Location: arch/x86/include/asm/pgtable.h:1159
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff812fc7ef)
Location: arch/x86/include/asm/pgtable.h:1159
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/hmm.c (0)
Location: arch/x86/include/asm/pgtable.h:1159
Inline: True
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131eb52)
Location: arch/x86/include/asm/pgtable.h:1159
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
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
In mm/memory.c (ffffffff812e544f)
Location: arch/x86/include/asm/pgtable.h:1130
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff8134666f)
Location: arch/x86/include/asm/pgtable.h:1130
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/hmm.c (0)
Location: arch/x86/include/asm/pgtable.h:1130
Inline: True
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136bf32)
Location: arch/x86/include/asm/pgtable.h:1130
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
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
In mm/gup.c (ffffffff8133a771)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
```
```
In mm/memory.c (ffffffff8134774b)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff813bc7ff)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/hmm.c (0)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
```
```
In mm/mapping_dirty_helpers.c (ffffffff813ea15f)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
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
In mm/gup.c (ffffffff813b2257)
Location: arch/x86/include/asm/pgtable.h:1159
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
```
```
In mm/memory.c (ffffffff813bfb05)
Location: arch/x86/include/asm/pgtable.h:1159
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff8143eda2)
Location: arch/x86/include/asm/pgtable.h:1159
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/hmm.c (0)
Location: arch/x86/include/asm/pgtable.h:1159
Inline: True
```
```
In mm/mapping_dirty_helpers.c (ffffffff8147221c)
Location: arch/x86/include/asm/pgtable.h:1159
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
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
In mm/gup.c (ffffffff813e7002)
Location: arch/x86/include/asm/pgtable.h:1160
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
```
```
In mm/memory.c (ffffffff813f47cf)
Location: arch/x86/include/asm/pgtable.h:1160
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff8147455e)
Location: arch/x86/include/asm/pgtable.h:1160
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/hmm.c (0)
Location: arch/x86/include/asm/pgtable.h:1160
Inline: True
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a69ed)
Location: arch/x86/include/asm/pgtable.h:1160
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
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
In mm/gup.c (ffffffff81411c82)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
```
```
In mm/memory.c (ffffffff81420dd1)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff814a3b0a)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/hmm.c (0)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d78ed)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
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
Location: include/asm-generic/pgtable.h:899
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
Location: include/asm-generic/pgtable.h:899
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
In mm/memory.c (ffffffff8125b011)
Location: arch/x86/include/asm/pgtable.h:1203
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff812ae792)
Location: arch/x86/include/asm/pgtable.h:1203
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/hmm.c (ffffffff812cee59)
Location: arch/x86/include/asm/pgtable.h:1203
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
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
In mm/memory.c (ffffffff8124d434)
Location: arch/x86/include/asm/pgtable.h:1203
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff8129fcf4)
Location: arch/x86/include/asm/pgtable.h:1203
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/hmm.c (ffffffff812bfaee)
Location: arch/x86/include/asm/pgtable.h:1203
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
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
In mm/memory.c (ffffffff81258db1)
Location: arch/x86/include/asm/pgtable.h:1203
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff812ac5a2)
Location: arch/x86/include/asm/pgtable.h:1203
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/hmm.c (ffffffff812ccc69)
Location: arch/x86/include/asm/pgtable.h:1203
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
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
In mm/memory.c (ffffffff812687b1)
Location: arch/x86/include/asm/pgtable.h:1203
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff812bc922)
Location: arch/x86/include/asm/pgtable.h:1203
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/hmm.c (ffffffff812dd9f9)
Location: arch/x86/include/asm/pgtable.h:1203
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
</details>
</li>
</ul>

## Differences
