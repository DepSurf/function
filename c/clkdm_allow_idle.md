# Function: <code>clkdm_allow_idle</code>

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
void clkdm_allow_idle(struct clockdomain *clkdm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/mach-omap2/clockdomain.c (c0347a20)
Location: arch/arm/mach-omap2/clockdomain.c:985
Inline: False
Direct callers:
  - arch/arm/mach-omap2/pm.c:omap_pm_clkdms_setup
  - arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_deassert_hardreset
  - arch/arm/mach-omap2/cpuidle34xx.c:omap3_enter_idle_bm
  - arch/arm/mach-omap2/cpuidle44xx.c:omap_enter_idle_coupled
  - arch/arm/mach-omap2/cpuidle44xx.c:omap_enter_idle_coupled
  - arch/arm/mach-omap2/cpuidle44xx.c:omap_enter_idle_coupled
  - arch/arm/mach-omap2/pdata-quirks.c:ti_sysc_clkdm_allow_idle
```
**Symbols:**

```
c0347a20-c0347a54: clkdm_allow_idle (STB_GLOBAL)
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
