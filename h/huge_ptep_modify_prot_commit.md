# Function: <code>huge_ptep_modify_prot_commit</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812866f0)
Location: include/linux/hugetlb.h:583
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
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
In mm/hugetlb.c (ffffffff812962d5)
Location: include/linux/hugetlb.h:583
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
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
In mm/hugetlb.c (ffffffff812c985e)
Location: include/linux/hugetlb.h:746
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
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
In mm/hugetlb.c (ffffffff812d55c8)
Location: include/linux/hugetlb.h:765
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812dc243)
Location: include/linux/hugetlb.h:867
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff813233d9)
Location: include/linux/hugetlb.h:895
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81390ce7)
Location: include/linux/hugetlb.h:925
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff814125d2)
Location: include/linux/hugetlb.h:969
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
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
In mm/hugetlb.c (ffffffff81445ba5)
Location: include/linux/hugetlb.h:997
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
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
In mm/hugetlb.c (ffffffff8147f5c2)
Location: include/linux/hugetlb.h:1019
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In fs/proc/task_mmu.c (ffffffff8159cf45)
Location: include/linux/hugetlb.h:1019
Inline: True
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
In mm/hugetlb.c (ffff8000103359ac)
Location: include/linux/hugetlb.h:583
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void huge_ptep_modify_prot_commit(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep, pte_t old_pte, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/book3s64/hash_hugetlbpage.c (c00000000009e8b0)
Location: arch/powerpc/mm/book3s64/hash_hugetlbpage.c:147
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
**Symbols:**

```
c00000000009e8b0-c00000000009e910: huge_ptep_modify_prot_commit (STB_GLOBAL)
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
In mm/hugetlb.c (ffffffe000230dec)
Location: include/linux/hugetlb.h:583
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
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
In mm/hugetlb.c (ffffffff8128e8b5)
Location: include/linux/hugetlb.h:583
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
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
In mm/hugetlb.c (ffffffff81280669)
Location: include/linux/hugetlb.h:583
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
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
In mm/hugetlb.c (ffffffff8128c6c5)
Location: include/linux/hugetlb.h:583
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
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
In mm/hugetlb.c (ffffffff8129c4ad)
Location: include/linux/hugetlb.h:583
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
