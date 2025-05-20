# Function: <code>cpu_pm_register_notifier</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
int cpu_pm_register_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu_pm.c (ffff80001025b3b8)
Location: kernel/cpu_pm.c:45
Inline: False
Direct callers:
  - arch/arm64/kernel/fpsimd.c:fpsimd_init
  - virt/kvm/arm/arm.c:kvm_arch_init
  - virt/kvm/arm/arm.c:kvm_arch_init
  - drivers/irqchip/irq-gic.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/firmware/arm_sdei.c:sdei_probe
  - drivers/clocksource/arm_arch_timer.c:arch_timer_register
  - drivers/perf/arm_pmu.c:armpmu_register
```
**Symbols:**

```
ffff80001025b3b8-ffff80001025b3ec: cpu_pm_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cpu_pm_register_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu_pm.c (c048e538)
Location: kernel/cpu_pm.c:45
Inline: False
Direct callers:
  - arch/arm/vfp/vfpmodule.c:vfp_init
  - arch/arm/kernel/hw_breakpoint.c:arch_hw_breakpoint_init
  - arch/arm/mach-mvebu/pmsu.c:mvebu_v7_cpu_pm_init
  - arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_init
  - arch/arm/mach-tegra/irq.c:tegra_init_irq
  - drivers/irqchip/irq-gic.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-vf610-mscm-ir.c:vf610_mscm_ir_of_init
  - drivers/gpio/gpio-omap.c:omap_gpio_probe
  - drivers/clocksource/arm_arch_timer.c:arch_timer_of_init
  - drivers/perf/arm_pmu.c:armpmu_register
```
**Symbols:**

```
c048e538-c048e560: cpu_pm_register_notifier (STB_GLOBAL)
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
<b>Arch</b>
<ul>
</ul>
