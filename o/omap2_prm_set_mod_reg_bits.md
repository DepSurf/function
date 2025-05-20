# Function: <code>omap2_prm_set_mod_reg_bits</code>

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
In arch/arm/mach-omap2/ti81xx-restart.c (c033ceac)
Location: arch/arm/mach-omap2/prm2xxx_3xxx.h:89
Inline: True
Inline callers:
  - arch/arm/mach-omap2/ti81xx-restart.c:ti81xx_restart
```
```
In arch/arm/mach-omap2/prm2xxx_3xxx.c (c034062c)
Location: arch/arm/mach-omap2/prm2xxx_3xxx.h:89
Inline: True
Inline callers:
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_clkdm_add_wkdep
```
```
In arch/arm/mach-omap2/prm3xxx.c (c0340fec)
Location: arch/arm/mach-omap2/prm2xxx_3xxx.h:89
Inline: True
Inline callers:
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_clear_global_cold_reset
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_reconfigure_io_chain
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_reconfigure_io_chain
  - arch/arm/mach-omap2/prm3xxx.c:omap3430_pre_es3_1_reconfigure_io_chain
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_dpll3_reset
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
