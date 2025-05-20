# Function: <code>is_omap44xx</code>

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
In arch/arm/mach-omap2/id.c (c0335020)
Location: arch/arm/mach-omap2/soc.h:142
Inline: True
```
```
In arch/arm/mach-omap2/control.c (c0335298)
Location: arch/arm/mach-omap2/soc.h:142
Inline: True
Inline callers:
  - arch/arm/mach-omap2/control.c:omap_ctrl_write_dsp_boot_addr
```
```
In arch/arm/mach-omap2/omap_hwmod.c (c1513734)
Location: arch/arm/mach-omap2/soc.h:142
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_init
```
```
In arch/arm/mach-omap2/omap_twl.c (c1514a9c)
Location: arch/arm/mach-omap2/soc.h:142
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap_twl.c:omap4_twl_init
```
```
In arch/arm/mach-omap2/omap4-common.c (c1514e10)
Location: arch/arm/mach-omap2/soc.h:142
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap4-common.c:omap4_sar_ram_init
  - arch/arm/mach-omap2/omap4-common.c:__omap4_sram_init
```
```
In arch/arm/mach-omap2/omap-wakeupgen.c (c151504c)
Location: arch/arm/mach-omap2/soc.h:142
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_init
```
```
In arch/arm/mach-omap2/omap-smp.c (c1515448)
Location: arch/arm/mach-omap2/soc.h:142
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap-smp.c:omap4_smp_prepare_cpus
```
```
In arch/arm/mach-omap2/omap-mpuss-lowpower.c (c15157fc)
Location: arch/arm/mach-omap2/soc.h:142
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_early_init
  - arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_early_init
  - arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_early_init
  - arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_init
  - arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_init
  - arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_init
```
```
In arch/arm/mach-omap2/pm44xx.c (c1515f44)
Location: arch/arm/mach-omap2/soc.h:142
Inline: True
Inline callers:
  - arch/arm/mach-omap2/pm44xx.c:omap4_pm_init
  - arch/arm/mach-omap2/pm44xx.c:omap4_pm_init
  - arch/arm/mach-omap2/pm44xx.c:omap4_pm_init
```
```
In arch/arm/mach-omap2/sr_device.c (c1516508)
Location: arch/arm/mach-omap2/soc.h:142
Inline: True
Inline callers:
  - arch/arm/mach-omap2/sr_device.c:sr_dev_init
  - arch/arm/mach-omap2/sr_device.c:sr_set_nvalues
```
```
In arch/arm/mach-omap2/vc.c (c1517410)
Location: arch/arm/mach-omap2/soc.h:142
Inline: True
Inline callers:
  - arch/arm/mach-omap2/vc.c:omap_vc_init_channel
  - arch/arm/mach-omap2/vc.c:omap_vc_init_channel
```
```
In arch/arm/mach-omap2/powerdomain.c (c0344db0)
Location: arch/arm/mach-omap2/soc.h:142
Inline: True
Inline callers:
  - arch/arm/mach-omap2/powerdomain.c:pwrdm_register_pwrdms
```
```
In arch/arm/mach-omap2/clock.c (c151811c)
Location: arch/arm/mach-omap2/soc.h:142
Inline: True
Inline callers:
  - arch/arm/mach-omap2/clock.c:ti_clk_init_features
```
```
In arch/arm/mach-omap2/omap_phy_internal.c (c1518e2c)
Location: arch/arm/mach-omap2/soc.h:142
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap_phy_internal.c:__omap4430_phy_power_down
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
