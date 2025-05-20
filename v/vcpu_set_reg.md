# Function: <code>vcpu_set_reg</code>

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
In virt/kvm/arm/mmio.c (ffff8000100cd9c0)
Location: arch/arm64/include/asm/kvm_emulate.h:176
Inline: True
Inline callers:
  - virt/kvm/arm/mmio.c:kvm_handle_mmio_return
```
```
In virt/kvm/arm/psci.c (ffff8000100ce544)
Location: arch/arm64/include/asm/kvm_emulate.h:176
Inline: True
Inline callers:
  - virt/kvm/arm/psci.c:kvm_hvc_call_handler
  - virt/kvm/arm/psci.c:kvm_hvc_call_handler
  - virt/kvm/arm/psci.c:kvm_hvc_call_handler
  - virt/kvm/arm/psci.c:kvm_hvc_call_handler
  - virt/kvm/arm/psci.c:kvm_hvc_call_handler
  - virt/kvm/arm/psci.c:kvm_hvc_call_handler
  - virt/kvm/arm/psci.c:kvm_hvc_call_handler
  - virt/kvm/arm/psci.c:kvm_hvc_call_handler
  - virt/kvm/arm/psci.c:kvm_hvc_call_handler
  - virt/kvm/arm/psci.c:kvm_psci_0_2_call
  - virt/kvm/arm/psci.c:kvm_psci_0_2_call
  - virt/kvm/arm/psci.c:kvm_psci_0_2_call
  - virt/kvm/arm/psci.c:kvm_psci_0_2_call
```
```
In arch/arm64/kvm/handle_exit.c (ffff8000100d0350)
Location: arch/arm64/include/asm/kvm_emulate.h:176
Inline: True
Inline callers:
  - arch/arm64/kvm/handle_exit.c:handle_smc
  - arch/arm64/kvm/handle_exit.c:handle_hvc
```
```
In arch/arm64/kvm/reset.c (ffff8000100d4d64)
Location: arch/arm64/include/asm/kvm_emulate.h:176
Inline: True
Inline callers:
  - arch/arm64/kvm/reset.c:kvm_reset_vcpu
```
```
In arch/arm64/kvm/sys_regs.c (ffff8000100d95b8)
Location: arch/arm64/include/asm/kvm_emulate.h:176
Inline: True
Inline callers:
  - arch/arm64/kvm/sys_regs.c:kvm_handle_sys_reg
  - arch/arm64/kvm/sys_regs.c:kvm_handle_cp_32
  - arch/arm64/kvm/sys_regs.c:kvm_handle_cp_64
  - arch/arm64/kvm/sys_regs.c:kvm_handle_cp_64
```
```
In virt/kvm/arm/hyp/vgic-v3-sr.c (ffff800010dabeec)
Location: arch/arm64/include/asm/kvm_emulate.h:176
Inline: True
Inline callers:
  - virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_read_ctlr
  - virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_read_rpr
  - virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_read_pmr
  - virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_read_hppir
  - virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_read_apxrn
  - virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_read_bpr1
  - virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_read_bpr0
  - virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_read_igrpen1
  - virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_read_igrpen0
  - virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_read_iar
  - virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_read_iar
```
```
In arch/arm64/kvm/hyp/vgic-v2-cpuif-proxy.c (ffff800010dad1bc)
Location: arch/arm64/include/asm/kvm_emulate.h:176
Inline: True
Inline callers:
  - arch/arm64/kvm/hyp/vgic-v2-cpuif-proxy.c:__vgic_v2_perform_cpuif_access
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
