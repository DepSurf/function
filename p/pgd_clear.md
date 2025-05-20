# Function: <code>pgd_clear</code>

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
In arch/x86/mm/init_64.c (ffffffff810695dc)
Location: arch/x86/include/asm/paravirt.h:605
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c985)
Location: arch/x86/include/asm/paravirt.h:605
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pgd_range
```
```
In mm/memory.c (ffffffff811bd01b)
Location: arch/x86/include/asm/paravirt.h:605
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff811d0385)
Location: arch/x86/include/asm/paravirt.h:605
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
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
In arch/x86/mm/init_64.c (ffffffff81069375)
Location: arch/x86/include/asm/paravirt.h:578
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:sync_global_pgds
```
```
In mm/memory.c (ffffffff811d7dfa)
Location: arch/x86/include/asm/paravirt.h:578
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff811ed535)
Location: arch/x86/include/asm/paravirt.h:578
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
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
In mm/memory.c (ffffffff811e7ad1)
Location: arch/x86/include/asm/paravirt.h:569
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff811f7925)
Location: arch/x86/include/asm/paravirt.h:569
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/pgtable-generic.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/pgtable-generic.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable-nop4d.h:25
Inline: True
```
```
In mm/pgtable-generic.c (0)
Location: include/asm-generic/pgtable-nop4d.h:25
Inline: True
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
In arch/x86/mm/pgtable.c (0)
Location: include/asm-generic/pgtable-nop4d.h:25
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable-nop4d.h:25
Inline: True
```
```
In mm/pgtable-generic.c (0)
Location: include/asm-generic/pgtable-nop4d.h:25
Inline: True
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
In arch/x86/mm/pgtable.c (0)
Location: include/asm-generic/pgtable-nop4d.h:25
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable-nop4d.h:25
Inline: True
```
```
In mm/pgtable-generic.c (0)
Location: include/asm-generic/pgtable-nop4d.h:25
Inline: True
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
In arch/x86/mm/pgtable.c (0)
Location: include/asm-generic/pgtable-nop4d.h:25
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable-nop4d.h:25
Inline: True
```
```
In mm/pgtable-generic.c (0)
Location: include/asm-generic/pgtable-nop4d.h:25
Inline: True
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In virt/kvm/arm/mmu.c (ffff8000100c96dc)
Location: arch/arm64/include/asm/pgtable.h:605
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
```
```
In mm/memory.c (ffff8000102f55ec)
Location: arch/arm64/include/asm/pgtable.h:605
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffff800010307ee8)
Location: arch/arm64/include/asm/pgtable.h:605
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
  - mm/pgtable-generic.c:p4d_clear_bad
  - mm/pgtable-generic.c:pgd_clear_bad
  - mm/pgtable-generic.c:pgd_clear_bad
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
In arch/arm/mm/pgd.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:30
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:30
Inline: True
```
```
In mm/pgtable-generic.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:30
Inline: True
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
In arch/powerpc/mm/hugetlbpage.c (c0000000000a607c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:954
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range
```
```
In mm/memory.c (c0000000003bcb68)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:954
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (c0000000003d7018)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:954
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
  - mm/pgtable-generic.c:pgd_clear_bad
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
Location: include/asm-generic/pgtable-nop4d.h:25
Inline: True
```
```
In mm/pgtable-generic.c (0)
Location: include/asm-generic/pgtable-nop4d.h:25
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
In arch/x86/mm/pgtable.c (0)
Location: include/asm-generic/pgtable-nop4d.h:25
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable-nop4d.h:25
Inline: True
```
```
In mm/pgtable-generic.c (0)
Location: include/asm-generic/pgtable-nop4d.h:25
Inline: True
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
In arch/x86/mm/pgtable.c (0)
Location: include/asm-generic/pgtable-nop4d.h:25
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable-nop4d.h:25
Inline: True
```
```
In mm/pgtable-generic.c (0)
Location: include/asm-generic/pgtable-nop4d.h:25
Inline: True
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
In arch/x86/mm/pgtable.c (0)
Location: include/asm-generic/pgtable-nop4d.h:25
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable-nop4d.h:25
Inline: True
```
```
In mm/pgtable-generic.c (0)
Location: include/asm-generic/pgtable-nop4d.h:25
Inline: True
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
In arch/x86/mm/pgtable.c (0)
Location: include/asm-generic/pgtable-nop4d.h:25
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable-nop4d.h:25
Inline: True
```
```
In mm/pgtable-generic.c (0)
Location: include/asm-generic/pgtable-nop4d.h:25
Inline: True
```
</details>
</li>
</ul>

## Differences
