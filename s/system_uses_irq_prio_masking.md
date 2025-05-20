# Function: <code>system_uses_irq_prio_masking</code>

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
bool system_uses_irq_prio_masking();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/debug-monitors.c (ffff800010085d3c)
Location: arch/arm64/include/asm/cpufeature.h:604
Inline: True
Inline callers:
  - arch/arm64/kernel/debug-monitors.c:send_user_sigtrap
  - arch/arm64/kernel/debug-monitors.c:mdscr_write
  - arch/arm64/kernel/debug-monitors.c:mdscr_write
  - arch/arm64/kernel/debug-monitors.c:mdscr_write
  - arch/arm64/kernel/debug-monitors.c:mdscr_write
```
```
In arch/arm64/kernel/irq.c (ffff800010086f64)
Location: arch/arm64/include/asm/cpufeature.h:604
Inline: False
Direct callers:
  - arch/arm64/kernel/irq.c:init_IRQ
  - arch/arm64/kernel/irq.c:init_IRQ
```
```
In arch/arm64/kernel/process.c (ffff8000100893b8)
Location: arch/arm64/include/asm/cpufeature.h:604
Inline: True
Inline callers:
  - arch/arm64/kernel/process.c:copy_thread_tls
  - arch/arm64/kernel/process.c:cpu_do_idle
Direct callers:
  - arch/arm64/kernel/process.c:__show_regs
```
```
In arch/arm64/kernel/setup.c (ffff80001008f6cc)
Location: arch/arm64/include/asm/cpufeature.h:604
Inline: False
Direct callers:
  - arch/arm64/kernel/setup.c:setup_arch
```
```
In arch/arm64/kernel/signal.c (ffff8000100932ac)
Location: arch/arm64/include/asm/cpufeature.h:604
Inline: True
Inline callers:
  - arch/arm64/kernel/signal.c:do_notify_resume
  - arch/arm64/kernel/signal.c:do_notify_resume
  - arch/arm64/kernel/signal.c:do_notify_resume
```
```
In arch/arm64/kernel/traps.c (ffff800010095990)
Location: arch/arm64/include/asm/cpufeature.h:604
Inline: True
Inline callers:
  - arch/arm64/kernel/traps.c:bad_mode
```
```
In arch/arm64/kernel/smp.c (ffff80001009c2bc)
Location: arch/arm64/include/asm/cpufeature.h:604
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:secondary_start_kernel
  - arch/arm64/kernel/smp.c:secondary_start_kernel
Direct callers:
  - arch/arm64/kernel/smp.c:smp_prepare_boot_cpu
```
```
In arch/arm64/kernel/syscall.c (ffff80001009d940)
Location: arch/arm64/include/asm/cpufeature.h:604
Inline: True
```
```
In arch/arm64/kernel/suspend.c (ffff8000100a6d9c)
Location: arch/arm64/include/asm/cpufeature.h:604
Inline: True
Inline callers:
  - arch/arm64/kernel/suspend.c:cpu_suspend
  - arch/arm64/kernel/suspend.c:cpu_suspend
  - arch/arm64/kernel/suspend.c:cpu_suspend
  - arch/arm64/kernel/suspend.c:cpu_suspend
```
```
In arch/arm64/kernel/acpi.c (ffff8000100a941c)
Location: arch/arm64/include/asm/cpufeature.h:604
Inline: True
Inline callers:
  - arch/arm64/kernel/acpi.c:apei_claim_sea
  - arch/arm64/kernel/acpi.c:apei_claim_sea
  - arch/arm64/kernel/acpi.c:apei_claim_sea
  - arch/arm64/kernel/acpi.c:apei_claim_sea
```
```
In arch/arm64/kernel/machine_kexec.c (ffff8000100a9cfc)
Location: arch/arm64/include/asm/cpufeature.h:604
Inline: True
Inline callers:
  - arch/arm64/kernel/machine_kexec.c:machine_kexec
```
```
In arch/arm64/kernel/sdei.c (ffff800010da7eb8)
Location: arch/arm64/include/asm/cpufeature.h:604
Inline: True
Inline callers:
  - arch/arm64/kernel/sdei.c:__sdei_handler
```
```
In arch/arm64/mm/fault.c (ffff8000100ad1e8)
Location: arch/arm64/include/asm/cpufeature.h:604
Inline: True
Inline callers:
  - arch/arm64/mm/fault.c:debug_exception_exit
  - arch/arm64/mm/fault.c:debug_exception_enter
  - arch/arm64/mm/fault.c:do_sp_pc_abort
  - arch/arm64/mm/fault.c:do_el0_ia_bp_hardening
```
```
In virt/kvm/arm/arm.c (ffff8000100c6e0c)
Location: arch/arm64/include/asm/cpufeature.h:604
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
```
```
In arch/arm64/kvm/hyp/switch.c (ffff800010daeb70)
Location: arch/arm64/include/asm/cpufeature.h:604
Inline: True
Inline callers:
  - arch/arm64/kvm/hyp/switch.c:__kvm_vcpu_run_nvhe
  - arch/arm64/kvm/hyp/switch.c:__kvm_vcpu_run_nvhe
```
```
In fs/binfmt_elf.c (ffff80001041f900)
Location: arch/arm64/include/asm/cpufeature.h:604
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffff800010423288)
Location: arch/arm64/include/asm/cpufeature.h:604
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In drivers/irqchip/irq-gic-v3.c (ffff80001066f398)
Location: arch/arm64/include/asm/cpufeature.h:604
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_cpu_sys_reg_init
  - drivers/irqchip/irq-gic-v3.c:gic_handle_irq
  - drivers/irqchip/irq-gic-v3.c:gic_handle_irq
Direct callers:
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
```
```
In drivers/xen/events/events_2l.c (ffff80001083321c)
Location: arch/arm64/include/asm/cpufeature.h:604
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
**Symbols:**

```
ffff80001066dc38-ffff80001066dc60: system_uses_irq_prio_masking (STB_LOCAL)
ffff800010086f64-ffff800010086f90: system_uses_irq_prio_masking (STB_LOCAL)
ffff800010088cd0-ffff800010088cf8: system_uses_irq_prio_masking (STB_LOCAL)
ffff80001008f6cc-ffff80001008f6f8: system_uses_irq_prio_masking (STB_LOCAL)
ffff80001009bc60-ffff80001009bc88: system_uses_irq_prio_masking (STB_LOCAL)
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
