# Function: <code>arch_send_wakeup_ipi_mask</code>

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
void arch_send_wakeup_ipi_mask(const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/smp.c (ffff80001009c8e0)
Location: arch/arm64/kernel/smp.c:816
Inline: False
Direct callers:
  - arch/arm64/kernel/acpi_parking_protocol.c:acpi_parking_protocol_cpu_boot
```
**Symbols:**

```
ffff80001009c8e0-ffff80001009c9b4: arch_send_wakeup_ipi_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void arch_send_wakeup_ipi_mask(const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/smp.c (c0312e88)
Location: arch/arm/kernel/smp.c:561
Inline: False
Direct callers:
  - arch/arm/common/mcpm_platsmp.c:mcpm_boot_secondary
  - arch/arm/mach-exynos/platsmp.c:exynos_boot_secondary
  - arch/arm/mach-hisi/platmcpm.c:hip04_boot_secondary
  - arch/arm/mach-hisi/platsmp.c:hix5hd2_boot_secondary
  - arch/arm/mach-hisi/platsmp.c:hi3xxx_boot_secondary
  - arch/arm/mach-mvebu/platsmp.c:mv98dx3236_boot_secondary
  - arch/arm/mach-mvebu/platsmp.c:armada_xp_boot_secondary
  - arch/arm/mach-mvebu/platsmp-a9.c:mvebu_cortex_a9_boot_secondary
  - arch/arm/mach-imx/platsmp.c:ls1021a_boot_secondary
  - arch/arm/mach-mediatek/platsmp.c:mtk_boot_secondary
  - arch/arm/mach-milbeaut/platsmp.c:m10v_boot_secondary
  - arch/arm/mach-omap2/omap-smp.c:omap4_boot_secondary
  - arch/arm/mach-qcom/platsmp.c:qcom_boot_secondary
  - arch/arm/mach-shmobile/smp-emev2.c:emev2_boot_secondary
  - arch/arm/plat-versatile/platsmp.c:versatile_boot_secondary
  - drivers/soc/renesas/r9a06g032-smp.c:r9a06g032_smp_boot_secondary
```
**Symbols:**

```
c0312e88-c0312fb0: arch_send_wakeup_ipi_mask (STB_GLOBAL)
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
