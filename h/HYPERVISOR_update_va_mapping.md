# Function: <code>HYPERVISOR_update_va_mapping</code>

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
In arch/x86/xen/enlighten.c (ffffffff81f607b3)
Location: arch/x86/include/asm/xen/hypercall.h:352
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten.c:set_aliased_prot
  - arch/x86/xen/enlighten.c:set_aliased_prot
```
```
In arch/x86/xen/setup.c (ffffffff81f6130f)
Location: arch/x86/include/asm/xen/hypercall.h:352
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu.c (ffffffff81f6238a)
Location: arch/x86/include/asm/xen/hypercall.h:352
Inline: True
```
```
In arch/x86/xen/suspend.c (ffffffff81023efd)
Location: arch/x86/include/asm/xen/hypercall.h:352
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
```
In drivers/xen/balloon.c (ffffffff814c65fa)
Location: arch/x86/include/asm/xen/hypercall.h:352
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:balloon_process
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
In arch/x86/xen/enlighten.c (ffffffff81f8841f)
Location: arch/x86/include/asm/xen/hypercall.h:353
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten.c:set_aliased_prot
  - arch/x86/xen/enlighten.c:set_aliased_prot
```
```
In arch/x86/xen/setup.c (ffffffff81f8923c)
Location: arch/x86/include/asm/xen/hypercall.h:353
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu.c (ffffffff81f89fa6)
Location: arch/x86/include/asm/xen/hypercall.h:353
Inline: True
```
```
In arch/x86/xen/suspend.c (ffffffff8102319a)
Location: arch/x86/include/asm/xen/hypercall.h:353
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
```
In drivers/xen/balloon.c (ffffffff815174b9)
Location: arch/x86/include/asm/xen/hypercall.h:353
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
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
In arch/x86/xen/enlighten.c (ffffffff81fc380d)
Location: arch/x86/include/asm/xen/hypercall.h:353
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten.c:set_aliased_prot
  - arch/x86/xen/enlighten.c:set_aliased_prot
```
```
In arch/x86/xen/setup.c (ffffffff81fc4630)
Location: arch/x86/include/asm/xen/hypercall.h:353
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu.c (ffffffff81fc53a0)
Location: arch/x86/include/asm/xen/hypercall.h:353
Inline: True
```
```
In arch/x86/xen/suspend.c (ffffffff810238ea)
Location: arch/x86/include/asm/xen/hypercall.h:353
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
```
In drivers/xen/balloon.c (ffffffff815438ea)
Location: arch/x86/include/asm/xen/hypercall.h:353
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
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
In arch/x86/xen/setup.c (ffffffff820a4479)
Location: arch/x86/include/asm/xen/hypercall.h:358
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101cdfe)
Location: arch/x86/include/asm/xen/hypercall.h:358
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff820a5a61)
Location: arch/x86/include/asm/xen/hypercall.h:358
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff820a61e8)
Location: arch/x86/include/asm/xen/hypercall.h:358
Inline: True
```
```
In drivers/xen/balloon.c (ffffffff815577a0)
Location: arch/x86/include/asm/xen/hypercall.h:358
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
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
In arch/x86/xen/setup.c (ffffffff826aab57)
Location: arch/x86/include/asm/xen/hypercall.h:358
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101daae)
Location: arch/x86/include/asm/xen/hypercall.h:358
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff826ac12f)
Location: arch/x86/include/asm/xen/hypercall.h:358
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826ac8b2)
Location: arch/x86/include/asm/xen/hypercall.h:358
Inline: True
```
```
In drivers/xen/balloon.c (ffffffff815bb8e1)
Location: arch/x86/include/asm/xen/hypercall.h:358
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
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
In arch/x86/xen/setup.c (ffffffff826d3cd7)
Location: arch/x86/include/asm/xen/hypercall.h:358
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101e511)
Location: arch/x86/include/asm/xen/hypercall.h:358
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff826d531c)
Location: arch/x86/include/asm/xen/hypercall.h:358
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826d591b)
Location: arch/x86/include/asm/xen/hypercall.h:358
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
```
```
In drivers/xen/balloon.c (ffffffff815f3e3c)
Location: arch/x86/include/asm/xen/hypercall.h:358
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
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
In arch/x86/xen/setup.c (ffffffff82889d6a)
Location: arch/x86/include/asm/xen/hypercall.h:325
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101dda1)
Location: arch/x86/include/asm/xen/hypercall.h:325
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8288b2fa)
Location: arch/x86/include/asm/xen/hypercall.h:325
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8288b9c1)
Location: arch/x86/include/asm/xen/hypercall.h:325
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
```
```
In drivers/xen/mem-reservation.c (ffffffff8160feda)
Location: arch/x86/include/asm/xen/hypercall.h:325
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
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
In arch/x86/xen/setup.c (ffffffff828a1123)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101f93f)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a2748)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a2dfa)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
```
```
In drivers/xen/mem-reservation.c (ffffffff81643d14)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
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
In arch/x86/xen/setup.c (ffffffff828a41e3)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8102029f)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a57fc)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a5ead)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
```
```
In drivers/xen/mem-reservation.c (ffffffff816662c4)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
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
In arch/x86/xen/setup.c (ffffffff82cca75b)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_update_mem_tables
```
```
In arch/x86/xen/suspend_pv.c (ffffffff810228ef)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82ccb86b)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82ccc189)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
```
```
In drivers/xen/mem-reservation.c (ffffffff81715a8e)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
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
In arch/x86/xen/setup.c (ffffffff82fb65c9)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_update_mem_tables
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81022ebf)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82fb76d9)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82fb7fc7)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
```
```
In drivers/xen/mem-reservation.c (ffffffff8173240e)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
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
In arch/x86/xen/setup.c (ffffffff831c0cbc)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_update_mem_tables
```
```
In arch/x86/xen/suspend_pv.c (ffffffff810251df)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff831c1e81)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff831c2714)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
```
```
In drivers/xen/mem-reservation.c (ffffffff81715ece)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
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
In arch/x86/xen/setup.c (ffffffff832a1576)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/suspend_pv.c (ffffffff810296ef)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff832a28cf)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff832a3104)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:make_lowmem_page_readwrite
  - arch/x86/xen/mmu_pv.c:make_lowmem_page_readonly
```
```
In drivers/xen/mem-reservation.c (ffffffff8179312e)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
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
In arch/x86/xen/setup.c (ffffffff834505c9)
Location: arch/x86/include/asm/xen/hypercall.h:303
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8102e18d)
Location: arch/x86/include/asm/xen/hypercall.h:303
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff83451b44)
Location: arch/x86/include/asm/xen/hypercall.h:303
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103430d)
Location: arch/x86/include/asm/xen/hypercall.h:303
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
  - arch/x86/xen/mmu_pv.c:make_lowmem_page_readwrite
  - arch/x86/xen/mmu_pv.c:make_lowmem_page_readonly
```
```
In drivers/xen/mem-reservation.c (ffffffff818cbabe)
Location: arch/x86/include/asm/xen/hypercall.h:303
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
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
In arch/x86/xen/setup.c (ffffffff83e6c96d)
Location: arch/x86/include/asm/xen/hypercall.h:303
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8103559d)
Location: arch/x86/include/asm/xen/hypercall.h:303
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff83e6ebf9)
Location: arch/x86/include/asm/xen/hypercall.h:303
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103bddf)
Location: arch/x86/include/asm/xen/hypercall.h:303
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_release_pmd_init
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd_init
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In drivers/xen/mem-reservation.c (ffffffff81a1ce8e)
Location: arch/x86/include/asm/xen/hypercall.h:303
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
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
In arch/x86/xen/setup.c (ffffffff8368d490)
Location: arch/x86/include/asm/xen/hypercall.h:303
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8103551d)
Location: arch/x86/include/asm/xen/hypercall.h:303
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8368fb19)
Location: arch/x86/include/asm/xen/hypercall.h:303
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103a557)
Location: arch/x86/include/asm/xen/hypercall.h:303
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_release_pmd_init
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd_init
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In drivers/xen/mem-reservation.c (ffffffff81a6608e)
Location: arch/x86/include/asm/xen/hypercall.h:303
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
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
In arch/x86/xen/setup.c (ffffffff838bd050)
Location: arch/x86/include/asm/xen/hypercall.h:303
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8103b71d)
Location: arch/x86/include/asm/xen/hypercall.h:303
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff838befe9)
Location: arch/x86/include/asm/xen/hypercall.h:303
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81040a17)
Location: arch/x86/include/asm/xen/hypercall.h:303
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_release_pmd_init
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
  - arch/x86/xen/mmu_pv.c:make_lowmem_page_readonly
```
```
In drivers/xen/mem-reservation.c (ffffffff81ab88ce)
Location: arch/x86/include/asm/xen/hypercall.h:303
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
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
In arch/x86/xen/setup.c (ffffffff82892209)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/suspend_pv.c (ffffffff810203ff)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82893805)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82893eb6)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
```
```
In drivers/xen/mem-reservation.c (ffffffff8162bff4)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
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
In arch/x86/xen/setup.c (ffffffff828a51e3)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8102025f)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a67fc)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a6ead)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
```
```
In drivers/xen/mem-reservation.c (ffffffff8165a104)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
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
In arch/x86/xen/setup.c (ffffffff828a51b7)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/suspend_pv.c (ffffffff810204af)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a67d0)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a6e81)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
```
```
In drivers/xen/mem-reservation.c (ffffffff816746d4)
Location: arch/x86/include/asm/xen/hypercall.h:344
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
```
</details>
</li>
</ul>

## Differences
