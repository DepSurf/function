# Function: <code>system_supports_address_auth</code>

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
In arch/arm64/kernel/process.c (ffff800010089734)
Location: arch/arm64/include/asm/cpufeature.h:590
Inline: True
Inline callers:
  - arch/arm64/kernel/process.c:arch_setup_new_exec
```
```
In arch/arm64/kernel/ptrace.c (ffff80001008cc00)
Location: arch/arm64/include/asm/cpufeature.h:590
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:pac_address_keys_set
  - arch/arm64/kernel/ptrace.c:pac_address_keys_get
  - arch/arm64/kernel/ptrace.c:pac_mask_get
```
```
In arch/arm64/kernel/pointer_auth.c (ffff8000100ac33c)
Location: arch/arm64/include/asm/cpufeature.h:590
Inline: True
Inline callers:
  - arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys
  - arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys
  - arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys
```
```
In virt/kvm/arm/arm.c (ffff8000100c6558)
Location: arch/arm64/include/asm/cpufeature.h:590
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_load
```
```
In arch/arm64/kvm/handle_exit.c (ffff8000100d1648)
Location: arch/arm64/include/asm/cpufeature.h:590
Inline: True
```
```
In arch/arm64/kvm/reset.c (ffff8000100d4c64)
Location: arch/arm64/include/asm/cpufeature.h:590
Inline: True
Inline callers:
  - arch/arm64/kvm/reset.c:kvm_reset_vcpu
  - arch/arm64/kvm/reset.c:kvm_arch_vm_ioctl_check_extension
```
```
In arch/arm64/kvm/sys_regs.c (ffff8000100d73c0)
Location: arch/arm64/include/asm/cpufeature.h:590
Inline: True
Inline callers:
  - arch/arm64/kvm/sys_regs.c:ptrauth_visibility
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
