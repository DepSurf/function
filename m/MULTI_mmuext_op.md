# Function: <code>MULTI_mmuext_op</code>

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
In arch/x86/xen/enlighten.c (ffffffff8101d2df)
Location: arch/x86/include/asm/xen/hypercall.h:576
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_set_ldt
```
```
In arch/x86/xen/mmu.c (ffffffff8101edac)
Location: arch/x86/include/asm/xen/hypercall.h:576
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_flush_tlb
  - arch/x86/xen/mmu.c:xen_flush_tlb_single
  - arch/x86/xen/mmu.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
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
In arch/x86/xen/enlighten.c (ffffffff8101c49f)
Location: arch/x86/include/asm/xen/hypercall.h:577
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_set_ldt
```
```
In arch/x86/xen/mmu.c (ffffffff81020c72)
Location: arch/x86/include/asm/xen/hypercall.h:577
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
  - arch/x86/xen/mmu.c:xen_flush_tlb_single
  - arch/x86/xen/mmu.c:xen_flush_tlb
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
  - arch/x86/xen/mmu.c:xen_extend_mmuext_op
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
In arch/x86/xen/enlighten.c (ffffffff8101cb6f)
Location: arch/x86/include/asm/xen/hypercall.h:577
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_set_ldt
```
```
In arch/x86/xen/mmu.c (ffffffff810213dc)
Location: arch/x86/include/asm/xen/hypercall.h:577
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
  - arch/x86/xen/mmu.c:xen_flush_tlb_single
  - arch/x86/xen/mmu.c:xen_flush_tlb
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
  - arch/x86/xen/mmu.c:xen_extend_mmuext_op
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
In arch/x86/xen/mmu.c (ffffffff8101a709)
Location: arch/x86/include/asm/xen/hypercall.h:593
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8101f961)
Location: arch/x86/include/asm/xen/hypercall.h:593
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810227df)
Location: arch/x86/include/asm/xen/hypercall.h:593
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_single
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
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
In arch/x86/xen/mmu.c (ffffffff8101afd9)
Location: arch/x86/include/asm/xen/hypercall.h:595
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff810205b1)
Location: arch/x86/include/asm/xen/hypercall.h:595
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810234e2)
Location: arch/x86/include/asm/xen/hypercall.h:595
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
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
In arch/x86/xen/mmu.c (ffffffff8101b814)
Location: arch/x86/include/asm/xen/hypercall.h:595
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff810208bf)
Location: arch/x86/include/asm/xen/hypercall.h:595
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81024b0b)
Location: arch/x86/include/asm/xen/hypercall.h:595
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
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
In arch/x86/xen/enlighten_pv.c (ffffffff810208ff)
Location: arch/x86/include/asm/xen/hypercall.h:500
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810224f4)
Location: arch/x86/include/asm/xen/hypercall.h:500
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
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
In arch/x86/xen/enlighten_pv.c (ffffffff81022442)
Location: arch/x86/include/asm/xen/hypercall.h:510
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810234a4)
Location: arch/x86/include/asm/xen/hypercall.h:510
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
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
In arch/x86/xen/enlighten_pv.c (ffffffff81022d82)
Location: arch/x86/include/asm/xen/hypercall.h:510
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023f64)
Location: arch/x86/include/asm/xen/hypercall.h:510
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
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
In arch/x86/xen/enlighten_pv.c (ffffffff81025532)
Location: arch/x86/include/asm/xen/hypercall.h:510
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81026911)
Location: arch/x86/include/asm/xen/hypercall.h:510
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
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
In arch/x86/xen/enlighten_pv.c (ffffffff810257ac)
Location: arch/x86/include/asm/xen/hypercall.h:510
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81027120)
Location: arch/x86/include/asm/xen/hypercall.h:510
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
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
In arch/x86/xen/enlighten_pv.c (ffffffff81027c0e)
Location: arch/x86/include/asm/xen/hypercall.h:510
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102906e)
Location: arch/x86/include/asm/xen/hypercall.h:510
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
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
In arch/x86/xen/enlighten_pv.c (ffffffff8102c28b)
Location: arch/x86/include/asm/xen/hypercall.h:510
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102d7be)
Location: arch/x86/include/asm/xen/hypercall.h:510
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
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
In arch/x86/xen/enlighten_pv.c (ffffffff81030f72)
Location: arch/x86/include/asm/xen/hypercall.h:361
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81032595)
Location: arch/x86/include/asm/xen/hypercall.h:361
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
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
In arch/x86/xen/enlighten_pv.c (ffffffff810383d2)
Location: arch/x86/include/asm/xen/hypercall.h:361
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81039f95)
Location: arch/x86/include/asm/xen/hypercall.h:361
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
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
In arch/x86/xen/enlighten_pv.c (ffffffff810385d2)
Location: arch/x86/include/asm/xen/hypercall.h:361
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103a025)
Location: arch/x86/include/asm/xen/hypercall.h:361
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
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
In arch/x86/xen/enlighten_pv.c (ffffffff8103e942)
Location: arch/x86/include/asm/xen/hypercall.h:361
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810404e5)
Location: arch/x86/include/asm/xen/hypercall.h:361
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81022ee2)
Location: arch/x86/include/asm/xen/hypercall.h:510
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810240c4)
Location: arch/x86/include/asm/xen/hypercall.h:510
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81022d42)
Location: arch/x86/include/asm/xen/hypercall.h:510
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023f24)
Location: arch/x86/include/asm/xen/hypercall.h:510
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
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
In arch/x86/xen/enlighten_pv.c (ffffffff81023152)
Location: arch/x86/include/asm/xen/hypercall.h:510
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102441b)
Location: arch/x86/include/asm/xen/hypercall.h:510
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
```
</details>
</li>
</ul>

## Differences
