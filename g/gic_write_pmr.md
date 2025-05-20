# Function: <code>gic_write_pmr</code>

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
In arch/arm64/kernel/debug-monitors.c (ffff80001008610c)
Location: arch/arm64/include/asm/arch_gicv3.h:112
Inline: True
Inline callers:
  - arch/arm64/kernel/debug-monitors.c:mdscr_write
  - arch/arm64/kernel/debug-monitors.c:mdscr_write
  - arch/arm64/kernel/debug-monitors.c:mdscr_write
```
```
In arch/arm64/kernel/irq.c (ffff800011433838)
Location: arch/arm64/include/asm/arch_gicv3.h:112
Inline: True
Inline callers:
  - arch/arm64/kernel/irq.c:init_IRQ
```
```
In arch/arm64/kernel/process.c (ffff800010088df4)
Location: arch/arm64/include/asm/arch_gicv3.h:112
Inline: True
Inline callers:
  - arch/arm64/kernel/process.c:cpu_do_idle
  - arch/arm64/kernel/process.c:cpu_do_idle
```
```
In arch/arm64/kernel/setup.c (ffff80001143414c)
Location: arch/arm64/include/asm/arch_gicv3.h:112
Inline: True
Inline callers:
  - arch/arm64/kernel/setup.c:setup_arch
```
```
In arch/arm64/kernel/signal.c (ffff800010093474)
Location: arch/arm64/include/asm/arch_gicv3.h:112
Inline: True
Inline callers:
  - arch/arm64/kernel/signal.c:do_notify_resume
  - arch/arm64/kernel/signal.c:do_notify_resume
  - arch/arm64/kernel/signal.c:do_notify_resume
```
```
In arch/arm64/kernel/traps.c (ffff8000100959b0)
Location: arch/arm64/include/asm/arch_gicv3.h:112
Inline: True
Inline callers:
  - arch/arm64/kernel/traps.c:bad_mode
```
```
In arch/arm64/kernel/smp.c (ffff80001009c384)
Location: arch/arm64/include/asm/arch_gicv3.h:112
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:secondary_start_kernel
  - arch/arm64/kernel/smp.c:init_gic_priority_masking
```
```
In arch/arm64/kernel/syscall.c (ffff80001009d99c)
Location: arch/arm64/include/asm/arch_gicv3.h:112
Inline: True
```
```
In arch/arm64/kernel/suspend.c (ffff8000100a6e14)
Location: arch/arm64/include/asm/arch_gicv3.h:112
Inline: True
Inline callers:
  - arch/arm64/kernel/suspend.c:cpu_suspend
  - arch/arm64/kernel/suspend.c:cpu_suspend
  - arch/arm64/kernel/suspend.c:cpu_suspend
```
```
In arch/arm64/kernel/acpi.c (ffff8000100a94bc)
Location: arch/arm64/include/asm/arch_gicv3.h:112
Inline: True
Inline callers:
  - arch/arm64/kernel/acpi.c:apei_claim_sea
  - arch/arm64/kernel/acpi.c:apei_claim_sea
  - arch/arm64/kernel/acpi.c:apei_claim_sea
```
```
In arch/arm64/kernel/machine_kexec.c (ffff8000100a9ef0)
Location: arch/arm64/include/asm/arch_gicv3.h:112
Inline: True
Inline callers:
  - arch/arm64/kernel/machine_kexec.c:machine_kexec
```
```
In arch/arm64/mm/fault.c (ffff8000100815f0)
Location: arch/arm64/include/asm/arch_gicv3.h:112
Inline: True
Inline callers:
  - arch/arm64/mm/fault.c:do_sp_pc_abort
  - arch/arm64/mm/fault.c:do_el0_ia_bp_hardening
```
```
In virt/kvm/arm/arm.c (ffff8000100c6e54)
Location: arch/arm64/include/asm/arch_gicv3.h:112
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
```
```
In arch/arm64/kvm/hyp/switch.c (ffff800010daeb9c)
Location: arch/arm64/include/asm/arch_gicv3.h:112
Inline: True
Inline callers:
  - arch/arm64/kvm/hyp/switch.c:__kvm_vcpu_run_nvhe
  - arch/arm64/kvm/hyp/switch.c:__kvm_vcpu_run_nvhe
```
```
In drivers/irqchip/irq-gic-v3.c (ffff80001066db88)
Location: arch/arm64/include/asm/arch_gicv3.h:112
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_has_group0
  - drivers/irqchip/irq-gic-v3.c:gic_has_group0
  - drivers/irqchip/irq-gic-v3.c:gic_handle_irq
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
In drivers/irqchip/irq-gic-v3.c (c0817674)
Location: arch/arm/include/asm/arch_gicv3.h:243
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_cpu_sys_reg_init
  - drivers/irqchip/irq-gic-v3.c:gic_cpu_sys_reg_init
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
