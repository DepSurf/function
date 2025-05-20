# Function: <code>hv_result</code>

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
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff831c50bc)
Location: include/asm-generic/mshyperv.h:45
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff8103270d)
Location: include/asm-generic/mshyperv.h:45
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff81032efd)
Location: include/asm-generic/mshyperv.h:45
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff81033227)
Location: include/asm-generic/mshyperv.h:45
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81033f3d)
Location: include/asm-generic/mshyperv.h:45
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff810345fd)
Location: include/asm-generic/mshyperv.h:45
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
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
In arch/x86/hyperv/hv_init.c (ffffffff832a5aa4)
Location: include/asm-generic/mshyperv.h:49
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_get_partition_id
```
```
In arch/x86/hyperv/mmu.c (ffffffff8103789c)
Location: include/asm-generic/mshyperv.h:49
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff810380ad)
Location: include/asm-generic/mshyperv.h:49
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff810383c7)
Location: include/asm-generic/mshyperv.h:49
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff810391c9)
Location: include/asm-generic/mshyperv.h:49
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff8103989d)
Location: include/asm-generic/mshyperv.h:49
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
```
```
In drivers/hv/hv_common.c (ffffffff81a6102a)
Location: include/asm-generic/mshyperv.h:49
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
In arch/x86/hyperv/hv_init.c (ffffffff83454b3f)
Location: include/asm-generic/mshyperv.h:60
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_get_partition_id
```
```
In arch/x86/hyperv/mmu.c (ffffffff8103dad1)
Location: include/asm-generic/mshyperv.h:60
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff8103e342)
Location: include/asm-generic/mshyperv.h:60
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8103e6a3)
Location: include/asm-generic/mshyperv.h:60
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/ivm.c (ffffffff8103f33f)
Location: include/asm-generic/mshyperv.h:60
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8103ffed)
Location: include/asm-generic/mshyperv.h:60
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff8104077a)
Location: include/asm-generic/mshyperv.h:60
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
```
```
In drivers/hv/hv_common.c (ffffffff81bd165f)
Location: include/asm-generic/mshyperv.h:60
Inline: True
Inline callers:
  - drivers/hv/hv_common.c:hv_query_ext_cap
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
In arch/x86/hyperv/hv_init.c (ffffffff83e726d8)
Location: include/asm-generic/mshyperv.h:60
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_get_partition_id
```
```
In arch/x86/hyperv/mmu.c (ffffffff810468f2)
Location: include/asm-generic/mshyperv.h:60
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff81047206)
Location: include/asm-generic/mshyperv.h:60
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8104759a)
Location: include/asm-generic/mshyperv.h:60
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/ivm.c (ffffffff8104847d)
Location: include/asm-generic/mshyperv.h:60
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8104921d)
Location: include/asm-generic/mshyperv.h:60
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81049a3d)
Location: include/asm-generic/mshyperv.h:60
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
```
```
In drivers/hv/hv_common.c (ffffffff81d7d0db)
Location: include/asm-generic/mshyperv.h:60
Inline: True
Inline callers:
  - drivers/hv/hv_common.c:hv_query_ext_cap
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
In arch/x86/hyperv/hv_init.c (ffffffff836935f8)
Location: include/asm-generic/mshyperv.h:63
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_get_partition_id
```
```
In arch/x86/hyperv/mmu.c (ffffffff81046b12)
Location: include/asm-generic/mshyperv.h:63
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff81047586)
Location: include/asm-generic/mshyperv.h:63
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8104791a)
Location: include/asm-generic/mshyperv.h:63
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/ivm.c (ffffffff81048829)
Location: include/asm-generic/mshyperv.h:63
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8104947d)
Location: include/asm-generic/mshyperv.h:63
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81049c6d)
Location: include/asm-generic/mshyperv.h:63
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
```
```
In drivers/hv/hv_common.c (ffffffff81deb4cb)
Location: include/asm-generic/mshyperv.h:63
Inline: True
Inline callers:
  - drivers/hv/hv_common.c:hv_query_ext_cap
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
In arch/x86/hyperv/hv_init.c (ffffffff838c3145)
Location: include/asm-generic/mshyperv.h:71
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_get_partition_id
```
```
In arch/x86/hyperv/mmu.c (ffffffff8104d34a)
Location: include/asm-generic/mshyperv.h:71
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff8104dd2f)
Location: include/asm-generic/mshyperv.h:71
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8104e198)
Location: include/asm-generic/mshyperv.h:71
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/ivm.c (ffffffff8104f93e)
Location: include/asm-generic/mshyperv.h:71
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
  - arch/x86/hyperv/ivm.c:hv_snp_boot_ap
  - arch/x86/hyperv/ivm.c:hv_snp_boot_ap
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff810503f0)
Location: include/asm-generic/mshyperv.h:71
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81050f07)
Location: include/asm-generic/mshyperv.h:71
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
```
```
In drivers/hv/hv_common.c (ffffffff81ea1903)
Location: include/asm-generic/mshyperv.h:71
Inline: True
Inline callers:
  - drivers/hv/hv_common.c:hv_query_ext_cap
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
