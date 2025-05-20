# Function: <code>omap_type</code>

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
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int omap_type();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/arm/mach-omap2/id.c (c0334fcc)
Location: arch/arm/mach-omap2/id.c:50
Inline: True
Inline callers:
  - arch/arm/mach-omap2/id.c:omap_get_type
Direct callers:
  - arch/arm/mach-omap2/id.c:omap_get_type
  - arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents
  - arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents
  - arch/arm/mach-omap2/timer.c:__omap_sync32k_timer_init
  - arch/arm/mach-omap2/dma.c:omap2_system_dma_init_dev
  - arch/arm/mach-omap2/dma.c:omap2_system_dma_init_dev
  - arch/arm/mach-omap2/dma.c:omap2_system_dma_init_dev
  - arch/arm/mach-omap2/sram.c:omap_sram_init
  - arch/arm/mach-omap2/sram.c:omap_sram_init
  - arch/arm/mach-omap2/sram.c:omap_sram_init
  - arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_init
  - arch/arm/mach-omap2/pm34xx.c:omap3_pm_init
  - arch/arm/mach-omap2/pm34xx.c:omap3_pm_init
  - arch/arm/mach-omap2/pm34xx.c:omap_sram_idle
  - arch/arm/mach-omap2/pm34xx.c:omap_sram_idle
  - arch/arm/mach-omap2/pm34xx.c:omap_sram_idle
  - arch/arm/mach-omap2/pm34xx.c:omap_sram_idle
  - arch/arm/mach-omap2/pm33xx-core.c:am33xx_suspend_init
  - arch/arm/mach-omap2/clock.c:ti_clk_init_features
  - arch/arm/mach-omap2/omap_hwmod_3xxx_data.c:omap3xxx_hwmod_init
  - arch/arm/mach-omap2/omap_hwmod_3xxx_data.c:omap3xxx_hwmod_is_hs_ip_block_usable
  - arch/arm/mach-omap2/omap_hwmod_7xx_data.c:dra7xx_hwmod_init
  - arch/arm/mach-omap2/pdata-quirks.c:nokia_n900_legacy_init
```
**Symbols:**

```
c0334ecc-c0334f88: omap_type.part.0 (STB_LOCAL)
c0334f88-c0334fb8: omap_type (STB_GLOBAL)
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
