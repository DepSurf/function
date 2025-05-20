# Function: <code>hv_do_rep_hypercall</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8102a785)
Location: arch/x86/include/asm/mshyperv.h:260
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
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
In arch/x86/hyperv/mmu.c (ffffffff8102b333)
Location: arch/x86/include/asm/mshyperv.h:201
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102bdc2)
Location: arch/x86/include/asm/mshyperv.h:201
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
In arch/x86/hyperv/mmu.c (ffffffff8102bf19)
Location: arch/x86/include/asm/mshyperv.h:247
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8102c99c)
Location: arch/x86/include/asm/mshyperv.h:247
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102cdca)
Location: arch/x86/include/asm/mshyperv.h:247
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
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
In arch/x86/hyperv/mmu.c (ffffffff8102dfd8)
Location: arch/x86/include/asm/mshyperv.h:181
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8102e6f2)
Location: arch/x86/include/asm/mshyperv.h:181
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102ea08)
Location: arch/x86/include/asm/mshyperv.h:181
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
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
In arch/x86/hyperv/mmu.c (ffffffff8102e8e8)
Location: arch/x86/include/asm/mshyperv.h:181
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8102f002)
Location: arch/x86/include/asm/mshyperv.h:181
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f318)
Location: arch/x86/include/asm/mshyperv.h:181
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
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
In arch/x86/hyperv/mmu.c (ffffffff81030f46)
Location: arch/x86/include/asm/mshyperv.h:174
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff81031643)
Location: arch/x86/include/asm/mshyperv.h:174
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81031838)
Location: arch/x86/include/asm/mshyperv.h:174
Inline: True
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
In arch/x86/hyperv/mmu.c (ffffffff81031cb6)
Location: arch/x86/include/asm/mshyperv.h:189
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff81032353)
Location: arch/x86/include/asm/mshyperv.h:189
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81032538)
Location: arch/x86/include/asm/mshyperv.h:189
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
In arch/x86/hyperv/mmu.c (ffffffff810327d2)
Location: include/asm-generic/mshyperv.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff81032ece)
Location: include/asm-generic/mshyperv.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff810335ae)
Location: include/asm-generic/mshyperv.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8103397c)
Location: include/asm-generic/mshyperv.h:66
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff810341d2)
Location: include/asm-generic/mshyperv.h:66
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
In arch/x86/hyperv/mmu.c (ffffffff8103796a)
Location: include/asm-generic/mshyperv.h:70
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff8103807e)
Location: include/asm-generic/mshyperv.h:70
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff81038746)
Location: include/asm-generic/mshyperv.h:70
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81038e0a)
Location: include/asm-generic/mshyperv.h:70
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81039472)
Location: include/asm-generic/mshyperv.h:70
Inline: True
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
In arch/x86/hyperv/mmu.c (ffffffff8103db89)
Location: include/asm-generic/mshyperv.h:81
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff8103e31a)
Location: include/asm-generic/mshyperv.h:81
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8103e9d3)
Location: include/asm-generic/mshyperv.h:81
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/ivm.c (ffffffff8103f312)
Location: include/asm-generic/mshyperv.h:81
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8103fbae)
Location: include/asm-generic/mshyperv.h:81
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff810402e1)
Location: include/asm-generic/mshyperv.h:81
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
In arch/x86/hyperv/mmu.c (ffffffff810469b4)
Location: include/asm-generic/mshyperv.h:81
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff810471de)
Location: include/asm-generic/mshyperv.h:81
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff81047983)
Location: include/asm-generic/mshyperv.h:81
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/ivm.c (ffffffff8104844f)
Location: include/asm-generic/mshyperv.h:81
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81048ae7)
Location: include/asm-generic/mshyperv.h:81
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff8104954b)
Location: include/asm-generic/mshyperv.h:81
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
In arch/x86/hyperv/mmu.c (ffffffff81046c0a)
Location: include/asm-generic/mshyperv.h:84
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff8104755e)
Location: include/asm-generic/mshyperv.h:84
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff81047c79)
Location: include/asm-generic/mshyperv.h:84
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/ivm.c (ffffffff810487ff)
Location: include/asm-generic/mshyperv.h:84
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81048d59)
Location: include/asm-generic/mshyperv.h:84
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff810497ae)
Location: include/asm-generic/mshyperv.h:84
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
In arch/x86/hyperv/mmu.c (ffffffff8104d3d8)
Location: include/asm-generic/mshyperv.h:92
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff8104dce0)
Location: include/asm-generic/mshyperv.h:92
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8104e3e4)
Location: include/asm-generic/mshyperv.h:92
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/ivm.c (ffffffff8104f8f3)
Location: include/asm-generic/mshyperv.h:92
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81050011)
Location: include/asm-generic/mshyperv.h:92
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81050cec)
Location: include/asm-generic/mshyperv.h:92
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8102ea48)
Location: arch/x86/include/asm/mshyperv.h:181
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8102f162)
Location: arch/x86/include/asm/mshyperv.h:181
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f478)
Location: arch/x86/include/asm/mshyperv.h:181
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
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
In arch/x86/hyperv/mmu.c (ffffffff8101e326)
Location: arch/x86/include/asm/mshyperv.h:181
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8101ead4)
Location: arch/x86/include/asm/mshyperv.h:181
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8101ee02)
Location: arch/x86/include/asm/mshyperv.h:181
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
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
In arch/x86/hyperv/mmu.c (ffffffff8102e8a8)
Location: arch/x86/include/asm/mshyperv.h:181
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8102efc2)
Location: arch/x86/include/asm/mshyperv.h:181
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f2d8)
Location: arch/x86/include/asm/mshyperv.h:181
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
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
In arch/x86/hyperv/mmu.c (ffffffff8102f6b1)
Location: arch/x86/include/asm/mshyperv.h:181
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8102fde2)
Location: arch/x86/include/asm/mshyperv.h:181
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81030118)
Location: arch/x86/include/asm/mshyperv.h:181
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
</details>
</li>
</ul>

## Differences
