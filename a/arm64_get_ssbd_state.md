# Function: <code>arm64_get_ssbd_state</code>

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
In arch/arm64/kernel/process.c (ffff800010089514)
Location: arch/arm64/include/asm/cpufeature.h:628
Inline: True
Inline callers:
  - arch/arm64/kernel/process.c:__switch_to
  - arch/arm64/kernel/process.c:copy_thread_tls
```
```
In arch/arm64/kernel/cpu_errata.c (ffff800011434dcc)
Location: arch/arm64/include/asm/cpufeature.h:628
Inline: True
Inline callers:
  - arch/arm64/kernel/cpu_errata.c:arm64_enable_wa2_handling
```
```
In arch/arm64/kernel/cpufeature.c (ffff800010099cfc)
Location: arch/arm64/include/asm/cpufeature.h:628
Inline: True
```
```
In arch/arm64/kernel/suspend.c (ffff8000100a6a8c)
Location: arch/arm64/include/asm/cpufeature.h:628
Inline: True
Inline callers:
  - arch/arm64/kernel/suspend.c:__cpu_suspend_exit
```
```
In arch/arm64/kernel/ssbd.c (ffff8000100ac148)
Location: arch/arm64/include/asm/cpufeature.h:628
Inline: True
Inline callers:
  - arch/arm64/kernel/ssbd.c:arch_prctl_spec_ctrl_get
  - arch/arm64/kernel/ssbd.c:arch_prctl_spec_ctrl_set
```
```
In virt/kvm/arm/arm.c (ffff8000100c5b7c)
Location: arch/arm64/include/asm/cpufeature.h:628
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:cpu_hyp_reinit
```
```
In virt/kvm/arm/psci.c (ffff8000100cef34)
Location: arch/arm64/include/asm/cpufeature.h:628
Inline: True
Inline callers:
  - virt/kvm/arm/psci.c:kvm_arm_set_fw_reg
  - virt/kvm/arm/psci.c:kvm_hvc_call_handler
```
```
In arch/arm64/kvm/reset.c (ffff8000100d4c04)
Location: arch/arm64/include/asm/cpufeature.h:628
Inline: True
Inline callers:
  - arch/arm64/kvm/reset.c:kvm_reset_vcpu
```
```
In fs/binfmt_elf.c (ffff80001041f910)
Location: arch/arm64/include/asm/cpufeature.h:628
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffff8000104232ac)
Location: arch/arm64/include/asm/cpufeature.h:628
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
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
