# Function: <code>omap2_cm_write_mod_reg</code>

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
In arch/arm/mach-omap2/prm3xxx.c (c1516dc0)
Location: arch/arm/mach-omap2/cm2xxx_3xxx.h:55
Inline: True
Inline callers:
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_clear_mod_irqs
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_clear_mod_irqs
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_clear_mod_irqs
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_clear_mod_irqs
```
```
In arch/arm/mach-omap2/cm3xxx.c (c034181c)
Location: arch/arm/mach-omap2/cm2xxx_3xxx.h:55
Inline: True
Inline callers:
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_disable
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_disable
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_disable
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_disable
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_enable
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_enable
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_enable
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_deny_idle
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_allow_idle
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clear_all_sleepdeps
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_del_sleepdep
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_add_sleepdep
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
