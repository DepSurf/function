# Function: <code>pte_modify</code>

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
In mm/memory.c (ffffffff811bf632)
Location: arch/x86/include/asm/pgtable.h:366
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/mprotect.c (ffffffff811c84df)
Location: arch/x86/include/asm/pgtable.h:366
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/hugetlb.c (ffffffff811de056)
Location: arch/x86/include/asm/pgtable.h:366
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
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
In mm/memory.c (ffffffff811db319)
Location: arch/x86/include/asm/pgtable.h:395
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/mprotect.c (ffffffff811e474e)
Location: arch/x86/include/asm/pgtable.h:395
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/hugetlb.c (ffffffff811fc42b)
Location: arch/x86/include/asm/pgtable.h:395
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
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
In mm/memory.c (ffffffff811eae7b)
Location: arch/x86/include/asm/pgtable.h:395
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/mprotect.c (ffffffff811f476e)
Location: arch/x86/include/asm/pgtable.h:395
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/hugetlb.c (ffffffff8120cf1b)
Location: arch/x86/include/asm/pgtable.h:395
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
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
In mm/memory.c (ffffffff811f5f94)
Location: arch/x86/include/asm/pgtable.h:532
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mprotect.c (ffffffff811ff9a4)
Location: arch/x86/include/asm/pgtable.h:532
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/hugetlb.c (ffffffff81218ee6)
Location: arch/x86/include/asm/pgtable.h:532
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
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
In mm/memory.c (ffffffff8120dbe8)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
```
```
In mm/mprotect.c (ffffffff812180cc)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/hugetlb.c (ffffffff81233e79)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
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
In mm/memory.c (ffffffff8122e64b)
Location: arch/x86/include/asm/pgtable.h:584
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
```
```
In mm/mprotect.c (ffffffff81239286)
Location: arch/x86/include/asm/pgtable.h:584
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff81256de7)
Location: arch/x86/include/asm/pgtable.h:584
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
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
In mm/memory.c (ffffffff81242551)
Location: arch/x86/include/asm/pgtable.h:586
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mprotect.c (ffffffff8124d805)
Location: arch/x86/include/asm/pgtable.h:586
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/hugetlb.c (ffffffff8126b39e)
Location: arch/x86/include/asm/pgtable.h:586
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
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
In mm/memory.c (ffffffff8125130b)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff8125f80a)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff8128666b)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
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
In mm/memory.c (ffffffff8125f8bb)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff8126e01a)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff81296250)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
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
In mm/memory.c (ffffffff8128fd6b)
Location: arch/x86/include/asm/pgtable.h:636
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff8129e621)
Location: arch/x86/include/asm/pgtable.h:636
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff812c97d3)
Location: arch/x86/include/asm/pgtable.h:636
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
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
In mm/memory.c (ffffffff8129a7eb)
Location: arch/x86/include/asm/pgtable.h:635
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff812a99e1)
Location: arch/x86/include/asm/pgtable.h:635
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff812d553e)
Location: arch/x86/include/asm/pgtable.h:635
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
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
In mm/memory.c (ffffffff8129fc07)
Location: arch/x86/include/asm/pgtable.h:635
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff812aee6c)
Location: arch/x86/include/asm/pgtable.h:635
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff812dc1b8)
Location: arch/x86/include/asm/pgtable.h:635
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
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
In mm/memory.c (ffffffff812e31fd)
Location: arch/x86/include/asm/pgtable.h:606
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff812f065c)
Location: arch/x86/include/asm/pgtable.h:606
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff8132334e)
Location: arch/x86/include/asm/pgtable.h:606
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
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
In mm/memory.c (ffffffff81344584)
Location: arch/x86/include/asm/pgtable.h:609
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff81353c72)
Location: arch/x86/include/asm/pgtable.h:609
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff81390c44)
Location: arch/x86/include/asm/pgtable.h:609
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
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
In mm/memory.c (ffffffff813bc6bb)
Location: arch/x86/include/asm/pgtable.h:626
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff813ce158)
Location: arch/x86/include/asm/pgtable.h:626
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff8141254b)
Location: arch/x86/include/asm/pgtable.h:626
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
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
In mm/memory.c (ffffffff813f10a8)
Location: arch/x86/include/asm/pgtable.h:627
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff81402a0c)
Location: arch/x86/include/asm/pgtable.h:627
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff81445b21)
Location: arch/x86/include/asm/pgtable.h:627
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
In mm/memory.c (ffffffff8141bd9c)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff8142f012)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff8147f4e5)
Location: arch/x86/include/asm/pgtable.h:796
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102fa058)
Location: arch/arm64/include/asm/pgtable.h:658
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mprotect.c (ffff800010305260)
Location: arch/arm64/include/asm/pgtable.h:658
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/hugetlb.c (ffff800010335958)
Location: arch/arm64/include/asm/pgtable.h:658
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/migrate.c (ffff800010353380)
Location: arch/arm64/include/asm/pgtable.h:658
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffff8000103581dc)
Location: arch/arm64/include/asm/pgtable.h:658
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/memory.c (0)
Location: arch/arm/include/asm/pgtable.h:321
Inline: True
```
```
In mm/mprotect.c (c0523390)
Location: arch/arm/include/asm/pgtable.h:321
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
In mm/memory.c (c0000000003bf41c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:711
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (c0000000003d2210)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:711
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/hugetlb.c (c00000000040fd10)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:711
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
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
In mm/memory.c (0)
Location: arch/riscv/include/asm/pgtable.h:292
Inline: True
```
```
In mm/mprotect.c (ffffffe000211208)
Location: arch/riscv/include/asm/pgtable.h:292
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/hugetlb.c (ffffffe000230de4)
Location: arch/riscv/include/asm/pgtable.h:292
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81257f0b)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff8126666a)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff8128e830)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
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
In mm/memory.c (ffffffff8124da20)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mprotect.c (ffffffff81258d45)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/hugetlb.c (ffffffff812805f1)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
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
In mm/memory.c (ffffffff81255cab)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff8126440a)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff8128c640)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
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
In mm/memory.c (ffffffff8126573b)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff81273dca)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff8129c428)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
</details>
</li>
</ul>

## Differences
