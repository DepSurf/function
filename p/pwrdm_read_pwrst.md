# Function: <code>pwrdm_read_pwrst</code>

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
int pwrdm_read_pwrst(struct powerdomain *pwrdm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm/mach-omap2/powerdomain.c (c03465b4)
Location: arch/arm/mach-omap2/powerdomain.c:583
Inline: True
Inline callers:
  - arch/arm/mach-omap2/powerdomain.c:pwrdms_lost_power
  - arch/arm/mach-omap2/powerdomain.c:omap_set_pwrdm_state
  - arch/arm/mach-omap2/powerdomain.c:pwrdm_register_pwrdms
  - arch/arm/mach-omap2/powerdomain.c:_pwrdm_state_switch
Direct callers:
  - arch/arm/mach-omap2/pm34xx.c:omap_sram_idle
  - arch/arm/mach-omap2/pm34xx.c:omap_sram_idle
  - arch/arm/mach-omap2/pm33xx-core.c:am33xx_suspend
  - arch/arm/mach-omap2/cpuidle34xx.c:omap3_enter_idle_bm
  - arch/arm/mach-omap2/cpuidle44xx.c:omap_enter_idle_coupled
```
**Symbols:**

```
c034539c-c03453fc: pwrdm_read_pwrst (STB_GLOBAL)
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
