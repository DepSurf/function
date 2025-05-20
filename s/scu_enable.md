# Function: <code>scu_enable</code>

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
<summary>In <code>armhf</code>: ✅</summary>

```c
void scu_enable(void *scu_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/smp_scu.c (c03144c8)
Location: arch/arm/kernel/smp_scu.c:38
Inline: False
Direct callers:
  - arch/arm/mach-actions/platsmp.c:s500_smp_prepare_cpus
  - arch/arm/mach-berlin/platsmp.c:berlin_smp_prepare_cpus
  - arch/arm/mach-exynos/platsmp.c:exynos_scu_enable
  - arch/arm/mach-hisi/platsmp.c:hisi_enable_scu_a9
  - arch/arm/mach-meson/platsmp.c:meson_smp_prepare_cpus
  - arch/arm/mach-mvebu/board-v7.c:mvebu_init_irq
  - arch/arm/mach-imx/platsmp.c:imx_smp_prepare_cpus
  - arch/arm/mach-npcm/platsmp.c:npcm7xx_smp_prepare_cpus
  - arch/arm/mach-omap2/omap-smp.c:omap4_smp_prepare_cpus
  - arch/arm/mach-rockchip/platsmp.c:rockchip_smp_prepare_cpus
  - arch/arm/mach-shmobile/platsmp-scu.c:shmobile_smp_scu_prepare_cpus
  - arch/arm/mach-tegra/platsmp.c:tegra_smp_prepare_cpus
  - arch/arm/mach-vexpress/platsmp.c:vexpress_smp_dt_prepare_cpus
```
**Symbols:**

```
c03144c8-c0314560: scu_enable (STB_GLOBAL)
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
