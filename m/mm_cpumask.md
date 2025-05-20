# Function: <code>mm_cpumask</code>

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
In arch/x86/events/core.c (ffffffff81005786)
Location: include/linux/mm_types.h:527
Inline: True
```
```
In arch/x86/xen/mmu.c (0)
Location: include/linux/mm_types.h:527
Inline: True
```
```
In arch/x86/kernel/ldt.c (ffffffff81032dbc)
Location: include/linux/mm_types.h:527
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/mm/tlb.c (ffffffff81072848)
Location: include/linux/mm_types.h:527
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_current_task
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - arch/x86/mm/tlb.c:flush_tlb_page
```
```
In kernel/cpu.c (0)
Location: include/linux/mm_types.h:527
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/mm_types.h:527
Inline: True
```
```
In mm/mmu_context.c (0)
Location: include/linux/mm_types.h:527
Inline: True
```
```
In mm/rmap.c (ffffffff811cb3fd)
Location: include/linux/mm_types.h:527
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In fs/exec.c (0)
Location: include/linux/mm_types.h:527
Inline: True
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
In arch/x86/events/core.c (ffffffff81005926)
Location: include/linux/mm_types.h:534
Inline: True
```
```
In arch/x86/xen/mmu.c (0)
Location: include/linux/mm_types.h:534
Inline: True
```
```
In arch/x86/kernel/ldt.c (ffffffff81031f51)
Location: include/linux/mm_types.h:534
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/mm/tlb.c (ffffffff81072a27)
Location: include/linux/mm_types.h:534
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_page
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - arch/x86/mm/tlb.c:flush_tlb_current_task
```
```
In kernel/cpu.c (0)
Location: include/linux/mm_types.h:534
Inline: True
```
```
In mm/rmap.c (ffffffff811e858f)
Location: include/linux/mm_types.h:534
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
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
In arch/x86/events/core.c (0)
Location: include/linux/mm_types.h:529
Inline: True
```
```
In arch/x86/xen/mmu.c (0)
Location: include/linux/mm_types.h:529
Inline: True
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/mm_types.h:529
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/mm_types.h:529
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/mm_types.h:529
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/mm_types.h:529
Inline: True
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
In arch/x86/events/core.c (0)
Location: include/linux/mm_types.h:520
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/mm_types.h:520
Inline: True
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/mm_types.h:520
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/mm_types.h:520
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/mm_types.h:520
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/mm_types.h:520
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
In arch/x86/events/core.c (0)
Location: include/linux/mm_types.h:524
Inline: True
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/mm_types.h:524
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/mm_types.h:524
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/mm_types.h:524
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/mm_types.h:524
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
In arch/x86/events/core.c (0)
Location: include/linux/mm_types.h:510
Inline: True
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/mm_types.h:510
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/mm_types.h:510
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/mm_types.h:510
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/mm_types.h:510
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
In arch/x86/events/core.c (ffffffff8100616d)
Location: include/linux/mm_types.h:522
Inline: True
```
```
In arch/x86/kernel/ldt.c (ffffffff810347b2)
Location: include/linux/mm_types.h:522
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/mm/tlb.c (ffffffff810846be)
Location: include/linux/mm_types.h:522
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In kernel/cpu.c (0)
Location: include/linux/mm_types.h:522
Inline: True
```
```
In mm/rmap.c (ffffffff81253593)
Location: include/linux/mm_types.h:522
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
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
In arch/x86/events/core.c (ffffffff81006328)
Location: include/linux/mm_types.h:542
Inline: True
```
```
In arch/x86/kernel/ldt.c (ffffffff81036647)
Location: include/linux/mm_types.h:542
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/mm/tlb.c (ffffffff8108836f)
Location: include/linux/mm_types.h:542
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In kernel/cpu.c (0)
Location: include/linux/mm_types.h:542
Inline: True
```
```
In mm/rmap.c (ffffffff81265812)
Location: include/linux/mm_types.h:542
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
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
In arch/x86/events/core.c (ffffffff810063d8)
Location: include/linux/mm_types.h:550
Inline: True
```
```
In arch/x86/kernel/ldt.c (ffffffff81036e77)
Location: include/linux/mm_types.h:550
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/mm/tlb.c (ffffffff8108901f)
Location: include/linux/mm_types.h:550
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In kernel/cpu.c (0)
Location: include/linux/mm_types.h:550
Inline: True
```
```
In mm/rmap.c (ffffffff81274127)
Location: include/linux/mm_types.h:550
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
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
In arch/x86/events/core.c (ffffffff81007308)
Location: include/linux/mm_types.h:564
Inline: True
```
```
In arch/x86/kernel/ldt.c (ffffffff81038e30)
Location: include/linux/mm_types.h:564
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/mm/tlb.c (ffffffff8108b71f)
Location: include/linux/mm_types.h:564
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In kernel/cpu.c (0)
Location: include/linux/mm_types.h:564
Inline: True
```
```
In mm/rmap.c (ffffffff812a53a7)
Location: include/linux/mm_types.h:564
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
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
In arch/x86/events/core.c (ffffffff81006208)
Location: include/linux/mm_types.h:588
Inline: True
```
```
In arch/x86/kernel/ldt.c (ffffffff810396a0)
Location: include/linux/mm_types.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/mm_types.h:588
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff8108b76f)
Location: include/linux/mm_types.h:588
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In kernel/cpu.c (0)
Location: include/linux/mm_types.h:588
Inline: True
```
```
In mm/rmap.c (ffffffff812b083b)
Location: include/linux/mm_types.h:588
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In drivers/iommu/intel/svm.c (ffffffff817b614c)
Location: include/linux/mm_types.h:588
Inline: True
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
In arch/x86/events/core.c (ffffffff81005f78)
Location: include/linux/mm_types.h:599
Inline: True
```
```
In arch/x86/kernel/ldt.c (ffffffff8103b170)
Location: include/linux/mm_types.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/mm_types.h:599
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff8108c35e)
Location: include/linux/mm_types.h:599
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In kernel/cpu.c (0)
Location: include/linux/mm_types.h:599
Inline: True
```
```
In mm/rmap.c (ffffffff812b5e66)
Location: include/linux/mm_types.h:599
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In drivers/iommu/intel/svm.c (ffffffff817993ff)
Location: include/linux/mm_types.h:599
Inline: True
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
In arch/x86/events/core.c (ffffffff81006628)
Location: include/linux/mm_types.h:606
Inline: True
```
```
In arch/x86/kernel/ldt.c (ffffffff81040ba0)
Location: include/linux/mm_types.h:606
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/mm_types.h:606
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff8109bb87)
Location: include/linux/mm_types.h:606
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In kernel/cpu.c (0)
Location: include/linux/mm_types.h:606
Inline: True
```
```
In mm/rmap.c (ffffffff812f7a86)
Location: include/linux/mm_types.h:606
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In drivers/iommu/intel/svm.c (ffffffff81821939)
Location: include/linux/mm_types.h:606
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
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
In arch/x86/events/core.c (ffffffff81005a1a)
Location: include/linux/mm_types.h:693
Inline: True
```
```
In arch/x86/kernel/ldt.c (ffffffff810484e8)
Location: include/linux/mm_types.h:693
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/mm_types.h:693
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff810aeff7)
Location: include/linux/mm_types.h:693
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In kernel/cpu.c (0)
Location: include/linux/mm_types.h:693
Inline: True
```
```
In mm/rmap.c (ffffffff8135da7b)
Location: include/linux/mm_types.h:693
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
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
In arch/x86/events/core.c (ffffffff81006f8a)
Location: include/linux/mm_types.h:828
Inline: True
```
```
In arch/x86/kernel/ldt.c (ffffffff81053248)
Location: include/linux/mm_types.h:828
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/mm_types.h:828
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff810c939e)
Location: include/linux/mm_types.h:828
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In kernel/cpu.c (0)
Location: include/linux/mm_types.h:828
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/mm_types.h:828
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
In arch/x86/events/core.c (ffffffff8100672a)
Location: include/linux/mm_types.h:863
Inline: True
```
```
In arch/x86/kernel/ldt.c (ffffffff81054222)
Location: include/linux/mm_types.h:863
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/mm_types.h:863
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff810cca3c)
Location: include/linux/mm_types.h:863
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In kernel/cpu.c (0)
Location: include/linux/mm_types.h:863
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/mm_types.h:863
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
In arch/x86/events/core.c (ffffffff8100be2a)
Location: include/linux/mm_types.h:1004
Inline: True
```
```
In arch/x86/kernel/ldt.c (ffffffff8105b452)
Location: include/linux/mm_types.h:1004
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/mm_types.h:1004
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff810d50db)
Location: include/linux/mm_types.h:1004
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In kernel/cpu.c (0)
Location: include/linux/mm_types.h:1004
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/mm_types.h:1004
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
In kernel/cpu.c (0)
Location: include/linux/mm_types.h:550
Inline: True
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
In arch/arm/kernel/smp.c (0)
Location: include/linux/mm_types.h:550
Inline: True
```
```
In arch/arm/kernel/smp_tlb.c (c0314388)
Location: include/linux/mm_types.h:550
Inline: True
Inline callers:
  - arch/arm/kernel/smp_tlb.c:flush_tlb_range
  - arch/arm/kernel/smp_tlb.c:flush_tlb_page
  - arch/arm/kernel/smp_tlb.c:flush_tlb_mm
```
```
In arch/arm/mm/flush.c (0)
Location: include/linux/mm_types.h:550
Inline: True
```
```
In arch/arm/mm/context.c (0)
Location: include/linux/mm_types.h:550
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/mm_types.h:550
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/mm_types.h:550
Inline: True
```
```
In mm/mmu_context.c (0)
Location: include/linux/mm_types.h:550
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/mm_types.h:550
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
In arch/powerpc/mm/mmu_context.c (0)
Location: include/linux/mm_types.h:550
Inline: True
```
```
In arch/powerpc/mm/book3s64/hash_pgtable.c (0)
Location: include/linux/mm_types.h:550
Inline: True
```
```
In arch/powerpc/mm/book3s64/hash_utils.c (0)
Location: include/linux/mm_types.h:550
Inline: True
```
```
In arch/powerpc/mm/book3s64/pgtable.c (c000000000090ce8)
Location: include/linux/mm_types.h:550
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/pgtable.c:pmdp_invalidate
```
```
In arch/powerpc/mm/book3s64/hash_tlb.c (0)
Location: include/linux/mm_types.h:550
Inline: True
```
```
In arch/powerpc/mm/book3s64/radix_tlb.c (c00000000009d140)
Location: include/linux/mm_types.h:550
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_collapsed_pmd
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_page_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:__flush_all_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:exit_flush_lazy_tlbs
```
```
In kernel/cpu.c (0)
Location: include/linux/mm_types.h:550
Inline: True
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
In arch/riscv/mm/cacheflush.c (0)
Location: include/linux/mm_types.h:550
Inline: True
```
```
In arch/riscv/mm/context.c (0)
Location: include/linux/mm_types.h:550
Inline: True
```
```
In arch/riscv/mm/tlbflush.c (ffffffe0000ba5a2)
Location: include/linux/mm_types.h:550
Inline: True
Inline callers:
  - arch/riscv/mm/tlbflush.c:flush_tlb_range
  - arch/riscv/mm/tlbflush.c:flush_tlb_page
  - arch/riscv/mm/tlbflush.c:flush_tlb_mm
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
In arch/x86/events/core.c (ffffffff810063d8)
Location: include/linux/mm_types.h:550
Inline: True
```
```
In arch/x86/kernel/ldt.c (ffffffff81036fd7)
Location: include/linux/mm_types.h:550
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/mm/tlb.c (ffffffff81087fdf)
Location: include/linux/mm_types.h:550
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In kernel/cpu.c (0)
Location: include/linux/mm_types.h:550
Inline: True
```
```
In mm/rmap.c (ffffffff8126c777)
Location: include/linux/mm_types.h:550
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
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
In arch/x86/events/core.c (ffffffff81004b58)
Location: include/linux/mm_types.h:550
Inline: True
```
```
In arch/x86/kernel/ldt.c (ffffffff810268cf)
Location: include/linux/mm_types.h:550
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/mm/tlb.c (ffffffff81076c3f)
Location: include/linux/mm_types.h:550
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In kernel/cpu.c (0)
Location: include/linux/mm_types.h:550
Inline: True
```
```
In mm/rmap.c (ffffffff8125e7cf)
Location: include/linux/mm_types.h:550
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
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
In arch/x86/events/core.c (ffffffff81006398)
Location: include/linux/mm_types.h:550
Inline: True
```
```
In arch/x86/kernel/ldt.c (ffffffff81036e37)
Location: include/linux/mm_types.h:550
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/mm/tlb.c (ffffffff81087f8f)
Location: include/linux/mm_types.h:550
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In kernel/cpu.c (0)
Location: include/linux/mm_types.h:550
Inline: True
```
```
In mm/rmap.c (ffffffff8126a517)
Location: include/linux/mm_types.h:550
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
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
In arch/x86/events/core.c (ffffffff810064f8)
Location: include/linux/mm_types.h:550
Inline: True
```
```
In arch/x86/kernel/ldt.c (ffffffff81037e37)
Location: include/linux/mm_types.h:550
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/mm/tlb.c (ffffffff8108a1e6)
Location: include/linux/mm_types.h:550
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In kernel/cpu.c (0)
Location: include/linux/mm_types.h:550
Inline: True
```
```
In mm/rmap.c (ffffffff81279e8d)
Location: include/linux/mm_types.h:550
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
</details>
</li>
</ul>

## Differences
