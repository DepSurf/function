# Function: <code>_clkdm_deps_lookup</code>

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

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/arm/mach-omap2/clockdomain.c (c03475d4)
Location: arch/arm/mach-omap2/clockdomain.c:102
Inline: True
Inline callers:
  - arch/arm/mach-omap2/clockdomain.c:clkdm_read_sleepdep
  - arch/arm/mach-omap2/clockdomain.c:clkdm_del_sleepdep
  - arch/arm/mach-omap2/clockdomain.c:clkdm_add_sleepdep
  - arch/arm/mach-omap2/clockdomain.c:clkdm_read_wkdep
  - arch/arm/mach-omap2/clockdomain.c:clkdm_del_wkdep
  - arch/arm/mach-omap2/clockdomain.c:clkdm_add_wkdep
  - arch/arm/mach-omap2/clockdomain.c:_clkdm_del_sleepdep
  - arch/arm/mach-omap2/clockdomain.c:_clkdm_add_sleepdep
  - arch/arm/mach-omap2/clockdomain.c:_clkdm_del_wkdep
  - arch/arm/mach-omap2/clockdomain.c:_clkdm_add_wkdep
Direct callers:
  - arch/arm/mach-omap2/clockdomain.c:clkdm_read_sleepdep
  - arch/arm/mach-omap2/clockdomain.c:clkdm_del_sleepdep
  - arch/arm/mach-omap2/clockdomain.c:clkdm_add_sleepdep
  - arch/arm/mach-omap2/clockdomain.c:clkdm_read_wkdep
  - arch/arm/mach-omap2/clockdomain.c:clkdm_del_wkdep
  - arch/arm/mach-omap2/clockdomain.c:clkdm_add_wkdep
  - arch/arm/mach-omap2/clockdomain.c:_clkdm_del_sleepdep
  - arch/arm/mach-omap2/clockdomain.c:_clkdm_add_sleepdep
  - arch/arm/mach-omap2/clockdomain.c:_clkdm_del_wkdep
  - arch/arm/mach-omap2/clockdomain.c:_clkdm_add_wkdep
```
**Symbols:**

```
c0346b40-c0346bb8: _clkdm_deps_lookup.part.0 (STB_LOCAL)
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
