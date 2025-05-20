# Function: <code>is_kernel_in_hyp_mode</code>

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
In arch/arm64/kernel/irq.c (ffff800010086e2c)
Location: arch/arm64/include/asm/virt.h:81
Inline: True
```
```
In arch/arm64/kernel/ptrace.c (ffff80001008a19c)
Location: arch/arm64/include/asm/virt.h:81
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:ptrace_hbp_get_ctrl
```
```
In arch/arm64/kernel/traps.c (ffff800010095768)
Location: arch/arm64/include/asm/virt.h:81
Inline: True
Inline callers:
  - arch/arm64/kernel/traps.c:do_serror
  - arch/arm64/kernel/traps.c:do_serror
```
```
In arch/arm64/kernel/cpu_errata.c (ffff800010098368)
Location: arch/arm64/include/asm/virt.h:81
Inline: True
Inline callers:
  - arch/arm64/kernel/cpu_errata.c:has_cortex_a76_erratum_1463225
```
```
In arch/arm64/kernel/cpufeature.c (ffff8000100992b8)
Location: arch/arm64/include/asm/virt.h:81
Inline: True
Inline callers:
  - arch/arm64/kernel/cpufeature.c:runs_at_el2
```
```
In arch/arm64/kernel/perf_event.c (ffff8000100a3b54)
Location: arch/arm64/include/asm/virt.h:81
Inline: True
Inline callers:
  - arch/arm64/kernel/perf_event.c:armv8pmu_set_event_filter
```
```
In arch/arm64/kernel/hw_breakpoint.c (ffff8000100a5d6c)
Location: arch/arm64/include/asm/virt.h:81
Inline: True
Inline callers:
  - arch/arm64/kernel/hw_breakpoint.c:hw_breakpoint_control
```
```
In arch/arm64/kernel/acpi.c (ffff8000100a9434)
Location: arch/arm64/include/asm/virt.h:81
Inline: True
Inline callers:
  - arch/arm64/kernel/acpi.c:apei_claim_sea
  - arch/arm64/kernel/acpi.c:apei_claim_sea
```
```
In arch/arm64/kernel/machine_kexec.c (ffff8000100a9d14)
Location: arch/arm64/include/asm/virt.h:81
Inline: True
Inline callers:
  - arch/arm64/kernel/machine_kexec.c:machine_kexec
```
```
In arch/arm64/kernel/sdei.c (ffff800010da7d08)
Location: arch/arm64/include/asm/virt.h:81
Inline: True
Inline callers:
  - arch/arm64/kernel/sdei.c:__sdei_handler
  - arch/arm64/kernel/sdei.c:__sdei_handler
  - arch/arm64/kernel/sdei.c:sdei_arch_get_entry_point
```
```
In arch/arm64/kernel/probes/kprobes.c (ffff800011436f9c)
Location: arch/arm64/include/asm/virt.h:81
Inline: True
Inline callers:
  - arch/arm64/kernel/probes/kprobes.c:arch_populate_kprobe_blacklist
```
```
In virt/kvm/arm/arm.c (ffff8000100c7ec8)
Location: arch/arm64/include/asm/virt.h:81
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_arch_init
  - virt/kvm/arm/arm.c:init_hyp_mode
  - virt/kvm/arm/arm.c:init_hyp_mode
  - virt/kvm/arm/arm.c:init_hyp_mode
  - virt/kvm/arm/arm.c:init_hyp_mode
  - virt/kvm/arm/arm.c:init_hyp_mode
  - virt/kvm/arm/arm.c:init_hyp_mode
  - virt/kvm/arm/arm.c:init_hyp_mode
  - virt/kvm/arm/arm.c:cpu_hyp_reinit
  - virt/kvm/arm/arm.c:cpu_hyp_reinit
  - virt/kvm/arm/arm.c:cpu_hyp_reinit
  - virt/kvm/arm/arm.c:cpu_hyp_reinit
  - virt/kvm/arm/arm.c:cpu_hyp_reinit
  - virt/kvm/arm/arm.c:cpu_hyp_reinit
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_vcpu_init
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_load
```
```
In virt/kvm/arm/mmu.c (ffff8000100caf24)
Location: arch/arm64/include/asm/virt.h:81
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:create_hyp_exec_mappings
  - virt/kvm/arm/mmu.c:create_hyp_io_mappings
  - virt/kvm/arm/mmu.c:create_hyp_mappings
```
```
In arch/arm64/kvm/va_layout.c (ffff8000100cf9c0)
Location: arch/arm64/include/asm/virt.h:81
Inline: True
Inline callers:
  - arch/arm64/kvm/va_layout.c:kvm_patch_vector_branch
```
```
In arch/arm64/kvm/debug.c (ffff8000100d3de0)
Location: arch/arm64/include/asm/virt.h:81
Inline: True
Inline callers:
  - arch/arm64/kvm/debug.c:kvm_arm_init_debug
```
```
In virt/kvm/arm/vgic/vgic-init.c (ffff8000100de328)
Location: arch/arm64/include/asm/virt.h:81
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-init.c:kvm_vgic_init_cpu_hardware
```
```
In virt/kvm/arm/vgic/vgic-v3.c (ffff8000100e0688)
Location: arch/arm64/include/asm/virt.h:81
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_put
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_vmcr_sync
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_load
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_load
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_probe
```
```
In virt/kvm/arm/arch_timer.c (ffff8000100ec7e4)
Location: arch/arm64/include/asm/virt.h:81
Inline: True
Inline callers:
  - virt/kvm/arm/arch_timer.c:set_cntvoff
```
```
In arch/arm64/kvm/hyp/switch.c (ffff8000100efc74)
Location: arch/arm64/include/asm/virt.h:81
Inline: True
Inline callers:
  - arch/arm64/kvm/hyp/switch.c:activate_traps_vhe
  - arch/arm64/kvm/hyp/switch.c:activate_traps_vhe
```
```
In drivers/irqchip/irq-gic-v3.c (ffff800010081a64)
Location: arch/arm64/include/asm/virt.h:81
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_handle_irq
  - drivers/irqchip/irq-gic-v3.c:gic_handle_irq
```
```
In drivers/clocksource/arm_arch_timer.c (ffff8000114a8c74)
Location: arch/arm64/include/asm/virt.h:81
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_populate_kvm_info
  - drivers/clocksource/arm_arch_timer.c:arch_timer_select_ppi
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clocksource/arm_arch_timer.c (0)
Location: arch/arm/include/asm/virt.h:65
Inline: True
```
</details>
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
