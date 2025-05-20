# Function: <code>pwrdm_lookup</code>

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
<summary>In <code>armhf</code>: ✅</summary>

```c
struct powerdomain *pwrdm_lookup(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/mach-omap2/powerdomain.c (c0344fc0)
Location: arch/arm/mach-omap2/powerdomain.c:415
Inline: False
Direct callers:
  - arch/arm/mach-omap2/omap-smp.c:omap4_boot_secondary
  - arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_init
  - arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_init
  - arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_init
  - arch/arm/mach-omap2/pm34xx.c:omap3_pm_init
  - arch/arm/mach-omap2/pm34xx.c:omap3_pm_init
  - arch/arm/mach-omap2/pm34xx.c:omap3_pm_init
  - arch/arm/mach-omap2/pm34xx.c:omap3_pm_init
  - arch/arm/mach-omap2/pm33xx-core.c:am33xx_suspend_init
  - arch/arm/mach-omap2/pm33xx-core.c:am33xx_suspend_init
  - arch/arm/mach-omap2/pm33xx-core.c:am33xx_suspend_init
  - arch/arm/mach-omap2/pm33xx-core.c:am33xx_suspend_init
  - arch/arm/mach-omap2/cpuidle34xx.c:omap3_idle_init
  - arch/arm/mach-omap2/cpuidle34xx.c:omap3_idle_init
  - arch/arm/mach-omap2/cpuidle34xx.c:omap3_idle_init
  - arch/arm/mach-omap2/cpuidle34xx.c:omap3_idle_init
  - arch/arm/mach-omap2/cpuidle44xx.c:omap4_idle_init
  - arch/arm/mach-omap2/cpuidle44xx.c:omap4_idle_init
  - arch/arm/mach-omap2/cpuidle44xx.c:omap4_idle_init
  - arch/arm/mach-omap2/clockdomain.c:clkdm_register_clkdms
```
**Symbols:**

```
c0344fc0-c0344fec: pwrdm_lookup (STB_GLOBAL)
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
