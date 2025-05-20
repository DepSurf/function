# Function: <code>ptep_set_wrprotect</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811c13ae)
Location: arch/x86/include/asm/pgtable.h:794
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/hugetlb.c (ffffffff811deb4f)
Location: arch/x86/include/asm/pgtable.h:794
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811dce41)
Location: arch/x86/include/asm/pgtable.h:849
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/hugetlb.c (ffffffff811fcfbe)
Location: arch/x86/include/asm/pgtable.h:849
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811ec939)
Location: arch/x86/include/asm/pgtable.h:849
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/hugetlb.c (ffffffff8120da98)
Location: arch/x86/include/asm/pgtable.h:849
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f77c7)
Location: arch/x86/include/asm/pgtable.h:1043
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/hugetlb.c (ffffffff812198c5)
Location: arch/x86/include/asm/pgtable.h:1043
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In mm/memory.c (ffffffff8120a50a)
Location: arch/x86/include/asm/pgtable.h:1050
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/hugetlb.c (ffffffff812347cb)
Location: arch/x86/include/asm/pgtable.h:1050
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In mm/memory.c (ffffffff8122b36f)
Location: arch/x86/include/asm/pgtable.h:1101
Inline: True
```
```
In mm/hugetlb.c (ffffffff812576c3)
Location: arch/x86/include/asm/pgtable.h:1101
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In mm/memory.c (ffffffff8123e7e3)
Location: arch/x86/include/asm/pgtable.h:1126
Inline: True
```
```
In mm/hugetlb.c (ffffffff8126bf02)
Location: arch/x86/include/asm/pgtable.h:1126
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In mm/memory.c (ffffffff8125063a)
Location: arch/x86/include/asm/pgtable.h:1146
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128722b)
Location: arch/x86/include/asm/pgtable.h:1146
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In mm/memory.c (ffffffff8125ebea)
Location: arch/x86/include/asm/pgtable.h:1146
Inline: True
```
```
In mm/hugetlb.c (ffffffff81296e32)
Location: arch/x86/include/asm/pgtable.h:1146
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In mm/memory.c (ffffffff8128ece0)
Location: arch/x86/include/asm/pgtable.h:1106
Inline: True
Inline callers:
  - mm/memory.c:copy_one_pte
```
```
In mm/hugetlb.c (ffffffff812ca526)
Location: arch/x86/include/asm/pgtable.h:1106
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In mm/memory.c (ffffffff81299ade)
Location: arch/x86/include/asm/pgtable.h:1102
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/hugetlb.c (ffffffff812d615b)
Location: arch/x86/include/asm/pgtable.h:1102
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In mm/memory.c (ffffffff8129ed63)
Location: arch/x86/include/asm/pgtable.h:1102
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/hugetlb.c (ffffffff812dd03d)
Location: arch/x86/include/asm/pgtable.h:1102
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In mm/memory.c (ffffffff812e0054)
Location: arch/x86/include/asm/pgtable.h:1073
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/hugetlb.c (ffffffff81324224)
Location: arch/x86/include/asm/pgtable.h:1073
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In mm/memory.c (ffffffff813402f9)
Location: arch/x86/include/asm/pgtable.h:1076
Inline: True
Inline callers:
  - mm/memory.c:copy_present_pte
```
```
In mm/hugetlb.c (ffffffff81392411)
Location: arch/x86/include/asm/pgtable.h:1076
Inline: True
Inline callers:
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
In mm/memory.c (ffffffff813b8289)
Location: arch/x86/include/asm/pgtable.h:1094
Inline: True
Inline callers:
  - mm/memory.c:copy_present_pte
```
```
In mm/hugetlb.c (ffffffff8140f3bf)
Location: arch/x86/include/asm/pgtable.h:1094
Inline: True
Inline callers:
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
In mm/memory.c (ffffffff813ecff6)
Location: arch/x86/include/asm/pgtable.h:1095
Inline: True
Inline callers:
  - mm/memory.c:copy_present_pte
```
```
In mm/hugetlb.c (ffffffff8144276d)
Location: arch/x86/include/asm/pgtable.h:1095
Inline: True
Inline callers:
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
In mm/memory.c (ffffffff814185d5)
Location: arch/x86/include/asm/pgtable.h:1310
Inline: True
Inline callers:
  - mm/memory.c:copy_present_pte
```
```
In mm/hugetlb.c (ffffffff8147c965)
Location: arch/x86/include/asm/pgtable.h:1310
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In arch/arm64/mm/hugetlbpage.c (ffff8000100b16b8)
Location: arch/arm64/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - arch/arm64/mm/hugetlbpage.c:huge_ptep_set_wrprotect
```
```
In mm/memory.c (ffff8000102f6638)
Location: arch/arm64/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/huge_memory.c (ffff800010356ed8)
Location: arch/arm64/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
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
In mm/memory.c (c0518768)
Location: include/asm-generic/pgtable.h:222
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003be130)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:427
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
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
In mm/memory.c (ffffffe00020a000)
Location: arch/riscv/include/asm/pgtable.h:380
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/hugetlb.c (ffffffe00023133e)
Location: arch/riscv/include/asm/pgtable.h:380
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In mm/memory.c (ffffffff8125723a)
Location: arch/x86/include/asm/pgtable.h:1146
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128f412)
Location: arch/x86/include/asm/pgtable.h:1146
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In mm/memory.c (ffffffff81249b11)
Location: arch/x86/include/asm/pgtable.h:1146
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/hugetlb.c (ffffffff81281115)
Location: arch/x86/include/asm/pgtable.h:1146
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In mm/memory.c (ffffffff81254fda)
Location: arch/x86/include/asm/pgtable.h:1146
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128d222)
Location: arch/x86/include/asm/pgtable.h:1146
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In mm/memory.c (ffffffff81264a96)
Location: arch/x86/include/asm/pgtable.h:1146
Inline: True
```
```
In mm/hugetlb.c (ffffffff8129cfe7)
Location: arch/x86/include/asm/pgtable.h:1146
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
</details>
</li>
</ul>

## Differences
