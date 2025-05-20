# Function: <code>apic_write</code>

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
In arch/x86/events/core.c (ffffffff81005835)
Location: arch/x86/include/asm/apic.h:389
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100c4fc)
Location: arch/x86/include/asm/apic.h:389
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff810127dc)
Location: arch/x86/include/asm/apic.h:389
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff81047a48)
Location: arch/x86/include/asm/apic.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff810499d7)
Location: arch/x86/include/asm/apic.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/smpboot.c (ffffffff81051936)
Location: arch/x86/include/asm/apic.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81052c05)
Location: arch/x86/include/asm/apic.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_next_event
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
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
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:default_init_apic_ldr
  - arch/x86/kernel/apic/apic.c:default_init_apic_ldr
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81f720f5)
Location: arch/x86/include/asm/apic.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105614b)
Location: arch/x86/include/asm/apic.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810590e5)
Location: arch/x86/include/asm/apic.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059685)
Location: arch/x86/include/asm/apic.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059b05)
Location: arch/x86/include/asm/apic.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_self
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a2a5)
Location: arch/x86/include/asm/apic.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
```
```
In arch/x86/kernel/kvm.c (ffffffff81063abf)
Location: arch/x86/include/asm/apic.h:389
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
In arch/x86/events/core.c (ffffffff810073b4)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100c734)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff810121ec)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff81047b2e)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81049b65)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/smpboot.c (ffffffff81051e52)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81f9a46a)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
  - arch/x86/kernel/apic/apic.c:default_init_apic_ldr
  - arch/x86/kernel/apic/apic.c:default_init_apic_ldr
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
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
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_next_event
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81f9a7e5)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81f9b0fe)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81059455)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810598d5)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059da5)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_self
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a4f5)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
```
```
In arch/x86/kernel/kvm.c (ffffffff810636db)
Location: arch/x86/include/asm/apic.h:396
Inline: True
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
In arch/x86/events/core.c (ffffffff810073b4)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100c80f)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff8101231c)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff81049759)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104bf65)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105474f)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81fd5931)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
  - arch/x86/kernel/apic/apic.c:default_init_apic_ldr
  - arch/x86/kernel/apic/apic.c:default_init_apic_ldr
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
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
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_next_event
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81fd5cac)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81fd6637)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105c1e5)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105c685)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105cb65)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_self
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105d305)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
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
In arch/x86/events/core.c (ffffffff810070cd)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100c366)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff8101088c)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff810490ef)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104b5a7)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/smpboot.c (ffffffff810540a1)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
```
```
In arch/x86/kernel/apic/apic.c (ffffffff820b6677)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
  - arch/x86/kernel/apic/apic.c:default_init_apic_ldr
  - arch/x86/kernel/apic/apic.c:default_init_apic_ldr
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
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
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_timer_shutdown
  - arch/x86/kernel/apic/apic.c:lapic_timer_shutdown
  - arch/x86/kernel/apic/apic.c:lapic_next_event
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:__setup_APIC_LVTT
  - arch/x86/kernel/apic/apic.c:__setup_APIC_LVTT
  - arch/x86/kernel/apic/apic.c:__setup_APIC_LVTT
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff820b6af9)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff820b7396)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105b8e5)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105bdb5)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c2a5)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_self
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105ca25)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
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
In arch/x86/events/core.c (ffffffff810074fd)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100c906)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff81010e8c)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104cae6)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104efb7)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/smpboot.c (ffffffff81057e23)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
```
```
In arch/x86/kernel/apic/apic.c (ffffffff826bcea6)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
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
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_timer_shutdown
  - arch/x86/kernel/apic/apic.c:lapic_timer_shutdown
  - arch/x86/kernel/apic/apic.c:lapic_next_event
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:__setup_APIC_LVTT
  - arch/x86/kernel/apic/apic.c:__setup_APIC_LVTT
  - arch/x86/kernel/apic/apic.c:__setup_APIC_LVTT
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff826bd41a)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff826bdd39)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105f9e5)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105fe45)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_self
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81060765)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
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
In arch/x86/events/core.c (ffffffff81007b24)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100d069)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff810118e1)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104f6fc)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81051cd8)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105ab7f)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
```
```
In arch/x86/kernel/apic/apic.c (ffffffff826e6c5d)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
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
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_next_event
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff826e7366)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff826e7aec)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81062af5)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81062f35)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_self
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81063876)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
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
In arch/x86/events/core.c (ffffffff81007a04)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100d75e)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
```
```
In arch/x86/events/intel/p4.c (ffffffff81011f61)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104cdbc)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff8104f358)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/smpboot.c (ffffffff810607ff)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8289d7a6)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
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
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_next_event
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8289deaf)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8289e635)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810687f5)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81068c35)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_self
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81069561)
Location: arch/x86/include/asm/apic.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
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
In arch/x86/events/core.c (ffffffff81007ce4)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100e01e)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
```
```
In arch/x86/events/intel/p4.c (ffffffff810132d4)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104fcec)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052478)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/smpboot.c (ffffffff81063fb2)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810668ca)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
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
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_next_event
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828b5d47)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828b64bd)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106c005)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106c445)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_self
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106cd76)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
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
In arch/x86/events/core.c (ffffffff81007f04)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100e65e)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
```
```
In arch/x86/events/intel/p4.c (ffffffff81013a84)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105067c)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052d68)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064650)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81066f3a)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
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
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_next_event
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828b920b)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828b9980)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106cbb5)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106d2d5)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106db45)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_self
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106e4d6)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff81099e0e)
Location: arch/x86/include/asm/apic.h:401
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
In arch/x86/events/core.c (ffffffff81008f64)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_enable
```
```
In arch/x86/events/intel/core.c (ffffffff8100f791)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
```
```
In arch/x86/events/intel/p4.c (ffffffff810150b4)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8101f794)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81054c2d)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81057d78)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106b032)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106db4a)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
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
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_next_event
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:__setup_APIC_LVTT
  - arch/x86/kernel/apic/apic.c:__setup_APIC_LVTT
  - arch/x86/kernel/apic/apic.c:__setup_APIC_LVTT
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff82cde211)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff82cdedad)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81073e95)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074455)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81075005)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_self
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810759d6)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109f46e)
Location: arch/x86/include/asm/apic.h:401
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
In arch/x86/events/core.c (ffffffff81008014)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_enable
```
```
In arch/x86/events/intel/core.c (ffffffff8100edb1)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
```
```
In arch/x86/events/intel/p4.c (ffffffff81015554)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81020234)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81053b6d)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81056af8)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106cca2)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106f2ca)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
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
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_next_event
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:__setup_APIC_LVTT
  - arch/x86/kernel/apic/apic.c:__setup_APIC_LVTT
  - arch/x86/kernel/apic/apic.c:__setup_APIC_LVTT
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff82fca5cf)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff82fcb154)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810749ff)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074fcf)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8107563f)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_self
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81076006)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109afae)
Location: arch/x86/include/asm/apic.h:391
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
In arch/x86/events/core.c (ffffffff81008884)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_enable
```
```
In arch/x86/events/intel/core.c (ffffffff8100f519)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff810167e3)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff810225b4)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105543d)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106d73c)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106fdfa)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
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
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_next_event
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:__setup_APIC_LVTT
  - arch/x86/kernel/apic/apic.c:__setup_APIC_LVTT
  - arch/x86/kernel/apic/apic.c:__setup_APIC_LVTT
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff831d4ef4)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff831d59eb)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810754ef)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81075a6f)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810760df)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_self
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81076a96)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109b75e)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_init
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff819474b8)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
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
In arch/x86/events/core.c (ffffffff810096a4)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_enable
```
```
In arch/x86/events/intel/core.c (ffffffff810102e9)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff810182ae)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81026414)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105dddd)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
```
```
In arch/x86/kernel/smpboot.c (ffffffff81078e9a)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8107b82a)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
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
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_next_event
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:__setup_APIC_LVTT
  - arch/x86/kernel/apic/apic.c:__setup_APIC_LVTT
  - arch/x86/kernel/apic/apic.c:__setup_APIC_LVTT
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff832b7a50)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff832b8620)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810829bf)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81082f0f)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810836bf)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_self
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810842e0)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810abace)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_init
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff819ec31c)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
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
In arch/x86/events/core.c (ffffffff81008d46)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_enable
```
```
In arch/x86/events/intel/core.c (ffffffff81011909)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff8101a3fb)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8102a511)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8106a52e)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
```
```
In arch/x86/kernel/smpboot.c (ffffffff81087c91)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8108a9da)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
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
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_next_event
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff834696cb)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8346a363)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8109263f)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81092cdf)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810935ef)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_self
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8109443e)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810c15ce)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_init
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81b5230b)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
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
In arch/x86/events/core.c (ffffffff83e64c50)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_enable
```
```
In arch/x86/events/intel/core.c (ffffffff81015769)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff8101e50e)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81031101)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107a34e)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109b621)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8109eaaa)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
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
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_next_event
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff83e8e07b)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff83e8f2a4)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810a76df)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810a7f3f)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810a8bdf)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_self
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810a9d6e)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810ddf7e)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_init
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81cea4cb)
Location: arch/x86/include/asm/apic.h:391
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
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
In arch/x86/events/core.c (ffffffff83685315)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_enable
```
```
In arch/x86/events/intel/core.c (ffffffff81014ff9)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff8101e206)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81031112)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107c5fe)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109c4bb)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:send_init_sequence
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a1a8a)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
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
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_next_event
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff836b191b)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff836b2b44)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810aa93f)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810ab1af)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810abe0f)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_self
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810ad12e)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e956e)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_init
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81d52fff)
Location: arch/x86/include/asm/apic.h:392
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
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
In arch/x86/events/core.c (ffffffff838b44b5)
Location: arch/x86/include/asm/apic.h:399
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_enable
```
```
In arch/x86/events/intel/core.c (ffffffff8101a0b3)
Location: arch/x86/include/asm/apic.h:399
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff810242d6)
Location: arch/x86/include/asm/apic.h:399
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81037412)
Location: arch/x86/include/asm/apic.h:399
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81083af9)
Location: arch/x86/include/asm/apic.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
```
```
In arch/x86/kernel/smpboot.c (ffffffff810a3a5b)
Location: arch/x86/include/asm/apic.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a8b0f)
Location: arch/x86/include/asm/apic.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:sync_Arb_IDs
  - arch/x86/kernel/apic/apic.c:disable_local_APIC
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_periodic
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_periodic
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_periodic
  - arch/x86/kernel/apic/apic.c:lapic_next_event
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
```
```
In arch/x86/kernel/apic/apic_common.c (ffffffff810a9145)
Location: arch/x86/include/asm/apic.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_common.c:default_init_apic_ldr
  - arch/x86/kernel/apic/apic_common.c:default_init_apic_ldr
```
```
In arch/x86/kernel/apic/vector.c (ffffffff838e22c0)
Location: arch/x86/include/asm/apic.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff838e3444)
Location: arch/x86/include/asm/apic.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810b1ad8)
Location: arch/x86/include/asm/apic.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810b2b78)
Location: arch/x86/include/asm/apic.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_self
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f1763)
Location: arch/x86/include/asm/apic.h:399
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_init
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81e09d8f)
Location: arch/x86/include/asm/apic.h:399
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
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
In arch/x86/events/core.c (ffffffff81007f04)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100e65e)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
```
```
In arch/x86/events/intel/p4.c (ffffffff81013a84)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105077c)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052e68)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064140)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81066a2a)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
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
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_next_event
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828a7212)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828a7998)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106c6a5)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106cae5)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_self
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106d476)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
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
In arch/x86/events/core.c (ffffffff810066f4)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100d30e)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
```
```
In arch/x86/events/intel/p4.c (ffffffff81012c6f)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8103fdc9)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff810428bf)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054440)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81056dfa)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
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
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_next_event
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8289f327)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8289fa62)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105c955)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105cdf5)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_self
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105d8b6)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
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
In arch/x86/events/core.c (ffffffff81007ec4)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100e61e)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
```
```
In arch/x86/events/intel/p4.c (ffffffff81013a44)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105062c)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052d18)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/smpboot.c (ffffffff810645f0)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81066eda)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
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
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_next_event
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828ba122)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828ba897)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106cb55)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106cf95)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_self
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106d926)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
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
In arch/x86/events/core.c (ffffffff81008024)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100e7ee)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
```
```
In arch/x86/events/intel/p4.c (ffffffff81013c64)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81051a6c)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81054198)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/smpboot.c (ffffffff81065bb0)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810684ba)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:disconnect_bsp_APIC
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
  - arch/x86/kernel/apic/apic.c:init_bsp_APIC
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
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_next_event
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828ba238)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828ba9ad)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106e255)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106e935)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_self
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106f215)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_self
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106fba6)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
  - arch/x86/kernel/apic/apic_flat_64.c:flat_init_apic_ldr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109b2de)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_init
```
</details>
</li>
</ul>

## Differences
