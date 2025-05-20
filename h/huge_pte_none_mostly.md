# Function: <code>huge_pte_none_mostly</code>

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
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int huge_pte_none_mostly(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8138e2ad)
Location: include/asm-generic/hugetlb.h:102
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:102
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:102
Inline: False
```
**Symbols:**

```
ffffffff813e3ec0-ffffffff813e3f4d: huge_pte_none_mostly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int huge_pte_none_mostly(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8140cea4)
Location: include/asm-generic/hugetlb.h:102
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:102
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:102
Inline: False
```
**Symbols:**

```
ffffffff8146b920-ffffffff8146b9ad: huge_pte_none_mostly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int huge_pte_none_mostly(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mincore.c (0)
Location: include/asm-generic/hugetlb.h:109
Inline: False
```
```
In mm/hugetlb.c (ffffffff8144026b)
Location: include/asm-generic/hugetlb.h:109
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:109
Inline: False
Direct callers:
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:109
Inline: False
```
**Symbols:**

```
ffffffff814a0790-ffffffff814a081d: huge_pte_none_mostly (STB_LOCAL)
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
In mm/mincore.c (0)
Location: include/asm-generic/hugetlb.h:109
Inline: False
```
```
In mm/hugetlb.c (ffffffff8147a062)
Location: include/asm-generic/hugetlb.h:109
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:109
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:109
Inline: False
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
