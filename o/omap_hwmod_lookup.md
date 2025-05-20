# Function: <code>omap_hwmod_lookup</code>

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
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct omap_hwmod *omap_hwmod_lookup(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm/mach-omap2/omap_hwmod.c (c15143f0)
Location: arch/arm/mach-omap2/omap_hwmod.c:3025
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap_hwmod.c:__omap_hwmod_setup_all
  - arch/arm/mach-omap2/omap_hwmod.c:__omap_hwmod_setup_all
Direct callers:
  - arch/arm/mach-omap2/timer.c:__omap_sync32k_timer_init
  - arch/arm/mach-omap2/timer.c:__omap_sync32k_timer_init
  - arch/arm/mach-omap2/timer.c:omap_dm_timer_init_one
  - arch/arm/mach-omap2/display.c:omap_dss_reset
  - arch/arm/mach-omap2/omap_device.c:omap_device_get_by_hwmod_name
  - arch/arm/mach-omap2/omap_device.c:omap_device_build_from_dt
  - arch/arm/mach-omap2/pm33xx-core.c:am43xx_get_rtc_base_addr
  - arch/arm/mach-omap2/hsmmc.c:omap_hsmmc_init
```
**Symbols:**

```
c0339700-c033972c: omap_hwmod_lookup (STB_GLOBAL)
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
