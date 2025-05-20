# Function: <code>huge_ptep_modify_prot_start</code>

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
In mm/hugetlb.c (ffffffff81286666)
Location: include/linux/hugetlb.h:574
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
In mm/hugetlb.c (ffffffff8129624b)
Location: include/linux/hugetlb.h:574
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
In mm/hugetlb.c (ffffffff812c97ce)
Location: include/linux/hugetlb.h:737
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
In mm/hugetlb.c (ffffffff812d5539)
Location: include/linux/hugetlb.h:756
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
In mm/hugetlb.c (ffffffff812dc1b3)
Location: include/linux/hugetlb.h:858
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
In mm/hugetlb.c (ffffffff81323349)
Location: include/linux/hugetlb.h:886
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
In mm/hugetlb.c (ffffffff81390c35)
Location: include/linux/hugetlb.h:916
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
In mm/hugetlb.c (ffffffff8141253c)
Location: include/linux/hugetlb.h:960
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
In mm/hugetlb.c (ffffffff81445b12)
Location: include/linux/hugetlb.h:988
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8147f4d5)
Location: include/linux/hugetlb.h:1010
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
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
In mm/hugetlb.c (ffff800010335948)
Location: include/linux/hugetlb.h:574
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
pte_t huge_ptep_modify_prot_start(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/book3s64/hash_hugetlbpage.c (c00000000009e770)
Location: arch/powerpc/mm/book3s64/hash_hugetlbpage.c:132
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
**Symbols:**

```
c00000000009e770-c00000000009e8a8: huge_ptep_modify_prot_start (STB_GLOBAL)
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
In mm/hugetlb.c (ffffffe000230dde)
Location: include/linux/hugetlb.h:574
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
In mm/hugetlb.c (ffffffff8128e82b)
Location: include/linux/hugetlb.h:574
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
In mm/hugetlb.c (ffffffff812805ec)
Location: include/linux/hugetlb.h:574
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
In mm/hugetlb.c (ffffffff8128c63b)
Location: include/linux/hugetlb.h:574
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
In mm/hugetlb.c (ffffffff8129c423)
Location: include/linux/hugetlb.h:574
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
