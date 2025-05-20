# Function: <code>__SCT__apic_call_read</code>

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
<details>
<summary>In <code>6.8</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/entry/common.c:do_int80_emulation
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
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
  - arch/x86/kernel/apic/apic_common.c:default_init_apic_ldr
  - arch/x86/kernel/apic/apic_common.c:default_apic_id_registered
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
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
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unmask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_phys_pkg_id
  - arch/x86/kernel/vsmp_64.c:apicid_phys_pkg_id
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_init
  - drivers/thermal/intel/therm_throt.c:therm_lvt_init
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_offline
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
```
**Symbols:**

```
ffffffff8223ea00-ffffffff8223ea08: __SCT__apic_call_read (STB_GLOBAL)
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
