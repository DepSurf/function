# Function: <code>omap_hwmod_write</code>

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
void omap_hwmod_write(u32 v, struct omap_hwmod *oh, u16 reg_offs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm/mach-omap2/omap_hwmod.c (c03380b4)
Location: arch/arm/mach-omap2/omap_hwmod.c:2978
Inline: True
Direct callers:
  - arch/arm/mach-omap2/display.c:omap_dss_reset
  - arch/arm/mach-omap2/display.c:omap_dss_reset
  - arch/arm/mach-omap2/display.c:omap_dss_reset
  - arch/arm/mach-omap2/display.c:omap_dss_reset
  - arch/arm/mach-omap2/display.c:omap_dss_reset
  - arch/arm/mach-omap2/display.c:omap_dss_reset
  - arch/arm/mach-omap2/display.c:omap_dss_reset
  - arch/arm/mach-omap2/i2c.c:omap_i2c_reset
  - arch/arm/mach-omap2/i2c.c:omap_i2c_reset
  - arch/arm/mach-omap2/hdq1w.c:omap_hdq1w_reset
  - arch/arm/mach-omap2/omap_hwmod_reset.c:omap_hwmod_rtc_lock
  - arch/arm/mach-omap2/omap_hwmod_reset.c:omap_hwmod_rtc_lock
  - arch/arm/mach-omap2/omap_hwmod_reset.c:omap_hwmod_rtc_unlock
  - arch/arm/mach-omap2/omap_hwmod_reset.c:omap_hwmod_rtc_unlock
```
**Symbols:**

```
c0339610-c033964c: omap_hwmod_write (STB_GLOBAL)
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
