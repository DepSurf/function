# Function: <code>has_vhe</code>

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
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool has_vhe();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/perf_event.c (ffff8000100a4aec)
Location: arch/arm64/include/asm/virt.h:86
Inline: True
Inline callers:
  - arch/arm64/kernel/perf_event.c:armv8pmu_disable_event
  - arch/arm64/kernel/perf_event.c:armv8pmu_enable_event
  - arch/arm64/kernel/perf_event.c:armv8pmu_enable_event
```
```
In virt/kvm/arm/arm.c (ffff8000100c5b10)
Location: arch/arm64/include/asm/virt.h:86
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:cpu_hyp_reinit
  - virt/kvm/arm/arm.c:cpu_hyp_reinit
  - virt/kvm/arm/arm.c:cpu_hyp_reinit
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_load
  - virt/kvm/arm/arm.c:kvm_arch_free_vm
  - virt/kvm/arm/arm.c:kvm_arch_alloc_vm
```
```
In virt/kvm/arm/mmu.c (ffff8000100c83ec)
Location: arch/arm64/include/asm/virt.h:86
Inline: True
```
```
In arch/arm64/kvm/va_layout.c (ffff8000100cf94c)
Location: arch/arm64/include/asm/virt.h:86
Inline: True
Inline callers:
  - arch/arm64/kvm/va_layout.c:kvm_patch_vector_branch
Direct callers:
  - arch/arm64/kvm/va_layout.c:kvm_update_va_mask
  - arch/arm64/kvm/va_layout.c:kvm_update_va_mask
```
```
In arch/arm64/kvm/debug.c (ffff8000100d3f1c)
Location: arch/arm64/include/asm/virt.h:86
Inline: True
Inline callers:
  - arch/arm64/kvm/debug.c:kvm_arm_setup_debug
  - arch/arm64/kvm/debug.c:kvm_arm_init_debug
```
```
In arch/arm64/kvm/reset.c (ffff8000100d4b90)
Location: arch/arm64/include/asm/virt.h:86
Inline: True
Inline callers:
  - arch/arm64/kvm/reset.c:kvm_reset_vcpu
  - arch/arm64/kvm/reset.c:kvm_reset_vcpu
  - arch/arm64/kvm/reset.c:kvm_arch_vm_ioctl_check_extension
```
```
In arch/arm64/kvm/pmu.c (ffff8000100db3b0)
Location: arch/arm64/include/asm/virt.h:86
Inline: True
Inline callers:
  - arch/arm64/kvm/pmu.c:kvm_vcpu_pmu_restore_host
  - arch/arm64/kvm/pmu.c:kvm_vcpu_pmu_restore_guest
  - arch/arm64/kvm/pmu.c:kvm_set_pmu_events
```
```
In virt/kvm/arm/vgic/vgic.c (ffff8000100dd140)
Location: arch/arm64/include/asm/virt.h:86
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_flush_hwstate
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_sync_hwstate
```
```
In virt/kvm/arm/vgic/vgic-init.c (ffff8000100de320)
Location: arch/arm64/include/asm/virt.h:86
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-init.c:kvm_vgic_init_cpu_hardware
```
```
In virt/kvm/arm/vgic/vgic-v3.c (ffff8000100e0680)
Location: arch/arm64/include/asm/virt.h:86
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_put
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_put
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_vmcr_sync
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_load
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_load
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_load
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_probe
```
```
In virt/kvm/arm/arch_timer.c (ffff8000100edae0)
Location: arch/arm64/include/asm/virt.h:86
Inline: True
Inline callers:
  - virt/kvm/arm/arch_timer.c:kvm_timer_hyp_init
  - virt/kvm/arm/arch_timer.c:set_cntvoff
  - virt/kvm/arm/arch_timer.c:get_timer_map
```
```
In virt/kvm/arm/hyp/vgic-v3-sr.c (ffff800010dac908)
Location: arch/arm64/include/asm/virt.h:86
Inline: True
Inline callers:
  - virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_activate_traps
  - virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_restore_state
  - virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_save_state
```
```
In arch/arm64/kvm/hyp/sysreg-sr.c (ffff8000100efaa8)
Location: arch/arm64/include/asm/virt.h:86
Inline: True
Inline callers:
  - arch/arm64/kvm/hyp/sysreg-sr.c:kvm_vcpu_put_sysregs
  - arch/arm64/kvm/hyp/sysreg-sr.c:kvm_vcpu_load_sysregs
  - arch/arm64/kvm/hyp/sysreg-sr.c:__sysreg32_restore_state
  - arch/arm64/kvm/hyp/sysreg-sr.c:__sysreg32_save_state
```
```
In arch/arm64/kvm/hyp/debug-sr.c (ffff800010dae018)
Location: arch/arm64/include/asm/virt.h:86
Inline: True
Inline callers:
  - arch/arm64/kvm/hyp/debug-sr.c:__debug_switch_to_host
  - arch/arm64/kvm/hyp/debug-sr.c:__debug_switch_to_guest
```
```
In arch/arm64/kvm/hyp/switch.c (ffff800010dae7a0)
Location: arch/arm64/include/asm/virt.h:86
Inline: True
Inline callers:
  - arch/arm64/kvm/hyp/switch.c:fixup_guest_exit
  - arch/arm64/kvm/hyp/switch.c:__activate_traps
  - arch/arm64/kvm/hyp/switch.c:activate_traps_vhe
Direct callers:
  - arch/arm64/kvm/hyp/switch.c:hyp_panic
```
```
In arch/arm64/kvm/hyp/tlb.c (ffff800010daf0c0)
Location: arch/arm64/include/asm/virt.h:86
Inline: True
Inline callers:
  - arch/arm64/kvm/hyp/tlb.c:__kvm_tlb_flush_vmid_ipa
  - arch/arm64/kvm/hyp/tlb.c:__tlb_switch_to_guest
```
**Symbols:**

```
ffff8000100cf7d0-ffff8000100cf7f8: has_vhe (STB_LOCAL)
ffff8000100efb58-ffff8000100efb80: has_vhe (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
