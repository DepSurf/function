# Function: <code>soc_is_omap</code>

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
In arch/arm/mach-omap2/id.c (c15110bc)
Location: arch/arm/mach-omap2/soc.h:52
Inline: True
Inline callers:
  - arch/arm/mach-omap2/id.c:__omap_feed_randpool
```
```
In arch/arm/mach-omap2/pm.c (c15133bc)
Location: arch/arm/mach-omap2/soc.h:52
Inline: True
Inline callers:
  - arch/arm/mach-omap2/pm.c:__omap2_common_pm_late_init
```
```
In arch/arm/mach-omap2/dma.c (c1513404)
Location: arch/arm/mach-omap2/soc.h:52
Inline: True
Inline callers:
  - arch/arm/mach-omap2/dma.c:__omap2_system_dma_init
```
```
In arch/arm/mach-omap2/omap_hwmod.c (c1514350)
Location: arch/arm/mach-omap2/soc.h:52
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap_hwmod.c:__omap_hwmod_setup_all
```
```
In arch/arm/mach-omap2/omap_device.c (c15144c4)
Location: arch/arm/mach-omap2/soc.h:52
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap_device.c:__omap_device_late_init
  - arch/arm/mach-omap2/omap_device.c:__omap_device_init
```
```
In arch/arm/mach-omap2/omap4-common.c (c1514c04)
Location: arch/arm/mach-omap2/soc.h:52
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap4-common.c:__omap4_sram_init
```
```
In arch/arm/mach-omap2/pm-debug.c (c151610c)
Location: arch/arm/mach-omap2/soc.h:52
Inline: True
Inline callers:
  - arch/arm/mach-omap2/pm-debug.c:__pm_dbg_init
```
```
In arch/arm/mach-omap2/smartreflex-class3.c (c1516634)
Location: arch/arm/mach-omap2/soc.h:52
Inline: True
Inline callers:
  - arch/arm/mach-omap2/smartreflex-class3.c:__sr_class3_init
```
```
In arch/arm/mach-omap2/omap_phy_internal.c (c1518e20)
Location: arch/arm/mach-omap2/soc.h:52
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
