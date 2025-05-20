# Function: <code>is_pte_marker</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81343baa)
Location: include/linux/swapops.h:313
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_marker
```
```
In mm/mincore.c (ffffffff813494b2)
Location: include/linux/swapops.h:313
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/hugetlb.c (ffffffff8138e36e)
Location: include/linux/swapops.h:313
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/memcontrol.c (ffffffff813ce83c)
Location: include/linux/swapops.h:313
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff813e4454)
Location: include/linux/swapops.h:313
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff813e843b)
Location: include/linux/swapops.h:313
Inline: True
```
```
In fs/userfaultfd.c (ffffffff8145da39)
Location: include/linux/swapops.h:313
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
In mm/mincore.c (ffffffff813c18a1)
Location: include/linux/swapops.h:423
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/hugetlb.c (ffffffff814124dd)
Location: include/linux/swapops.h:423
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/memcontrol.c (ffffffff81453426)
Location: include/linux/swapops.h:423
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff8146bf2c)
Location: include/linux/swapops.h:423
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff8147036a)
Location: include/linux/swapops.h:423
Inline: True
```
```
In fs/userfaultfd.c (ffffffff814ed46a)
Location: include/linux/swapops.h:423
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
In mm/mincore.c (ffffffff813f673a)
Location: include/linux/swapops.h:414
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/hugetlb.c (ffffffff81445ab3)
Location: include/linux/swapops.h:414
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/memcontrol.c (ffffffff8148915c)
Location: include/linux/swapops.h:414
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff814a0c87)
Location: include/linux/swapops.h:414
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff814a4b41)
Location: include/linux/swapops.h:414
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/userfaultfd.c (ffffffff81524160)
Location: include/linux/swapops.h:414
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
In mm/mincore.c (ffffffff814223ea)
Location: include/linux/swapops.h:419
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/hugetlb.c (ffffffff8147f469)
Location: include/linux/swapops.h:419
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/memcontrol.c (ffffffff814b9015)
Location: include/linux/swapops.h:419
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff814d2417)
Location: include/linux/swapops.h:419
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff814d5b6b)
Location: include/linux/swapops.h:419
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/userfaultfd.c (ffffffff815586ab)
Location: include/linux/swapops.h:419
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8159ce7c)
Location: include/linux/swapops.h:419
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
