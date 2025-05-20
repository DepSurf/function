# Function: <code>local_daif_restore</code>

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
In arch/arm64/kernel/debug-monitors.c (ffff8000100860c0)
Location: arch/arm64/include/asm/daifflags.h:65
Inline: True
Inline callers:
  - arch/arm64/kernel/debug-monitors.c:mdscr_write
```
```
In arch/arm64/kernel/irq.c (ffff80001143382c)
Location: arch/arm64/include/asm/daifflags.h:65
Inline: True
Inline callers:
  - arch/arm64/kernel/irq.c:init_IRQ
```
```
In arch/arm64/kernel/setup.c (ffff800011434140)
Location: arch/arm64/include/asm/daifflags.h:65
Inline: True
Inline callers:
  - arch/arm64/kernel/setup.c:setup_arch
```
```
In arch/arm64/kernel/signal.c (ffff8000100932ac)
Location: arch/arm64/include/asm/daifflags.h:65
Inline: True
Inline callers:
  - arch/arm64/kernel/signal.c:do_notify_resume
  - arch/arm64/kernel/signal.c:do_notify_resume
```
```
In arch/arm64/kernel/smp.c (ffff80001009c340)
Location: arch/arm64/include/asm/daifflags.h:65
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:secondary_start_kernel
```
```
In arch/arm64/kernel/syscall.c (ffff80001009d940)
Location: arch/arm64/include/asm/daifflags.h:65
Inline: True
```
```
In arch/arm64/kernel/suspend.c (ffff8000100a6e68)
Location: arch/arm64/include/asm/daifflags.h:65
Inline: True
Inline callers:
  - arch/arm64/kernel/suspend.c:cpu_suspend
```
```
In arch/arm64/kernel/acpi.c (ffff8000100a9424)
Location: arch/arm64/include/asm/daifflags.h:65
Inline: True
Inline callers:
  - arch/arm64/kernel/acpi.c:apei_claim_sea
  - arch/arm64/kernel/acpi.c:apei_claim_sea
```
```
In arch/arm64/mm/fault.c (ffff8000100815a8)
Location: arch/arm64/include/asm/daifflags.h:65
Inline: True
Inline callers:
  - arch/arm64/mm/fault.c:do_sp_pc_abort
  - arch/arm64/mm/fault.c:do_el0_ia_bp_hardening
```
```
In virt/kvm/arm/arm.c (ffff8000100c6e28)
Location: arch/arm64/include/asm/daifflags.h:65
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
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
