# Function: <code>omap2_prm_write_mod_reg</code>

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
In arch/arm/mach-omap2/ti81xx-restart.c (c033cec0)
Location: arch/arm/mach-omap2/prm2xxx_3xxx.h:58
Inline: True
Inline callers:
  - arch/arm/mach-omap2/ti81xx-restart.c:ti81xx_restart
```
```
In arch/arm/mach-omap2/prm2xxx_3xxx.c (c0340788)
Location: arch/arm/mach-omap2/prm2xxx_3xxx.h:58
Inline: True
Inline callers:
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_clkdm_clear_all_wkdeps
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_clkdm_del_wkdep
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_clkdm_add_wkdep
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_pwrdm_set_logic_retst
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_pwrdm_set_mem_retst
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_pwrdm_set_mem_onst
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_prm_deassert_hardreset
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_prm_deassert_hardreset
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_prm_assert_hardreset
```
```
In arch/arm/mach-omap2/prm3xxx.c (c0340cb8)
Location: arch/arm/mach-omap2/prm2xxx_3xxx.h:58
Inline: True
Inline callers:
  - arch/arm/mach-omap2/prm3xxx.c:omap3_pwrdm_disable_hdwr_sar
  - arch/arm/mach-omap2/prm3xxx.c:omap3_pwrdm_enable_hdwr_sar
  - arch/arm/mach-omap2/prm3xxx.c:omap3_pwrdm_clear_all_prev_pwrst
  - arch/arm/mach-omap2/prm3xxx.c:omap3_pwrdm_set_next_pwrst
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_clear_global_cold_reset
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_reconfigure_io_chain
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_reconfigure_io_chain
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_reconfigure_io_chain
  - arch/arm/mach-omap2/prm3xxx.c:omap3430_pre_es3_1_reconfigure_io_chain
  - arch/arm/mach-omap2/prm3xxx.c:omap3430_pre_es3_1_reconfigure_io_chain
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_reset_modem
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_reset_modem
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_clear_mod_irqs
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_restore_irqen
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_save_and_clear_irqen
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_dpll3_reset
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_vcvp_rmw
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_vcvp_write
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_vp_clear_txdone
```
```
In arch/arm/mach-omap2/powerdomains3xxx_data.c (c03466f8)
Location: arch/arm/mach-omap2/prm2xxx_3xxx.h:58
Inline: True
Inline callers:
  - arch/arm/mach-omap2/powerdomains3xxx_data.c:ti81xx_pwrdm_set_next_pwrst
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
