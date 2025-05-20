# Function: <code>pte_clear_uffd_wp</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:329
Inline: True
```
```
In mm/mprotect.c (ffffffff8129e8c6)
Location: arch/x86/include/asm/pgtable.h:329
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:328
Inline: True
```
```
In mm/mprotect.c (ffffffff812a9c7c)
Location: arch/x86/include/asm/pgtable.h:328
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:328
Inline: True
```
```
In mm/mprotect.c (ffffffff812af107)
Location: arch/x86/include/asm/pgtable.h:328
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:299
Inline: True
```
```
In mm/mprotect.c (ffffffff812f0916)
Location: arch/x86/include/asm/pgtable.h:299
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:302
Inline: True
```
```
In mm/mprotect.c (ffffffff81353f71)
Location: arch/x86/include/asm/pgtable.h:302
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff813921b3)
Location: arch/x86/include/asm/pgtable.h:302
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:319
Inline: True
```
```
In mm/mprotect.c (ffffffff813ce41b)
Location: arch/x86/include/asm/pgtable.h:319
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff8140f18f)
Location: arch/x86/include/asm/pgtable.h:319
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:325
Inline: True
```
```
In mm/mprotect.c (ffffffff81402cc6)
Location: arch/x86/include/asm/pgtable.h:325
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff81442479)
Location: arch/x86/include/asm/pgtable.h:325
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In mm/memory.c (ffffffff81419c0d)
Location: arch/x86/include/asm/pgtable.h:415
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
```
```
In mm/mprotect.c (ffffffff8142f31e)
Location: arch/x86/include/asm/pgtable.h:415
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff8147ef64)
Location: arch/x86/include/asm/pgtable.h:415
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
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
