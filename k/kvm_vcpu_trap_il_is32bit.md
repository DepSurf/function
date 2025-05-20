# Function: <code>kvm_vcpu_trap_il_is32bit</code>

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
In virt/kvm/arm/mmu.c (ffff8000100cc2e0)
Location: arch/arm64/include/asm/kvm_emulate.h:330
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:kvm_handle_guest_abort
```
```
In virt/kvm/arm/mmio.c (ffff8000100cd9d8)
Location: arch/arm64/include/asm/kvm_emulate.h:330
Inline: True
Inline callers:
  - virt/kvm/arm/mmio.c:kvm_handle_mmio_return
```
```
In arch/arm64/kvm/inject_fault.c (ffff8000100cf468)
Location: arch/arm64/include/asm/kvm_emulate.h:330
Inline: True
Inline callers:
  - arch/arm64/kvm/inject_fault.c:kvm_inject_undefined
  - arch/arm64/kvm/inject_fault.c:inject_abt64
```
```
In arch/arm64/kvm/handle_exit.c (ffff8000100d18c4)
Location: arch/arm64/include/asm/kvm_emulate.h:330
Inline: True
Inline callers:
  - arch/arm64/kvm/handle_exit.c:handle_exit
  - arch/arm64/kvm/handle_exit.c:kvm_handle_wfx
  - arch/arm64/kvm/handle_exit.c:handle_smc
```
```
In arch/arm64/kvm/sys_regs.c (ffff8000100d5650)
Location: arch/arm64/include/asm/kvm_emulate.h:330
Inline: True
Inline callers:
  - arch/arm64/kvm/sys_regs.c:perform_access
```
```
In virt/kvm/arm/hyp/vgic-v3-sr.c (ffff800010dacbec)
Location: arch/arm64/include/asm/kvm_emulate.h:330
Inline: True
Inline callers:
  - virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_perform_cpuif_access
```
```
In arch/arm64/kvm/hyp/vgic-v2-cpuif-proxy.c (ffff800010dad114)
Location: arch/arm64/include/asm/kvm_emulate.h:330
Inline: True
Inline callers:
  - arch/arm64/kvm/hyp/vgic-v2-cpuif-proxy.c:__vgic_v2_perform_cpuif_access
  - arch/arm64/kvm/hyp/vgic-v2-cpuif-proxy.c:__vgic_v2_perform_cpuif_access
```
```
In arch/arm64/kvm/hyp/switch.c (ffff800010dae410)
Location: arch/arm64/include/asm/kvm_emulate.h:330
Inline: True
Inline callers:
  - arch/arm64/kvm/hyp/switch.c:handle_tx2_tvm
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
