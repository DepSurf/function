# Function: <code>scu_a9_get_base</code>

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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/mach-exynos/platsmp.c (c032e510)
Location: arch/arm/include/asm/smp_scu.h:19
Inline: True
Inline callers:
  - arch/arm/mach-exynos/platsmp.c:exynos_scu_enable
```
```
In arch/arm/mach-hisi/platsmp.c (c150cfe8)
Location: arch/arm/include/asm/smp_scu.h:19
Inline: True
Inline callers:
  - arch/arm/mach-hisi/platsmp.c:hisi_enable_scu_a9
```
```
In arch/arm/mach-omap2/omap-smp.c (c1515254)
Location: arch/arm/include/asm/smp_scu.h:19
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap-smp.c:omap4_smp_init_cpus
```
```
In arch/arm/mach-tegra/platsmp.c (c151ac10)
Location: arch/arm/include/asm/smp_scu.h:19
Inline: True
Inline callers:
  - arch/arm/mach-tegra/platsmp.c:tegra_smp_prepare_cpus
  - arch/arm/mach-tegra/platsmp.c:tegra_smp_prepare_cpus
  - arch/arm/mach-tegra/platsmp.c:tegra_smp_prepare_cpus
  - arch/arm/mach-tegra/platsmp.c:tegra_smp_prepare_cpus
  - arch/arm/mach-tegra/platsmp.c:tegra_smp_prepare_cpus
  - arch/arm/mach-tegra/platsmp.c:tegra_smp_prepare_cpus
  - arch/arm/mach-tegra/platsmp.c:tegra_smp_prepare_cpus
  - arch/arm/mach-tegra/platsmp.c:tegra_smp_prepare_cpus
  - arch/arm/mach-tegra/platsmp.c:tegra_smp_prepare_cpus
  - arch/arm/mach-tegra/platsmp.c:tegra_smp_prepare_cpus
  - arch/arm/mach-tegra/platsmp.c:tegra_smp_prepare_cpus
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
