# Function: <code>hv_do_hypercall</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 hv_do_hypercall(u64 control, void *input, void *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102bba0)
Location: arch/x86/hyperv/hv_init.c:203
Inline: False
```
**Symbols:**

```
ffffffff8102bba0-ffffffff8102bc28: hv_do_hypercall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 hv_do_hypercall(u64 control, void *input, void *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff81029de0)
Location: arch/x86/hyperv/hv_init.c:184
Inline: False
```
**Symbols:**

```
ffffffff81029de0-ffffffff81029e62: hv_do_hypercall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8102a794)
Location: arch/x86/include/asm/mshyperv.h:179
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
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
In arch/x86/hyperv/mmu.c (ffffffff8102b39c)
Location: arch/x86/include/asm/mshyperv.h:128
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102bd07)
Location: arch/x86/include/asm/mshyperv.h:128
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
In arch/x86/hyperv/mmu.c (ffffffff8102bf8f)
Location: arch/x86/include/asm/mshyperv.h:140
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8102ca11)
Location: arch/x86/include/asm/mshyperv.h:140
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102cdca)
Location: arch/x86/include/asm/mshyperv.h:140
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
In arch/x86/hyperv/mmu.c (ffffffff8102e053)
Location: arch/x86/include/asm/mshyperv.h:74
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8102e771)
Location: arch/x86/include/asm/mshyperv.h:74
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102ea08)
Location: arch/x86/include/asm/mshyperv.h:74
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
In arch/x86/hyperv/mmu.c (ffffffff8102e963)
Location: arch/x86/include/asm/mshyperv.h:74
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8102f081)
Location: arch/x86/include/asm/mshyperv.h:74
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f318)
Location: arch/x86/include/asm/mshyperv.h:74
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
In arch/x86/hyperv/mmu.c (ffffffff81030f4a)
Location: arch/x86/include/asm/mshyperv.h:67
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff810316ca)
Location: arch/x86/include/asm/mshyperv.h:67
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81031838)
Location: arch/x86/include/asm/mshyperv.h:67
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
In arch/x86/hyperv/mmu.c (ffffffff81031cba)
Location: arch/x86/include/asm/mshyperv.h:82
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff810323da)
Location: arch/x86/include/asm/mshyperv.h:82
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81032538)
Location: arch/x86/include/asm/mshyperv.h:82
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
In arch/x86/hyperv/hv_init.c (ffffffff831c5075)
Location: arch/x86/include/asm/mshyperv.h:48
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff810327d6)
Location: arch/x86/include/asm/mshyperv.h:48
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff81032f3f)
Location: arch/x86/include/asm/mshyperv.h:48
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff810331cf)
Location: arch/x86/include/asm/mshyperv.h:48
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8103397c)
Location: arch/x86/include/asm/mshyperv.h:48
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff810345a9)
Location: arch/x86/include/asm/mshyperv.h:48
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
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
In arch/x86/hyperv/hv_init.c (ffffffff832a5a5d)
Location: arch/x86/include/asm/mshyperv.h:46
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_get_partition_id
```
```
In arch/x86/hyperv/mmu.c (ffffffff8103796e)
Location: arch/x86/include/asm/mshyperv.h:46
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff810380ed)
Location: arch/x86/include/asm/mshyperv.h:46
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8103836f)
Location: arch/x86/include/asm/mshyperv.h:46
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81038e0a)
Location: arch/x86/include/asm/mshyperv.h:46
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81039849)
Location: arch/x86/include/asm/mshyperv.h:46
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
```
```
In drivers/hv/hv_common.c (ffffffff81a60fe6)
Location: arch/x86/include/asm/mshyperv.h:46
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
In arch/x86/hyperv/hv_init.c (ffffffff83454af8)
Location: arch/x86/include/asm/mshyperv.h:39
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_get_partition_id
```
```
In arch/x86/hyperv/mmu.c (ffffffff8103db8d)
Location: arch/x86/include/asm/mshyperv.h:39
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff8103e381)
Location: arch/x86/include/asm/mshyperv.h:39
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8103e656)
Location: arch/x86/include/asm/mshyperv.h:39
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/ivm.c (ffffffff8103f388)
Location: arch/x86/include/asm/mshyperv.h:39
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8103fbae)
Location: arch/x86/include/asm/mshyperv.h:39
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff8104071c)
Location: arch/x86/include/asm/mshyperv.h:39
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
```
```
In drivers/hv/hv_common.c (ffffffff81bd161b)
Location: arch/x86/include/asm/mshyperv.h:39
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
In arch/x86/hyperv/hv_init.c (ffffffff83e7269b)
Location: arch/x86/include/asm/mshyperv.h:37
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_get_partition_id
```
```
In arch/x86/hyperv/mmu.c (ffffffff810469b8)
Location: arch/x86/include/asm/mshyperv.h:37
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff81047245)
Location: arch/x86/include/asm/mshyperv.h:37
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff81047550)
Location: arch/x86/include/asm/mshyperv.h:37
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/ivm.c (ffffffff810484c6)
Location: arch/x86/include/asm/mshyperv.h:37
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81048ae7)
Location: arch/x86/include/asm/mshyperv.h:37
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff810499e2)
Location: arch/x86/include/asm/mshyperv.h:37
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
```
```
In drivers/hv/hv_common.c (ffffffff81d7d09b)
Location: arch/x86/include/asm/mshyperv.h:37
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
In arch/x86/hyperv/hv_init.c (ffffffff836935bb)
Location: arch/x86/include/asm/mshyperv.h:54
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_get_partition_id
```
```
In arch/x86/hyperv/mmu.c (ffffffff81046c0e)
Location: arch/x86/include/asm/mshyperv.h:54
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff810475c5)
Location: arch/x86/include/asm/mshyperv.h:54
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff810478d0)
Location: arch/x86/include/asm/mshyperv.h:54
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/ivm.c (ffffffff81048872)
Location: arch/x86/include/asm/mshyperv.h:54
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81048d59)
Location: arch/x86/include/asm/mshyperv.h:54
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81049c12)
Location: arch/x86/include/asm/mshyperv.h:54
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
```
```
In drivers/hv/hv_common.c (ffffffff81deb48b)
Location: arch/x86/include/asm/mshyperv.h:54
Inline: True
Inline callers:
  - drivers/hv/hv_common.c:hv_query_ext_cap
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
u64 hv_do_hypercall(u64 control, void *input, void *output);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/include/asm/mshyperv.h:71
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_get_partition_id
```
```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/include/asm/mshyperv.h:71
Inline: True
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (0)
Location: arch/x86/include/asm/mshyperv.h:71
Inline: True
Direct callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/irqdomain.c (0)
Location: arch/x86/include/asm/mshyperv.h:71
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/ivm.c (0)
Location: arch/x86/include/asm/mshyperv.h:71
Inline: False
Direct callers:
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
  - arch/x86/hyperv/ivm.c:hv_snp_boot_ap
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: arch/x86/include/asm/mshyperv.h:71
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (0)
Location: arch/x86/include/asm/mshyperv.h:71
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
```
```
In drivers/hv/hv_common.c (0)
Location: arch/x86/include/asm/mshyperv.h:71
Inline: True
Direct callers:
  - drivers/hv/hv_common.c:hv_query_ext_cap
```
**Symbols:**

```
ffffffff8104b3c0-ffffffff8104b4dd: hv_do_hypercall.constprop.0 (STB_LOCAL)
ffffffff821aac8d-ffffffff821aacb7: hv_do_hypercall.constprop.0.cold (STB_LOCAL)
ffffffff8104cf60-ffffffff8104d089: hv_do_hypercall.constprop.0 (STB_LOCAL)
ffffffff821aad24-ffffffff821aad4e: hv_do_hypercall.constprop.0.cold (STB_LOCAL)
ffffffff8104da10-ffffffff8104db39: hv_do_hypercall.constprop.0 (STB_LOCAL)
ffffffff821aadae-ffffffff821aadd8: hv_do_hypercall.constprop.0.cold (STB_LOCAL)
ffffffff8104dfb0-ffffffff8104e110: hv_do_hypercall (STB_LOCAL)
ffffffff821aadd8-ffffffff821aae02: hv_do_hypercall.cold (STB_LOCAL)
ffffffff8104f140-ffffffff8104f28e: hv_do_hypercall (STB_LOCAL)
ffffffff821aae93-ffffffff821aaedd: hv_do_hypercall.cold (STB_LOCAL)
ffffffff8104fd00-ffffffff8104fe29: hv_do_hypercall.constprop.0 (STB_LOCAL)
ffffffff821aaf07-ffffffff821aaf31: hv_do_hypercall.constprop.0.cold (STB_LOCAL)
ffffffff81050870-ffffffff810509d0: hv_do_hypercall (STB_LOCAL)
ffffffff821aaf68-ffffffff821aaf92: hv_do_hypercall.cold (STB_LOCAL)
ffffffff81ea1780-ffffffff81ea189a: hv_do_hypercall.constprop.0 (STB_LOCAL)
ffffffff8220d50b-ffffffff8220d535: hv_do_hypercall.constprop.0.cold (STB_LOCAL)
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
In arch/x86/hyperv/mmu.c (ffffffff8102eac3)
Location: arch/x86/include/asm/mshyperv.h:74
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8102f1e1)
Location: arch/x86/include/asm/mshyperv.h:74
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f478)
Location: arch/x86/include/asm/mshyperv.h:74
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
In arch/x86/hyperv/mmu.c (ffffffff8101e3a0)
Location: arch/x86/include/asm/mshyperv.h:74
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8101eb5e)
Location: arch/x86/include/asm/mshyperv.h:74
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8101ee02)
Location: arch/x86/include/asm/mshyperv.h:74
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In drivers/hv/hv.c (ffffffff8184f6ea)
Location: arch/x86/include/asm/mshyperv.h:74
Inline: True
Inline callers:
  - drivers/hv/hv.c:hv_post_message
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
In arch/x86/hyperv/mmu.c (ffffffff8102e923)
Location: arch/x86/include/asm/mshyperv.h:74
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8102f041)
Location: arch/x86/include/asm/mshyperv.h:74
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f2d8)
Location: arch/x86/include/asm/mshyperv.h:74
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
In arch/x86/hyperv/mmu.c (ffffffff8102f72c)
Location: arch/x86/include/asm/mshyperv.h:74
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8102fe61)
Location: arch/x86/include/asm/mshyperv.h:74
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81030118)
Location: arch/x86/include/asm/mshyperv.h:74
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
