# Function: <code>vcpu_el1_is_32bit</code>

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
In virt/kvm/arm/arm.c (ffff8000100c45c4)
Location: arch/arm64/include/asm/kvm_emulate.h:40
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_vcpu_init
```
```
In arch/arm64/kvm/inject_fault.c (ffff8000100cf3e0)
Location: arch/arm64/include/asm/kvm_emulate.h:40
Inline: True
Inline callers:
  - arch/arm64/kvm/inject_fault.c:kvm_inject_undefined
  - arch/arm64/kvm/inject_fault.c:kvm_inject_pabt
  - arch/arm64/kvm/inject_fault.c:kvm_inject_dabt
```
```
In arch/arm64/kvm/guest.c (ffff8000100d382c)
Location: arch/arm64/include/asm/kvm_emulate.h:40
Inline: True
Inline callers:
  - arch/arm64/kvm/guest.c:kvm_arm_set_reg
  - arch/arm64/kvm/guest.c:kvm_arm_set_reg
```
```
In arch/arm64/kvm/hyp/sysreg-sr.c (ffff800010dad4e8)
Location: arch/arm64/include/asm/kvm_emulate.h:40
Inline: True
Inline callers:
  - arch/arm64/kvm/hyp/sysreg-sr.c:__sysreg32_restore_state
  - arch/arm64/kvm/hyp/sysreg-sr.c:__sysreg32_save_state
```
```
In arch/arm64/kvm/hyp/switch.c (ffff800010daecc0)
Location: arch/arm64/include/asm/kvm_emulate.h:40
Inline: True
Inline callers:
  - arch/arm64/kvm/hyp/switch.c:__kvm_vcpu_run_nvhe
  - arch/arm64/kvm/hyp/switch.c:kvm_vcpu_run_vhe
  - arch/arm64/kvm/hyp/switch.c:__activate_traps_fpsimd32
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
