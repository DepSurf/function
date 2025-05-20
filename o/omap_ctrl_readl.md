# Function: <code>omap_ctrl_readl</code>

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
u32 omap_ctrl_readl(u16 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm/mach-omap2/control.c (c0335988)
Location: arch/arm/mach-omap2/control.c:164
Inline: True
Inline callers:
  - arch/arm/mach-omap2/control.c:am43xx_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_ctrl_init
  - arch/arm/mach-omap2/control.c:omap3_ctrl_init
  - arch/arm/mach-omap2/control.c:omap3_ctrl_init
  - arch/arm/mach-omap2/control.c:omap3_ctrl_init
  - arch/arm/mach-omap2/control.c:omap3_ctrl_save_padconf
  - arch/arm/mach-omap2/control.c:omap3_ctrl_save_padconf
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap_ctrl_writeb
  - arch/arm/mach-omap2/control.c:omap_ctrl_readb
Direct callers:
  - arch/arm/mach-omap2/id.c:am33xx_check_features
  - arch/arm/mach-omap2/id.c:omap3xxx_check_features
  - arch/arm/mach-omap2/timer.c:realtime_counter_init
  - arch/arm/mach-omap2/pm34xx.c:omap_sram_idle
  - arch/arm/mach-omap2/sr_device.c:sr_set_nvalues
  - arch/arm/mach-omap2/pdata-quirks.c:omap3_logicpd_torpedo_init
  - arch/arm/mach-omap2/pdata-quirks.c:omap3_logicpd_torpedo_init
  - arch/arm/mach-omap2/pdata-quirks.c:am35xx_emac_reset
  - arch/arm/mach-omap2/pdata-quirks.c:am35xx_emac_reset
  - arch/arm/mach-omap2/pdata-quirks.c:am35xx_disable_emac_int
  - arch/arm/mach-omap2/pdata-quirks.c:am35xx_disable_emac_int
  - arch/arm/mach-omap2/pdata-quirks.c:am35xx_enable_emac_int
  - arch/arm/mach-omap2/pdata-quirks.c:am35xx_enable_emac_int
  - arch/arm/mach-omap2/pdata-quirks.c:hsmmc2_internal_input_clk
  - arch/arm/mach-omap2/omap_phy_internal.c:am35x_set_mode
  - arch/arm/mach-omap2/omap_phy_internal.c:am35x_musb_clear_irq
  - arch/arm/mach-omap2/omap_phy_internal.c:am35x_musb_clear_irq
  - arch/arm/mach-omap2/omap_phy_internal.c:am35x_musb_phy_power
  - arch/arm/mach-omap2/omap_phy_internal.c:am35x_musb_phy_power
  - arch/arm/mach-omap2/omap_phy_internal.c:am35x_musb_phy_power
  - arch/arm/mach-omap2/omap_phy_internal.c:am35x_musb_reset
  - arch/arm/mach-omap2/omap_phy_internal.c:am35x_musb_reset
```
**Symbols:**

```
c0335130-c0335164: omap_ctrl_readl (STB_GLOBAL)
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
