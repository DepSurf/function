# Function: <code>apic_read</code>

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
In arch/x86/kernel/irq.c (ffffffff81031071)
Location: arch/x86/include/asm/apic.h:384
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81f6b204)
Location: arch/x86/include/asm/apic.h:384
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:mcheck_intel_therm_init
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/smpboot.c (ffffffff810515cc)
Location: arch/x86/include/asm/apic.h:384
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81052c86)
Location: arch/x86/include/asm/apic.h:384
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:disable_local_APIC
  - arch/x86/kernel/apic/apic.c:sync_Arb_IDs
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:default_init_apic_ldr
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81f71e01)
Location: arch/x86/include/asm/apic.h:384
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_APIC_field
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81056135)
Location: arch/x86/include/asm/apic.h:384
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:native_disable_io_apic
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105a166)
Location: arch/x86/include/asm/apic.h:384
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a2c8)
Location: arch/x86/include/asm/apic.h:384
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
  - arch/x86/kernel/apic/apic_flat_64.c:flat_apic_id_registered
```
```
In arch/x86/platform/sfi/sfi.c (ffffffff81f7b460)
Location: arch/x86/include/asm/apic.h:384
Inline: True
Inline callers:
  - arch/x86/platform/sfi/sfi.c:sfi_parse_cpus
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
In arch/x86/kernel/irq.c (ffffffff81030129)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81049c6a)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:mcheck_intel_therm_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff81f98002)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81f9a4ad)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
  - arch/x86/kernel/apic/apic.c:default_init_apic_ldr
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:__smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:sync_Arb_IDs
  - arch/x86/kernel/apic/apic.c:disable_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81f9a652)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_APIC_field
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810563d5)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:native_disable_io_apic
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105a3b6)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a585)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_apic_id_registered
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
```
```
In arch/x86/platform/sfi/sfi.c (ffffffff81fa3f82)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/platform/sfi/sfi.c:sfi_parse_cpus
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
In arch/x86/kernel/irq.c (ffffffff810300e7)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104c06a)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:mcheck_intel_therm_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff81fd3474)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81fd5974)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
  - arch/x86/kernel/apic/apic.c:default_init_apic_ldr
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:__generic_processor_info
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:__smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:sync_Arb_IDs
  - arch/x86/kernel/apic/apic.c:disable_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81fd5b19)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_APIC_field
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81059185)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:native_disable_io_apic
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d1b6)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105d395)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_apic_id_registered
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
```
```
In arch/x86/platform/sfi/sfi.c (ffffffff81fdf84a)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/platform/sfi/sfi.c:sfi_parse_cpus
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
In arch/x86/kernel/irq.c (ffffffff8102e38d)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104b6ea)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:mcheck_intel_therm_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff820b410b)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81056344)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
  - arch/x86/kernel/apic/apic.c:default_init_apic_ldr
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:__smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:sync_Arb_IDs
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:lapic_timer_shutdown
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:__setup_APIC_LVTT
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/vector.c (ffffffff820b6894)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_APIC_field
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810587e5)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:native_disable_io_apic
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c8e6)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105cab5)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_apic_id_registered
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
```
```
In arch/x86/platform/sfi/sfi.c (ffffffff820c05f0)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/platform/sfi/sfi.c:sfi_parse_cpus
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
In arch/x86/kernel/irq.c (ffffffff8103020b)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104f100)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:mcheck_intel_therm_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff826ba83f)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105a034)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:sync_Arb_IDs
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:lapic_timer_shutdown
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:__setup_APIC_LVTT
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/vector.c (ffffffff826bd1b5)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_APIC_field
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105cd05)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:native_disable_io_apic
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81060275)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810607f5)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_apic_id_registered
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
```
```
In arch/x86/platform/sfi/sfi.c (ffffffff826c87cf)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/platform/sfi/sfi.c:sfi_parse_cpus
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
In arch/x86/kernel/irq.c (ffffffff8103147b)
Location: arch/x86/include/asm/apic.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81051e06)
Location: arch/x86/include/asm/apic.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:mcheck_intel_therm_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff826e460e)
Location: arch/x86/include/asm/apic.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105d925)
Location: arch/x86/include/asm/apic.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:sync_Arb_IDs
  - arch/x86/kernel/apic/apic.c:disable_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/vector.c (ffffffff826e7101)
Location: arch/x86/include/asm/apic.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_APIC_field
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105fcd5)
Location: arch/x86/include/asm/apic.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81063376)
Location: arch/x86/include/asm/apic.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810638e5)
Location: arch/x86/include/asm/apic.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_apic_id_registered
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
```
```
In arch/x86/platform/sfi/sfi.c (ffffffff826f2943)
Location: arch/x86/include/asm/apic.h:390
Inline: True
Inline callers:
  - arch/x86/platform/sfi/sfi.c:sfi_parse_cpus
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
In arch/x86/kernel/irq.c (ffffffff8103271b)
Location: arch/x86/include/asm/apic.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff8104f486)
Location: arch/x86/include/asm/apic.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:mcheck_intel_therm_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff8289b0d3)
Location: arch/x86/include/asm/apic.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810635b5)
Location: arch/x86/include/asm/apic.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:sync_Arb_IDs
  - arch/x86/kernel/apic/apic.c:disable_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8289dc4a)
Location: arch/x86/include/asm/apic.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_APIC_field
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81065945)
Location: arch/x86/include/asm/apic.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81069066)
Location: arch/x86/include/asm/apic.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810695e5)
Location: arch/x86/include/asm/apic.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_apic_id_registered
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
```
```
In arch/x86/platform/sfi/sfi.c (ffffffff828a973a)
Location: arch/x86/include/asm/apic.h:390
Inline: True
Inline callers:
  - arch/x86/platform/sfi/sfi.c:sfi_parse_cpus
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
In arch/x86/kernel/irq.c (ffffffff8103442d)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff810525a9)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:mcheck_intel_therm_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff828b2eab)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81066c35)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:sync_Arb_IDs
  - arch/x86/kernel/apic/apic.c:disable_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828b5ae0)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_APIC_field
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810690f5)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106c886)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106ce45)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_apic_id_registered
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
```
```
In arch/x86/platform/sfi/sfi.c (ffffffff828c1dfe)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/platform/sfi/sfi.c:sfi_parse_cpus
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
In arch/x86/kernel/irq.c (ffffffff81034ced)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052e99)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:mcheck_intel_therm_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff828b6301)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810672a5)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
  - arch/x86/kernel/apic/apic.c:sync_Arb_IDs
  - arch/x86/kernel/apic/apic.c:apic_soft_disable
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828b8fa4)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_APIC_field
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81069a75)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106c599)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106d295)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_phys_pkg_id
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106dfd6)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106e5a5)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_apic_id_registered
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
```
```
In arch/x86/platform/sfi/sfi.c (ffffffff828c8254)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/platform/sfi/sfi.c:sfi_parse_cpus
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff81099df5)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_init
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
In arch/x86/kernel/irq.c (ffffffff81036aed)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff82cd5a14)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:mcheck_intel_therm_init
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
```
```
In arch/x86/kernel/smpboot.c (ffffffff82cdb4a4)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106deb5)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:apic_check_and_ack
  - arch/x86/kernel/apic/apic.c:apic_check_and_ack
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:sync_Arb_IDs
  - arch/x86/kernel/apic/apic.c:apic_soft_disable
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:__setup_APIC_LVTT
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/vector.c (ffffffff82cddfaa)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_APIC_field
  - arch/x86/kernel/apic/vector.c:__sysvec_irq_move_cleanup
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810709a5)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8107388b)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074415)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_phys_pkg_id
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075486)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81075c15)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_apic_id_registered
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
```
```
In arch/x86/platform/sfi/sfi.c (ffffffff82ceb353)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/platform/sfi/sfi.c:sfi_parse_cpus
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109f455)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_init
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
In arch/x86/kernel/irq.c (ffffffff81037cdc)
Location: arch/x86/include/asm/apic.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff82fc19bc)
Location: arch/x86/include/asm/apic.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:mcheck_intel_therm_init
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
```
```
In arch/x86/kernel/smpboot.c (ffffffff82fc78fa)
Location: arch/x86/include/asm/apic.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106f655)
Location: arch/x86/include/asm/apic.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:apic_check_and_ack
  - arch/x86/kernel/apic/apic.c:apic_check_and_ack
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:sync_Arb_IDs
  - arch/x86/kernel/apic/apic.c:apic_soft_disable
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:__setup_APIC_LVTT
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/vector.c (ffffffff82fca368)
Location: arch/x86/include/asm/apic.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_APIC_field
  - arch/x86/kernel/apic/vector.c:__sysvec_irq_move_cleanup
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81071ce5)
Location: arch/x86/include/asm/apic.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
```
```
In arch/x86/kernel/apic/msi.c (ffffffff81074689)
Location: arch/x86/include/asm/apic.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074f95)
Location: arch/x86/include/asm/apic.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_phys_pkg_id
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075ac4)
Location: arch/x86/include/asm/apic.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81076245)
Location: arch/x86/include/asm/apic.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_apic_id_registered
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
```
```
In arch/x86/platform/sfi/sfi.c (ffffffff82fd8b84)
Location: arch/x86/include/asm/apic.h:386
Inline: True
Inline callers:
  - arch/x86/platform/sfi/sfi.c:sfi_parse_cpus
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109af95)
Location: arch/x86/include/asm/apic.h:386
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_init
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
In arch/x86/kernel/irq.c (ffffffff8103987c)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/smpboot.c (ffffffff831d2198)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81070185)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:sync_Arb_IDs
  - arch/x86/kernel/apic/apic.c:apic_soft_disable
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:__setup_APIC_LVTT
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/vector.c (ffffffff831d4c8d)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_APIC_field
  - arch/x86/kernel/apic/vector.c:__sysvec_irq_move_cleanup
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810727f5)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
```
```
In arch/x86/kernel/apic/msi.c (ffffffff81075150)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81075a35)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_phys_pkg_id
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81076566)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81076cd5)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_apic_id_registered
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109b745)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_init
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff8321d9ea)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:therm_lvt_init
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_offline
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
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
In arch/x86/kernel/irq.c (ffffffff8103f0e1)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/smpboot.c (ffffffff832b49a5)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8107bca5)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:sync_Arb_IDs
  - arch/x86/kernel/apic/apic.c:apic_soft_disable
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:__setup_APIC_LVTT
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/vector.c (ffffffff832b7807)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_APIC_field
  - arch/x86/kernel/apic/vector.c:__sysvec_irq_move_cleanup
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8107e795)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
```
```
In arch/x86/kernel/apic/msi.c (ffffffff81082600)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81082ff5)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_phys_pkg_id
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81083bda)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810844b5)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_apic_id_registered
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810abab5)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_init
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff83306c60)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:therm_lvt_init
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_offline
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
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
In arch/x86/kernel/irq.c (ffffffff810466f1)
Location: arch/x86/include/asm/apic.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/smpboot.c (ffffffff83466252)
Location: arch/x86/include/asm/apic.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8108aed5)
Location: arch/x86/include/asm/apic.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:apic_pending_intr_clear
  - arch/x86/kernel/apic/apic.c:apic_pending_intr_clear
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:sync_Arb_IDs
  - arch/x86/kernel/apic/apic.c:apic_soft_disable
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/vector.c (ffffffff834698e2)
Location: arch/x86/include/asm/apic.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_APIC_field
  - arch/x86/kernel/apic/vector.c:__sysvec_irq_move_cleanup
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8108df25)
Location: arch/x86/include/asm/apic.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810921da)
Location: arch/x86/include/asm/apic.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81092dd5)
Location: arch/x86/include/asm/apic.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_phys_pkg_id
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81093c2c)
Location: arch/x86/include/asm/apic.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810944b5)
Location: arch/x86/include/asm/apic.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_apic_id_registered
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810c15b5)
Location: arch/x86/include/asm/apic.h:389
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_init
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff834bfeb8)
Location: arch/x86/include/asm/apic.h:389
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:therm_lvt_init
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_offline
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
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
In arch/x86/kernel/irq.c (ffffffff81050751)
Location: arch/x86/include/asm/apic.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/smpboot.c (ffffffff83e89c3f)
Location: arch/x86/include/asm/apic.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8109f0a5)
Location: arch/x86/include/asm/apic.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
  - arch/x86/kernel/apic/apic.c:sync_Arb_IDs
  - arch/x86/kernel/apic/apic.c:apic_soft_disable
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/vector.c (ffffffff83e8e18d)
Location: arch/x86/include/asm/apic.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_APIC_field
  - arch/x86/kernel/apic/vector.c:__sysvec_irq_move_cleanup
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a26b5)
Location: arch/x86/include/asm/apic.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810a71ca)
Location: arch/x86/include/asm/apic.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810a7ff5)
Location: arch/x86/include/asm/apic.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_phys_pkg_id
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810a991c)
Location: arch/x86/include/asm/apic.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810a9df5)
Location: arch/x86/include/asm/apic.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_apic_id_registered
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810ddf65)
Location: arch/x86/include/asm/apic.h:386
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_init
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff83efeb5d)
Location: arch/x86/include/asm/apic.h:386
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:therm_lvt_init
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_offline
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
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
In arch/x86/kernel/irq.c (ffffffff81051481)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109c4d2)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:send_init_sequence
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a2035)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
  - arch/x86/kernel/apic/apic.c:sync_Arb_IDs
  - arch/x86/kernel/apic/apic.c:apic_soft_disable
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/vector.c (ffffffff836b1a2d)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_APIC_field
  - arch/x86/kernel/apic/vector.c:__sysvec_irq_move_cleanup
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a56a5)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810aa42a)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810ab265)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_phys_pkg_id
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810ad1b5)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_apic_id_registered
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e9555)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_init
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff837249cd)
Location: arch/x86/include/asm/apic.h:387
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:therm_lvt_init
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_offline
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
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
In arch/x86/entry/common.c (ffffffff8221b96b)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_int80_emulation
```
```
In arch/x86/kernel/irq.c (ffffffff810586b1)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8107d811)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8107e58f)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/smpboot.c (ffffffff810a3a67)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a8af5)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:apic_read_boot_cpu_id
  - arch/x86/kernel/apic/apic.c:apic_read_boot_cpu_id
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:sync_Arb_IDs
  - arch/x86/kernel/apic/apic.c:disable_local_APIC
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_periodic
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
```
```
In arch/x86/kernel/apic/apic_common.c (ffffffff810a915c)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_common.c:default_init_apic_ldr
  - arch/x86/kernel/apic/apic_common.c:default_apic_id_registered
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff810a9e17)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
```
```
In arch/x86/kernel/apic/vector.c (ffffffff838e209d)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:__vector_cleanup
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff838e324d)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810b14ba)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810b2115)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_phys_pkg_id
```
```
In arch/x86/kernel/vsmp_64.c (ffffffff810cc6c5)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/vsmp_64.c:apicid_phys_pkg_id
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f1755)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_init
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff8395883d)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:therm_lvt_init
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_offline
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
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
In arch/x86/kernel/irq.c (ffffffff81034e4d)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052f99)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:mcheck_intel_therm_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff828a430d)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81066d95)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
  - arch/x86/kernel/apic/apic.c:sync_Arb_IDs
  - arch/x86/kernel/apic/apic.c:apic_soft_disable
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828a6fab)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_APIC_field
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81069565)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106c089)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106cf76)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106d545)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_apic_id_registered
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
```
```
In arch/x86/platform/sfi/sfi.c (ffffffff828b31ec)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/platform/sfi/sfi.c:sfi_parse_cpus
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
In arch/x86/kernel/irq.c (ffffffff8102478d)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff810429c2)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:mcheck_intel_therm_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff8289c44f)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81057165)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
  - arch/x86/kernel/apic/apic.c:sync_Arb_IDs
  - arch/x86/kernel/apic/apic.c:apic_soft_disable
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8289f0a2)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_APIC_field
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810598c5)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105c3a9)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d326)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105d985)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_apic_id_registered
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
```
```
In arch/x86/platform/sfi/sfi.c (ffffffff828ab36d)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/platform/sfi/sfi.c:sfi_parse_cpus
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
In arch/x86/kernel/irq.c (ffffffff81034cad)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052e49)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:mcheck_intel_therm_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff828b721d)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81067245)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
  - arch/x86/kernel/apic/apic.c:sync_Arb_IDs
  - arch/x86/kernel/apic/apic.c:apic_soft_disable
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828b9ebb)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_APIC_field
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81069a15)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106c539)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d426)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106d9f5)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_apic_id_registered
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
```
```
In arch/x86/platform/sfi/sfi.c (ffffffff828c60eb)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/platform/sfi/sfi.c:sfi_parse_cpus
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
In arch/x86/kernel/irq.c (ffffffff81035c03)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff810542c9)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:mcheck_intel_therm_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff828b7319)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81068825)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
  - arch/x86/kernel/apic/apic.c:sync_Arb_IDs
  - arch/x86/kernel/apic/apic.c:apic_soft_disable
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_apic_icr_read
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828b9fd1)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_APIC_field
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b195)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106dc39)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106e9c5)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_phys_pkg_id
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106f6a6)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106fc75)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_apic_id_registered
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
```
```
In arch/x86/platform/sfi/sfi.c (ffffffff828c9291)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/platform/sfi/sfi.c:sfi_parse_cpus
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109b2c5)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_init
```
</details>
</li>
</ul>

## Differences
