# Function: <code>is_omap3430</code>

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
In arch/arm/mach-omap2/id.c (c15113f0)
Location: arch/arm/mach-omap2/soc.h:233
Inline: True
Inline callers:
  - arch/arm/mach-omap2/id.c:omap3xxx_check_features
```
```
In arch/arm/mach-omap2/display.c (c03366d4)
Location: arch/arm/mach-omap2/soc.h:233
Inline: True
Inline callers:
  - arch/arm/mach-omap2/display.c:omap_dss_reset
```
```
In arch/arm/mach-omap2/pm34xx.c (c033d458)
Location: arch/arm/mach-omap2/soc.h:233
Inline: True
Inline callers:
  - arch/arm/mach-omap2/pm34xx.c:omap_sram_idle
  - arch/arm/mach-omap2/pm34xx.c:omap_sram_idle
```
```
In arch/arm/mach-omap2/cpuidle34xx.c (c15166f8)
Location: arch/arm/mach-omap2/soc.h:233
Inline: True
Inline callers:
  - arch/arm/mach-omap2/cpuidle34xx.c:omap3_idle_init
```
```
In arch/arm/mach-omap2/clock.c (c151808c)
Location: arch/arm/mach-omap2/soc.h:233
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
