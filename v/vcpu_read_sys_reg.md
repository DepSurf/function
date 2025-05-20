# Function: <code>vcpu_read_sys_reg</code>

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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
u64 vcpu_read_sys_reg(const struct kvm_vcpu *vcpu, int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kvm/sys_regs.c (ffff8000100d747c)
Location: arch/arm64/kvm/sys_regs.c:68
Inline: True
Inline callers:
  - arch/arm64/kvm/sys_regs.c:access_ccsidr
  - arch/arm64/kvm/sys_regs.c:access_vm_reg
Direct callers:
  - virt/kvm/arm/arm.c:kvm_mpidr_to_vcpu
  - virt/kvm/arm/mmu.c:kvm_toggle_cache
  - virt/kvm/arm/mmu.c:kvm_set_way_flush
  - virt/kvm/arm/mmio.c:io_mem_abort
  - virt/kvm/arm/mmio.c:kvm_handle_mmio_return
  - virt/kvm/arm/psci.c:kvm_psci_0_2_call
  - arch/arm64/kvm/inject_fault.c:kvm_inject_undefined
  - arch/arm64/kvm/inject_fault.c:inject_abt64
  - arch/arm64/kvm/inject_fault.c:get_except64_pstate
  - arch/arm64/kvm/debug.c:kvm_arm_clear_debug
  - arch/arm64/kvm/debug.c:kvm_arm_setup_debug
  - arch/arm64/kvm/debug.c:kvm_arm_setup_debug
  - arch/arm64/kvm/debug.c:kvm_arm_setup_debug
  - arch/arm64/kvm/debug.c:kvm_arm_setup_debug
  - arch/arm64/kvm/debug.c:kvm_arm_setup_debug
  - arch/arm64/kvm/debug.c:kvm_arm_setup_debug
  - arch/arm64/kvm/debug.c:kvm_arm_setup_debug
  - arch/arm64/kvm/reset.c:kvm_reset_vcpu
  - arch/arm64/kvm/sys_regs.c:trap_debug_regs
  - arch/arm64/kvm/sys_regs.c:access_vm_reg
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_v3_dispatch_sgi
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_mmio_read_v3r_typer
```
**Symbols:**

```
ffff8000100d8ea8-ffff8000100d8fc0: vcpu_read_sys_reg (STB_GLOBAL)
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
