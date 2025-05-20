# Function: <code>is_hyp_mode_available</code>

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
In arch/arm64/kernel/fpsimd.c (ffff800010087aec)
Location: arch/arm64/include/asm/virt.h:69
Inline: True
Inline callers:
  - arch/arm64/kernel/fpsimd.c:sve_verify_vq_map
```
```
In arch/arm64/kernel/cpu_errata.c (ffff800010098640)
Location: arch/arm64/include/asm/virt.h:69
Inline: True
```
```
In arch/arm64/kernel/smp.c (ffff8000114358a0)
Location: arch/arm64/include/asm/virt.h:69
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:smp_cpus_done
```
```
In arch/arm64/kernel/machine_kexec.c (ffff8000100a9d20)
Location: arch/arm64/include/asm/virt.h:69
Inline: True
Inline callers:
  - arch/arm64/kernel/machine_kexec.c:machine_kexec
```
```
In arch/arm64/kernel/sdei.c (ffff8000100abda4)
Location: arch/arm64/include/asm/virt.h:69
Inline: True
Inline callers:
  - arch/arm64/kernel/sdei.c:sdei_arch_get_entry_point
```
```
In virt/kvm/arm/arm.c (ffff8000100c7e64)
Location: arch/arm64/include/asm/virt.h:69
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_arch_init
```
```
In drivers/irqchip/irq-gic.c (ffff8000114718dc)
Location: arch/arm64/include/asm/virt.h:69
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_v2_acpi_init
  - drivers/irqchip/irq-gic.c:gic_of_init
```
```
In drivers/irqchip/irq-gic-v3.c (ffff800011472cb4)
Location: arch/arm64/include/asm/virt.h:69
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
```
```
In drivers/clocksource/arm_arch_timer.c (ffff8000114a8c04)
Location: arch/arm64/include/asm/virt.h:69
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_select_ppi
  - drivers/clocksource/arm_arch_timer.c:arch_timer_common_init
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/reboot.c (c030d268)
Location: arch/arm/include/asm/virt.h:53
Inline: True
Inline callers:
  - arch/arm/kernel/reboot.c:__soft_restart
```
```
In arch/arm/kernel/setup.c (c15047c0)
Location: arch/arm/include/asm/virt.h:53
Inline: True
Inline callers:
  - arch/arm/kernel/setup.c:hyp_mode_check
```
```
In drivers/irqchip/irq-gic.c (c154ae80)
Location: arch/arm/include/asm/virt.h:53
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_of_init
```
```
In drivers/irqchip/irq-gic-v3.c (c154b770)
Location: arch/arm/include/asm/virt.h:53
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
```
```
In drivers/clocksource/arm_arch_timer.c (c15ad0ec)
Location: arch/arm/include/asm/virt.h:53
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_of_init
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
