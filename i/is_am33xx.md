# Function: <code>is_am33xx</code>

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
In arch/arm/mach-omap2/id.c (c1511d1c)
Location: arch/arm/mach-omap2/soc.h:145
Inline: True
Inline callers:
  - arch/arm/mach-omap2/id.c:omap_soc_device_init
```
```
In arch/arm/mach-omap2/timer.c (c1512fa0)
Location: arch/arm/mach-omap2/soc.h:145
Inline: True
Inline callers:
  - arch/arm/mach-omap2/timer.c:__omap_sync32k_timer_init
```
```
In arch/arm/mach-omap2/omap_hwmod.c (c1513868)
Location: arch/arm/mach-omap2/soc.h:145
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_init
```
```
In arch/arm/mach-omap2/pm33xx-core.c (c1516078)
Location: arch/arm/mach-omap2/soc.h:145
Inline: True
Inline callers:
  - arch/arm/mach-omap2/pm33xx-core.c:amx3_common_pm_init
  - arch/arm/mach-omap2/pm33xx-core.c:amx3_get_sram_addrs
```
```
In arch/arm/mach-omap2/clock.c (c15180fc)
Location: arch/arm/mach-omap2/soc.h:145
Inline: True
Inline callers:
  - arch/arm/mach-omap2/clock.c:ti_clk_init_features
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
