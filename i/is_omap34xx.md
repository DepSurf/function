# Function: <code>is_omap34xx</code>

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
In arch/arm/mach-omap2/id.c (c1511cd4)
Location: arch/arm/mach-omap2/soc.h:141
Inline: True
Inline callers:
  - arch/arm/mach-omap2/id.c:omap_soc_device_init
  - arch/arm/mach-omap2/id.c:omap2_set_globals_tap
```
```
In arch/arm/mach-omap2/io.c (c1512320)
Location: arch/arm/mach-omap2/soc.h:141
Inline: True
Inline callers:
  - arch/arm/mach-omap2/io.c:omap_sdrc_init
```
```
In arch/arm/mach-omap2/control.c (c03352d8)
Location: arch/arm/mach-omap2/soc.h:141
Inline: True
Inline callers:
  - arch/arm/mach-omap2/control.c:omap_ctrl_write_dsp_boot_mode
  - arch/arm/mach-omap2/control.c:omap_ctrl_write_dsp_boot_addr
```
```
In arch/arm/mach-omap2/fb.c (c15126f0)
Location: arch/arm/mach-omap2/soc.h:141
Inline: True
Inline callers:
  - arch/arm/mach-omap2/fb.c:omap_init_vrfb
```
```
In arch/arm/mach-omap2/timer.c (c1512ec0)
Location: arch/arm/mach-omap2/soc.h:141
Inline: True
Inline callers:
  - arch/arm/mach-omap2/timer.c:__omap_sync32k_timer_init
```
```
In arch/arm/mach-omap2/pm.c (c03360dc)
Location: arch/arm/mach-omap2/soc.h:141
Inline: True
Inline callers:
  - arch/arm/mach-omap2/pm.c:omap_pm_wake
  - arch/arm/mach-omap2/pm.c:omap_pm_begin
```
```
In arch/arm/mach-omap2/dma.c (c1513488)
Location: arch/arm/mach-omap2/soc.h:141
Inline: True
Inline callers:
  - arch/arm/mach-omap2/dma.c:omap2_system_dma_init_dev
  - arch/arm/mach-omap2/dma.c:omap2_system_dma_init_dev
  - arch/arm/mach-omap2/dma.c:omap2_system_dma_init_dev
```
```
In arch/arm/mach-omap2/i2c.c (c03368f8)
Location: arch/arm/mach-omap2/soc.h:141
Inline: True
Inline callers:
  - arch/arm/mach-omap2/i2c.c:omap_i2c_reset
```
```
In arch/arm/mach-omap2/omap_hwmod.c (c15136dc)
Location: arch/arm/mach-omap2/soc.h:141
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_init
```
```
In arch/arm/mach-omap2/sram.c (c1514930)
Location: arch/arm/mach-omap2/soc.h:141
Inline: True
Inline callers:
  - arch/arm/mach-omap2/sram.c:omap_sram_init
  - arch/arm/mach-omap2/sram.c:omap_sram_init
  - arch/arm/mach-omap2/sram.c:omap_sram_init
  - arch/arm/mach-omap2/sram.c:omap_sram_init
  - arch/arm/mach-omap2/sram.c:omap_sram_init
```
```
In arch/arm/mach-omap2/omap_twl.c (c1514b18)
Location: arch/arm/mach-omap2/soc.h:141
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap_twl.c:omap3_twl_init
```
```
In arch/arm/mach-omap2/pm34xx.c (c15159f4)
Location: arch/arm/mach-omap2/soc.h:141
Inline: True
Inline callers:
  - arch/arm/mach-omap2/pm34xx.c:omap3_pm_init
```
```
In arch/arm/mach-omap2/pm-debug.c (c033e63c)
Location: arch/arm/mach-omap2/soc.h:141
Inline: True
Inline callers:
  - arch/arm/mach-omap2/pm-debug.c:pwrdm_suspend_set
  - arch/arm/mach-omap2/pm-debug.c:pwrdm_suspend_get
```
```
In arch/arm/mach-omap2/sr_device.c (c15164b4)
Location: arch/arm/mach-omap2/soc.h:141
Inline: True
Inline callers:
  - arch/arm/mach-omap2/sr_device.c:sr_dev_init
```
```
In arch/arm/mach-omap2/vc.c (c151754c)
Location: arch/arm/mach-omap2/soc.h:141
Inline: True
Inline callers:
  - arch/arm/mach-omap2/vc.c:omap_vc_init_channel
```
```
In arch/arm/mach-omap2/powerdomains3xxx_data.c (c1517bbc)
Location: arch/arm/mach-omap2/soc.h:141
Inline: True
Inline callers:
  - arch/arm/mach-omap2/powerdomains3xxx_data.c:omap3xxx_powerdomains_init
```
```
In arch/arm/mach-omap2/clockdomain.c (c0347f74)
Location: arch/arm/mach-omap2/soc.h:141
Inline: True
Inline callers:
  - arch/arm/mach-omap2/clockdomain.c:clkdm_hwmod_disable
  - arch/arm/mach-omap2/clockdomain.c:clkdm_hwmod_enable
```
```
In arch/arm/mach-omap2/clockdomains3xxx_data.c (c1517e88)
Location: arch/arm/mach-omap2/soc.h:141
Inline: True
Inline callers:
  - arch/arm/mach-omap2/clockdomains3xxx_data.c:omap3xxx_clockdomains_init
```
```
In arch/arm/mach-omap2/clock.c (c15180e0)
Location: arch/arm/mach-omap2/soc.h:141
Inline: True
Inline callers:
  - arch/arm/mach-omap2/clock.c:ti_clk_init_features
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
